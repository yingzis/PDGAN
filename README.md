# PDGAN
This project first presents a coherent signal demodulation method based on generative adversarial networks (GAN), called a phase demodulation generative adversarial network (PDGAN). We applyed GAN method to the field of Doppler signal demodulation for laser voice detection.Demodulation of the Doppler signal from a coherent signal is accomplished through unsupervised learning within the PDGAN, layer by layer, with global supervised feedback learning for fine-tuning. Drawing upon the adversarial principle of GAN, we let the coherent signal, Z, serve as an input for G and let the generated demodulated Doppler signal G(Z) and the clean Doppler signal X serve as the input for D. By means of alternate training and optimization, G learns the mapping relationship between the coherent signal, Z, and the Doppler signal, X, thereby achieving the goal of demodulating the coherent signal.  This project mainly includes related data sets of Doppler signal and corresponding coherent signal. 
The structure and detailed description of the network are planned to be published in the Journal of "Optical Engineering". The author can also be contacted for information wangyahui@aoe.ac.cn
Here, we provide the program to prepare the data set, and we develop the data set according to the principle of interferometry.
Due to the large data set, we upload it in batches. The upload time is February 4, 2021.
The dataset contains three folders, which needed to train PDGAN
clean folder include clean Doppler signal and corresponding coherent signal
Babble folder includes Doppler signal with babble noise and corresponding coherent signal
White folder includes Doppler signal with white noise and corresponding coherent signal
