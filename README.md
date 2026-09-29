# Fix-Betteralarm-  I reverse-engineered and patched the SpringBoard crash that happens on iOS 17 when you stop an alarm in BetterAlarm 1.4.1 (rootless). It works on my device (iPhone 14 Pro Max, iOS 17.0).

The .deb doesn't contain or redistribute BetterAlarm itself — it only patches the copy you already have installed, and only if it matches the exact known hash for the unpatched 1.4.1 build. If your version doesn't match, it does nothing.

Install at your own risk. I've only tested this on my own device. Keep a way to recover your phone (SSH access, or know how to boot/restore) before installing, just in case. 
