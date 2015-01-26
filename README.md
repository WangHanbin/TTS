
# TTS
## Description
This program is developed in python. It can convert text to speech based on google translation engine.  
 Most of the codes comes from [hungtruong][1], however, I do some changes to make it **can be used in China and supports Chinese** now.

## How to use it ?
This program switch the operations by command line arguments.  
**_For example:_**
>1. A **String** to convert to speech
>```
> python tts.py -l en -o test.mp3 -s hello
> python tts.py -l zh -o test.mp3 -s 你好吗老韩 
> ``` 

>2. A **File** to convert to speech
>```
>  python tts.py -l en -o test.mp3 -f hello.txt  
>  ```

## Note:
1. Language mapping:
    >en-> English  
    zh-> Chinese  
    ja-> Japanese     
      
2.  Background  
 [Hacking Google’s Text To Speech “API”][2]

[1]:https://github.com/hungtruong/Google-Translate-TTS
[2]:http://www.hung-truong.com/blog/2013/04/26/hacking-googles-text-to-speech-api/