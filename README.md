# Non-binary LDPC (NB-LDPC) codes and their sources
The file 'Codes_AtoF.rar' contains the codes' matrics for the fast non-binary ldpc decoder on gpu. 
And, the sources of those codes are below:

1. Code_A is from [1];
2. Code_B and Code_E are from [2];
3. Code_C and Code_F are from [3];
4. Code_D is from [4];

[1] Short Block Length LDPC Codes for TC Synchronization and Channel Coding, Recommendation for Space Data System Standard, CCSDS
231.1-O-1, Orange Book, Apr. 2015.

[2] http://www.uni-kl.de/channel-codes/channel-codes-database/non-binary-ldpc/

[3] http://perso-etis.ensea.fr/~declercq/graphs.php

[4] Andrade J, Falcao G, Silva V, et al, “FFT-SPA non-binary LDPC decoding on GPU,” in Proc. IEEE ICASSP, 2013, pp. 5099-5103.

# BER performance of our NB-LDPC decoder on GPU
The figure below is the BER performance for our GPU-based NB-LDPC decoder at 5 layered decoding iterations.
![BER](https://github.com/Liubusy/Non-Binary-LDPC-codes/blob/master/BER.png)
