How to run Gemini Nano locally in your browser?

In this artile, I am going to share how to use Google Chrome(Developer) to run Gemini Nano.

Setup:
1.	Go to https://www.google.com/chrome/dev/
Download the Chrome Developer Version
2.	Go to chrome://flags
search prompt-api-for-gemini-nano
Select Enabled
search optimization-guide-on-device-model
Select Enabled BypassPerfRequirement

(/images/chrome_flags.jpg)

3.	Relaunch Chrome

4.	Go to chrome://components
Check Optimization Guide On Device Model version greater or equal to 2024.5.21.1031.

(/images/chrome_compoments.jpg)

5.	Press “F12” open DevTools and send
(await ai.assistant.capabilities()).available;
in the console.
If this returns “readily”, then you are all set.

Download test.html to your PC. Open it with Chrome Developer Version and enter your prompt.

(/images/test.jpg)

Now you can run Gemini Nano locally.
