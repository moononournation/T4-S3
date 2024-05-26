# T4-S3

## AVI

```sh
ffmpeg -i input.mp4 -c:a mp3 -c:v mjpeg -q:v 10 -vf "fps=10,scale=-1:450:flags=lanczos,crop=600:450:(in_w-600)/2:0" AviMp3Mjpeg450p10fps.avi

ffmpeg -i input.mp4 -c:a mp3 -c:v cinepak -q:v 20 -vf "fps=15,scale=-1:448:flags=lanczos,crop=600:448:(in_w-600)/2:0" AviMp3Cinepak448p15fps.avi
```
