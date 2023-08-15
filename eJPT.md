![image](https://github.com/darkoid/Reviews/assets/81341961/35afd66e-abf1-47f4-b39b-5ae5ffc4e15e)


On May 2023, I took the eJPTv2 exam. I’m excited to share my awesome journey of how I passed the eJPT exam on my first attempt!

My certifications ([Credential Status link](https://my.ine.com/certificate/37adc432-8111-44c9-9d23-e18a988ada55))

![image](https://github.com/darkoid/Reviews/assets/81341961/7ed4d9d7-414f-4ef8-8bb5-6a3d99de35a4)

# My Advise

Too long don’t have time to read. Here are the key points that I tell in this review you should focus on -

1. Don’t worry about the specific requirement for each section to pass the exam. Just focus getting access to all the target machines.
2. People say don’t treat it as CTF, I say don’t worry about it. For me I thought this means it’ll be more difficult than CTF which is scary but that not it, It just means its different and It’s actually easier than CTF. You’ll understand the meaning of why people say that while giving exam.
3. The exam time was previously 3 days and now its 2 with a bigger syllabus. Don’t worry you have more than sufficient time I passed the exam in 10 hours and I took breaks for about 4 hours. Some have passed the exam in 3 hours. Now don’t start competing to complete it faster use the time you have even after you answer every questions have some fun with the machine.
4. You have two attempts and the certificate doesn’t say if you passed in first or second attempt. So don’t worry if you fail the first time, just make sure to understand why you failed the first time.
5. Always double check the flags while submitting, I happen put the wrong flag because of a copy-paste problem with the machine.
6. You’ll get a nice animation for your results be ready to record screen before submitting.

# My story

It started when I saw the 50% off offer on eJPT exam. I wanted to have an exam experience before I buy a very expensive cert like OSCP. So I bought the exam.

Now this was time when eJPTv2 wasn't released. I started preparing but I was new to hostel as college just opened up after COVID and well you get lazy or “busy wasting your time” in hostel so I prepped very slowly for 6 months and was intent on giving it in hurry 15 days before the voucher expired. But maybe it was luck that I found the voucher exchange page(no longer available).

I did that and I got extra six months to prepare for my exam now this time I decided not to waste time I decided to give exam in less than 3 months so I would have about the same time to give second attempt if I failed. For my preparation i decided to do official lectures from ine. Since I got the exam from voucher exchange I didn’t get the course access so I got the course from unconventional method if you know what I mean. 

I had already done the thecybermentor’s 4 OG courses(PEH, OSINT, WPE, LPE) from udemy(now available on https://academy.tcm-sec.com/) and completed the Jr Penetration Tester pathway from tryhackme(https://tryhackme.com/path/outline/jrpenetrationtester). I started the PTSv2 course skipping labs and the Metasploit module as It was long I had already done most of it. It took me about 2 months because I was busy with college and laziness never goes away. During the second month I made a group on telegram, join it here https://t.me/eJPTv2_Exam where I could talk to people like me ask for help maybe help others and It actually made a difference I started doing the course faster when people on the group asked questions from which I couldn’t answer.

I completed the course but was very anxious as I didn’t do any labs. I delayed the exam for a week then I decided FU#K IT! lets give the exam If I fail I have another attempt and time of about 2 months to prepare more. I started the exam…

I begin the exam after a good night sleep of 7 hours. I started with our basic strategy first discover the target then nmap then look for vulnerabilities than gain shell on a user escalate privileges to root. HUH!! EASIER SAID THEN!

I didn’t get any access for about an hours so I took a break for an hour first went for running then eating then resting. (It was morning, I started the exam at 3am, I know my sleep cycle is terrible). I remembers that in most reviews I read this happened with everyone, most people don’t get anything for starting hours.

I calmed down and started the testing again and guess what its true, I started finding vulnerabilities now. Didn’t take any breaks for next 4 hours cause it was extremely fun. I solved many questions including two flags as well. I was stuck on a machine that later I found had web vulnerability. I took my second break for 2 hours.

I came back and I just started doing random things put `hydra` to work on all the service ports and started bunch of random `wpscan` commands from the internet without understanding that it does which you shouldn’t so but please understand I was desperate. And funny enough one of them gave me a password that got me access which I understood but no way could have done that manually. Atleast at that time.

Now I started gaining admin/root access on all machine and after an hours I had RDPs on 4 machine and ssh on the last one as it didn’t have desktop created(meaning never logined). Hopefully I didn’t give any spoilers by above sentence. The attack machine looked majestic filled with five machined accessed to its fullest extent. Enjoyed the view for about 10 minutes. (ALWAYS TAKE A MINUTE TO ENJOY YOUR ACCOMPLISHMENTS!)

Still I didn’t answer some questions so started to fill the flags which earlier I decided to fill after I had access to all of them. And here comes a sad moment due to some copy pasting problem I pasted another machines flag on another question. So lets this be warning for you to be careful about filling *flags* as they *are not changable*. I still hadn’t found all answers and I was quite frustrated as I have access to all machines yet I can’t answer some questions.

I decided to summit, guessed for remaining ones(none were right btw) thinking that I’m going to fail specially as I got one flag wrong. I’ll work harder for my next attempt. I was not ready for what was about to come, I PASSED THE EXAM! awesome can’t tell how exciting that was got on bike treated myself and my little cousin with PANI-PURIS.

Came back took some screenshot posted on social media and decided to write this story. Sorry for not uploading it right away thought I should research a bit and improve my writing skill before publishing this. But now I realised I should put it anyways this will ever be as good as I want it to.

# Tips

These are tips that I didn’t include in my advice as I learned this from other reviews and started the exam following it but in the end none were actually followed. But still mentioning as it did help a bit.

1. Create separate desktops for 5 different target machiens which you are going to hack.
2. Do not approach this exam as CTF, it's not.
3. Tools are not the most important things in hacking so make sure you understand what you do
4. The INE's course is really enough to pass the exam : do not rush to finish the course, take your time to understand every technique.
5. Make a structured cheatsheet - Note taking is one of the most important things in your hacking. I use notion for my note taking.

# About the criteria for specific domain

First let me start by telling you a little bit about the certificate, its syllabus, the PTSv2 course by ****Alexis Ahmed**** and the exam.

This certification is for an entry level penetration testing job role / Junior penetration testers. It is real world oriented. The essence of courseware and exam lies in the fact that it is supposed to be for beginners who have demonstrated their ability to use automated tools, to do manual exploitation and improvise as needed at various stages of penetration test. Lets see its blueprint from the [official source](https://ine.com/learning/certifications/internal/elearnsecurity-junior-penetration-tester-cert)(Read here to verify yourself) -

```
This certification is divided into four sections :

**Assessment Methodologies** (You must score at least 90%*)
**Host and Network Pentesting** (You must score at least 70%)
**Web Application Pentesting** (You must score at least 60%)
**Host & Network Auditing** (You must score at least 80%)

In addition to the minimum passign requirement, you also have to score atleast 70% overall to pass.
```

But I didn’t fulfil the requirement for **Host & Network Auditing** in my attempt as you can see below. So maybe they updated the exam requirement as I know people failed a lot in the beta exam but haven’t updated the page so I don’t know what the new requirement is.

![image](https://github.com/darkoid/Reviews/assets/81341961/d4b55674-c055-4768-bf80-af559b381fe6)

## What I learned ?

I learned that I’m bad at Web hacking yet lol !! Most of the time when I got stuck it was because of web hacking. It literally drove me crazy!!!! 

I never really connected to web hacking I do enjoy it but i also hate it. But I know this domain is very important for a career so I have to learn it as best as possible. So I’ve decided to get eWPTX the most difficult webapp pentesting cert there is. After I believe I’ll never have to work on webapp pentesting specifically I will only learn it when i hear a new exploit is in the market on the news or when I’m going through practice machine on tryhackme or hackthebox but even then only whats required as a time.

I started another telegram group, join it here https://t.me/eWPTX_Exam, for eWPTv2(beta will be released soon) and eWPTXv2(its old but still the hard work to pass this cert will help me get easy with this domain).

# The course

![image](https://github.com/darkoid/Reviews/assets/81341961/22669a27-adcb-4d25-9049-4d52647d2464)

I had already done about 5 courses on Ethical Hacking so I had some experience with watching videos and it was easy for me to just watch.

But I recommend doing these three steps(notes, labs, consistency) while doing the course if you’re new to watching lectures. If you have long courses like 20 hours lecture, and you have a methodology and it works then don’t change it. Otherwise -

1. Make sure you are making notes, if you’ve never made notes don’t worry this course includes video on making notes, I would suggest using NOTION app to make notes as its incredibly easy & fun to makes notes in notion. There isn’t day when I don’t open notion.
2. Do every single lab on your own before watching its solution. There are two very important labs just before the **********Privilege Escalation********** section in the **Host & Network Penetration Testing** module of PTS. I would recommend to giving atleast 20 hours of trying before moving to solution. If you solve it right away just move to Alex’s solution video to see his methodology.
3. Set a minimum amount to time(more than 60 minutes) to do lectures for each day, as someday you’ll feel lazy to not study but fight it **don’t skip a day.** Also, some days you’ll be motivated to watch lectures for hours so don’t limit your study if you can study like crazy.

This course is designed for anyone who want to start his journey in offensive security.

# The Exam

Things to keep in ming while giving exam -

- Use your notes when you’re stuck. And don’t go out looking for exotic pokemon exploits which will help you. Almost everything is taught in the course. I used almost because I don’t wanna be wrong but for me absolutely everything was taught in the course.
- Keep track of your actions, start making notes of what you do and find take screenshots, properly name it or time-stamp it, save your scan outputs. I did the following-

![image](https://github.com/darkoid/Reviews/assets/81341961/c27ca4f5-e0eb-49f4-981b-43a8989d79de)

- It’s much better to make a folders on the attack lab to keep files organised VPN, screenshots, credentials, scan outputs and so on.
- Take breaks, 48 hours is good enough time to pass this exam. I was live for 10 hours to pass the exam during which I took break for 4 hours.
- Please review your answers in MCQs before hitting the submit button. **Make sure to double check your flags while submitting as you can not edit it after you submit it.**

## **Resources**

The content of some of the people I followed before taking this exam :

- Notes
    - https://methodological-notes.gitbook.io/ejptv2-preparation/
    - https://sezioss-gitbook.gitbook.io/ejptv2cheatsheet/
    - https://blog.syselement.com/ine/courses/ejpt/ejpt-cheatsheet
- Another reviews
    - https://systemweakness.com/my-experience-of-the-free-ejptv2-exam-609beddab405
    - https://www.youtube.com/watch?v=Q2yTOo_IyUA
    - https://unblockweb.one/?cdURL=https://electronicsreference.com/my-review-of-the-ejptv2/
- Videos on specific topic. Search on following youtube-
    - ****************Heath Adams**************** aka TheCyberMentor [https://www.youtube.com/c/thecybermentor]
    - **John Hammond** [https://www.youtube.com/@_JohnHammond]

I hope this article will help you in your eJPTv2 journey. If you liked reading it do give it a star. I made a mistake or want to add something, make a pull request, I will respond as soon as possible.
