# How to use the Subtitles

Unlike other projects aiming to subtitle the show (Typically by burning-in the subtitles and re-uploading the episodes to YouTube), this project aims to provide the subtitles in such a way that does not infringe on the copyright of the show. This means that the subtitles are provided in the form of `.srt` files, which can be used with any media player that supports subtitles.

`.srt` files are a type of subtitle file that can be used with most media players. They contain the text of the subtitles, as well as the timecodes for when the subtitles should appear on screen. This means that the subtitles will automatically appear on screen at the correct time when the video is played. For instance:

```srt
1
00:00:00,000 --> 00:00:02,000
Hello, World!
```

This would display the text `Hello, World!` on screen from 0 seconds to 2 seconds into the video. 

While `.srt` files may look scary, they're actually quite simple to use. Here's a quick guide on how to use them:

## How to Use `.srt` Files
### 1. Download the Subtitles
First, you'll need to download the subtitle for the episode you want to watch. You can either download the entire repository as a `.zip` file, or you can download the individual `.srt` files from the `s2` folder. 

### 2. Download the episode you want to watch
As of right now, there is no *official* way to import `.srt` files into YouTube. This means that you have two options:

A) Download the episode you want to watch. You can do this by using a YouTube downloader like [yt-dlp](https://github.com/yt-dlp/yt-dlp), or any other online YouTube downloader.

B) Use my [Chrome Extension](https://github.com/IbraTech04/youtube-srt-injector) that injects the subtitles into the YouTube player. This is a bit more complicated, but it's the only way to watch the episodes with the subtitles on YouTube.

Please note that the subtitle injector is still in beta and unstable. It may not work as expected, and as such using a YouTube downloader is recommended.

### 3. Play the episode
Open the episode you downloaded in your media player of choice. Most media players support `.srt` files, so you shouldn't have any issues with this. Then, locate the option to add subtitles to the video. This is typically found in the `Subtitles` or `CC` menu. Select the option to either add or select a subtitle file, and then navigate to the `.srt` file you downloaded earlier. Select the file, and the subtitles should automatically appear on screen at the correct time! 

OR 

If you're using the Chrome Extension, simply open the episode on YouTube and paste the raw link to the SRT file in the extension's settings. The subtitles should automatically appear on screen at the correct time!

You can find the raw link by clicking on the `.srt` file you want to use, and then clicking the `Raw` button in the top bar. Copy the URL of the page that opens, and paste it into the extension's settings.

And that's it! You should now be able to watch the episode with the subtitles. If you have any issues, feel free to open an issue in the `Issues` tab and I'll do my best to help you out. Enjoy the show! 🎉