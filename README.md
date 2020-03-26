# Better

This is the frontend of a proof of concept I developed for manipulating traffic from the specific [online random choice utility](https://www.textfixer.com/tools/random-choice.php) that one of my teachers used to select students for in-class assignments. I never actually used it because I have a conscience.

The backend, whose source is lost to time, was a Raspberry Pi running a Node.js server controlling an [arpspoof](https://linux.die.net/man/8/arpspoof)/[evil twin](https://en.wikipedia.org/wiki/Evil_twin_(wireless_networks)) Man in The Middle setup along with [sslstrip](https://github.com/moxie0/sslstrip) for redirecting HTTPS traffic to use insecure HTTP.

[`MainActivity.java`](app/src/main/java/com/base512/better/MainActivity.java) was last modified October 29, 2016.
