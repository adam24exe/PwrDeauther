# PwrDeauther (V. 2.0)
PwrDeauther is an automatic deauthentication script that uses MDK3. MDK3 offers greater power than Aireplay. This script empowers users to deauthenticate either a specific SSID (Option 1) or an entire channel (Option 2).

## Showcase video

Check out our showcase video

<a href="https://youtu.be/ZiujaDVpdEk"><img src="https://i.imgur.com/f82biKP.png"></a>

## Preview

<img src="https://raw.githubusercontent.com/125K/PwrDeauther/master/img/1.png">

<img src="https://raw.githubusercontent.com/125K/PwrDeauther/master/img/2.png">

If you've found this project helpful and wish to support its development, you can donate:

<a href="https://www.buymeacoffee.com/rSiZtB3" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## Dependencies

MDK3 `sudo apt-get install mdk3`: https://github.com/wi-fi-analyzer/mdk3-master

MACCHANGER `sudo apt-get install macchanger` https://github.com/alobbs/macchanger

NMCLI `Preinstalled on most distros.`: https://github.com/mvidner/nmcli

## Notes
Certain Intel® hardware, particularly Centrino, may encounter issues due to the operation of MDK3. From the MDK3 documentation:

`MDK3 uses the drivers and Injection routines from this project and its predecessor. Thus, all drivers listed there should work with MDK3. (Some special hardware, like Intel Centrino (ipw2200) is NOT supported since they can only inject data, and no management information!)`

## Instalation
  1. Download the files `git clone https://github.com/125K/PwrDeauther.git`

  2. Dependency installation

  2.1. Method 1: `sudo chmod +x install.sh` and  `sudo install.sh`

  2.2. Method 2: manualy add sources and install packages listed above

  3. Run the script `sudo chmod +x PwrDeauther.sh` and `sudo PwrDeauther.sh`
  
Special thanks to <a href="https://github.com/digmorepaka">@digmorepaka</a>.

## Related links
Wi-Fi deauthentication attack: https://en.wikipedia.org/wiki/Wi-Fi_deauthentication_attack

Difference between Aireplay and MDK3: https://security.stackexchange.com/questions/61211/wifi-deauth-attack-difference-between-aireplay-and-mdk3

mdk3 Package Description: https://tools.kali.org/wireless-attacks/mdk3

## Check out my other projects

- **WiFi-Spam**: :email::satellite: Spam thousands of WiFi access points with custom SSIDs.
  - https://github.com/125K/WiFi-Spam

- **ESP8266 WiFi Captive Portal**: :key: WiFi captive portal for ESP8266 for phishing WiFi passwords.
  - https://github.com/125K/ESP8266_WiFi_Captive_Portal
  
## Disclaimer
This project is intended for testing and educational purposes only. Please use it responsibly and only on networks and devices you own. I do not take any responsibility for misuse of this program.
