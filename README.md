# M5Dial-GPS-Logger
M5Dial with AT6558 GPS unit configured as a GPS Logger

ChatGPT starting Prompt:
Need code to make a GPS logger with a M5 Dial and GPS/BDS unit (AT6558 & MAX 2659) connected to Port A, that records NMEA data in GPX format (lat, long, elevation and time) in files saved by daily and named by the nearest Australian State/Territories city in format YYYYMMDD-StateCity.GPX.

Only record position data if unit moves more than 2m.

Write the code for upload in Arduino IDE 2.3.2

Enable the following functions:

Enable logging with power on
Enable toggle on/off with main button click
Enable G27 LED to turn Red when Power On
Enable G27 LED to Blue program started but Satellite fix not yet enabled
Enable G27 LED to Flash Green when logging data to SD Card
Enable G27 LED to Flash Red when in error
Allow a Wi-Fi connection to get NTP data (when Wi-Fi available) and read the SD remotely via a we browser
Put WiFi Credential in 'secrets.py' file and use Wi-Fi SSID "Mumbo-Jumbo" & password "BPJY3Z5RF8@23"
Use Wi-Fi Password "BPJY3Z5RF@"
Allow a Bluetooth connection for iOS Bluetooth Terminal functions
Pick Nearest Australian city by size of city as at least 5% of State/Territories population (generate this list (for all Australian and New Zealand States/Territories) in the code with latitude and longitude sorted by State then City)
