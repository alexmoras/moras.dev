---
title: Hello World!
date: 2022-06-30T06:00:00+01:00
tags:
  - "lab"
  - "projects"
  - "me"
author: Alex Moras
draft: false
---

Hey there, I'm Alex! This is my first proper blog post on this site. Like many people in the tech world, I've had many website before this one but never had the motivation to actually post on them. I realised what I was doing wrong - the content I was trying to create was boring. Well, I found it boring. And if I found it boring, you probably did to.

### So what's different?

That's a good question. This site is going to be a rambling of my thoughts - I'm not writing it to gain a cult following or for it to become my main source of income. In fact, I won't be putting ads on this site at all.

### So if its not for money, why am I doing it?

I've got a great love for anything and everything *tech*. When I'm trying new things I inevitably run in to problems which need to be fixed - and I do that by Googling it to death. I usually find the answer on blogs, like this, where people walk through exactly what they did to fix it. I want to be able to write up how I fixed things and share it so anyone else that has issues can follow along.

Not only that, when I'm sat in work bored and drifting off, I quite like to peruse different projects people have worked on and get some ideas of my own. I wanted somewhere to list them all and explain them, something a bit more relaxed than the actual GitHub repo.


## `$> whoami`

So, as you've read, my name is Alex. I've got a Degree in Computer Science and a good few years experience with different tech-things. I like to think of myself as an *old school hacker*. Not the kind of hacker that you see in films, breaking in to banks and NASA. The kind that likes to explore the limits of technology and build something from it - the kind that takes something they've bought and mod the crap out of it.

I don't work in tech, in fact my day job is quite different. I won't go in to the details of my career on here but I will mention that its very time consuming so projects and website update may be a tad delayed.

I'm from Wales 🏴󠁧󠁢󠁷󠁬󠁳󠁿 which for those of you that aren't local, is a country that forms part of the United Kingdom. We're known for rain, hills, and sheep.

## Home Lab

I love my home lab. Its probably the only thing that keeps me sane when I get home from work. Being able to mess around and learn new stuff is brilliant.

At the time of writing this, my lab is made up of two main servers. The first is my XCP-NG server which runs all the VMs on my network. This machine is built on:
- i7-6700K
- 16GB non-ECC RAM
- 120GB SSD boot drive
- 1TB SSD VM drive

The second is my TrueNAS scale machine which I use to backup my VMs, run Plex, and backup my files. This machine is built on:
- i3-7100
- 12GB non-ECC RAM (currently a mix-match of sticks 😬)
- 3 x Seagate Barracuda 1TB drives in RAID-Z1

I'm saving to move house at the moment so the lab is in a bit of a state. Eventually, I'll be upgrading the RAM from the XCP-NG machine and moving the 16GB from there in to TrueNAS. I'll also be replacing all three Seagate drives and increasing my capacity.

At the moment, there's no fancy networking going on. When I get the new house, I'm planning to procure a Unifi UDM Pro as my router (yes, I know pfSense is better but I don't need the advanced features) since I also plan on getting Unifi Protect cameras. Both servers will also be upgraded with SFP+ cards so I can use Direct Attach Copper.

I'll write a further post detailing what is running on the XCP-NG machine since I don't want to clutter this one too much.

## Projects

Smart Home is my big interest at the moment. I have a Home Assistant instance running as a VM on my server with a Conbee II Zigbee adapter passed through to allow me to control different devices across my home.

I'll be writing a post at some point which details my full Home Assistant setup. Its not a big fancy setup, since my home is quite small, but almost everything that can be automated has been connected to HA. And it works flawlessly.

The next project, which coincidentally will be my next post, is all about energy monitoring through Home Assistant. I've just purchased a [Glow Smart Meter Display](https://shop.glowmarkt.com/products/display-and-cad-combined-for-smart-meter-customers) which connects to my Smart Meter and exposes a local MQTT service. The amazing thing about this is that I'll be able to get realtime electricity usage right in Home Assistant! The MQTT integration is very new but an [excellent article from Joshua Cooper](https://medium.com/@joshua.cooper/glow-local-mqtt-f69b776b7af4) explains the technical limitations of MQTT and how to implement it in to your smart home setup. As soon as the device arrives, I'll be sure to delve right in and note down my progress.

## What's next?

Keep an eye on this website if you're interested in any of the upcoming projects. I don't use social media, so the best way to get in touch is through [GitHub](https://github.com/alexmoras). Speaking of which - you can see a [list of my projects here](https://github.com/alexmoras?tab=repositories)! Cheers all.



>*PS: Yes, I know this is a bit of a boring post. There's no snazzy images or cool code snippets. That will all change, I just needed to get some content on the site to get it going. The more I put it off, the less likely I was to get started. Just wait until next time. 😉*