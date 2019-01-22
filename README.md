# WaveletTransform_with_pywt
Wavelet Transform with pywt (Python)

I did not find a detailed tutorial about wavelet transform with pywt (a package in Python) online. So, I tried to write my own in form of a jupyter notebook. The tutorial is fairly basic and detailed so that a non-expert with basic knowledge in Python and Fourier-Transform can understand it. 

The notebook WaveletTryout.ipynb explores the functionalities of pywt in general.
The notebook Extract_High_Freqs.ipynb is dedicated to the task of extracting the higher frequencies from a signal. 

Some questions and uncertainties remained, hence I formulated some questions within the notebooks. 

In the in the Extract_High_Freqs.ipynb notebook the following problem remains unresolved: 
Since I did not know how to directly reconstruct the higher frequency components of a signal I reconstructed them indirectly: I extracted the lower frequencies and subtracted them from the original signal in order to obtain the higher frequencies. 
However, the reconstructed lower frequency components are longer than the original signal and need to be sliced in order to have the same length before they can be subtracted from the original signal. Correct slicing can be obtained by trial and error or by visual inspection in the case of a simple illustrative example as in my notebook. But how would I know how to select the correct part of the reconstructed low frequency component in the case of real data? 
If anyone knows the answer i.e. how to solve the problem outlined in the notebook Extract_High_Freqs.ipynb correctly, I would be very grateful!

In general, feedback and corrections are most welcome!
