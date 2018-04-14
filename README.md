# Applications and Enhancements of the Deep Recurrent Neural Network For Speech Separation



### speech separation experiment

1. Training code: ```codes/TSP/train_TSP_demo_mini_clip.m```

2. Demo
 - Find the pre-trained model at ```codes/TSP/demo/model.mat``` 
 - Run the demo code at ```codes/TSP/demo/run_test_single_model.m```


## Dependencies
1. The package is modified based on [rnn-speech-denoising](https://github.com/amaas/rnn-speech-denoising)

2. The software depends on Mark Schmidt's [minFunc](http://www.di.ens.fr/~mschmidt/Software/minFunc.html) package for convex optimization.

3. Additionally, we have included Mark Hasegawa-Johnson's [HTK write and read functions](http://www.isle.illinois.edu/sst/software)
that are used to handle the MFCC files.

4. We use [HTK](http://htk.eng.cam.ac.uk) for computing features (MFCC, logmel) (HCopy).

5. We use signal processing functions from [labrosa](http://labrosa.ee.columbia.edu/).

6. We use [BSS Eval](http://bass-db.gforge.inria.fr/bss_eval/) toolbox Version 2.0, 3.0 for evaluation.



## Work on your data:
1. To try the codes on your data, see mir1k, TSP settings - put your data into ```codes/TSP/Data/``` accordingly.

2. Tune the parameters on the dev set and check the results.
 

### Notes 
The codes are tested using MATLAB R2014a

## Reference
1. P.-S. Huang, M. Kim, M. Hasegawa-Johnson, P. Smaragdis, "[Joint Optimization of Masks and Deep Recurrent Neural Networks for Monaural Source Separation](http://posenhuang.github.io/papers/Joint_Optimization_of_Masks_and_Deep%20Recurrent_Neural_Networks_for_Monaural_Source_Separation_TASLP2015.pdf)", IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 23, no. 12, pp. 2136–2147, Dec. 2015


## Authors

* **Mohamed Wahballah** - *Initial work* - [mawahballah](https://github.com/mawahballah)

* **Valentin Golodov** - *Initial work* - [valentingolodov](https://github.com/valentingolodov)
