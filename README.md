# UPS_(With_RTC_&_Coulometer)_For_Raspberry_Pi_SKU:_EP-0118
It is demo code for 52Pi UPS (With RTC &amp; Coulometer) For Raspberry Pi SKU: EP-0118
## WIKI URL 
* (UPS with RTC and Coulometer For Raspberry Pi SKU: EP-0118）[https://wiki.52pi.com/index.php/UPS_(With_RTC_&_Coulometer)_For_Raspberry_Pi_SKU:_EP-0118]
## How to use
* login to Raspberry Pi which running Raspbian (The latest version) 
* Turn on I2C function via "sudo raspi-config" and navigate to "interfaces options" and enable I2C.
* Assemble UPS to Raspberry Pi with screws and copper sticks.
* Open a terminal and typing following command:
```bash
git clone https://github.com/geeekpi/upsv3.git 
cd ~/upsv3/
sudo pip3 install pi-ina219
sudo python3 demo.py
```
* More Information please contact us at: https://www.facebook.com/groups/geeekpi/
## Have Fun
