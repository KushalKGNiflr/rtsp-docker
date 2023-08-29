# rtsp-docker

Execute this using command: 
docker run --rm -it -p 1935:1935 -v $PWD/videos:/videos -v $PWD/mediamtx.yml:/mediamtx.yml bluenviron/mediamtx:latest-ffmpeg


Change camera rtmp path to (in UNV website):
rtmp://192.168.0.154/8854	
