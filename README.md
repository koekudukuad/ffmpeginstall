# ffmpeginstall
ffmpeginstall
wget https://johnvansickle.com/ffmpeg/releases/ffmpeg-release-amd64-static.tar.xz
tar xf ffmpeg-release-amd64-static.tar.xz
cd ffmpeg-*-amd64-static
cp ffmpeg /usr/local/bin/
cp ffprobe /usr/local/bin/
ffmpeg -version
