# KillQQLoginSound
macOS下qq登陆声音真xxx


1 `brew install ffmpeg`
2 `ffmpeg -f lavfi -i aevalsrc=0 -t 1 -q:a 9 -acodec libmp3lame out.mp3&cp out.mp3 /Applications/QQ.app/Contents/Resources/LoginOKSound.mp3&mv out.mp3 /Applications/QQ.app/Contents/Resources/TerminalSound.mp3`
