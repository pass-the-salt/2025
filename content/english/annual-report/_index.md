---
title: "2025 Conference report"
permalink: /annual-report/
ref: report
---

Pass the SALT is a **free access, English spoken, 3-day conference** dedicated to Free software and Security. It provides a single track of talks and some workshops in parallel.<br><br>

This document is **our annual report for the 2025 edition** of the conference. We share all the figures, our insights and analysis about the event.

Direct sections access:
- **[TL;DR summary](#tldr-summary)**,
  - **[new location](#new-location)**,
  - **[conferences](#conferences)**,
  - **[attendance](#attendance)**,
  - **[some news features](#some-new-features)**,
  - **[failures and challenges](#failures-and-challenges)**,
- **[More event details](#more-event-details)**,
  - **[conferences and workshops](#conferences-and-workshops)**,
  - **[audience](#audience)**,
  - **[sponsors](#sponsors)**,
  - **[budget](#budget)**,
- **[Conclusion](#conclusion)**.

# TL;DR summary

## New location
Due to the unavailability of the Polytech lecture hall for our dates, we had the opportunity to host PTS25 at the **Catholic University of Lille**.

<img src="/images/room.jpg" alt="lecture hall" width="100%"/><br>

_Lecture hall. Photo by @julioloayzam._<br>

💚 The semi-underground lecture hall finally **handled quite well the high peak heat** (38°C on the first day).

💚 The variety of **transportation options** to get there (15 minutes by bus, 25/30 minutes on foot, 2 metro lines) provided **resilience and comfort for everyone**.

💚 The **green spaces** in an inner courtyard have been **really appreciated** by participants, especially with this temperature. <br><img src="/images/jardins.jpg" alt="Gardens inside university" width="100%"/>

😔 **No easy parking** when coming by car, including for the organizers; we will work for it if we come back there.

😐 No possibility of setting up food trucks. But there are a variety of street food restaurants nearby (5 min walk) 👍

## Conferences

PTS is a single-track conference with parallel workshops.

**Figures:** 49 submissions, **32 accepted**, including 4 invited (12.5%), for an **acceptance rate of 65%**. 👍

2024: 39, 30, 2 invited (6.66%), 76.9%.

We had also 6 workshops given all along the event (9 in 2024). 

**New in 2025** 

💚 a **secured messaging session** with very diverse and expert speakers,

💚 **more academic speakers**,

💚 speakers coming from **more diverse horizons** than the previous editions due to CFP pushing to new ecosystems (academia, messaging, hacktivists).    

## Attendance

**Figures:** 170 registered, **140 present**. After 8 editions, we can say that 130-170 is the typical size that fits the soul of the event where people can talk to everybody, speakers and attendees, in a comfortable and warm manner 💚

❤️ **2025 no-show rate: of 17.6%** (2024: 176/128, representing a no-show rate of 28%). As a free conference, we are **very happy** with these improving figures and the sharp drop in no-shows. Unfortunately, we don't have any further explanations for this figure 😐️

**Language:** As this was a conference held in English, we were very pleased to have **~20% of non-French speaking people 🇬🇧**, which is better than in the past. In particular, we had a larger number of Germans involved in activism and privacy (see presentations on the subject).

## Some new features

**Main point of contact for Code of Conduct enforcement:** this year, Nathan took the lead of the inclusion and safety initiative and will be able to bring his expertise in the domain to the organization. Thanks for it, Nathan 🙏 <br>![nathan](/images/nathan2.jpg)

**Best rump award:** we decided to distinguish the best lightning talk based on instant voting by the audience via an online service. It has been **fun** and **appreciated** by attendees and rumps speakers 🥇<br><img src="/images/best-rump-award.jpg" alt="best rump award" width="70%"/>

**Mascot:** Salty, hand maded by @\_cryptocorn\_, was born during the conference and made a brief appearance 😍 We can capitalize on its existence in future communications. <br><br><img src="/images/salty.jpg" alt="SALTY" width="100%"/><br>_Salty. Photo by @julioloayzam._<br>

**Org lunch:** the organizers allocated a budget to order food and have it delivered. This allowed us to **eat together**, work until the delivery arrived, chat, without the hassle of finding somewhere to eat, going there, coming back, etc. And it was great! 🤩

## Failures and challenges

### 1. Most epic first day in PTS history<br><br>

### 🚨 Server down 1 hour before conference start
Our **main server crashes one hour before the conference starts at 2 p.m.** It hosts the website, including  practical information on how to get there and the program, but not the ticket office. OVH works on it all afternoon.<br><img src="/images/everything.png" alt="everything is fine illustration in front a wall of flames" width="100%"/>

**Immediate impacts** 
  * **Many people were lost**. As previously said, this year, we changed the conference location. 1 p.m. on the first day is the exact time when most participants are looking for the practical information page on how to get there, and... the server is down. So they search from memory for “Université Catholique de Lille” on Maps, which sends them to another building further up the boulevard because the university occupies an entire neighborhood.<br>👉 **Server down, first  day, 1 hour before start of the con held in brand new location. All of this under 38°C. No worst time possible for this crash to happen!**
  * **Speaker absent:** this story causes our first speaker fail to join us on time, but he ends up arriving. In the end, we just swapped him with the second speaker (a big thank to Vincent Lopes!).

**Crisis management** 
  * 📣 As soon as we detected that the server was down, we (re)communicate the university's address via social media (X, Mastodon, LinkedIn). **Finally, people end up arriving more or less on time** 🎉 
  * 🛠️ **Recovering temporary website:** in the middle of the afternoon, we put **the site back online on Github Pages** thanks to the fact that it is mostly static (Hugo). The program based on Pretalx, which is self-hosted on the server, was affected. Fortunately, we were **able to replace the program with a PDF** generated elsewhere for physical display. <br><br><img src="/images/recovery-team.jpg" alt="2025 recovery team" width="100%"/><br> *The recovery team at work to bring up a backup website online. Photo by @julioloayzam.* <br><br>
  * **Server is back:** the server has been repaired and given back to us by OVH at 8 p.m. Everything on it was changed except for the disks, which meant we didn't have to do a full restore. The logs mention the CPU overheating. From there, it's easy to think that the data center's air conditioning had a hard time keeping the servers at the right temperature on that particularly hot day #EasyConspiracies 🤷‍♂️ 😉

**Law of series:** at the end of the conference, when we wanted to save the videos/slides from the year from our archive site to our backup disk, as we do every year, the data from the previous 15 years (RMLL+PTS) told us... *“We're gone, bye!”*. #WhenItDoesn'tWork. We backed up everything again.

**Conclusion:** we have a good post mortem analysis to do in order to build a more resilient infrastructure. But we'll say it again: **static site with markdown sources + Hugo + a repo on GitHub is a really good and cheap way to go** 💯

### 👀 Schrödinger Microphones 

At start of the conference, we had one more surprise ;)

Org: *"we don't have any Quantum talks, what a pity!"*<br>
Local video team: *"Hold my beer!"*

During our first talks, we faced **disappearing & reappearing microphones** with no particular reason!

But, of course, there is always a reason!
* **Root cause:** using network multicast mics on IT network requires filtering… and as all network people know since decades: ***”Correct filtering is hard”***
* **Solution:** let's back to old-fashion equipment! Yes, KISS solutions are often the way to go when you want to stay calm and keep an event on track ;)

### 2. The conference's late finishers challenge 🔥

About an hour after the conference ended, everything was packed up and all organizers and late speakers/participants headed to the station to go home. 

* 🎉 First step: **avoid the Tour de France parade** (which officially started two days later): it was impossible to get there on foot or by bus. **Our communication started the day before clearly worked**, as no one reported any difficulties.
* 🤦‍♂️ Once we arrived at the station: the **Lille-Paris line was cut** first due to a **collision between a TGV train and a wild boar**, **followed by a fire on the tracks (5-meter flames)**. It was a huge hassle for those who were finally able to board a train. <br><img src="/images/sanglier-incendiaire.png" alt="AI generated image to illustrate post event train failure" width="100%"/> <br> *AI-generated image of an incendiary boar by @regiteric*
* Main impact: a **large part of the organization, some speakers, and participants** were **stuck in Lille for one more night**. This did, however, lead to a final group meal in good spirits for those who were stuck! 😎 🍻

# More event details

## Conferences and workshops

### Submissions

| Year (IRL editions)  | Submissions   | Accepted      | Invited talks among accepted ones | Acceptation Rate |
| -------------        | ------------- | ------------- | --------------------------------- | ---------------- | 
| **2025**             | **49**        | **32**        | **4 (12.5%)**                     |  **65.0%**       |
| 2024                 | 39            | 30            | 2 (06.0%)                         |    77.0%         |
| 2023                 | 45            | 25            | 3 (12.0%)                         |    55.5%         |
| 2022                 | 39            | 27            | 5 (18.5%)                         |    69.2%         |
| 2019                 | 46            | 35            | 3 (12.0%)                         |    76.0%         |
| 2018                 | 37            | 29            | 2 (06.0%)                         |    78.3%         |

 
💚 **Number of submissions:** we are happy with the level and quality of the submissions. It is always a fight to get enough but also good quality content and this year is a good one! We had 26 talks and the number of workshops is also quite high (6) occupying all available slots.

<img src="/images/workshop.jpg" alt="2025 workshop" width="100%"/> 
<br> 

*Pauline & William workshop. Photo by julioloayzam* 

💚 **New in 2025** partly due to our extended core team, our CFP announcement and topics ideas have been able to be pushed to **different new ecosystems** (low level, secure messaging, privacy) but **also to more academics** we weren't able to reach previously. By this way, we have also been able to attract some attendees we usually didn't see at PTS (German activits for example).

💚 **New in 2025**
After boot security in 2023 and PKI/transparency in 2024 (which came back this year!), the **secured messagaing session** has been a good example of panel of different kind of speakers and topics (IETF and messging expert, long term OSS developer, researcher, core team of large secure messaging deployment), all with a high level of expertise.

We also have the **opportunity to have low level experts from academics** which is new for PTS! 

### Geograpical speakers distribution

| Year      | France   | (rest of) Europe | (rest of the) World |
| --------- | -------- | ---------------- | ------------------- |
| **2025**  | **67.5%**| **30%**          | **2.5%**            |
| 2024      | 61%      |  30%             | 9%                  |
| 2023      | 74%      | 22%              | 4%                  |
| 2022      | 77%      | 23%              | 0%                  |

The geographical distribution of our speakers is quite in the average of the conference.

### Recording, streaming and slides

**Video team** this year, our friends Fred and Florent from [Ubicast](https://www.ubicast.eu/) are back behind the camera and the result has been outstanding as always! 🎉

**Contents** each talk has been live streamed, recorded and the recording has been put online very quickly (<24h) due to a join effort of Ubicast guys and PTS team members @doegox and @_cryptocorn_ 🤩

💚 **Streaming:** we had between **40 and 50 people connected** to the streaming during all the 3 days which is a really good figure for us!

<img src="/images/videoteam.jpg" alt="2025 video team" width="100%"/> <br> 

_Video team: Fred & Florent from Ubicast. Photo by @julioloayzam_ . 

📣 A **very special thanks to Florent Thierry** (^on the right) from Ubicast that ends his long journey with Ubicast at #PTS25. Thanks so much Florent for these 15 years of support, expertise and kindness  from our early RMLL years to this edition of Pass the SALT 🙏 

Fred (left) has brilliantly taken over, and we are very happy to continue this PTS video adventure with such warm and competent people!

### Speakers feedback

<img src="/images/report-speakers.png" alt="2025 speakers experience" width="100%"/><br> 

The feedback of the speakers collected IRL and through the post event form has been **really positive**. 

💚 Main **positive points** have been:

- size and setup of the event allowed them to **chat with old friends and new people very easily**.
- speakers and attendees are **all relaxed and open minded**.
- despite the small size of the event(or because?), many new speakers have been surprised by the **high level of expertise** demonstrated all along the conference by people on stage.
- speaker gift and pauses content have been unanimously appreciated.
- 🤩 several speakers have pointed and appreciated the level of details (hand crafted badges, coins, **everything published openly** from talks to this report and more)

↗️ **Some improvements** have also been requested by speakers:

- speakers dinner has not been a perfect fit this year again (more room than in 2024 but less food, not top notch quality, quite noisy). Finding the right location for this speakers dinner is definitively the oldest challenge that we have not yet managed to overcome (perfectly)!
- several speakers have indicated that **too many emails** have been sent before the event (4/5) and they would like less emails, for example one or two with all required information on them. We will try to do it that way :) We have already 2 dedicated web pages for practical and speakers dedicated information.
- some adjustements on our Pretalx instance should be done in order to make speakers addition to an already proposed talk more reliable.
- adding a physical timer on stage would be great.

## Audience

### Figures

With 170 registered and 140 checked-in people, **2025 has been a good year!** 

As indicated in the summary, we are really happy of this year **historically low level of no show (17.6%)** 🤩  

Thanks to all committed attendees, it really matters for us!

### Geography & new comers

| Lille      | France (except Lille area)   | (rest of) Europe with UK | (rest of the) World |
| --------- | ----------------------------- | ------------------------ | ------------------- |
| **28.4%**  | **47.3%**                    | **19.6%**                | **4.7%**            |

We have been really pleased to have really more attendees coming from Europe and the rest of the world (x3 regardinbg 2024). **Diversity of speakers background** (private experts, academics, FLOSS devs, activists etc) **and nationality** has surely been a lever to reach these figures.

We asked also during registration if 2025 was their first Pass the SALT edition: **35% of new comers**. After 8 editions, we have finally reached the point where we have a core of regular attendees. We will try to always attract new people but it is also a real satisfaction to have committed people that come back for good reasons :)

### Occupation

| Occupation          | Value     | 
| ------------------- | ----------|
| **Private sector**  | **53.7%** | 
| **Public sector**   | **18.8%** | 
| **Students**        | **14.1%** | 
| **Academic**        | **08.1%** | 
| **Other**           | **05.4%** | 

We doubled the percentage of students and academics this year regarding 2024. Maybe the impact of the new location, more in town?

### Attendees feedback

💚 People appreciated:

- **Location:** being near downtown, possible to come by foot, bus or metro, gardens. A vast majority of you has really appreciated it!
- **Pauses:** a lot of you have given positive feedback about the quality and diversity of the pauses content. Canelés, pastries and fresh fruits got rewards!
- **Exchange:** you have really appreciated that the event allows you to chat easily with everybody, speakers included due to the small size, setup and the open state of mind of everybody.
- **Talks and workshops:** Their quality has been unanimously recognized.

↗️ Some improvements or regrets also:

- **Better A/C** 👉️ in the lecture hall, we can't do better: the system works to provide a temperature some degrees lower than the external temperature. IOHO the situation inside the room was tolerable regarding the 38°C outside. For the workshops rooms, some of you reported that it wasn't working correctly. We will try to check it next year more precisely.
- **No food trucks anymore** 👉️ Impossible to have them inside the university
- **Having rooms dedicated to specific purposes:** specific topics discussions, low noise/break room etc 👉️ We will try work on this, really!
- **Use the garden to do pauses** 👉️ Not sure due to the downstairs position of the lecture hall regarding the garden but why not.
- **Better signage for the event** 👉️ Difficult to do less than this year! We will try to improve it.
- **Some would like to have multi tracks in order to stay on topics they liked** 👉️ Unfortunately it is not the soul nor the mission of the event. We want to build bridges between communities and the way to reach this goal starts by ... listenning to each others :)
- **Almost no vegan alternatives and no way to indicate rare allergies** 👉️ our pauses have been more diverse than years before and for the first time, we have been able to provide fresh fruits. TBH it is quite hard on our side to provide a correct answer to so specific query 😔
- **Switch from bottles to a water dispenser during pauses** 👉️ Good point but onsite, everything is provided (or not) by the university. Will try to work on it because it is a valuable idea, thanks. 

## Sponsors

<img src="/images/sponsors.png" alt="2025 sponsors" width="100%"/> <br>

This year, [Penthertz](https://www.penthertz.com/) and [Epsilon](https://www.epsilon-sec.com/) supported us at a **Silver level**. They joined our group of sponsors and partners that support us on a mid to long term: 

- **Platinum level:** [Gandi](https://www.gandi.net/), [Passbolt](https://www.passbolt.com/), [Université Catholique de Lille](https://www.univ-catholille.fr/en/), 
- **Gold:** [Quarkslab](https://www.quarkslab.com/), 
- **Silver:** [Synacktiv](https://www.synacktiv.com/) and [RandoriSec](https://www.randorisec.fr/). 

Thanks so much to all of you, it simply allows us to exist and provide to the community this free event, share its content full of security expertise and create moments to meet and collaborate 💚

## Budget

In order to provide transparency to all but also to help everybody who would like to launch their own event, whe share the big lines of the budget:

**Approx. Budget: 14.000€~**

**Approx. Budget breakdown in %:**
- **47%:** catering (pauses, social event, spearkers dinner)
- **24%:** travel expenses reimbursement
- **16%:** onsite communication, identification and gifts expenses (badges, lanyards, tokens, kakemonos, stickers, speakers gifts etc)
- **10%:** recurrent expenses (bank account, servers, domain name etc).

## Conclusion

Each year, we try to produce the best event possible through high quality content on hot topics and all of this in a as warm and open atmosphere possible. At the end of the day, we just hope you will live a great event 

And when some speakers like Philippe and Thibault dropped us these kind words, we were just in a #JobSeemsToBeDone mood ❤️

**Philippe:** _"Thanks for organizing the conference and having us! It was great - I really enjoyed the talks, the vibe and meeting everybody who came from all over. And a special mention for... the snacks provided throughout the conference!"_<br>
**Thibault:** _"I second that. A great attention to details as well!"_

**_"attention to details"_** our small size (170p registered, 140 came) allows us to (try to) pay attention to details such as among others things custom badge design & fabrication in a fablab, specific lanyard for people requiring privacy, sharing everything (CFP & attendees figures, budget, slides/videos, badges design, contribs born during con etc), trying to speak with the vast majority of attendees and to all speakers etc. <br>
👉️ **It is really important for us and we really appreciate when it is pointed** 🙏 #SmallisBeautiful


It has been a blast! See you at #PTS25! 👋 😘<br>
**Pass the SALT 2025 organization team**

<img src="/images/team.jpg" alt="2025 team" width="100%"/> 
