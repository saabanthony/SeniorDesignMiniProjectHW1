Results of the Hardware Miniproject for Anthony Saab (U90831072) and Paul Stephen Hutchinson Maltaghati (U80438188)

After receiving the Raspberry Pi in class and the microSD card from Micro Center, we were successful in downloading the Raspberry Pi OS setting up all of the latest Raspberry Pi updates. We set up our Raspberry Pi in Ingalls where we used the available monitor and keyboard to get started. We were successful in collecting bluetooth data there, as we collected data from both BU devices as well as our own. We then completed the rest of our work in the Photonics senior design lab, where set up the Pi next to the window in order to collect as many wifi hotspots as possible, specifically those comming from cars passing by. While the code was running, we noticed that the only hotspots we were collecting were BU wifi (802.1x, Guest, and VPN) and eduoram. While we did not specifically notice any car wifi hotspots pop up in our JSON file data, our plots show that there was a change in hotspots captured over time, so it is possible that car data was obtained.   

Here are the first and second attempts at collecting data, where the first was generated using 100 datapoints and second was generated using 250 datapoints:

![Figure_miniproject](https://user-images.githubusercontent.com/74400483/133842951-134c3148-3530-40bf-a621-ba5ca3ea0ec4.png)
![Figure_2_Miniproject](https://user-images.githubusercontent.com/74400483/133842957-2ff43c8f-7d50-41d5-911a-42de39ee2c8c.png)

We then decided to try collecting Bluetooth data to see if we would get more significant results. While we did notice a change in bluetooth signals over time, we were not able to comfirm that we connected to any cars via bluetooth and thus were not able to monitor the cars passing by. If we had had significant results we could have estimated the amount of carbon dioxide emmited on the highway next to photonics for the given amount of time. However, it seems like the window is too far from the highway and therefore we could not collect any significant data. We also tested the bt_scan.py script to see if we could connect to additional devices. Initially, we were unable to make any connections, but after we both turned roaming on for our headphones, the Pi connected to the two devices.

Here is a screenshot of what we got from running bt_scan.py and ble_scan.py:

![2021-09-17-155441_2560x1440_scrot](https://user-images.githubusercontent.com/74400483/133846343-63f50a01-600d-4d43-9fdd-e43156e491fc.png)

We were both able to learn a lot from this project and gain a lot of experience working with the Raspberry Pi. This was the first time that both of us used Pi for a project, and it gave us a better understanding of how single-board computers work. We will definitely be using the knowledge we gained from the miniproject to help us on the senior design project we will each be working on for the remainder of the year.
