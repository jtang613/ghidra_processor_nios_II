# Altera Nios II for Ghidra

This repo contains an implementation of the [Altera Nios II soft-processor](https://www.intel.com/content/dam/www/programmable/us/en/pdfs/literature/hb/nios2/n2cpu-nii5v1gen2.pdf) for Ghidra.

## Installation

```

```

# Resources used

 - [Ghidra Language Specification](https://ghidra.re/courses/languages/index.html)
 - [Nios II Processor Reference Guide](https://www.intel.com/content/dam/www/programmable/us/en/pdfs/literature/hb/nios2/n2cpu-nii5v1gen2.pdf)
 - [Implementing a New CPU Architecture for Ghidra](https://guedou.github.io/talks/2019_BeeRump/slides.pdf)
 - [Specifying Representations of Machine Instructions](https://www.cs.tufts.edu/~nr/pubs/specifying.html)

 The documentation for `ldefs`, `cspec` and `pspec` files is kind of hidden. Inside the Ghidra repository, it is located at `REPO/Ghidra/Features/Decompiler/src/main/doc` and can be compiled to html with the following command: `xsltproc cspec_html.xsl cspec.xml > cspec.html`
