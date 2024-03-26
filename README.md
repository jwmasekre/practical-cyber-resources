# practical cyber resources

i was asked for some resources for someone wanting to get geared up to enter the information security workforce, and as i was compiling them, i realized that markdown would be a more effective formatting tool for what i was building, and that it'd be potentially useful for more than just the person who asked me, so here it is. this can be considered a living document, and i'm more than willing to accept contributions. some sections will definitely be anemic as i either don't have much experience in them or i lost steam when initially drafting this, so this will occasionally be updated as i find time.

## contents

1. [research and reporting](#research-and-reporting)
    1. [blogs](#blogs)
    2. [articles](#articles)
    3. [personal sites](#personal-sites)
2. [ctfs](#ctfs)
    1. [overthewire](#overthewire)
    2. [kringlecon](#kringlecon)
    3. [president's cup](#cisa-presidents-cup)
    4. [metactf](#metactf)
3. [conferences](#conferences)
    1. [defcon](#defcon)
    2. [wwhf](#wwhf)
    3. [bsides](#bsides)
4. [communities](#communities)
    1. [discord](#discord)
5. [training](#training)
    1. [antisyphon](#antisyphon)

## research and reporting

### blogs

when i was at BDS, we did both blog posts and threatwatch articles. below is an example of the types of blog posts we'd put out, which happens to be the most recent one by Jace Walker, who is incredibly talented:

[malsync teardown](https://www.binarydefense.com/resources/blog/malsync-teardown-from-dll-hijacking-to-php-malware-for-windows/)

### articles

threatwatch was a tamer version of a blog post, simply summarizing a threat and providing some generalized recommendations. note that a more robust version of each of these was also included in a tlp:amber report we distributed to customers, which included generalized (as in, tuning specific to client environments removed) detections. the following are some of the articles i wrote:

[stealc information stealer](https://www.binarydefense.com/resources/threat-watch/new-information-stealer-stealc-actively-used-in-the-wild/)  
[iot ransomware](https://www.binarydefense.com/resources/threat-watch/iot-ransomware-proof-of-concept-highlights-often-overlooked-vulnerable-devices/)  
[astralocker](https://www.binarydefense.com/resources/threat-watch/new-astralocker-ransomware-version-being-distributed-directly-from-phishing-attachments/)

performing this type of analysis and writing is useful for two reasons. one, it gives experience in understanding attacks for the purposes of detecting, defending, and remediating. second, it helps shape the way an analyst thinks about a problem. note that the analyst notes for the threatwatch articles are the "so what". the idea is that an analyst should be developing actionable guidance, provide as many opportunities for success as possible, and recognize the limitations of the environments they may be supporting. additionally, by writing it out, especially on a regular schedule, you get used to effective, concise writing.

### personal sites

i personally recommend standing up a site with [github pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/) and setting a regular schedule for yourself. [my own site](https://self.joshuamasek.com/) is a terrible example of that, since i never stuck to a schedule, but at the very least you can see what a [hugo](https://gohugo.io/)-based static site looks like. this also gets some added [experience with github](https://github.com/jwmasekre/self-site), however limited. i used it more for documenting ctfs and powershell scripts i'd worked on, and i have probably more drafts created than published blog posts, but at the very least the reps in writing articles helps develop communication skills while still getting to flex your cyber muscles

## ctfs

the fun part, and honestly my favorite piece to advertise. i've learned more *actually applicable* skills and tidbits of knowledge from ctfs than I have from any sort of formal education (though sans courses are a close second).

### overthewire

for my team back home, when we get someone new, i require them to work on [overthewire](https://overthewire.org/wargames/). i highly recommend completing `bandit`, as it's a great introduction to the linux cli, but it's also a great introduction to using your resources to figure out how to manipulate a system. however, it's simply *not enough* to just complete the challenges. if you force yourself to take robust notes (such as, idk, [setting up a personal blog](#personal-sites)), you get really good at practicing documenting your findings, and make sure to include what *doesn't* work as well. my [posts on kringlecon 2019](https://self.joshuamasek.com/posts/kringlecon2019/) kinda showcase this, which also takes me into my next suggestion...

### kringlecon

every year Ed Skoudis of sans fame puts on [kringlecon](https://holidayhackchallenge.com/2023/), which is an excellent ctf open to the public around christmas time. previous years are all available, and they actively encourage write-ups on problems. and speaking of annual ctfs...

### cisa president's cup

i cannot recommend the [president's cup](https://presidentscup.cisa.gov/) highly enough. it's incredibly educational and practical, and covers a very broad range of challenges. past years' challenges are available as well (with write-ups to help if you get stuck), so you don't have to wait until next year's challenge to kick off (likely around january) to get started. just note that you have to be a member of the executive branch, and that doesn't include contractors, so if you're not military (including guard/reserve) or work for a federal agency, you won't be able to participate.

also keep in mind that the difficulty curve is *brutal*. my first year i barely got a question in one problem completed, but i *learned so damn much*. the trick is learning how to determine the best use of your time, effectively seek out information, and, like i said earlier, *take good notes*. you never know when you'll need to remember how you did a thing, either in a ctf or in the real world (for example, i once recreated hydra functionality in python because hydra was being a shit. i have since lost that script and have lost time on challenges fighting hydra where that script would have been a godsend.)

### metactf

[this organization](https://metactf.com/) creates some really fun ctfs, and an [older one](https://metactf.com/cybergames) is still available online. they provided the ctf infrastructure for wild west hackin fest 2020, and the platform was very enjoyable to use. they sometimes do flash ctfs as well, which can be a fun way to just jump right into something (if you happen to be free when it's happening).

## conferences

my conference experience is fairly limited, so i'll include the ones i've been to and the ones i've frequently heard of, but you can hardly go anywhere without finding a conference local to the area.

### defcon

[defcon](https://defcon.org/) hardly needs an introduction, but it's huge, it's in vegas, and there's a wide variety of activities and talks to see. if you leave learning nothing, you have no one to blame but yourself. it's also a great way to network, meet others in similar or different industries, talk shop or talk not shop, etc. plus the rest of vegas is still going on, so you can catch a show, throw some dice, or just explore the strip.

### wwhf

[wild west hackin fest](https://wildwesthackinfest.com/) is put on by black hills information security (BHIS), a world-class security company located right in my home state. the original is held in deadwood, sd every fall, and they also hold one in san diego in the spring called way west hackin fest. it's a fun experience, great talks, good challenges, a relaxed vendor environment, and if you haven't experienced historic deadwood or the black hills in general, it's a surprisingly cool place for the middle of nowhere.

### bsides

[bsides](https://en.wikipedia.org/wiki/Security_BSides) are put on by locals to the area they are in. because of this, they're everywhere, and it's always worth looking into your local (or as local as you can get) event.

## communities

networking is critical to information sharing and maximizing your effectiveness in information security. the following are some communities i use to stay in touch. pretty much all of my digital social presence is on discord, so that's primarily what's here

### discord

in no particular order, these are the communities i'm in:  
* [metactf](https://discord.gg/yyKCWnb)
* [bhis](https://discord.gg/BHIS)
* [red siege infosec](https://discord.com/invite/VpHXYUp)
* [threat hunter community](https://discord.com/invite/threathunter)
* [vxug](https://discord.gg/MSjAQe4PUy)

## training

### antisyphon

created by bhis, [antisyphon](https://www.antisyphontraining.com/) is an excellent training opportunity, with a pay-what-you-want structure.
