# Inhumane-Treatment-of-Animals-ITA-
The ITA dataset with its annotation file. The original ITA does not compromise the video resolution or the audio channel.
ITA has 500 real world videos and the primary purpose behind creating this dataset was to fill the gap of a lack of a dataset for animal abuse classification tasks.

The annotation file contains the filename, start and end timestamps for the abuse if present in the video, the duration of the video, label as 'abuse' or 'no_abuse' and the type of abuse: 'industrial', 'personal', 'sport' or 'no_abuse'. The ITA directory structure is currently suitable for binary classification, 'abuse' or 'no_abuse' but can be changed for multiclass classification using the annotation file.

The initial test, train and val sub directories have 350, 75 and 75 video samples respectively.

The files have been zipped into 20MB files using 7zip. 7zip can be used to extract them all.
The directory structure is as such:

![image](https://github.com/SushovanNP/Inhumane-Treatment-of-Animals-ITA-/assets/66010602/00e6362b-bcf4-415a-9e33-96fb27771d2a)

