# EEG-waves-neural-networks
Emotion prediction using EEG waves and neural networks

## Dataset
-> Signals from 23 participants were recorded along with the participants’ self-assessment of their affective state after each stimulus, in terms of valence, arousal, and dominance. <br/>
-> The “DREAMER” variable is structured as follows:<br/>
  -> Data: {1×23 cell}<br/>
  -> EEG_SamplingRate: 128<br/>
  -> EEG_Electrodes: {'AF3' 'F7' 'F3' 'FC5' 'T7' 'P7' 'O1' 'O2' 'P8' 'T8' 'FC6' 'F4' 'F8' 'AF4’}<br/>
  -> noOfSubjects: 23<br/>
  -> noOfVideoSequences: 18<br/>

## Implementation
![image](https://github.com/shrav-6/EEG-waves-neural-networks/assets/59273748/c2b155cc-4229-4141-b138-ce0662e903bf)

## Results

![image](https://github.com/shrav-6/EEG-waves-neural-networks/assets/59273748/2b6dbc9c-a7ce-43d7-9175-911b82fe0d1b)<br/>
“Valence” is the level of pleasantness that an event generates and is defined along a continuum from negative to positive.<br/>

![image](https://github.com/shrav-6/EEG-waves-neural-networks/assets/59273748/e65676f9-3a30-425e-bd07-5fa91073698d)<br/>
“Arousal” is the state when you feel excited or very alert, for example, due to fear, stress, or anger.<br/>

![image](https://github.com/shrav-6/EEG-waves-neural-networks/assets/59273748/242fc370-f3d9-4c3a-956f-e2ed2e0d6fea)<br/>
“Dominance” - this feature is used to determine how strongly a particular emotion is felt<br/>

![image](https://github.com/shrav-6/EEG-waves-neural-networks/assets/59273748/6b172c84-6751-4c09-b69f-3a8b6ce8b17d)<br/>
Mapping of Valence, Arousal, and Dominance to the emotions predicted<br/>

## References
[1] C. A. Gabert-Quillen, E. E. Bartolini, B. T. Abravanel, and C. A. Sanislow, “Ratings for emotion film clips,” Behavior Research Methods, vol. 47, no. 3, pp. 773–787, 2015.<br/>
[2] S. Katsigiannis, N. Ramzan, “DREAMER: A Database for Emotion Recognition Through EEG and ECG Signals from Wireless Low-cost Off-the-Shelf Devices,” IEEE Journal
