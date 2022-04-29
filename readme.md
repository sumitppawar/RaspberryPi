
```script
nc -l -p 9090
nc -l -p 9090 < VID_20220307_195103639.mp4
netcat -l -p 8111 < 3.mp4
netcat localhost 8111 | cvlc -
netcat 192.168.43.252 65533 | vlc -


netcat -l -p 8111 <3.mp4
cvlc -I rc --rc-host localhost:8111 -d
alias vlc='/Applications/VLC.app/Contents/MacOS/VLC'

https://unix.stackexchange.com/questions/79103/stream-video-using-netcat-and-vlc
sudo apt-get install libcblas-dev
sudo apt-get install libhdf5-dev
sudo apt-get install libhdf5-serial-dev
sudo apt-get install libatlas-base-dev
sudo apt-get install libjasper-dev 
sudo apt-get install libqtgui4 
sudo apt-get install libqt4-test
```
