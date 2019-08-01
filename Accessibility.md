# Accessibility 
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
# Mobile Responsiveness 
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
