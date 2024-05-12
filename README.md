# Sendokai Champions Subtitles 
An open-source repository aiming to be a collaborative effort to recreate English subtitles for the show "Sendokai Champions" (AKA "Defasio Champions Sendokai")

*Instructions for how to contribute can be found below*

## Premise 
[Sendokai Champions](http://www.sendokaichampions.com/) (Known as *Defasio Champions Sendokai* in Spanish) is a Spanish animated series developed by Kotoc Productions and produced by RTVE, Planeta Junior, and Kotoc. Aired in 2013, the show was originally aired in Spanish, and later dubbed in English for airing on Cartoon Network. However, the English dub is now considered *Lost Media* after being taken down from their [Official YouTube Channel](https://www.youtube.com/@SendokaiChampionsEnglish), with no other Official hosting. Currently, only the Spanish version is available on their [Official YouTube Channel](https://www.youtube.com/@SendokaiChampions), and very few English-dubbed episodes are available on the internet - most of which are low-quality and incomplete. The entirety of Season 1 was archived and uploaded to a [YouTube Channel](https://www.youtube.com/@sendokaichampions7678), and only the first few episodes of season 2 can be found archived on websites like BilliBilli and KissCartoon.

We *know* the English version exists *somewhere* since the [Arabic Version](https://www.arabic-toons.com/m7arbi-sendokai-1434722187-11112.html#sets) is based off the English version. 

Many members of the Sendokai community have tried to create English subtitles for the show in the past (By downloading the Spanish version, chucking it into a video editor, and adding subtitles via burned-in text tools), however they were never completed due to either:
- Lack of resources (Time, Money, etc.)
- Copyright Takedowns (Remember, they're uploading basically the same episodes as the official channel; Fair use doesn't apply here)
- Lack of motivation (The show is relatively obscure, and the community is small)

This repository aims to rectify the above by doing the following

- Creating a collaborative effort to create English subtitles for the show - With the community working together, there will always be someone to pick up the slack if someone else is busy
- Hosting **only** the `.srt` subtitle files - The original issue with the burned-in subtitles was that they still contained the copyrighted material (i.e. the video itself). By hosting only the `.srt` files, we can avoid this issue entirely. The issue of copyright now falls onto the user choosing to download the `.srt` file and the video file, and not the repository itself

## Progress:
Currently, we're focusing on the second season since it's the most saught after. Once we finish the second season, the first season can be done easily since it's already available in English.

What [@IbraTech04](https://github.com/IbraTech04) has done so far:
- Rip all (auto-generated, or manually generated where applicable) subtitles from the Spanish version of the show from YouTube and compiled them into `.srt` files. These are mostly here for reference and aren't strictly necissary for the project, but they're here if you want them. 
    - You may choose to contribute to the Spanish version if you prefer, even that would be a great help since we could more accurately translate the Spanish version to English! 
    - You can find all the subtitles in the `s2` folder. There are two subfolders: `en` and `es` for English and Spanish respectively.
- Translated the Spanish subtitles into English using Google Translate 
- Manually corrected a few episodes
    - It's worth noting that I don't speak Spanish. I uses the auto-generated English translations along with my knowledge of the plot from the Arabic version to correct the subtitles. 
    - I noticed the Spanish dub on YouTube uses the same lip-sync as the English dub, so I try to read their lips to get a better translation.
- Created subtitles for the one episode that had its subtitles disabled (Episode 50)

**Legend:**
- 🟩 = Completed
    - This means that the subtitles for this particular episode are complete and ready to be used
- 🟦 = Abandoned
    - This means that the subtitles for this particular episode are incomplete, and the person working on them has abandoned the project. If you're interested in helping out, feel free to claim it in the `Issues` tab!
- 🟨 = In Progress
    - Someone has claimed this episode and is currently working on it. Check the `Issues` tab to see who's working on it!
- 🟥 = Not Started
    - No one has claimed this episode yet. If you're interested in helping out, feel free to claim it in the `Issues` tab!

- \* $\implies$ Episode has a surviving English dub, and is much easier to subtitle


**Season 2:**
- [🟩] Episode 27 - A Good Story*
- [🟩] Episode 28 - A New Adventure* 
- [🟩] Episode 29 - Danima*
- [🟨] Episode 30 - Yakis*
- [🟥] Episode 31 - Trust Us, Lon*
- [🟨] Episode 32 - Kido the Destroyer*
- [🟥] Episode 33 - Babysitter 
- [🟥] Episode 34 - An Unbreakable Team 
- [🟥] Episode 35 - Duo-Sen Lightning Bolt 
- [🟥] Episode 36 - A Good Leader 
- [🟥] Episode 37 - Uncertain Times 
- [🟥] Episode 38 - I'll Never Forget You 
- [🟥] Episode 39 - Stupid Sendokai 
- [🟥] Episode 40 - The First Great Tournament 
- [🟩] Episode 41 - The Norkingos 
- [🟩] Episode 42 - A Hero For Masara 
- [🟥] Episode 43 - You Are Alone 
- [🟩] Episode 44 - Friends and Rivals 
- [🟩] Episode 45 - May The Best Team Win 
- [🟩] Episode 46 - Traitors 
- [🟩] Episode 47 - The Twilight of the Hakuru 
- [🟩] Episode 48 - The Hour of Truth 
- [🟩] Episode 49 - The Power of the Baron 
- [🟩] Episode 50 - The Great Zorn 
- [🟩] Episode 51 - Rise of the Hakuru 
- [🟩] Episode 52 - Something in Common


## How to Contribute
Ready to help out? Great! Here's how you can get started:

**This repository relies on GitFlow**. If you're not familiar with Git, I reccomend you read up on it before contributing. You can find a great guide [here](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

### Step 1: Claim an Episode
First, check the progress section above to see which episodes are available. If you see an episode that's not claimed, feel free to claim it by creating an `Issue` in this repository. This will let others know that you're working on it, and will prevent others from working on the same episode at the same time (causing merge conflicts). If someone else is working on the episode you want to work on, feel free to reach out to them and see if they need any help!

### Step 2: Acquire the required resources
You'll need to acquire the Spanish version of the episode you're working on. You can do this by downloading the episode from the [Official YouTube Channel](https://www.youtube.com/@SendokaiChampions) using an online tool. 

You'll also need a `.srt` editor. I personally reccomend [Subtitle Edit](https://www.nikse.dk/subtitleedit/), but you can use any `.srt` editor you like.

### Step 3: Clone this repository
You'll need to clone this repository to your local machine. You can do this by running the following command in your terminal, or using the GUI buttons on the GitHub website. If you really wanna get fancy, you can use [GitHub Desktop](https://desktop.github.com/) to clone the repository.

### Step 4: Subtitle the Episode! 
Once you're all setup, you can start subtitling the episode! You can do this by opening the `.srt` file for the episode you're working on in your `.srt` editor, loading in the episode, and adding the subtitles. Once you're done, save the file and move onto the next step.

This step will take you the longest, at around 20-30 minutes per episode.

### Step 5: Push your changes and create a Pull Request
Once you're done, push your changes to the repository and create a Pull Request. This will let others know that you're done, and will allow others to review your work. If there are any issues, you can make the necessary changes and push them to the repository. Once your Pull Request is approved, your subtitles will be added to the repository and marked as complete!
