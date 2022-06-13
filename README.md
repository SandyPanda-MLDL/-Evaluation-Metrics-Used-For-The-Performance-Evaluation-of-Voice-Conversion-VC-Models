# Evaluation Metrics Used For The Performance Evaluation of Voice Conversion VC Models

<p align="center">
    <strong>Authors</strong>
  <p align="center">
     <a href="https://www.linkedin.com/in/md-tousin-akhter-807620151?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BqM3cV%2BRZQVyQhmzlHywpvw%3D%3D" >Md Tousin Akhter</a> • <a href="https://www.linkedin.com/in/padmanabha-banerjee-b16800171/">Padmanabha Banerjee</a> • <a href="https://www.linkedin.com/in/sandi94/">Sandipan Dhar</a> • <a href="https://scholar.google.com/citations?user=69EVBBsAAAAJ&hl=en&oi=ao">Nanda Dulal Jana</a>
    
  </p>
</p>



Voice Conversion (VC) has been a prominent subject of research in the science of speech synthesis in recent years as a result of its growing use in voice-assistance technology, automated movie dubbing, and speech-to-singing conversion, to mention a few applications.
VC is concerned with the conversion of one speaker's vocal style to that of another while maintaining the linguistic content. The speech analysis, speech feature mapping, and speech reconstruction stages of the VC job are accomplished in a three-stage pipeline. For voice feature mapping from source to target speaker, the Generative Adversarial Network (GAN) models are now commonly used. Evolution of models will enhance the quality of synthesized speech and also will enable real world application of VC commercially and also in medical field. To ensure that the reproduced speech holds the characteristics of the voice and error are minimized to produce the finest quality , we need evaluation metrics to govern the quality.
Thus the presented models can elegantly execute the voice conversion task by attaining high speaker similarity and appropriate speech quality, according to subjective and objective evaluations of the generated speech samples.

The visual evaluation metric plots are available [here](https://sites.google.com/ece.jgec.ac.in/evaluation-metrics-of-vc/home).


### **The following files represent the various objecvtive and subjective evaluation metrics that can be used in Voice Conversion.**

* Mel-Cepstral Distortion [(MCD)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/1.MCD.ipynb)
* F0 Root Mean Square Error [(F0 RMSE)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/2.F0_RMSE.ipynb) 
* log F0 Root Mean Square Error [(log F0 RMSE)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/3.log_F0_RMSE.ipynb)
* Modulation Spectra Distance [(MSD)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/4.MSD.ipynb)
* Speech to Noise Ratio [(SNR)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/6.SNR.ipynb) 
* Perceptual Evaluation of Speech Quality [(PESQ)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/7.PESQ.ipynb)
* Global Variance [(GV)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/5.GV.ipynb)
* MCEP Trajectory [(link)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/8.MCEP_Trajectory.ipynb)
* Modulation Spectrum [(link)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/9.Modulation_Spectrum.ipynb)
* Mean MCEP [(link)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/10.Mean_MCEP.ipynb)
* MCEP Scatter Plot [(link)](https://github.com/SandyPanda-MLDL/-Evaluation-Metrics-Used-For-The-Performance-Evaluation-of-Voice-Conversion-VC-Models/blob/main/11.MCEP_Scatter_Plot.ipynb)

## Running the notebooks :

Each notebook allows the user to add the dataset and select the directory which contains the audio (.wav) files of their corresponding speech classes. Then as user input the directory path for the original and the generated speech audio files are given , along with the specifications like the markers and labels. In particular evaluation metrics , the dimensions that are to be visualized are also taken as user input. 

One can either use the google_drive_downloader library to load the zip files of the dataset into the workspace or you can directly load it by mounting your google drive and accessing it through Colab.  

## Contact :

Md. Tousin Akhter     -  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg' alt='gmail' height='20' align=center>](mailto:mta.21p10078@mtech.nitdgp.ac.in)

Padmanabha Banerjee    -  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg' alt='gmail' height='20' align=center>](mailto:pb2306@ece.jgec.ac.in)

Sandipan Dhar  -  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg' alt='gmail' height='20' align=center>](mailto:sd.19cs1101@phd.nitdgp.ac.in)

Nanda Dulal Jana  -  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg' alt='gmail' height='20' align=center>](mailto:nandadulal@cse.nitdgp.ac.in)


