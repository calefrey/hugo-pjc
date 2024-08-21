# Hugo-PJC
A simple hugo site for academics, specifcally designed for Princeton but can be tweaked as needed.

My friend was tired of hand-updating HTML, so I turned it into a hugo template.

They weren originally inspired by [Jon Barron's Site](https://jonbarron.info/), and this is decidedly... simpler but has a similar feel.

## Features
- Configurable Bio and links on the homepage
- News section for quick blurbs
- Publications, with a space to put a summary/notes
- Blog for making your own posts

## Installation
1. Make a folder for your site
1. Download and extract this repo, putting it in /themes
2. Move the ExampleSite contents to the parent directory
3. Modify as needed

## Configuration
Bio/Summary goes in /content/_index.md

Take a look at the documents in exampleSite to get a feel for where to edit.
Copy and modify the hugo.toml file from the exampleSite folder

You can add new publications with the command `hugo new content/publications/{your-pub-name}.md` and editing the file it creates in /content

You can add short news blurbs with `hugo new content/news/{your-news-title}.md` and then add a short blurb into the file.
File contents will be rendered on the main page, newest first

You can add new posts, which will be their own pages, with `hugo new content/posts/{your-post-title}.md`