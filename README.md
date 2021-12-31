# Audio_Signal_Processing_for_Music_Applications-Exam_Project_2021
### A take-home, 48-hour exam project for "Audio Signal Processing for Music Applications" optional course (taught by Xavier Serra at UPF) in MIIS master.
It consists of two main parts :

* _**_Simple DSP-audio analysis for a target sound, extracted from freesound.org_**_
* _**_KNN classification, for 3 custom-made classes that contain hand-picked audio tracks for the purpose of the task, using the Freesound API_**_

Project implemented from scratch, using Jupyter Notebooks.

### Original instructions:

_A) Download from http://www.freesound.org the sound assigned to you and read all the information describing it. 
If the sound is too long, select a representative fragment of less than five seconds in length (2 seconds would be
ideal). If the sound does not have the recommended format change it, using any sound editor.
You can also perform some pre-processing to create a more adequate sound. Save the edited
sound in your working directory.
Create the python notebook to be used for the whole exam and perform the following tasks.
Read the downloaded/edited sound and display it. Compute its STFT and show the magnitude
spectrogram. Describe the sound by using its temporal and spectral representation,
focusing on what information should be useful for processing the sound with spectral models,
thus for deciding the spectral analysis parameters._

_B)The aim of this exercise is to extend what you did in Assignment 9 using the assigned sound
and focusing on the topic of automatic sound classification. The goal is to perform a
classification of your sound within 3 sound classes that you define, extracting and using lowlevel Essentia descriptors and a k-NN classifier. 
The sound classes should be collections of sounds from freesound, but you should not attach the sound collections, your code should load
the sounds directly from freesound._

* _Analyze with Essentia your sound, selecting a maximum of 10 descriptors from the
ones used in the freesound extractor, that you believe are most adequate. Use only
statistical aggregations of each descriptor. Display the analysis data and explain your
choices and your results._
* _Create 3 sound collections manually, using sounds from freesound that you believe can
exemplify your classification task. Each collection should be a list of the freesound urls,
thus sounds should not be downloaded and edited. Your code should access directly the
sounds using the freesound api. Each collection should not be larger than 10 sounds
each. No collection should include any sound that is “very” similar to your sound and
each collection should have a coherence. You can use, and explain, your own definition
of similarity and coherence. Analyze the 3 sound collections with the descriptors chosen
in question 1. Display the analysis data and explain your choices and your results_
* _Perform a classification of your sound using a k-NN classifier, choosing your own k
value_ 

### Final Grade
_95%_

_Credits_
**_Emmanouil Palaiologos_**
