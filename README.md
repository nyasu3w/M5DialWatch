
Thanks to VolosR, I can have a good M5Dial watch design (watchESPI.ino). I updated the code to show real time and to adjust with NTP server.

Now only watchESPI is updated in devel branch.

![image](https://github.com/nyasu3w/M5DialWatch/assets/125797829/018c97c2-2c8a-4049-90c5-f73931992601)


## Note
- After boot-up, M5Dial will connect to WiFi AP if system time looks wrong.
- If WiFi connection successful, adjust system clock with NTP server. While connecting WiFi, 3 stars blink at the center of LCD.
- When Btn of M5Dial is pressed, the system clock is adjusted with NTP server. 3 stars blink and the other display is freezed.


