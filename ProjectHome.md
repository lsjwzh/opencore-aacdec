# 1. What Is opencore-aacdec? #

opencore-aacdec is a library, that implements fixed-point AAC decoder, optimized for ARM processors. This library is based on PacketVideo implementation.


## opencore-aacdec can decode: ##

  * AAC
  * AAC+SBR
  * AAC+SBR+PS




opencore-aacdec used fixed-point implementation with assembler optimisation for ARM processors. It able to decode ADTS (and maybe ADIF) streams.

The decoder's core, provided in this tarball licensed on "Apache V2" license, and other parts of code - licensed on GPL.

## Config parameters: ##

The library's configuration may require some parameters/flags, that gives aac, aac+ or he-aac+ codec options (all this options enabled by default):

  * --with-aac-plus - Enables SBR decoding.
  * --with-ps - Enables Parametric Stereo decoding.
  * --with-hq-sbr - Enables High-Quality SBR decoding.

## Optimisations: ##

If you are using gcc and want to optimise your core for ARM core, use additional flags, that enables optimisations for your  core version (disabled by default):

  * --with-arm-v4
  * --with-arm-v5
  * --with-arm-msc-evc-v4
  * --with-arm-msc-evc-v5
  * --with-arm-gcc-v4
  * --with-arm-gcc-v5

In most cases for gcc you have to use --enable-arm-gcc-v4 or --enable-arm-gcc-v5 for your arm core.



P.S. I'm using this library for receiving "Internet Radio" stations on my NSLU2.