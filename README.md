# Description

This project is intended to be used as a simulation of turbo encoding and decoding over a channel with Additive White Gaussian Noise. 

It contains two encoder/decoder architectures: a rate 1/3 encoder/decoder and a rate 1/4 encoder/decoder.

# Compilation and Usage

## Compliation

To compile the whole project, `cd` into `{PROJECT_HOME}` and execute

```
scons
```
to generate according executables under `{PROJECT_HOME}/scons_build` folder. 

## Usage

Execute `$ source run_turbo_test` or
execute `scons test`

# Notes

Code of encoder/decoder can be found in `code` folder.
I put the test code in the `test` folder.
You can set the detailed parameters in `run_turbo_test` script. In which, parameter `codetype` can be set to 1 to choose a rate 1/3 encoder/decoder architecture, or 2 to choose a rate 1/4 encoder/decoder architecture.
