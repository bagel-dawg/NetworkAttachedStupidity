---
layout:     post
title:      ComptTIA Security+ Certification&#58; My Experience.
author:     Bagel
description: My personal experience of the CompTIA Security+ Certification exam.
author_bio_link: "/author-bios/ryan-knauer/"
date:       2018-12-24 11:00:00
summary:    My opinions and review of the CompTIA SY0-501 exam for the Security+ Certification.
categories: certifications
thumbnail:  fa-shield-alt
tags:
 - CompTIA
 - Security
 - Certifications
---

As part of my employment, I was required to obtain an Operating System-based certificate and a Security-based certificate before being granted privileged account access. For this, I went and completed CompTIA’s SY0-501 exam, colloquially called the “Security+” certificate. After a couple of weeks of studying, I passed the test with an 846/900. This article will detail my studying and testing experience in hopes to give potential test-takers an idea of what to look forward to. If you’re interested in reading the Linux+ exam counterpart to this post, you may read it [here]({{ site.baseurl }}{% link _posts/2018-11-09-linux-plus.md%})

**Note:** This article pertains to the SY0-501 exam. CompTIA regularly updates these exams and changes their criteria.  While it is unlikely that the criteria will change so dramatically that this article is inaccurate, just know what there could potentially be changes to your test.

{% include toc.html %}

# Studying and Preparation

I began studying for the Security+ exam way back in 2016, when the exam was still the SY0-401. Due to my own procrastination and motivation issues, I never did end up taking the exam. At the time, I had gone through [CBTNugget’s SY0-401 Course narrated by Keith Baker]( https://www.cbtnuggets.com/it-training/comptia-security-plus-sy0-401).  While these course videos were informative, I ultimately don’t think they would have much helped for my SY0-501 exam. CBTNuggets now has a course for the SY0-501 exam by the same instructor, but I am unable to talk about its relevance.

Well then what did help? There is no substitution for experience. And unfortunately, experience requires both time and opportunity. That being said: You can definitely pass this exam, even when starting off with no IT/Security experience. The downside to this method is that it will be difficult for you.

[The book I had used to study, “CompTIA Security+ Get Certified Get Ahead: SY0-501 Study Guide”]( https://www.amazon.com/CompTIA-Security-Get-Certified-Ahead/dp/1939136059), was a good study guide for the exam. The book does however expect you to understand some basic concepts about networking and computing in general. Because of this, just reading the book with no prior knowledge will not get you through the exam with a passing score. You will need to read up on the underlying technology (IP addressing, switching/routing fundamentals, subnetting, etc) in order to get a good grasp. The exam questions are not all about the next-book definitions. You need to be able to apply the concepts as well.
Everyone’s study techniques will be different, but the bottom line is: If you come across a term or acronym that you don’t understand **_research it until you do._** Go beyond the first google result. You should be able to explain any term or idea in the exam curriculum to your grandmother.

*Important studying tip:* If a concept has multiple solutions (for example, different security style for Wireless Access Points, or encryption algorithms), rate them all from least-secure to most-secure. You will often come across questions that ask you for the _best_ possible answer.

In addition to the study guide above, I also used a [smart phone app for test questions.]( https://play.google.com/store/apps/details?id=com.learnzapp.securityplus&hl=en_US) The app at the time of writing was about $8, which I figured was the cost of lunch for a day and was worth it. It included about 300 or so test questions that I feel accurately represent the actual exam questions, in both wording and complexity. I can’t say for sure that it helped increase my score significantly, but it did encourage me to study when I would otherwise have not been by being readily available in my pocket. The app also includes a set of acronym slides, which I did find incredibly useful for drilling some of the lesser-known, business-related acronyms into my head.

If you are looking to study with some background noise, I would suggest watching [Pressor Messor’s SY0-501 Playlist.](https://www.youtube.com/watch?v=UbxRf_9Rcmg&list=PLG49S3nxzAnnVhoAaL4B6aMFDQ8_gdxAy) Just watching these videos alone won’t cause a passing score, but the videos are excellent for introducing terms and concepts in an easy to understand video.

My final thoughts of preparation: CompTIA didn’t come up with thousands of new questions for the SY0-501 exam. Many of the exam objectives are the same, which means SY0-401 practice questions are still incredibly relevant, as well as available since it is no longer the current test. My suggestion to you is to answer and understand as many practice questions as possible. **_Pay close attention to the wording of each question and answer choices._**
If you are someone that has previous experience in IT, I would recommend dedicating about 30 hours to studying/instruction before taking the exam. If you do not have previous IT experience, the amount of time will increase based on how much you have to learn along the way.

**Note:** I’ve been a Systems Administrator for years and spent the last 3 years as a Linux administrator for Higher Education. I mention this because my previous experience certainly had an influence on my view of the tests, even though it was not directly related to my Linux proficiency.

# The Exam

My Security+ exam included 85 ABCDE questions, and 5 “Simulations” (I’ve also heard them called PBQs, Performance-Based-Questions). At the very beginning of my test, the first 5 questions were simulations. I flagged all of them for review and skipped ahead to the multiple choice questions. My reasoning behind this is that you’ve only got 2 hours. You are much more likely to get the multiple choice questions correct in a shorter amount of time. Once you’ve answered all of the (comparatively easy) multiple choice questions, you can use the remainder of your time on the simulations without worrying about losing points to unanswered questions.

Fortunately, I felt that I had plenty of time to get through the exam, finishing with about 20 minutes to spare. The simulations I felt were somewhat challenging, but all of the criteria was covered in the exam objectives – there weren’t any “we weren’t told to studying that” questions that I encountered.

Pay incredible attention to the question being asked, as there are many “trick” questions. You will be intentionally misled by familiar-sounding words and phrases. Read the question and identify exactly what it is asking.

A repetitive concept that I found was the use of the words _best_, _most_, and _least_ in questions. You will encounter questions that ask for the _best_ possible answer, and then be presented with choices that could all be correct. Don’t let that fool you by instantly choosing the first correct answer. 

The simulations are an entirely different ball game. They require you to really understand how concepts get implemented. All of the simulations I encountered were drag-and-drop, or select from a list of multiple solutions – apart from one. One of the simulations I received was pretty poorly instructed. Perhaps I didn’t quite get what it was asking me to do, but I was pretty confused. That being said, given you have enough time, poke through all of the options presented and pick the options that make the  most since given the question asked. Above all else, do not leave any multiple choice question unanswered.

If you’ve never taken a CompTIA exam, here what you can expect from the testing facility:

The tests are conducted at a PearsonVUE test facility, in my case – a University in which I attended. Pearson has these guys all over the place, so you may pick your favorite. I’ve been to two different facilities and they’ve both been very similar. Quiet, comfortable temperature, very clean. The test is conducted on a standard computer desktop with a keyboard and mouse.

# After the Exam

Immediately after submitting your exam, there will be a short, 15-question survey for you to answer that asks about demographics, career field, why you took the exam, etc. It is ultimately unimportant, but you must get through it to get your test results. I find it a little cruel to put this questionnaire before receiving your results, but that’s just me. You will be shown your results immediately after answering the survey.

A day after taking the exam, the result status were on [certmetrics.]( https://www.certmetrics.com/comptia/login.aspx) 

There are several ways you can verify the results of the exam. The first of which is a paper-certificate with your name and ID on it. CompTIA/Certmetrics advertises that it may take _up to 8 weeks_ to print and delivery a physical paper certificate.

If you need to verify your certificate for any reason, you can download a PDF version of the certificate from certmetrics. You may also create a transcript via the same website, which will generate a file containing all of your CompTIA exams.

# Who is this exam for?

This exam is definitely for anyone who works for the Department of Defense, as it [counts as a security certificate for IAT Level 2 of the 8570 Baseline certifications]( https://iase.disa.mil/iawip/pages/iabaseline.aspx).

Apart from that, I’m not sure what other industries expect it. Seeing as it is vendor-agnostic, it could be a good “downtime” or “getting-your-foot-in-the-door” certificate, along with the [Linux+.]({{ site.baseurl }}{% link _posts/2018-11-09-linux-plus.md%}) It covers a lot of ground, as well as some more complex topics. It can certainly open your eyes to security threats in your place of work that you may have otherwise overlooked. Things like physical security, policies that should be implemented, etc.

If you can get your employer to pay for the exam (and, even better, dedicate study time to it) then I would highly recommend you take the opportunity as it is, at the very least, _not_ a waste of time.
