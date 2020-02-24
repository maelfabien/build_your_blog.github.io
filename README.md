# Building your blog with Jekyll Minimal Mistake

This blog is a version that I slightly modified from the Jekyll Minimal Mistake blog. I am using it for my personal blog: [maelfabien.github.io](https://maelfabien.github.io/).

![images](/assets/images/image_blog.png)

In this folder, you'll find the steps to build your own blog. Jekyll mainly uses Markdown, rather than HTML, which makes it really easy to play around with.

## Create a dedicated repository

Github offers hosting for your personal blog. All you need to do is to create a repository whose name is:

`yourname.github.io`

Github will automatically offer to host it. Accept, create it, and setup your repo in a local folder with the commands given.

Then, put the content of this repository (download the ZIP or git clone) in this folder.

## What file is what?

- `config.yml`: Page to change your name, profile picture, linkedin, github link, add Google analytics...
- `_data/navigation.yml`: Change the name of the sections of your website in the upper band
- `_pages`: Contains the pages that your created. Pages are made to contain articles or projects.
- `_posts`: Contains the articles/posts directly as Markdown files. 
- `favicon.ico`: Your favicon, displayed in the tabs of browsers.
- `index.md`: The landing page of your website.
- `assets/images`: Put the images you'll use in your articles there.

All the other files are default ones, have a look at them, but you don't need to modify them to get started !

## What to modify?

- Take a look at `index.md` to check how to put links, bold text, scripts... Keep this information somewhere, it's a good template.
- Change the config file, and your personal image in the `assets/images` folder.
- Set up the tabs you want to display using `navigation.yml`. Watch out, they must point to existing pages in order to work.

![images](/assets/images/banner.png)

- Add pages if needed, or simply stick to the existing ones: a `blog.md` to add your articles inside, and a `portfolio-archive` that automatically displays your projects.
- Change the favicon. Check a favicon generator like [this one](https://favicon.io/).
- Change the `index.md` page and describe yourself
- Change in `navigation.md` the link to your resume. Add your resume in the `assets/images` or `assets/files`.
- Write your first article in the `_posts` section using the existing template. 
- Write your first project in the `_posts` section using the existing template. Make sure to have the `project` category on these articles, and they will be automatically added to the page `/portfolio`

## Cheat sheet

Just a few recaps on how to include and modify content on Markdown:

```
Here's how to insert a [link](https://www.google.com/).

You can also add all HTML elements you are used to:

<div class="github-card" data-github="maelfabien/Machine_Learning_Tutorials" data-width="100%" data-height="" data-theme="default"></div>
<script src="//cdn.jsdelivr.net/github-cards/latest/widget.js"></script>

You can make a link to your [email address](mailto:yourmail@gmail.com).

Your can put text in *italic*, **bold**, ***bold italic*** and use classic HTML too.

<hr>

Just add any script that you want at the end:

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/8.js?i=5ewlq11o62v&amp;m=0&amp;c=ff0000&amp;cr1=ffffff&amp;f=arial&amp;l=33" async="async"></script>
```

## How to publish?

To publish your website, simple push your modifications to Github. Your website will be hosted on `yourgitusernamegithub.io`. Explore, iterate, have fun :)