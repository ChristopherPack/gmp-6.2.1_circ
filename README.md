# gmp-6.2.1_circ
An implementation of a circulant matrix multiplication in the GNU MP library

This implementation of GMP contains a replacement algorithm for FFT.
The new algorithm, called circulant matrix algorithm, achieves a speedup of about 1%.

Subsequently, the only change to the standard gmp-6.2.1 distribution is located in /mpn/generic/mul_fft.c

While this distribution should be installable the same way as the standard gmp-6.2.1 distribution, if the installation is somehow not working, I recommend just copying mul_fft.c into a standard gmp-6.2.1 distribution, available at https://gmplib.org/
