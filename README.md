# Lockcord
![Lockcord icon](https://i.postimg.cc/W4GxsDTy/icon.png)

Lockcord is an Android WebView client for Discord that wraps the mobile site into a standalone Kotlin app. I made this because the official Discord app is full of trackers and I didn't like that the mobile site couldn't be made into a PWA, and I prefer to keep apps in my app drawer instead of having shortcuts on the homescreen. I'm releasing it here for the likely small number of users out there who feel similarly.

### Consider the following:
- There is no voice chatting enabled for the Discord mobile site. Even when changing the user agent to that of a desktop browser, the microphone will still not be detected regardless of which permissions the app is given. Maybe this will bother me enough to further persue workarounds, or maybe not. I rarely voice chat on my phone and this app was ultimately made for my use cases.

- When using 3 button navigation, the back button will exit to launcher instead of returning to the previous page in the app. The onBackPressed function is deprecated and every workaround I've tried to find for webview has not worked. The mobile site is very wonky when it comes to the back button as well so in the end it doesn't really bother me. If I end up finding a way to fix it I probably will but for now its fine for me.

- ***I AM NOT (TYPICALLY) A DEVELOPER.*** I spent about 4 days learning Java and Kotlin because I spontaneously had the idea to make this and wanted to see it through. As a result, most of the code was written thanks to various stackoverflow answers found on DuckDuckGo from the last 10-15 years. That being said, I plan to keep learning Kotlin so I will probably work more on this app in the future.

### Download
You can add this repo to obtanium if you'd like, but for the most part don't expect frequent updates. I'm fine with this project as it is because it suits my needs. If you would like to download the APK, feel free to check the releases tab or click the button below:

[<img src="https://i.postimg.cc/6QTVWgry/148696068-0cfea65d-b18f-4685-82b5-329a330b1c0d.png">](https://github.com/SailingTheMoon/lockcord/releases)

### Disclaimer
Discord is a product of Discord Inc. and this project is in no way affiliated with it. "Discord" and any mention of it are purely descriptive. 
