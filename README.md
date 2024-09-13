# Alpinist Examples

This repository contains the source code of examples in the paper "Alpinist: an Annotation-Aware GPU Program Optimizer" submitted to the International Conference on Tools and Algorithms for the Construction and Analysis of Systems (TACAS) 2022. 

The implementation of the annotated-program optimizer, which is implemented in the VerCors verifier, is available [here](https://github.com/utwente-fmt/vercors/tree/gpgpu-optimizations).

In addition to the TACAS22 conference, the failed_opt_examples folder has been appended. This folder contains examples that verify using VerCors, however do not pass the applicability checking phase of their respective optimizations using Alpinist. Each folder contains the example (prefixed with bad_), the log file of VerCors named verification.log and the log file of Alpinist.