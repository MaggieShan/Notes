# **Web Development Topics** 
## Block Element Modifier (BEM)
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

## Accessibility 
Tips on how to improve user experience for people that struggle with any kind of vision, hearing, motor or cognitive impairments. 

| Type | Description |
|------| ----------- |
|Design| Make layout of content in an easy to follow order with the help of headings, subtitles, HTML semantics |
| | Consider keyboard only navigation and add HTML attributes like tabindex to help 
|| Ensure color palette has a strong contrast and does not clash with any complementary colours |  
|Text| Ensure font choice and size are readable and can be enlarged, use tables only for data and ensure descriptive headings |
|| Avoid vague titles for hyperlinks like "Click Here" |
|| Use proportional sizing to allow zooms and responsiveness| 
| Media| Always include alt text for images (consider which images need them decorative purpose vs contxt purpose) |
|| Add closed captions, descriptions and/or transcripts for audio and video files | 
|| Avoid using dynamic content that changes automatically (prompt users first) |
*** 
## Mobile Responsiveness 
Responsive websites
: respond to changes based on needs of the user and device

Mobile-friendly websites
: are designed to work the exact same way across all devices

| Element | Description | Practice |
|-----------------|-----------| ---|
|Viewport| instructs browsers on how to control page dimensions and scaling | establish 1:1 relationshpi between css pixels and device independent pixels| 
Media Queries | filters applied to css styles to change styles based on characteristics (width, orientation)| choose breakpoints for your code specifically, not for a device's size |
Images| media on your site | include breakpoints for images to use different resolutions based on different window sizes; compress images | 
***

## Search Engine Optimization (SEO)
SEO 
: the practice of increasing quality and quantity of website traffic, brand exposure and __organic__ search engine results 

Search engines
: use a process of "crawling and indexing" to evaluate and catablogue available/new/updated content and orders them based on how well it matches the query 

Understand user purpose:
 * Navigational --> looking for specific web page
 * Informational --> looking for specific topic
 * Transactional --> look to purchase specific product 

|Properties| Practices| 
|---|-----|
|Google specific| indicate specific pages to and not to crawl with sitemaps and robots.txt (also consider using google search console) |
HTML| titles should be unique and short| 
|| meta tags for descriptions should summarize the page |
|| use headings for keywords instead of excessively using <strong> or <em> |
| Navigation| use breadcrumb lists, keep directory well structured around the homepage/root (naturally flowing hierarchy)|
|| show useful 404 pages, avoid deeply nested directories, keep URLs short and easy to understand (less special chars)|
Link Profile| link to other credible and popular sites to maintain healty link profile| 
General| be responsive and accessible

Sitemaps
: XML file that provides search engines with information about pages available for crawling (eg. how important it is relative to other pages, and how often it's modified)

***



