Results of the Hardware Miniproject for Anthony Saab (U90831072) and Paul Stephen Hutchinson Maltaghati (U80438188)

After receiving the Raspberry Pi in class and the microSD card from MicroCenter, we were successful in downloading the Raspberry Pi OS, setting up the Raspberry Pi and used the Lab in Photonics to collect wifi data from cars. Prior to collecting wifi data from Photonics, we had first set up our Raspberry Pi in Ingalls where we used the available monitor and keyboard to get started. We were successful in collecting bluetooth data there. In the Photonics lab, we have set up the Pi next to the window in order to collect as many wifi hotspots as possible, specifically those comming from cars passing by. We noticed that the only hotspots we were collecting were BU wifi (802.1x, Guest, and VPN) and eduoram, and therefore could not extract any meaningful information from the cars passing by.  

Here are the first and second attempt at collecting data: first was 100 datapoints and second was 250 datapoints

![Figure_miniproject](https://user-images.githubusercontent.com/74400483/133842951-134c3148-3530-40bf-a621-ba5ca3ea0ec4.png)
![Figure_2_Miniproject](https://user-images.githubusercontent.com/74400483/133842957-2ff43c8f-7d50-41d5-911a-42de39ee2c8c.png)

We decided to try collecting Bluetooth data to see if we would get more significant results. Unfortunately, we were not able to connect to any cars via bluetooth and were not able to monitor cars passing by. If we had had significant results we could have estimated the amount of carbon dioxide emmited on the highway next to photonics for the given amount of time. However, it seems like the window is too far from the highway and therefore we could not collect any significant data.

Here is what we got from running bt_scan.py (ble_scan.py did not yeild any better results)

<img width="1680" alt="Screen Shot 2021-09-17 at 15 44 20" src="https://user-images.githubusercontent.com/74400483/133845183-9249f5d9-b1e2-4803-97b6-5c5fe3b1e8ab.png">
