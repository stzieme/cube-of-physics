# Cube of Physics, based on Spectral - Jekyll Theme

A Jekyll version of the "Spectral" theme by [HTML5 UP](https://html5up.net/).

![Spectral Theme](screenshot.jpg "Spectral Theme")

# How to Work with Git

First, checkout a copy of the website from the repository

`git clone https://github.com/kasumac/cube-of-physics`

Every change needs to be communicated into Git's index via

`git add <filename>` or
`git add *`

In Atom, you'll find all changes in "Unstaged Changes" resp. in "Staged Changes" after adding them. The second step is to commit these changes by transfering them with an according messaged into Git's head

`git commit -m "Message"`

Again, this can be done also in Atom by clicking "Commit to master". All changes are still local. To send them into the remote repository GitHub by

`git push origin master`

Now, you'll see all changes at [https://github.com/kasumac/cube-of-physics](https://github.com/kasumac/cube-of-physics) and, of course, live at [https://kasumac.github.io/cube-of-physics](https://kasumac.github.io/cube-of-physics).


# How to Use Jekyll

For those unfamiliar with how Jekyll works, check out [https://jekyllrb.com/](https://jekyllrb.com/) for all the details,
or read up on just the basics of [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/),
and [creating pages](https://jekyllrb.com/docs/pages/).

- **GitLab**: Simply fork this repository and start editing the `_config.yml` file!  
- **GitHub**: Fork this reposity and create a branch named `gh-pages`, then start editing the `_config.yml` file! The `.gitlab-ci.yml` file is only needed for GitLab Pages, so feel free to delete this if you are using GitHub instead.

bundle exec jekyll serve

# Added Features

* Add your **social profiles** easily in `_config.yml`. Only social profiles buttons you enter in `config.yml` show up on the site footer!
* **Coming soon**: Set **featured images** in front matter.
* **Coming soon**: Front page sections automatically pull from posts.

# Credits

Original README from HTML5 UP:

```
Spectral by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A big, modern, blocky affair with a mobile-style menu, fully responsive styling,
and an assortment of pre-styled elements. So, pretty much what you were expecting
-- except, of course, for how it's put together, specifically:

- It's built on Skel 3*, a leaner, more modular rewrite of my responsive framework.

  (* = still in development as of this writing)

- It uses flexbox*, which eliminates all kinds of terrible hacks and clunky layout
  stopgaps (like CSS grid systems).

  (* = not supported on IE8/9, but non-flexbox fallbacks are included)

- It uses Sass* a lot more intelligently, thanks in part to several new mixins
  and functions I've been working on (as well as a few by @HugoGiraudel).

  (* = still entirely optional if you prefer vanilla CSS :)

- A ton of other stuff.

In short, Spectral's the culmination of several new things I'm working on/trying out,
so please, let me know what you think :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)

```

Repository [Jekyll logo](https://github.com/jekyll/brand) icon licensed under a [Creative Commons Attribution 4.0 International License](http://choosealicense.com/licenses/cc-by-4.0/).
