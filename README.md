##  Music🎵 player with Emotion😂😥😡😱 Recognition

### Code Requirements
- Tensorflow
- Download my repository
- Own Expression dataset(NOTE: You can downlaod expression images from google, or you can record your video make diffrent expression ,and
  converts into Grayscale images(For more accurate prediction))
- Song dataset


### What steps you have to follow??
- Download my repository 
- Make 'Images' folder in your project ,make subfolder for emotions like Happy,sad,Angry.
- Put `Face_crop.py` & `haarcascade_frontalface_alt.xml` in every type of image folder,ex : put this program in "happy' image folder and 
  run this program it will detect faces from images and convert it into grayscale and make a new images in same folder.
- Make 'Songs' folder make subfolders for emotions and put Songs,Like Happy songs in happy folder.
- After that you have to create model, for that copy code from code.txt file and open CMD in your project folder and paste it & enter
- It will take training aaround 20-25 minutes so keep patience.
- After training it will create two files `retrained_graph.pb` & `retrained_labels.txt`
- Now run `music_player_webcam.py` (give proper path of songs and Mediaplayer according to your location in code)
- If you want to fetch video from your mobile cam than use `music_player_android.py`,but you have to install IPWebcam app in your system
  and replace your server URL with my URL
- That's all 

### How it works? See:)

<img src="https://github.com/Spidy20/Music_player_with_Emotions_recognition/blob/master/Emotion_recognition_Music_player.gif">

### Notes
- It will require high processing power(I have 8 GB RAM & 2 GB GC)
- If you think it will recognise expression just like humans,than leave it ,its not possible.
- Download 300 Images for every expression(you can use batch downloader)
- Noisy image can reduce your accuracy so quality of images matter.

## Just follow☝️ me and Star⭐ my repository 
