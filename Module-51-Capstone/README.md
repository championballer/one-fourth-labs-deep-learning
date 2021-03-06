# Important details


1) Text Detection: An object detection engine to detect signboard objects in the given image

2) Text Recognition: A CNN-RNN encoder decoder model to convert the cropped signboard into text (a sequence of characters)

3) Transliteration: A sequence-to-sequence with attention model for transliterating the above sequence of characters to the desired language.

The datasets for each of these tasks is available at the below mentioned URLs:

1. Text Detection (Detecting bounding boxes containing text in the images)

Train Set: https://drive.google.com/open?id=1E5kI8CLoC-XffqQMTWwSpBIPp1Wb2tne

Test Set: https://drive.google.com/open?id=1Z6Qxr-q-F54iYB2G1AyoDymBh64f5REZ
(428 real images with annotations)

2. Text Recognition (Getting the text from the detected crop)

Train Set: https://drive.google.com/open?id=1E5kI8CLoC-XffqQMTWwSpBIPp1Wb2tne

Test Set: https://drive.google.com/open?id=1C0-mc0WAIdssS5KJwOjghaWaqiImZZUr
(1740 cropped word images from real pictures with annotations)

3. Transliteration (Transliterating Indic text to English)
Link: https://github.com/GokulNC/NLP-Exercises/tree/master/Transliteration-Indian-Languages/Original-NEWS2012-data