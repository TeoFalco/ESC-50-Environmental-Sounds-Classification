README

to display the dashboard extract the folder "dashboard", from the terminal enter into the folder and execute the file "audio.py" e.g.:

>>>> cd "YOUR_DIRECTORY/audio.py"
>>>> streamlit run audio.py

here's the list of the required libraries:

streamlit
librosa
torchvision 
PIL 
matplotlib.pyplot as plt
numpy
pandas
torch

WARNING: if you want to test both the CNNs on the ESC50 dataset, make sure to select only the audio files from the folders 4 and 5 since 
1,2 and 3 belong to the train set