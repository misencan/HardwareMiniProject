# HardwareMiniProject
In this project, we learned to use the Rasperry Pi to scan bluetooth and Wifi devices nearby. We successfully obtained the bluetooth data however had an issue with measuring WiFi. One difficulty we faces was an error we kept getting while scanning WiFi's. 
The error was:
"subprocess.CalledProcessError: Command '['iwlist', 'wlan0', 'scan']' returned non-zero exit status 255.

After scanning the Wifi devices, the code would stop midway and give this error, which made it difficult for us to get measurements for 15 minutes

Based on the bluetooh measurements and about 5 minutes of WiFi measurements, our Rasperry Pi seems to be successful at finding the nearby devices.
However, we were not able to observe as many traffic cars as we thought. We believe this issue is related to location problems of our testing.
