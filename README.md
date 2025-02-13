# fr3068e-c-micropython
#使用富芮坤FR3068x-C开发板，实现MicroPython实现本地音乐播放
#mp3转wav格式，借助ffmpeg工具，发送指令示例如下：
ffmpeg/ffmpeg.exe -i horizon.mp3 -ac 1 -ar 16000 -acodec pcm_s16le -ss 00:00:00 -t 00:02:00 horizon.wav
ffmpeg/ffmpeg.exe -i onlyloveyou.mp3 -ac 1 -ar 16000 -acodec pcm_s16le -ss 00:00:00 -t 00:01:30 onlyloveyou.wav
ffmpeg/ffmpeg.exe -i qifengle.mp3 -ac 1 -ar 16000 -acodec pcm_s16le -ss 00:00:00 -t 00:01:00 qifengle.wav
