# Web Accessibility

Web accessibility tends to be implemented as an afterthought after audits, because of ignorance rather than ill will. a11y should be seen as a basic requirement, we currently are lacking awareness for. Don't exclude people. Start removing physical and/or cognitive barriers people have with software.

This repo is meant as learning material for web development with accessibility top of mind.

## Goals

1. A button does things, a link takes you places
2. Experiment: Instead of powering smoke tests via XPath and CSS selectors, use the a11y tree (or tab navigation)
3. Browse a page with NVDA and/or VoiceOver
4. Develop a custom select
5. Develop a popup menu

## Tutorials

- https://developers.google.com/web/fundamentals/accessibility  (added 2021-05-05)
- https://www.w3.org/WAI/tutorials/ (added 2021-05-05)

## Reading list

1. [Accessibility: Where to start?](https://www.youtube.com/watch?v=byh6G3vViWM) (added 2021-05-05)
2. [Creating an Accessibility Engineering Practice](https://blog.danielna.com/creating-an-accessibility-engineering-practice/) (added: 2021-05-05)
3. [Introduction to Web Accessibility](https://webaim.org/intro/) (added: 2021-05-05)
4. [Constructing a POUR Website](https://webaim.org/articles/pour/) (added: 2021-05-10)
5. [The web accessibility basics](https://www.marcozehe.de/articles/2015-12-14-the-web-accessibility-basics/) (added: 2021-05-05)
6. [Five Rules of ARIA](https://www.w3.org/TR/aria-in-html/#notes2) (added: 2021-06-03)

- https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/ (added 2021-05-05)
- https://hiddedevries.nl/en/blog/2021-04-02-accessible-front-end-components-claims-vs-reality (added 2021-05-05)
- https://inclusivedesignprinciples.org/ (added 2021-05-05)
- https://alistapart.com/article/my-accessibility-journey-what-ive-learned-so-far/ (added 2021-05-05)
- https://www.a11ymatters.com/patterns (added 2021-05-05)
- https://developer.mozilla.org/en-US/docs/Web/Accessibility (added 2021-05-05)
- https://www.w3.org/WAI/fundamentals/ (added 2021-05-05)
- https://www.youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g (added 2021-05-05)
- https://ux.shopify.com/make-commerce-better-for-everyone-b96f0621ddf3 (added: 2021-05-10)

## Component examples

- [Example implementations of ARIA design patterns](https://www.w3.org/TR/wai-aria-practices-1.1/examples/) (added: 2021-05-05)

## Reference material

- https://empathyprompts.net/ (added: 2021-05-05)
- https://inclusive-components.design/ (added: 2021-05-05)
- https://pattern-library.dequelabs.com/ (added: 2021-05-05)
- https://w3c.github.io/html-aria/ (added: 2021-05-10)
- https://ebay.gitbook.io/mindpatterns/ (added: 2021-05-10)

## Q & A

| Question | Answer |
| - | - |
| Why the name a11y? | a11y is a numeronym (words replaced with numbers), in which the word "accessibility" has 11 characters between first and last letter. |
| What is AT? | Acronym of Assistive Technologies; broad range of automation tooling built for people with disabilities to use software. Use accessibility tree to create alternate user interface. AT relays user interactions via APIs to the browser for translation into application actions. |
| What is a11y tree? | The accessibility tree exposes an interface representing a UI's meaning and associations between nodes. |
| Why semantic HTML? | Specified behavior and associations between elements cannot be interpreted by AT if visuals used to describe meaning. |
| What's the acronym ARIA? | Accessible Rich Internet Applications. |
| What's the use case for ARIA? | Set of HTML attributes to directly and intentionally adapt the a11y tree, like hiding or manipulate meaning. |
| What's a screen reader? | An operative level tool that explains content to users |

## Be helpful

The web offer **independent access** to information. Instead of seeing a11y as a feature, design for everyone. Simple navigation, helpful illustrations and logically organized content increase usability for all users.

### POUR website

- Perceivable (P)

  Anyone should be able to input information into their brain for further processing. If they can't, the information is inaccessible. In practice, content should be communicate its message with styling disabled.

- Operable (O)

  Don't expect everyone to use the same input device as you to navigate the web. As a rule of thumb, make the page usable with only a keyboard, as most alternative devices emulate a keyboard's functionality.

  Don't expect others to navigate the way you are. Often overviewing and quick navigation through content is supported.

  Don't commit changes without confirmation, if recovery isn't easy. Include instructions and expect mistakes. For cognitive purposes, make animations optional.

- Understandable (U)

  Don't separate usability and accessibility. Use simple and concise language, adapted to users and intention. Be consistent and predictable in interactions.

- Robust (R)

  Validate HTML! Sticking to standards is a safe bet for robustness. Aim to not require specific browsers or devices. At least, use a baseline, where sacrifices in functionality is thought through when using browsers with less capabilities.

## Accessibility checks

- Does a control semantically represent what it's used for?
- Which actual element has focus when a control is highlighted? Is it directly interactable?

## Tools

- [The W3C Markup Validation Service](https://validator.w3.org/)
- a11y tree in Edge/Chrome's DevTools: `CTRL+SHIFT+P` then search for _Show Accessibility_
- axe DevTools: Accessibility Checker browser plugin

## Log

1. 2021-05-03: Find study material. Only briefly browsed through.
2. 2021-05-03: Watched presentation about Getting Started with #a11y: https://www.youtube.com/watch?v=byh6G3vViWM
3. 2021-05-05: Goal 1-4 defined
4. 2021-05-05: Read https://blog.danielna.com/creating-an-accessibility-engineering-practice/. It's a keeper 👍
5. 2021-05-10: Notes from last session
6. 2021-05-10: Start describing a POUR website
7. 2021-05-19: POUR principles described
8. 2021-05-24: Performed first accessibility audit
9. 2021-05-24: Built breadcrumb component based on https://www.w3.org/TR/wai-aria-practices-1.1/examples/breadcrumb/index.html
10. 2021-06-03: Improved description for assistive technologies and accessibility tree
