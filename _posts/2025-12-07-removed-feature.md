---
layout: post
title: "Removed Feature"
date: 2025-12-07
categories: post
---

## Removed Feature

In my first post I alluded to a feature that I personally would never make public and is Google Maps Navigation.

Before I go too deep into this my reasoning behind removing this feature is 100% based on reliability and support. Theoretically this feature works and is integrated but it's very hacky and I absolutely don't trust this.

My fear with actually releasing this feature is WHEN it goes wrong I'll be flooded with messages and support requests.

## How Does It Work?

Well my requirements for this feature to work are absolutely no api or server backends which eliminates Google Cloud and basically everything else hence the hacky workaround needed to implement this. 

Currently it reads the Google Maps notification for directions specifically compass directions (North, West, South etc.) and then converts that into directions (Left, Right, Forward etc.) for the Glyph Matrix.

I've done very minimal testing for this so in the current 1.7 build it's disabled entirely and commented out. All I've been able to confirm about this feature is that the glyphs work and that it can parse the Google Maps notifications.

# Why even implement this?

I saw a tweet from @JayAlto on X (Twitter) that sums up my thoughts perfectly regarding these personal projects of mine

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">no piece of advice has had more of an impact on my life than &quot;make the thing you wish existed.&quot; wish a certain podcast existed? cool, go record it. wish a certain product existed? cool, go build it. wish a certain essay existed? cool, go write it.</p>&mdash; Jay Alto (@theJayAlto) <a href="https://twitter.com/theJayAlto/status/1997009518660931898?ref_src=twsrc%5Etfw">December 5, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

I saw a chance to make something that would be fun for me. I saw people in the Nothing community requesting features. I saw apps that did something similar but I thought could be improved

## You think you're better than them?

Absolutely not, I just saw glyph toys that I thought could be improved. Like the music visualizer for instance. There are a lot of already existing implementations but none where I could see the current song progress. All had cool quirky visuals, some had showed the title and artist. None did all of that and showed visually the song's progress.

Another example is the weather toy. I understand the limitations of most APIs and how inaccurate they can be but still it should be an easy implementation but I haven't seen anything for the Glyph Matrix yet. I understand it's kinda pointless for current weather but I also implemented "Forecast Time" it allows you to pick from today, tomorrow or day after and also shows a small visual indicator in the top right that is easy to see at a glance what day the weather is for.

Again really simple ideas but just small things I thought would be fun

## What's next?

Well currently I have to remove the notification permission that is leftover from the Google Maps glyph toy and then I need to redo the visuals for the new quick settings feature I implemented.

It's a very pointless feature imo but fun. I had to target a lower Android SDK version which means I probably can't release this on the playstore not that it was ever an option to me. The lower version allows me to toggle wifi and bluetooth without any extra hacky workarounds, it just works. 

## Future and open source?

It's been suggested I post this to the Nothing Playground website and GitHub multiple times from various people. A playstore release is 100% out of the question I'd literally lose money and have support requests and bugs that I literally couldn't care less about.

Nothing Playground is a maybe, there's probably a higher chance of me posting this to GitHub

As for GitHub I'm open to posting it with 2 caveats. 1 being the repo has to be archived that removes all possible support and issues which is my biggest concern. 2 I'd want to implement a full screen visual on startup that tells the users the app is provided as is and no support will be given.

If they accept they can proceed to onboarding, if they decline it'll take them to app info where they can uninstall it. 
