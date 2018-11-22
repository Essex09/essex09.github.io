---
layout: post
title: My OSCP Journey - Part 2
tags: [hacking, oscp, pwk, penetration testing, offensive security]
---

### The Exam
The morning of my exam, I woke up extremely nervous. I barely slept and knew I had a long day ahead of me. I scheduled my first exam to begin at 8:00 AM EST and when 8:01 AM rolled around, I expected to receive my email with exam instructions. I figured there was a slight delay so I decided to wait. Twenty minutes passed by and nothing. I reached out to OffSec and after forty-five minutes, I received an email containing the instructions. I VPN’d into the exam network, read the objectives, and proceeded. About two hours in, I had my first box and was feeling great. The nerves started to calm, so I pressed on. About 10 hours later, I expected to have at least one other box, but nothing came through for me. I couldn’t focus on one box and kept jumping around. I did the opposite of my plan, which was to focus on one box until I exhausted all options. Around 10:00 PM, I popped my second box, which lifted my spirits a little. I moved onto my next box, but nothing. This kept on until 3:30 AM when I decided to call it. I felt defeated and didn’t know what else to try. I’m very embarrassed, not because I didn’t pass, but because I didn’t keep going until my VPN access was cut off. I woke up around 10 AM the next day and decided I was never going to quit again. 

OffSec has a cooling off period built into the program if you fail an exam attempt; If you fail it once, you have to wait a week before challenging the exam again; If you fail it twice, it’s a two week wait time. After about a week of sulking, I came around and scheduled another exam. In between exams, I was back in the labs.

I improved slightly on my second attempt, but not by much. After about an hour and a half, I had my first box rooted. Three to four hours after that, I had another. This time I focused better and was able to gain a low priv shell on a third system, but didn’t get much further than that. I didn’t quit and went all the way until my VPN access was cut off. Feeling defeated yet again, I decided to jump back into the labs and root some more boxes for practice. 

Jumping back into the labs did me well. During this time, I popped several more boxes, including Pain, Sufferance, and Humble. I was also doing a much better job of documenting my various attack paths and notes. I developed a great note set and checklist of things to try when enumerating a system. After a few more weeks of practice, I challenged the exam for a third time. 

My third attempt went much better than my first two. I had a much better game plan and knew what to expect. After about an hour and a half, I had one box rooted. A couple of hours later I rooted a second. I kept enumerating the remaining boxes and reviewing results from scripts and tools I ran. About ten to twelve hours later, I was able to gain a remote shell on a third box. At this point, I was ecstatic because I made more progress in less time than my previous two attempts. A couple hours later I rooted the box. I was very happy, but I needed to root one more box to pass. I moved onto the remaining two boxes and kept poking around. I tried everything I could, but realized around the twenty-one-hour mark, I wasn’t going to pass. I didn’t let that discourage me and kept pressing on. Eventually my VPN access died and I failed the exam again. I wasn’t too disappointed this time because I improved and knew the specific areas I needed to improve on.

After the cooling off period passed, I rescheduled for a fourth attempt. I won’t get into much detail here, because it was the exact same outcome of my last attempt: I gained access to three systems, but didn’t have enough points to pass. I was discouraged, but knew areas I needed to continue to focus on. Before my fourth attempt, I welcomed my second child into this world. My hat’s off to my supportive wife who allowed me to take the exam with a two-week-old-newborn. She’s awesome and my rock. Without her, none of this would have been possible.

During the six-week cooling off period, I started to work on areas I was weak in. I tried to focus more on web apps and SQL injection. I want to take a second here to thank several friends who were there to help pick me up when I felt stuck and discouraged. They helped me by suggesting resources to use and study along with some much-needed confidence. If it weren’t for them, I’m not sure I would have passed. 

Over the next six weeks, I focused on ten Vulnhub VMs that I found on the PWK forums. I also ran through [Security Shepherd from OWASP](https://www.owasp.org/index.php/OWASP_Security_Shepherd) (or as much as I could finish) and reviewed [PentesterLab](https://pentesterlab.com/exercises/web_for_pentester/course) exercises. After six weeks of studying and regaining confidence, I was ready to sit for my last exam. At this point my exam was scheduled for March 8, 2018. 

### My Final Attempt
On March 8th, precisely at 8:00 AM, I received my exam email from OffSec. It’s go time, baby! I logged in to the VPN and began reading the supplied instructions. After two hours, my first box was rooted with plenty of documentation to show my attack path. After another hour and a half, another box went down. I decided to go after, what I thought was the hardest box then, and began enumerating it. After about twenty minutes of reviewing various tools output, I realized my way in. A few minutes later, I had a reverse shell! This was record time for me, but I knew only half the battle was won on this particular system. Once on the system, I went through my normal checklist of things to privesc. I was about two hours deep into trying to escalate when I decided to move on. I didn’t want to get stuck and wanted to keep my pace going. I decided to take a break while I finished enumerating the last two boxes and ate lunch. When I returned, I reviewed the output on both boxes and began formulating my attack path for one of them. After a while of reviewing output and manual enumeration, I had a reverse shell! I quickly figured out the way to escalate and had rooted my third box! At this point, I was ecstatic! I needed one more box to pass, but in the back of my mind, I knew this is where I got stuck during the previous two exam attempts. 

I moved back to the other box with a reverse shell and decided to approach it as if it were my first time on it. I reran my scripts and went through my normal checklist to privesc. A few hours had gone by and the panic started to set in. It was about 8 PM at this time and I felt at my worst. Anxiety began to set in and I began to think I was going to fail just like the other attempts. I knew not to let that get me down, so I stepped out of the room and played with my two boys for about twenty minutes and talked with my wife. This was the best thing for me, because when I sat back down, a nugget was beaming right in front of me. I knew what I had to do, but didn’t know exactly how to execute it. About an hour and a half later, twelve hours into the exam by this time, I figured out what I needed to do and escalated to root! When I realized I rooted the box, it set in that I had enough points to pass! I jumped out of my chair and ran out to celebrate with my wife. I was extremely happy because all of the hard work and studying paid off. A few minutes later, I was back on the keyboard documenting my attack path for the box. I took some time to make sure I had enough documentation for all of the boxes I popped then focused my efforts on the last box. Around eighteen hours into the exam, I couldn’t figure out how to get a reverse shell on the final box, so I decided to begin writing my report and make sure I had everything I needed before my VPN access was cut. Three hours later, my report was written. After I submitted my report, I couldn't’ sleep. I believe I only got around 4 hours of sleep until I received the email from OffSec that I passed, on March 10th.

### Conclusion
I’ve never felt more accomplished in my life than when I received my certificate in the mail. I went from almost no experience in the field to laying a solid base of knowledge. After obtaining the cert, it’s allowed me to transition into a pentesting role with my employer! My journey with OSCP may have ended, but my pentesting career is only just beginning. I’m in no position to even think I know it all and will always consider myself a n00b and push myself to learn and do more. If there’s one thing you should take away from reading this review, it is that no matter what your background is, if you are motivated and willing to learn, you can pass the OSCP! Thanks for reading this long-winded post, and if you liked it, give me a shout out on Twitter.