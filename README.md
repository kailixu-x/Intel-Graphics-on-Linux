# Intel graphics on Linux

## Introduction

This document is a summary of the Linux graphics stack and Intel GPU.

The Linux graphics software stack includes many individual and connected components, from kernel space to user space, from past to the current and future. This document focuses on the current general setup as the middle of year 2024. Not all components will be documented, however the whole picture and the most important concepts as the writers understand shall be provided to the readers to know how Linux works with GPU in general and could use this document as a reference to GPU under Linux in the daily use of Linux machines and development.

For Intel GPU, this document aims to be a summary of information. General knowledge of Intel GPU and its software will be documented for the average developers to understand the background, history and capabilities; More information for developments shall be mentioned and referenced to so when needed the developers can find the details themselves.

The target audiences of this document are interested developers, the prior knowledge of Linux graphics stack and Intel GPU are not needed.

## Generate document to HTML format

The document can be generated from the raw markdown files to HTML for better reading. `mdbook` is used:

```shell
# if cargo exists
cargo install mdbook
# if not, go to https://github.com/rust-lang/mdBook/releases to download the pre-built binary and put into PATH.

# generate the HTML
mdbook build
```
