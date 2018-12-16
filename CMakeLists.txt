project(UMDHMM)
cmake_minimum_required(VERSION 2.6)


add_executable(testvit testvit.c viterbi.c nrutil.c hmmutils.c sequence.c hmmrand.c hmm.h nrutil.h)
