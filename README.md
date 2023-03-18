# A cli tool built on top of Node.js to download videos from skill-capped.

This cli assume that u have **installed [aria2c](https://github.com/aria2/aria2/releases) , [ffmpeg](https://www.gyan.dev/ffmpeg/builds/ffmpeg-git-full.7z) and accessible from your terminal**.

# Usages
   ## 1.Download a single video
    
```
            skillcapped.exe --video VIDEO_URL
```
   ## 2.Download Full Course
    
```
            skillcapped.exe --course VIDEO_URL
```
   ## 3.Download list of random videos
   
    create a .txt file and put all the video links.Links should be separated by a comma.
    
```
            skillcapped.exe --list test.txt
```

