# Learning Journal: Week 3

## Learning Activities

After watching the lecture demo, I went to my hosting provider to set up a WordPress installation on my site.

I copied my content from my Joomla site, which included several pages, but I forgot to change the category and commenting settings at the time I created these pages, so I found and used the bulk page editor onthhe WordPress dashboard to make all of my changes simultaneously.

Completed practical: [OverPro (WordPress)](https://sites.glam.dev/overpro-wp/)

## Estimated Hours

9 hours

# Content Insights

I added additional CSS to my site (lifted straight from my static site from week 1) to switch my theme to light-on-dark colours. The CSS was valid, but WordPress refused to save my changes with an unspecified error. After looking for mentions of similar problems online and a bit of trial and error, I found tha the 'additional CSS' field will refuse `@import`s, even though the live preview will consume and use these rules without issue.
