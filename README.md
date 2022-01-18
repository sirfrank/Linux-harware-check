# Linux-hardware-check command line tools (ubuntu)

## general data
cmd : htop \
shows: CPU usage, RAM size/usage, swap file size/usage\
install : sudo apt install htop\
source : my brain, lol

## Intel Core i7, i5, i3 CPU information
cmd : sudo i7z \
shows: CPU information including temperatures , physical and virtual cores\
install : sudo apt install i7z \
source : https://www.tecmint.com/monitor-cpu-and-gpu-temperature-in-ubuntu/

## Find graphic cards
cmd: lspci | grep VGA \
shows: GPU card's model \
install : preinstalled \
source : https://askubuntu.com/questions/72766/how-do-i-find-out-the-model-of-my-graphics-card \
note : (better than "sudo lshw -C display -short" as it shows manufacturer also)
