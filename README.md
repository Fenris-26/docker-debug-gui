# docker-debug-gui
thomas-variant-novnc

build :  sudo docker build -t treycraf7/gui-debug . 
run: sudo docker run -it --rm -p 80:6901 treycraf7/gui-debug 
# must run the start_vnc.sh script upon entering bash. 
# after it runs, will prompt with a password to connect to the vnc server @ "static address (http or HTTPS"
