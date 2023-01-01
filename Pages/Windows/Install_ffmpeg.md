- https://self-development.info/windows%E3%81%ABffmpeg%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%99%E3%82%8B/

choreo masterの.vttファイルを動画に結合するためにffmpegを利用する.

> ffmpeg -i 3450626.3459932.mp4 -i 3450626.3459932.vtt -map 0:v -map 0:a -map 1 -metadata:s:s:0 language=jpn -c:v copy -c:a copy -c:s srt fuga.mkv