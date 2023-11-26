
Thanks to VolosR, I can have a good M5Dial watch design (watchESPI.ino). I updated the code to show real time and to adjust with NTP server.

Now only watchESPI is updated in devel branch.

## Note
- After boot-up, M5Dial will connect to WiFi AP
- If WiFi connection successful, adjust system clock with NTP server. At this timing, 3 stars blink at the center of LCD.
- When Btn of M5Dial is pressed, the system clock is adjusted with NTP server. 3 stars blink and the other display is freezed.


