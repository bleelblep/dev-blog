---
layout: post
title: "Thoughts about making Glyph Buddy public"
date: 2025-12-05
categories: general
---

# What is Glyph Buddy?

Glyph Buddy is a personal project for my recently acquired Nothing Phone (3). It utilizes the 25x25 LED array on the back that Nothing calls the "Glyph Matrix."

## What's the deal then?

I tried (and in my personal opinion failed) to make an application for all Nothing Phones (actually 2 applications) called Glyph-Zen and Glyph-Sharge. The first was a breathing exercise app that used the glyph lights on the back of Nothing phones to help guide a person through box breathing or 478 breathing patterns. The latter was a "toolbox" of random ideas from cool unlock patterns using the glyph lights to battery stuff (I kinda forgot the features tbh.)

## What are you rambling about!

Basically I believe I failed because the app was buggy as fuck and it turned from a personal project into a let's make this thing for others which meant support and bug fixes and all for something that was meant to be fun and only for me.

Glyph Buddy is my new "toolbox" or all in one app but for the Glyph Matrix. This time however I don't really plan on making it public. I've posted a few APKs (latest public one being v1.4) and beyond a few minor bugs I think it's in a quite good state.

## Why not make public and open source!

Honestly I don't want to provide support for anyone. I don't want to deal with the issues that come with posting projects online. This is purely for me and making my phone fun. 

For instance there's a "weather glyph toy" where the user can choose a location (manually or via GPS) then configure if the Glyph Matrix will show either today's, tomorrow or day after weather conditions via animated icons and text with current temp and conditions via a long press of the glyph button.

Now the issues that come with making this public are:

1) Weather API support
2) General support from users
3) Complaints and feature requests

I originally used openweathermap as they allow you to sign up and get a free API key (I made the app ask the user for this API key). Which posed a little issue when I posted the APK, a user couldn't figure out how to get or use the API key.

I'm certain they either copied the key wrong or entered it wrong. Regardless this brings up issues 1 and 2. 

## API Support? What's that!

Basically a company will allow developers to use their services in their own app. The one we are focusing on is Weather APIs. 

In simple terms I'm not personally recording the temperatures of every city and predicting the weather, that's a silly idea. Instead I'm using another company that already does that and will allow me to fetch weather data based on a user's location.

That doesn't seem like a problem right? The issue is rate limits. It's essentially an allowance you get every X period of time. With a handful of users that isn't a problem at all but if you scale this it can become a real issue and that means I'd have to pay for a higher tier or I'd have to provide support for users to grab their own API key which isn't feasible.

I don't know the rate limit for openweathermap but the second "API Keyless" weather provider I implemented and changed to default has around 10k API calls a day, completely free and no API key needed. I could probably get away with posting this to GitHub but that's where issue 3 comes into play.

## You don't want to support your users?

I didn't make this app for anyone else but me. I don't care that their weather information is incorrect. I don't care they can't set it up. I don't care about X, Y, Z feature because 1) I'm not getting paid for this and 2) it doesn't make me happy.

Does that make me an asshole? Probably but I have my own reasons for this that I won't disclose here. My main focus is for this to be fun and to enjoy myself. I fear making this any kind of public will kill that entirely. 

## What would it take for you to make this public?

Essentially I'd need to post it then immediately abandon it or have every user understand that the project is AS-IS and if it doesn't work well I'm not gonna spend hours trying to fix it.

There's also the issue of posting this on the Play Store. 1) it costs money which isn't worth it if I post it for free. 2) privacy concerns, Google now requires developers to publicly disclose their location and email address for anyone to see.

Again it just isn't worth it. I could probably charge a few dollars and make money but (this might come as a shock.) I don't care about the money. 

## So why even do this then?

Because I enjoy making things for my phone. I enjoy the process and the iteration of coming up with ideas and implementing them. It's a small thing but it makes me happy and that's what I care about.

## FAQ

**Do I want to share this app?**
Yes kind of but the downsides aren't worth it to me.

**Why post about it then?**
Because I want to show this off. I want to post and let people know what I'm doing and how cool this is.

**So what features does "Glyph Buddy" have?**
Right now there's 2 features: a music visualizer and the weather information. These add something a little different to the existing solutions.

**What's unique about the music visualizer and weather information?**
Lots and lots of people have done music visualizers for the Glyph Matrix now but nearly all of them miss an important feature IMO, song progress. Like yeah it's cool to see things move and animals dance but it would be useful to see how far along you are in the song, what's the title and who sings it.

The weather one is unique in that I don't think anyone (yet) has tried to implement this (at least publicly) and I totally understand why.

---

My next post will go into a feature that I'll absolutely never ever make public but is very cool if it actually works properly (spoiler: it doesn't, not right now.)
