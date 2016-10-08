# linux-conf

## Introduction

These are various configuration files for many components of linux. As
of writing this (October 8, 2016), this repository just hosts kernel
configs for building customized kernels.

## Repo layout

The config files are stored under master. As configs get refined,
they'll be tagged for the version of the Linux kernel that they apply
to, plus my own "-rc-n" release candidate number.

The directory structure is as follows:
kernel/\<arch\>/\<bits\>/\<cpu_type\>/\<hardware_profile\>_config
