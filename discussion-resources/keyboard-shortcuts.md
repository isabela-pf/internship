# What are keyboard shortcuts' relationship to accessibility?

[Keyboard shortcuts](https://en.wikipedia.org/wiki/Keyboard_shortcut) are
a key or series of keys that can be used to immediately access an action 
in a piece of software. In many cases, they may move the user's focus to a 
new region of the interface quickly or remove the need to repeatedly navigate
to the same parts of the interface to access common actions.

Because of this, we came to a discussion about how keyboard shortcuts contribute
to accessibility. Can they alone count for keyboard navigation, or are they at
best an extremely helpful addition? How accessible can they be when they often 
require users to memorize their combinations? How accessible can they be when 
they often require fine motor skills to press multiple buttons at once?

## Are keyboard shortcuts sufficient navigation for accessibility?

- [Keyboard Accessibility Accesskey - WebAIM](https://webaim.org/techniques/keyboard/accesskey)
     - There's a mix of information here, but it also discusses the limits of the idea that shortcuts will work without fail and may always be relied on.
- [Keyboard access - 18F Accessibility Guide](https://accessibility.18f.gov/keyboard/)
     - There's no mention of shortcuts in many keyboard accessibility tests or discussions. 
- Isabela: I'm struggling to find good resources for this, but that does make me think shortcuts are probably a useful enchancement on top of good standard keyboard navigation, not a replacement.

## What should be considered when choosing keyboard shortcuts?

- [WCAG 2.1 Success Criterion 2.1.4 Character Key Shortcuts](https://www.w3.org/TR/WCAG21/#character-key-shortcuts)
     - Lists a foundation for what functionality is needed to have an accessible shortcut
- [Appreciating accessibility - Keyboard shortcut guidelines - 
erresen.github.io](https://erresen.github.io/csharp/dotnet/accessibility/shortcuts/visualstudio/2020/07/26/appreciating-accessibility.html)
     - Mentions "one-handed shortcuts" as an addition
- [User experience design - Keyboard - IBM Accessibility](https://www.ibm.com/able/toolkit/design/ux/keyboard/)

## Conclusion

We probably need more information to be confident about any conclusion!
But some takeaways are:
- Keyboard shortcuts are not innately inaccessible! In fact, they can be extremely helpful!
- Shortcuts need to be discoverable in interface, without the need for hover interactions (a mouse-only interaction)
- Shortcuts need to be remappable and/or able to be turned off
- Shortcuts will always conflict with something (OS, browser, assistive tech, so on), and may be different based on localization
- Shortcuts related to a specific selection need to only be active when that selection is focused
- Keyboard shortcuts probably should not be the only way to navigate an interface
