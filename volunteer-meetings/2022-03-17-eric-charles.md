# Meeting with Eric Charles to Audit JupyterLab with MacOS

## Meeting Agenda
1. Run audit of JupyterLab RTC using Eric's screen-reader, completing these 5 actions
- Share document
- Make a comment
- Read a comment
- Respond to a comment
- Find where other people in document
2. Discuss this question with Eric: If you were to read a best-practices document about accessible RTC, what would you like to look for?

## Discussion Points
### Eric's work'
- Doesn't have much experince with VoiceOver but knows a lot about Jupyter and RTC
- Worked on the RTC of JupyterLab, so knows a lot about the architecture of RTCs. This architecture in turn affects the front-end experience and navigation of RTC tools.
- Mars think his experience as a developer is really valuable and can help us make Swast's report.
- Also working on adding RTC to another project, 'Jupyter React with Slate'

### Eric's opinion:
- We should audit Jupyter first, then audit Jupter RTC later
  - Jupyter, then Jupyter RTC on top of that: adding layers of complexity, need to know the base

### Setup
- Running local instance of Jupyter, running Mac VoiceOver
- Setup takes time, some difficulties with using keyboard commands

## Audit JupyterLab with Mac VoiceOver
- Some agenda actions are not applicable to Jupyter: no built-in comment abilitity, unless use extensions
- Commenting extensions people often use
  - [old commenting extension, from calpoly](https://github.com/jupyterlab/jupyterlab-commenting)
  - [new: commenting extension](https://github.com/jupytercalpoly/jupyterlab-comments)
  - Not  commenting, but one workaround is leaving inline comments
  - However, inline comments do not have advantage of comments in other RTC, such as seeing commenter, time of comment and respond to comment in a comment thread
- Decided to focus on action: Share a document

### Action: Share a document:
- Process
  - Authorize share token
  - Find file in file directory
  - Right click a file
  - Copy shareable link
  - Share link

### Keyboard Commands
- Turn VoiceOver on and off: Cmd f5
- Move across UI and to file directory: Tab
- Keyboard shortcut for right click: Ctrl + Option, Shift M

### Evaulation of Audit
- Going down file directory, VoiceOVer reads out very long file properties: Not good user experience, information overload, cannot easily skim file directory
  - Eric said he could see how ARIA labels could help. To replace the long file name, identify element quicker
  - However, Isabela has some reservation about ARIA labels- could it be useful in this case?
- If you have a tree or list, provide option in JupyterLab or screen-reader properties customize how much read
  - VoiceOver has Verbosity feature

## Disucssion: If you were to read a best-practices document about accessible RTC, what would you like to look for?
- Developers love patterns. Code patterns, UI compnents, and design systems
- Don't know how VoiceOver works, until manually testing afterwards- pushing testing accessibility to later or too late in development cycle
- As a developer, would like to know patterns, how to code for VoiceOver or other screen-readers: sooner your know, easier to implement
- As a developer, need to know which details will be spoken by VoiceOver, filename only or creation date or status
- What are standards we should implement, such as how much options to give to user in making their user experience better? 
- Developers may generally understand what a screen-reader does, but not have expereince or know specifics about screen-readers, such as Eric admitting he did not know about VoiceOver Verbosity feature- if he did, he could write code with that feature in mind
- How does Verbosity work in general and then in JupyterLab or an RTC tool? High, Low Verbosity?
- Are there differences in developing and optimizing for different screen-readers? Does VoiceOver and NVDA need different code? Like app development has subtle differences for iOS vs Android.
- Need to see if there is common ground for all products- reduce redundancies
- Developer culture promotes keyboard use for efficiency. However, familiarity with casual keyboard use does not adequately prepare developers to use keyboard commands specific for VoiceOver/screen-readers. Thus have difficulty testing their code for screen-readers.

## Disucssion: Why would developers look at this report?
- Be interested in overview of content without getting too much information
- Understand report cannot give specific code or implementation for RTC> But would like to know patterns of how RTC work and how they interact with RTC components (such as VoiceOver Verbosity interacts with a tree or list or navigating folder)

## Next possible actions
- Completed one action! However, could not complete other actions
  - as not applicable to JuptyerLab RTC, such as commenting
  - unfamiliarity with VoiceOver set-up navigation, thus ran out of time
- Eric requested specific keyboard commands for each action
  - Share a file
    - Turn on VoiceOver: Cmd F5
    - Right click a file: Ctrl + Option, Shift M
    - Go down menu action 'Copy Shareable link': Arrow key down
- If we decide to try this audit again with Eric with more specfic keyboard commands, we will let him know