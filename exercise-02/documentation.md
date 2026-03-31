Portfolio Project: Documentation

Tech Stack used- HTML, TAILWINDCSS
Ideation Process
The goal was to create a minimalist and modern portfolio that prioritizes content clarity.
I thought of the design of the website first and then designed it on canva, this was the initial design-”Shourya Sharma.pdf”.
I first looked at several portfolio websites online to figure out the layout, color scheme and the content.
Color theme-
From the canva design I decided that my website background will be shades of gray and my text will mostly be yellow and sometimes white.
After I made the hero and landing page I realized I needed a change in the colors, and after asking a friend I settled of gray-900 in tailwind for the hero section.
I decided to keep the gray-900 shade for alternate sections and used a lighter shade of gray for the others.
Text-
While designing the website on canva, I tried searching for fonts related to tech, and eventually found an inbuilt font. On searching on chatgpt, I found out the name of the font was “Jetbrains Mono” and I imported it from google fonts into my code.
Logo-
Canva had a font where the text starts and ends with “<>” I thought of putting my initials and putting it as the logo for a website.
Added Responsiveness-
Added conditions for medium sized screen and "min-h-screen" aswell to make it responsive and adjust div size according to screen.
Design and alignment-
I first gave my website design from canva to chatgpt to review it and it gave me some better ideas like enclosing my tech stack languages in square brackets and the alignment of the hero section.
Challenges Faced
Alignment of containers: Aligning texts and divs like I wanted to was a nightmare. Even a small tweak in the code would change the layout completely and I would have to figure out why and where it went wrong. It took me about 3 hours to get the navbar and hero section aligned properly.
Size of containers: The amount of times i had to specifically type in the exact padding, margin height and width just to make it look good is huge. Initially images were behaving very differently and were changing in size a lot of times, I had to prompt chatgpt about 30-40 times about flex, gap, width,height ad other sizing factors in tailwind, just to figure out how to make it work.

Known Bugs-
Overuse of mx-auto: max-auto solved some of my alignment problems so I used them as the first solution i na lot of places, they didnt work most of the times though, and the code had a lot of useless mx-auto.
Not useful max-w-6xl: I used this in some parent containers where there is no use of max-width.
Misuse of justify-between: I used justify-between in places I was not supposed to, leading to it sometimes overriding spacing logic.
Hardcoded widths-I hardcoded some widths to satisfy the alignment and sizing needs but they might hurt responsiveness.


Additional Insights-
I learnt to add a scroll animation using “scroll-smooth” when i clicked on a div that is supposed to take me to another section of a website.
I learnt about various styling effects like transition-colors
I learnt to use leading-tight to control line height
Resources-
Learning Tailwind-
Tailwind CSS Tutorial For Beginners in Hindi | Tailwind CSS in One Shot By Hitesh Choudhary
     2.Tailwind CSS - Rapidly build modern websites without ever leaving your HTML.

Learning HTML-Code your first HTML Program || Complete HTML Series || Episode - 4

Designing Website-Home - Canva
Inspiration-
emmabostian/developer-portfolios: A list of developer portfolios for your inspiration


