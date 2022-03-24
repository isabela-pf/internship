# Meeting Notes for March 21, 2022
Meeting topics: Collaborating to make the report outline more concrete

Collaboration, writing together in a [shared Notion document](https://www.notion.so/Documentation-Outline-9b78b3959c854a5b8cdd808350527203).

## Why this meeting occured:
- Since we couldn't find good example outlines of a best practices document, we decided to make one ourselves, collaboratively on a Notion document

## Format of meeting
- Swast shared link, we had edit permissions
- For 15 minutes, we each wrote our own report outline
- Each person presented their outline and what they feel like is imporant
- Then we discussed the simliarities across the outlines
- Isabela to help make a consolidated 'mega-outline' that Swast expand on

## Actions to do after today's meeting
1. Isabela make Mega Outline of Report, based on our collaborative work in Notion
2. Mars make meeting notes in internship repo
3. Swast to make Meeting Agenda with Gabriel by linking to Notion table of actions
4. Mars to post Meeting Agenda in group chat with No

## Discussion/resource topics from meeting:
- Most important parts is the middle- summarize/key takeways from the Audit Report
- Rest of report, up to Swast and how confident she feels or information available 
- User Stories illustrations- nice, makes report more narrative and personal, leverages on Swast's strengths but optional.
- For summarizing/key takeways from Audit Report, find general patterns. Based on patterns, think of possible Recommendations
- Different ways we could present the Audit Results- such as table in report or link out to Notion document 
- Other discussion- prepare agenda for meeting with other volunteers.

## Writing from shared Notion document
Taken directly from the [shared Notion document](https://www.notion.so/Documentation-Outline-9b78b3959c854a5b8cdd808350527203).

[Figma report outlines](https://www.figma.com/file/FvWBXRoJzuBZmYfheD2cZS/QLABS---planning-and-scoping?node-id=0%3A1)

### Notes from discussion, after writing individually and comparing outlines
- Emphasis could be on Audit Findings Summary OR Recommendation
- Summarize report/Major Takeaway: Summarize patterns in report
- Recommendations: Based on Audit Summary/Major Takeaway
- Can omit Recommendations, if feel cannot recommend
- Ending with call for more support, research in this area
- Swast’s report: seems more developer focused, provide steps, resources

---

## Mars thoughts:

Format: Write in Markdown

### Introduction

Short introduction on accessibility broadly

- Don’t need to be detailed

Short introduction on accessibility RTC

- Why important

### User Stories (Swast’s diagrams)

- Persona: Motor disabilities, Keyboard user
- Persona: Visual disability, Screenreader user
- More personal section, emotionally engaging

### Audit Report

- Tools used
- RTC audited
- Results (in Markdown Table format or link out to Notion table)
    - Keyboard
    - Screen-reader
- More detailed, impersonal section
- Don’t need to write much new material for this section

### Summary of Audit

- Summarize general patterns in one audit (such as long titles read out for comments for Google Docs audit with screen-reader)

### Recommendations

- Not code specific
- One specific Recommendation: Allow for user to customize their experience (like a Google Docs Verbosity: how much of a comment is read)
- For developers,
    - From meeting with Eric Charles ([link to meeting notes and more questions](https://github.com/MarsBarLee/internship/blob/volunteer-meetings/volunteer-meetings/2022-03-17-eric-charles.md)):
        - Developers love patterns. Code patterns, UI compnents, and design systems
        - Don't know how VoiceOver works, until manually testing afterwards- pushing testing accessibility to later or too late in development cycle
        - As a developer, would like to know patterns, how to code for VoiceOver or other screen-readers: sooner your know, easier to implement
        - As a developer, need to know which details will be spoken by VoiceOver, filename only or creation date or status
        - What are standards we should implement, such as how much options to give to user in making their user experience better?
        - Developers may generally understand what a screen-reader does, but not have expereince or know specifics about screen-readers, such as Eric admitting he did not know about VoiceOver Verbosity feature- if he did, he could write code with that feature in mind
        - How does Verbosity work in general and then in JupyterLab or an RTC tool? High, Low Verbosity?
        - Are there differences in developing and optimizing for different screen-readers? Does VoiceOver and NVDA need different code? Like app development has subtle differences for iOS vs Android.

### Conclusion

- Brief thoughts about process
- Admit shortcomings
- what more can be done, possible actions or places to do more research (eg ‘more work should be done with more RTC tools, besides Google Docs’ or ‘more work should be with Linux OS such as the Orca Screen-reader’

### Methodology

- Similar to Audit Report, but with more details
- VoiceOver version, keyboard type (such as US-International keyboard?)
- Link to Notion table
- Replicate results and how it can be done again
- Meeting volunteers, questions and actions asked

### Why this structure

Both personal and impersonal

Covers Previously discussed possible outlines
1. By disability
2. By tool
3. By RTC tools
4. By Use Case (What, Why, How Where)
5. Inter-disability

---

## Isabela thoughts:

There are multiple outlines with overlapping pieces,  I’d choose which one to follow based on what work we end up doing.

1. **If we have recommendations**
- Intro (what this will cover)
- Background (the why/motivation)
- Methods (how did we do this)
    - Summarized version
    - This links out to whatever in-detail audits we have
- Recommendations (the what should people do in the future)
    - This would be the largest part of the document
    - May include examples where relevant
- Discussion (a place for further thoughts/any end notes)

1. **If we have several audits and/or want to highlight the audits**
- Intro
- Methods
    - Summary of methods
    - List of audits
- Audit 1
    - Notes on method for this audit
    - Full audit info (not linked out)
    - Major takeaways/patterns
- Audit 2
    - Repeat Audit 1’s structure as-needed
- Patterns (and/or recommendations)
    - Major takeaways/patterns from all the audits combined (high/level)
    - This is could have some recommendations if we end up having things we want to recommend.
- Discussion/conclusion
    - combined summary of the work and what we’d do next with more time

1. **If we end up with more questions than answers, not enough to feel recommendation confident**
- Intro
- Background (especially important in this one because it helps us note the absence of work in this area)
- What we have found
    - Methods (summary and link out)
    - Summarize what information we have found, major patterns, any other reports on this, so on.
- Things that are still missing
    - List what we know we are not covering and could not find info on, but know are problems (ie. little to no focus on cognitive disability)
    - Call out lack of open literature on this
- What we’d want to do next
    - Questions we still have
    - Methods we wanted to try but do not have time/other resources to (ie. user testing with disabled people, using other assistive tech)
    - What literature we’d like to see in the future
    - This is like a Recommendations section, but for the things we didn’t do
- Conclusion

---

### Swastika thoughts:

1. What is the problem - how lack of accessibility can effect
2. Top RTC tools which are not exactly accessible but using assistive techs it can be made accessible.
3. For any developer/designer, after a software or website is made - 

    — mostly accessibility is not considered from the beginning. 

    — Which is a common case and later they realise or if they want to make it accessible it is    tougher. Keeping this in mind - 

how can they improve their existing platform to make it more accessible
— showing them other tools such as NVDA and Voiceover which are also effective and can be included easily. 

— Giving the audit proof of how to improve any RTC to make it accessible with simple tools and understanding

— how can they support people even though they missed in the beginning 

— This can be used by other developers and designers as well and not limiting to RTC   tools

— Do’s and Don’ts of making the platform accessible - what can be done to make it easier for the users to use it

— Anything else if can be done - new - like when building something from scratch what all they should do - any new ideas

     
---

## Mega Outline

Because we liked pieces of all and know there will be a need for cuts, let’s start with a big scope and narrow as we work!

This is a collection/convergence of all the above outlines!

### Introduction

Short introduction on accessibility broadly

- Don’t need to be detailed
- Isabela: this may be linkable; people have made this argument and you can lean on them

Short introduction on accessibility RTC

- Why important
- Intros also scope the document and set up reader expectations

### Background

The “why are you writing this?” and “what’s the problem?”

From Swast’s section

1. What is the problem - how lack of accessibility can effect
2. Top RTC tools which are not exactly accessible but using assistive techs it can be made accessible.

### Methods

Summarized. More specifics can be provided per-section as needed.

### User Stories (Swast’s diagrams)

- Persona: Motor disabilities, Keyboard user
- Persona: Visual disability, Screenreader user
- More personal section, emotionally engaging

## User Stories (Swast’s diagrams)

- Persona: Motor disabilities, Keyboard user
- Persona: Visual disability, Screenreader user
- More personal section, emotionally engaging

### Audit Report(s)

- Tools used
- RTC interface audited
- Results (in Markdown Table format or link out to Notion table)
- Don’t need to write much new material for this section
- (If there are maultiple audits, we may include major takeaways/patterns per audit)

### Summary of Audit(s)

- The big picture/”why should I care?” of all this research

### Recommendations

From Swast section:

1. For any developer/designer, after a software or website is made - 

       — mostly accessibility is not considered from the beginning. 

       — Which is a common case and later they realise or if they want to make it accessible it is    tougher. Keeping this in mind - 

how can they improve their existing platform to make it more accessible - 

       — showing them other tools such as NVDA and Voiceover which are also effective and can be included easily. 

       — Giving the audit proof of how to improve any RTC to make it accessible with simple tools and understanding

       — how can they support people even though they missed in the beginning 

             —- This can be used by other developers and designers as well and not limiting to RTC   tools

       — Do’s and Don’ts of making the platform accessible - what can be done to make it easier for the users to use it

       — Anything else if can be done - new - like when building something from scratch what all they should do - any new ideas

- May include examples where relevant

### Next steps

- Things that are still missing
    - List what we know we are not covering and could not find info on, but know are problems (ie. little to no focus on cognitive disability)
    - Call out lack of open literature on this
- What we’d want to do next
    - Questions we still have
    - Methods we wanted to try but do not have time/other resources to (ie. user testing with disabled people, using other assistive tech)
    - What literature we’d like to see in the future
    - what more can be done, possible actions or places to do more research (eg ‘more work should be done with more RTC tools, besides Google Docs’ or ‘more work should be with Linux OS such as the Orca Screen-reader’
    
### Conclusion
    
    - Brief thoughts about process
    - Admit shortcomings
    - Summarize patterns of problem and recommendations.