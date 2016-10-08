# linux-conf

## Introduction

These are various configuration files for many components of linux. As
of writing this (October 8, 2016), this repository just hosts kernel
configs for building customized kernels.

## Repo layout

The config files are stored under annotated tags, with versions matching
the the major release versions of linux. For example, kernel configs for
Linux v4.6.3 can be found under annotated tag "v4.6".

The directory structure is as follows:
kernel/\<arch\>/\<bit-depth\>/\<cpu_type\>/\<hardware_profile\>_config
