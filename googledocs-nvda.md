# Collaborative exploration of Google Docs with NVDA

## Meeting Agenda

1. Quick Audit a few real time collaborative tasks on Google Docs using NVDA.
2. Let us know your journey using NVDA screen reader on Google Docs.
3. Quick question in the end: What do you wish to have or expect in a report called “Best Accessibility Practices for Real Time Collaborative tools”

## Audit Task and Table

[Google Docs (NVDA Screen reader)](https://www.notion.so/0089cba329cd479095e4af2a537a84cd)

Other resources for NVDA:

[https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts#nvda-nvda_shortcut_keys](https://dequeuniversity.com/screenreaders/nvda-keyboard-shortcuts#nvda-nvda_shortcut_keys)

[https://webaim.org/resources/shortcuts/nvda](https://webaim.org/resources/shortcuts/nvda)

## Notes

Too much verbosity, not easy to remember the keyboard shortcuts

Not proficient user

NVDA puts the UI type first and Voiceover keeps the experience side first

### Isabela notes

- Microsoft Edge browser on a Windows machine. NVDA. (Done 22 March 2022)
- Elements list: NVDA button + F7
- No links, elements, landmarks, forms appear in the elements list. Very weird.
- No resources on NVDA verbosity, maybe it isn’t a thing!
- Visible focus is a mix of Docs UI and screen reader (when the UI does not have it, like a stopgap)
- Didn’t tell that the link was copied! Visual-only notification. (share task)
- Shift + F10 for context menu
- Unclear how to navigate the main regions of Google docs (ie. how to get from the document (the place instantly focused by entering) to the toolbar, the left sidebar/toc, the right sidebar/comments. We spend lots of time being unsure there.
- Actually element list is working, we think it’s a NVDA mode we didn’t realize we were in. (Capslock-space bar?). There are headings to bring people to to some main areas, including the toc. From the toc you can navigate document.
- NVDA prioritizes describing the action/type of UI in many cases. Like it will say “dialog” then the comment input area’s title. Or “clickable” then user name of that clickable user name. (I don’t think this was VoiceOver’s behavior).
- Responses post-action as important. Confirmation that you made a comment, for example. Confirmation that a link has been copied to clipboard. It seems like that happens sometimes, but not always.
- Does not announce users coming and going (entering document). (Webex actually does this, makes a notification when people enter or leave meetings on a “participants list.” Webex is operating on a different time scale than Docs, though.)
- Inline commenting doesn’t seem clear? Like it doesn’t announce the text it’s tied to. Is this a whole document comment, or a specific text one?
- Mention:
    - we aren’t pro screen reader users.
    - Google Docs is an unusual case! It may not be the “normal case” but that it actually is calibrated to work well if you know what you are doing.
    - [https://webaim.org/blog/seismic-change-to-docs/](https://webaim.org/blog/seismic-change-to-docs/)
    - So it may have a unique experience for us to think about, but don’t expect it to be the normal (or even navigable for us non-daily screen reader users.)
- What’s useful with an RTC best practices for accessibility?
    - Depends on context! If I’m a developer, I want to see a how-to. How to make different types of things, with examples.
    - WAI ARIA authoring practices are a useful example. Describes what it is (with a navigable heading), how to do it, and has interactable examples.
    - “What hat I’m wearing” changes what I want to find.
        - Implementer/developer
        - Reviewer (though there is overlap here)
        - Fun police (may be during review, may be earlier.) (Warning ahead of time that people are doing inaccessible things.)
            - Understanding WCAG docs  [https://www.w3.org/WAI/WCAG21/Understanding/](https://www.w3.org/WAI/WCAG21/Understanding/)
            - These talk about “why things matter” not how to do it right or anything.
    - Frustrating about documentation: when people don’t give examples and/or compare to similar, more familiar things. Also when people don’t say “what the thing is not.”
        - Giving concrete examples

