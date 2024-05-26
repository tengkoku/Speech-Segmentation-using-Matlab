# Speech-Segmentation-using-Matlab
Simple speech segmentation in Matlab

 The two dataset are Set-C and Set-G, where each set consists of 10
 wav files and 10 segmentation files. For Set-C files,
 all of them are from a female speaker, while the Set-G files are from a male speaker.

Experimental setup and Result of Proposed Algorithm
 Experiment setup :
 • Experimental Variable : Time tolerance, Threshold and win size
 • Time tolerance: t = {0.01 0.02 0.03 0.04 0.05 0.06 0.07 0.08 0.09 0.10 }
 • Threshold : Thres = { 1.4 , 2.4, 3.4}
 • Win size : W = {256}

The proposed algorithm adds a end point of the  soundwave.
The proposed algorithm also adds a moving average filter (‘movmean’) in order to reduce noise and fluctuations. This is to smoothen out the energy curve. 
 ![image](https://github.com/tengkoku/Speech-Segmentation-using-Matlab/assets/148973550/aca76f57-df20-4caf-b889-f7ccf71cae7c)

![image](https://github.com/tengkoku/Speech-Segmentation-using-Matlab/assets/148973550/35d18881-4dce-4971-bf46-66cfe20d9cf3)

![image](https://github.com/tengkoku/Speech-Segmentation-using-Matlab/assets/148973550/0a671f6d-942b-46e2-859f-508331049662)

![image](https://github.com/tengkoku/Speech-Segmentation-using-Matlab/assets/148973550/2d222c8d-e16b-40eb-8094-29a8d6ca3225)

By implementing the smoothing effect of the moving average filter and the inclusion of end points in the proposed algorithm, it offers an improved approach for speech segmentation, enabling a more accurate identification of segment boundaries and potentially enhancing subsequent analysis or processing tasks on the segmented portions of the speech.![image](https://github.com/tengkoku/Speech-Segmentation-using-Matlab/assets/148973550/07219490-e6b2-462b-b2fb-fd5deb5471d5)




 
