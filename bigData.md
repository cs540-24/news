# Big Data Task 

## Determine if a specific package/include/import is implemented in at least one file in the repository

agautam1 - Julia

aravi - PHP

catwater - Ruby

cmuncey  - TypeScript

dnguye18 - Rust

dshekou1 - Scala

dxh594 - Kotlin

jalle119 - C/C++

jblanche1325 - Fortran

jhammer3 - Go

jhills - Basic

jisber - Erlang

nwest13 - Lua

pprovins - Clojure

rtodd11 - Dart

spatel84 - Swift

tfry2  - Perl

tnguye69 - Java

# Steps to identify where a certain functionality is implemented:

1. Identify filnames typical for your assigned language, use e.g., https://github.com/github/linguist
2. Find 10 exampe files+blobs in WoC, e.g., zcat /da0_data/basemaps/gz/b2fFullS0.s| grep pattern
3. Find 10 projects that that mostly contain the files of the specified language using mongodb / WoC / proj_metadata.S
4. Find if the language uses package manager (e.g, JS uses NPM, but C/C++ does not)
5. If it does, look at the package repository to identify how it exports functionality
6. Write a script that given a blob and language determines what functionality is implemented/exported 


