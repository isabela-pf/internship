# Best Practices for Accessible Real-Time Collaboration - Draft

## Accessibility - Introduction

[Accessibility](https://en.wikipedia.org/wiki/Accessibility) can be understood as the ability to access. Enabling access to disabled people by using assistive technologies which could bring benefits to everyone. Within the context of  Web accessibility or, it can be understood as a practice of ensuring there are no barriers that prevent action by people with [physical disabilities](https://en.wikipedia.org/wiki/Physical_disability#:~:text=A%20physical%20disability%20is%20a,blindness%2C%20epilepsy%20and%20sleep%20disorders.)), [situational disabilities](https://www.usabilityfirst.com/glossary/situational-impairment/index.html#:~:text=a%20difficulty%20accessing%20computers%20due,audio%20when%20attending%20a%20lecture.)), and socio-technical restrictions such as internet bandwidth or availability.

While many factors can be a part of accessibility, this research focuses only on the accessibility of digital platforms, also considering the digital environment of the user. For example: Using voiceover on a Google document on Mac. It also depends on the environment a user is interacting with and many more.

Broadly speaking, disabilities can be categorised in five groups:

*[Visual](https://www.news-medical.net/health/Types-of-visual-impairment.aspx#:~:text=Visual%20impairment%20is%20defined%20as,perform%20activities%20of%20daily%20living.)) - Myopia, colour blindness, Glaucoma, Albinism*

*[Auditory](https://webaim.org/articles/auditory/auditorydisabilities) - Persbycusis, Acoustic Trauma, Auditory processing disorder, Otosclerosis*

*[Motor](https://webaim.org/articles/motor/motordisabilities) - RSI, Cerebral Palsy, Parkinson’s, Muscular dystrophy*

*[Cognitive](https://webaim.org/articles/cognitive/) - Down’s Syndrome, Autism, Global developmental delay, Dyslexia*

*[Temporary disabilities](https://disability.tamu.edu/temporary/) - Arm or wrist injury, basically fully-abled people facing a situation of temporary disability*

### ***Accessibility - Why is it important?***

Accessibility is easily ignored, mostly because many abled people that build products don’t even know why it is necessary. People may ask why they should worry about accessibility? Is it because it is the right thing to do? or does it make sense financially? If it is really the right thing to do then why do we lack so much of this knowledge or even do not understand its actual importance?

Accessibility is a fundamental foundation for inclusion. There are multiple answers to the questions we listed down - of why is [accessibility actually important](https://www.w3.org/WAI/fundamentals/accessibility-intro/#important) be it [business case of accessibility](https://www.w3.org/WAI/business-case/), and what are the [benefits to the organization](https://www.w3.org/WAI/media/av/users-orgs/#benefits). Accessibility measures also need to take all types of disability previously listed into account.

### ***RTC - What is this, and how is it related to accessibility here?***

[Real time collaboration](https://en.wikipedia.org/wiki/Collaborative_real-time_editor) allows multiple users to work together on a project, or even simultaneously. The coronavirus disease (COVID-19) ***pandemic*** caused a rapid shift to ***full-time*** remote work for information workers. A [Gartner survey](https://www.gartner.com/en/newsroom/press-releases/2021-08-23-gartner-survey-reveals-44-percent-rise-in-workers-use-of-collaboration-tools-since-2019) reveals a 44% rise in the use of collaborative tools since 2019.

Here are some categories of RTC, with some examples:

*Video Conferencing - Zoom, Google Meets, Cisco Webex*

*Documentation and editing - Google Docs, Google sheets, Microsoft Office live etc.*

*Chat and threads platform - Slack, Discord, Reddit etc.*

Although this is just the list of RTC platforms, many such features build important aspects of real-time collaboration. Microsoft lists a good summary of these [popular features](https://www.microsoft.com/en-us/microsoft-365/business-insights-ideas/resources/real-time-collaboration-what-it-is-and-how-it-helps-your-business).

Our study focuses on the following common actions in an RTC environment:

- Users becoming or joining online
- Users being added to channels or docs
- Users replying to messages or comments
- Users 'reacting' to messages or comments

### ***Is everything accessible out there?***

Not really. There are still a lot of areas without any solution, and some are even unexplored. Accessibility in websites is usually ignored from the developing stages itself. Resources are available on the internet to make the platforms accessible, but most of these are focused on  code and tutorials and while missing out on the real impact and pathways of making  these implementations more usable and accessible. This made a small team at Quansight’s Internship program explore the available solutions out there and test them out to see how well they are solving their purposes.

We conducted audits of some of the standard RTC tools and platforms with a few assistive technologies available to us.

Here is the audit report to what we found out:

### ***User stories we are targeting!***

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/da60e229-8c5a-4d55-a8a2-2a5fa9fbe4f7/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220519%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220519T130745Z&X-Amz-Expires=86400&X-Amz-Signature=27648b3abe1e5636c3550766e6011dbd8f4d21cb58cfb4c608c2b0375562c3b9&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/676913c6-44b8-4941-a9c9-8c62069fdea9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220519%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220519T130729Z&X-Amz-Expires=86400&X-Amz-Signature=50c31ef3a1015a6207a74ac33735d4eea3e4791b33e2c43c429d6e993a5f574e&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

### **To check out details of the audits:**

[Assistive tech audit - Google docs + Voice over](https://www.notion.so/Assistive-tech-audit-Google-docs-Voice-over-643e4183aafb47a89d176c6fba3018bc)

[Auditing existing RTC tools](https://www.notion.so/Auditing-existing-RTC-tools-2efc708fef474c238e593e9a7ac9735d)

[User journey wise accessibility](https://www.notion.so/User-journey-wise-accessibility-1f7138e578524a86b55ae1afae7a38ea)

## **Audit Report**

### **Introduction**

This audit comprises tests of real time collaborative tools with assistive technologies. Google docs, one of the most used real-time real-time collaboration tools, was chosen. Following the complete journey, the audit

We performed the audit in two parts: Feature-wise audit and assistive tool wise audit, where we used keyboards and voiceover on MacBook.

### **Scope and objectives:**

The audit was done to understand the collaborative features of RTC tools and how they work when used with assistive technologies. This could give us an idea of the areas of improvement, how to help develop platforms which are accessible, what to do and what not to do and being a beginner with accessibility, understanding what is it and its scope. This audit is to get the idea of effective assistive techs on real time collaborative platforms. Scoping out to Google Docs, motor and visual assists and real-time collaborative features.

### What we covered:

- Testing out real time collaborative features of [Google Docs](https://www.google.com/docs/about/)
- Testing out assistive technology available on [Google Docs](https://www.google.com/docs/about/)
- [VoiceOver](https://support.apple.com/en-in/guide/voiceover/welcome/mac) on [Google Docs](https://www.google.com/docs/about/) to perform real-time collaborative tasks
- [NVDA](https://www.nvaccess.org/about-nvda/) on [Google Docs](https://www.google.com/docs/about/)
- [VoiceOver](https://support.apple.com/en-in/guide/voiceover/welcome/mac) on [JupyterLab](https://jupyter.org/)
- All the above testing were carried out using keyboard shortcuts

### What we did not cover:

- Performing these actions on other computers.
- Using [special tools](https://abilitynet.org.uk/factsheets/keyboard-and-mouse-alternatives-and-adaptations) used by disabled people. For example; Maltron expanded keyboard is designed to assist people with cerebral palsy and to provide better access for physically disabled and visually impaired users.
- Due to resource limitations, we were not able to complete user testing with disabled users.

### **Tools used**

- [Google Docs](https://www.google.com/docs/about/)
- [JupyterLab](https://jupyter.org/)
- [NVDA](https://www.nvaccess.org/about-nvda/)
- [VoiceOver](https://support.apple.com/en-in/guide/voiceover/welcome/mac)
- MacBook Keyboard
- Windows Keyboard

### **Objective**

This audit was to test the real time collaborative actions of these collaborative tools. Basically, from sharing the document to inviting team members and commenting - interacting in real time. Focus was also put on the results and how real time collaboration could be made more accessible and more effective when used with assistive tools.

### **Methods:**

(not tutorial-level detail, just summarize the how). Abled people did this whole audit, hence might not be wholly accurate and, at the same time, efficient enough. These were the people who don’t use assistive tools daily.

- Reviewing existing resources and recommendations for digital accessibility, whether or not the real time collaborative tools we have chosen is accessible.
- Real time collaborative tasks were listed down. Tasks which allow users to collaborate online, like Sharing a document, commenting on a document, or when a user joins the document.
- Tasks were performed and noted down with the details of how the task was performed and what keys/buttons/actions were done to accomplish the task.
- Other notes about the task performed were noted down to make sure nothing was missed or lost.
- Responses post-action as important. Confirmation that you commented, for example. Confirmation that a link has been copied to the clipboard. It seems like that happens sometimes, but not always.

### **Conclusions (or Results):**

The audit results came out to be mostly doing the real-time collaborative functions such as sharing the document and collaborating on them online.Also pointing out that RTC accessibility is still full of questions and needs devoted, open research. We don't have all the answers but we have tried to question the concept.

- Actions were mostly easily performed using the “Tab” key on the keyboard for both VoiceOver and Keyboard shortcut audits.
- [Accessibility features](https://support.google.com/docs/answer/6282736?hl=en&co=GENIE.Platform%3DDesktop) available on Google docs did not work for us, there are a number of features available like verbalise to screen reader, showing live edits. Most of them were not usable and insufficient information regarding their usage was provided on the internet.
- Both the screen readers had different actions and outputs. Voiceover mainly focused on reading out the actions and experience, whereas NVDA mostly focused on reading out the interface.
- For building accessible software and platforms, being able to read out the essential actions instead of just dictating out all action buttons and interface actions is essential.
- Key features of building a software or web app or even a platform accessible are not discovered enough and need information and resources on this.
- Response to every action, before the action taking place and after the action happened is critical to understand if it is effective or not and the desired results are shown.

### **Recommendations:**

As per the audits and interviews conducted by us, we noted down some of the recommendations we had for someone who would like to build an accessible platform or make an existing platform accessible.

- Accessibility should be considered from the beginning. Many developers and designers think of accessibility very late and forget its core importance.
- Accessibility should not be considered only for the sake of completing it as a check box, but for product brilliance.
- One can start by solving general accessibility problems like adding alt texts for images and data and considering user testings for results.
- It is recommended to build a proper team for accessibility and not consider it a responsibility of a particular group (or designers).
- It is not necessary to have inbuilt tools on your platform or adding a ton of features around accessibility, making the product feasible to use even with external accessibility tools can help a lot as most of the users might be already comfortable with their usual tools. For example - focus on the verbal output from different screen readers of different companies, some focuses on interface and some on the experience to dictate out.
- It is recommended to divide the actions into input and output actions, then work on solving the accessibility problems. 
- Accessibility requires people to test and give input. Solving a problem can get more manageable if you face the issue directly.
