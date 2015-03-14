# Kevino
a minimal, plane ghost theme

## Overview

`Kevino` is a ghost blogging platform theme. The theme features a minimal, responsive design with a cover page, disqus comment integration, font icons and various color options.

### [Kevino Demo](http://kin-n.com/)(Japanese language)

## Features

#### Cover page

There is a beautiful full screen landing page for you to display a cover image with blur effect. I suppied several color for you to choose for the cover, while of course you can add your own. You can also place your avatar, blog title, your bio and some social button here.

#### Responsive and Animation

Kevino is following the responsive design and works well in mobile devices. You may find some events is driven by great animation, thanks to the [Animate.css](http://daneden.github.io/animate.css/), which makes all these possible.

#### Disqus comments and Font Awesome

Integrate comment system with a simple user name input with [Disqus](https://disqus.com). Use [Font Awesome](http://fontawesome.io) icon to express yourself better. They are perfect for a personal site (such as blog), as well as some commercial CMS.

#### Code highlight

[highlight.js](http://highlightjs.org) is used as the code highlight engine of this theme. You can get a clean and good-look code block in your tech blog.

##Installation

1. Go to your Ghost site folder (via FTP or just on hard drive if you are hosted locally).
2. Find `content/themes` folder — go inside.
3. Upload Kevino folder there.
4. Restart Ghost.
5. Open site's dashboard (`http://yoursite.com/ghost`).
6. Navigate to "Settings".
7. At the very bottom find "Theme" line — select "Kevino" from dropdown menu.
8. Click "Save".
**Done**

#####Comments

Ghost doesn't have native comment system yet, so we'll have to use third party solution. And this solution is Disqus.

1. Go to [disqus.com](http://disqus.com) and sign up. Or in, if you already have an account.
2. Register new site and get a `short name` of Disqus.
3. Open "comments.hbs".
4. Add Disqus `short name` to `disqus_shortname` and save the file.
5. Open "post.hbs".
6. replace the `{{!-- {{> comments}} --}}` with `{{> comments}}` in `post.hbs`.
7. Save the file.
**Done**

##### Social Buttons

You should update the links and icons in `partials/social.hbs`. The icons comes from Font Awesome, see [here](http://fontawesome.io/icons/) for all icons you can use.

#####Analyze it!

If you want to see statistics of your blog, you may use Google Analytics or something else.

1. Open "analytics.hbs"
2. Paste code you got from any analytics service there.
3. Save the file.
**Done**

###Not the end — the begining!

Well done! Your blog is ready and set to go. Hope you'll like it.

Enjoy it and give me feedback. If you find any bugs, do not hesitate to point them out, and a pull request would be appreciated!

##Credits

Something wrong? Can't make theme work? Problems with configurating? **Write me!** I'll help you with pleasure: [send me a letter](mailto:kin@kin-n.com).

Design and development — [kimen929](http://github.com/kimen929).

