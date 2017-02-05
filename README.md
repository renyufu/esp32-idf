# esp32-idf
Docker image for esp32-idf.

# Usage
```
sudo docker run --rm -it -v yourprojectdir:/proj renyufu/esp32-idf
sudo docker run --rm -it -v yourprojectdir:/proj renyufu/esp32-idf menuconfig
sudo docker run --rm -it -v yourprojectdir:/proj renyufu/esp32-idf all
sudo docker run --rm -it -v yourprojectdir:/proj renyufu/esp32-idf app
sudo docker run --rm -it -v yourprojectdir:/proj --device /dev/ttyS0 renyufu/esp32-idf flash
```
