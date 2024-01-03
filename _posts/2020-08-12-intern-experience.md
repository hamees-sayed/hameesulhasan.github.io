---
layout: distill
title: "Summer 2020 Internship Experience"
description: An article describing my first research internship experience 
date: 2020-08-12
show: true

authors:
  - name: Akkapaka Saikiran
    url: "https://akkapakasaikiran.github.io/" 

---


The way I obtained this internship was rather unconventional. I decided to pen down my experiences (and the lack thereof) as I had already written a subset of this for my intern report and I thought I could mold it for a general audience. I hope most of you take something away from this, a fact you didn’t know before, an anecdote you wish to share with friends, or a thought you hadn’t pondered over. So here goes.


### The Intro

My name is Akkapaka Saikiran and I’m a third-year undergraduate in the Computer Science and Engineering department. I am an ardent aficionado of carnatic music (a form of South Indian classical music), I enjoy swimming, and I used to read a lot before coming to insti so I’m trying to get back on track in the lockdown.
It was towards the end of September 2019 that we were told to prepare resumes to apply for internships. I wanted to do nothing but a Univ (University) intern at the time, mostly because of a vague idea of wanting to “study more”, which would eventually involve a research aspect. I also thought a teaching component would be cool as I had great respect and admiration for many of the teachers I had throughout my life. So I applied to most of the univs which came through PT cell. I didn’t harbor much hope as people much more accomplished than me had applied, so it was a huge surprise to be woken up by friends at 10 AM on a Sunday and finding out I’d been shortlisted for IRISA, a renowned research institute in France.


### The Interview(s)

There were to be two rounds of interviews. Round 1 was a non-technical round and was held a mere two days after the shortlisting. I tried to make sure I could explain my resume well, and let them know of my interest in research. I was excited to dress up in formal attire after a long time but due to connection issues, it was just an audio interview. I was tensed but the interview was smooth and I was shortlisted for Round 2, which was to be held after our endsems. Each of the five shortlisted candidates was given a research paper to read and describe in the interview. Endsems came and went and after a few days of respite I sat down to tackle the paper.

Around the same time, I talked to seniors who’d been through IRISA’s interviews before. One of them suggested I talk to [Prof Akshay](https://www.cse.iitb.ac.in/~akshayss/), a professor at CSE IITB, to seek general guidance as the paper was broadly aligned with his research interests. So I had a couple of short informal chats with Akshay sir and by the day of the interview, I had managed to understand most of the definitions and proofs of the paper and was again excited. The interview was decent but I wasn’t selected. The interviewers wrote back saying they were very happy with all five of us but only had enough funds for two. 


### The Intern Offer

After a couple of weeks I met Prof Akshay to seek guidance, yet again. This time it was for the next semester in general. It was then that I was introduced to [Prof Alain Finkel](http://www.lsv.fr/~finkel/), who was visiting IITB at the time. After a chat, which was kind of like an informal interview, he asked me to send him my CV as he may have some ideas for a research internship in the summer of 2020. Prof Finkel is a professor at École Normale Supérieure Paris-Saclay (ENS Paris-Saclay) and a senior researcher at Laboratoire Spécification et Vérification (LSV). Fast-forward a few weeks, while working in the Convocation Hall as a Techfest coordinator I got an email which I opened to find out that I had an internship offer. Yeah, I was really lucky. 

A few weeks were devoted to paperwork and this involved running about in the department and getting things signed. Be patient, profs tend to be busy and administration tends to be slow. I was fortunate in that the sem had only just begun, so there weren't a lot of acads going on. In the first week of Feb, I opened the official website of ReLaX (an  Indo-French joint research unit which is like an umbrella over LSV) to see my name listed [there](https://projects.lsv.ens-cachan.fr/relax/people/internships/#:~:text=Akkapaka%20Saikiran)!


### The Pandemic

Meanwhile, I got busy with the coursework of my fourth sem, sitting through an extra course which I couldn’t take for credits (CS 419M) to learn some of the prerequisites for my intern. March arrived soon enough, and fears about COVID-19 possibly playing truant to international travel surfaced. Within a couple of weeks, there was pandemonium and IITB shut itself down, sending (almost) all of its students home. Lockdowns were implemented all over India and France was one of the worst-hit countries (back then) so that slowly ruled out the possibility of traveling to ENS Paris-Saclay, something I was really looking forward to. A friend who’d secured an intern at ETH Zurich had his birthday on a weekend in June and we’d planned to celebrate it in Paris, but that plan went bust. Nevertheless, I braced myself for a virtual internship, which was to start when the semester got over. But IITB declared April and May as summer holidays so I got in touch with Prof Finkel and began reading relevant papers to get started with the internship.


### The Work

A Petri Net is a mathematical and graphical tool used to model parallel processes. There are two fast but complementary algorithms to find the minimal coverability set for Petri Nets. These algorithms are complementary in the sense that one is faster on “unsafe" instances and the other is faster on “safe" instances. It was found that running the algorithms in parallel improved results on benchmarks. So a team of four, including me, assembled with the goal of figuring out how to “learn” which algorithm was likely to do better on a particular input.

Most of April was spent in learning the relevant machine learning and reading the papers related to the two algorithms. I was lucky to be able to attend a talk given by one of my “team-mates” on one of these algorithms. I built up an understanding of the structures used in the formulation of the algorithms within a couple of weeks. It was an uphill journey that gave great pleasure after every day of ascent.
But the virtual nature of the job was a bottleneck. Moreover, everyone in the team except me was busy with multiple projects and as this was a relatively unexplored field, we couldn’t give enough time to it to get any insight. 

So towards the end of April Prof Finkel suggested it would be a better idea to abandon this topic, and he promised to come up with a more theoretical idea for an internship within a day, one which wouldn’t need the collaboration of many people, it would be just me and him. I was disappointed, having spent a month on the topic, but it was a good idea in retrospect. The Machine Learning I learned in April helped me for a course project I did a couple of months later, and the papers I read provided a solid foundation for many of the concepts involved in my new internship topic.


### The New Work

A Vector Addition System is sort of like an abstraction of a Petri Net. Projections of reachability sets of Vector Addition Systems are semi-linear (don’t bother trying to understand this). My task was to read the 1989 paper which proves this and to try and generate simpler proofs. The ambitious end goal was to design an algorithm to construct the aforementioned semi-linear set. 

May was spent reading the 1989 paper, page by page, subsection by subsection. I was writing an article on Overleaf summarizing my understanding. There was no coding component to the internship so I didn’t need any equipment as such. I progressed, slowly but surely, until I had rephrased more than half of the 1989 paper. But then for most of June, I was stuck in a rut and made progress only in improving the exposition of my article. I also had to do a course project (summer holidays were over) for the grading of the spring semester and that took a lot of time.

So towards the end of June, I requested for the internship to be terminated as I had spent a reasonable amount of time on the problem and wished to explore other stuff. It took more than half of July to wrap it up as Prof Finkel suggested I write an internship report to document my work experience. This took a long time as re-reading exposed faults and corrections had to be approved. In the end, it turned out to be fruitful and while I could have worked more proactively, I felt I’d done a decent job.


### Reflections

This was my first internship ever, and thus my first time trying research in an academic setting. I was slightly apprehensive about it when I secured it but also pretty excited. We didn’t achieve the end goal, but the experience taught me many things. I discovered that research papers are not necessarily written after one has a great idea. The process of research is inseparable from writing articles, which help solidify concepts studied and present possibilities of coming up with new ideas. Understanding how to pen down my thoughts formally was my biggest learning. I faced a lot of constructive criticism from Prof Finkel while writing my article and it has taught me many lessons which will stay with me for a long time.

The lockdown was a huge setback, and this being my first internship, I felt the need for more guidance and was periodically lost. There was a goal, but no plan of action or deadline-based schedule. At the same time, working from home has been a novel experience. It forced me to try and be self-reliant and diligent under the lack of regular supervision. I guess it also pacified my worries about the pandemic and the things I couldn’t control. Moreover, I consider myself extremely fortunate in that I still had an internship given the circumstances. My interaction with people was sparse but everyone was very amiable and helpful. 

During the internship, I also got the opportunity to think about where my interests are, and I felt probably this work was a bit too theoretical for me. I want to be cautious in my conclusions because the lockdown was hardly a normal setting for an internship (or is it the new normal?). But now I’m trying to figure out what interests me in computer science and work towards developing proficiency in the same.

I don’t think I want to give advice here but I strongly believe experiences (not necessarily in the first person) are great teachers. So seek out people, find out about their exploits, and think about what you can extrapolate to your situation. 

I conclude with a beautiful dialogue from Avengers: Infinity War between the Mad Titan and the God of Mischief.

*Loki: I do have a bit of experience in that arena.*
*Thanos: Well, if you consider failure experience.*
*Loki: I consider **experience** experience.*

Cheers, and stay safe.

