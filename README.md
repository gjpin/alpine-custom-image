# Build custom alpine ISO with iwd
```
sudo docker build -t alpine-iso .
sudo docker run -v "$(pwd):/build" -it alpine-iso
sudo chown $USERNAME:$USERNAME alpine-iwd-edge-x86_64.iso
```