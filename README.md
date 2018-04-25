# Converting video to audio

You  can convert whole folder of videos into audio format.-
It is for linux users.    
Install ffmpeg by typing :- sudo apt install ffmpeg   in terminal.     
Then Navigate to the target folder.    
Then type following command:-    
for f in *.mp4;do ffmpeg -i "$f" -ab 320k  "${f%.mp4}.mp3";done    
     
And it start doing its job.    
