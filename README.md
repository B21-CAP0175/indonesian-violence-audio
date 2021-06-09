# Audio dataset for Violence in Indonesian
##### Created for Bangkit Programme Capstone Project Zupa Team_B21-CAP0175

## Dataset 
This dataset consist of recording of volunteers given 40 situations. Those situations simulate violence and we record their response. We categorised violence into four types, domestic, physical, sexual, and stalking violence. Each category has its own folder. In total we have more than 120 unique audio data (means 30 in average for each situation). We acknowledge that a situation could have more than one violence, in that case we duplicate the audio and put them into correct folders respectively. For example `audio a` has domestic and sexual violence in it, so we put `audio a` in folder `/domestic` and `/sexual` .

We interpret the violence by listening the recording serveral times and not seeing the script. Notes by interpreter available in `dataset notes.txt`. Notes written in slang Indonesian.

### Situations
You can see what kind of situation we gave in the `/scripts` folder.
### Language
All of the recording using Indonesian, daily slang language.
### Gender
Most of the recording is in teenage to early adult female voice. As this could lead to a bias in machine learning / deep learning model, we will try to get more male volunteer in the future. Also in near future we will provide augmented recordings that can 'simulate' more male voice and bring more balance and variety to the dataset.

### Misc
Some of the recordings have background noise that also strengthen the nuance (example: hitting sound, 2nd person, small room reverb that simulates house situation, etc). We also provide sample if you want to test your ML/DL project.

## Formating
We have the recording in `.ogg` and `.wav` format. `/old_ver` is the early version of our dataset, consists only `.ogg` files and less diverse. `/dataset_wav` consists recordings in `.wav` format. `/dataset_mixed` consists recording in mixed audio format. Both of the audio format is readable using Python's `librosa` library. Sample rate for all audio recording is 44100 Hz, with Nyquist theorm in mind, you should process them in 22050 Hz.

## Contribute! (we will be super happy!)
If you want to contribute to the dataset, please see our notes, scripts, etc. Then contact our machine learning engineer [with email](mailto:iga.narendra@gmail.com). Don't hesitate to tell us your story. You can write your story inside the email or have a safe, under COVID-19 protocol meet (can be online or onsite around Jakarta, Bandung and Denpasar). Thank you so much! Hopefully together we can provide better safety for all.