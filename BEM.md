# Block Element Modifier (BEM)
BEM
: CSS methodology/naming convention to make code easier to read and understand; Helps make independent blocks and css selectors reusable and modular

| Type | Rules | Type of HTML/CSS |
| ------ | -------- | ------------ |
| **Block** --> standalone entity that is meaningful on its own (eg. header, menu, container) | latin letters, digits, and dashes; Class is formed with short prefix | only use for class names (no tags or ids), cannot be dependent on other blocks/elements| 
| **Element** --> semantically tied to a block with no standalone meaning (eg. menu item, list item)| latin letters, digits, dashes and underscores; Class is formed with block name + 2 underscores + element name| only use for class names, no dependencies| 
| **Modifier** --> flag on a block/element to change apperance or behaviour (eg. disabled, highlight, size big)| latin letters, digits, dashes and underscores; Class is formed with block/element name + 2 dashes + description| Extra class name added to original block/element class| 
\*\*Other notes: BEM does not welcome global modifiers

                .block 
                .block__elem
                .block--mod or .block__elem--mod or .block--color--red
*** 
