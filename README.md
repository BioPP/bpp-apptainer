Configuration file for main libraries & softwares of Bio++

This includes bpp-core, bpp-seq, bpp-phyl, bpp-popgen, bppsuite & testnh.

To build an image:

<code> apptainer build --fakeroot bppall.sif bppall.def 
</code>

A convenient way to use the image is to open a shell in it:

<code> apptainer shell bppall.sif 
</code>
