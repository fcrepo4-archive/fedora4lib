## fedora4lib

fedora4lib is the conference website for the Fedora Hackfest at code4lib 2013 in Chicago.

Built using [Octopress.org](http://octopress.org/).

Octopress is [Jekyll](https://github.com/mojombo/jekyll) blogging at its finest.

1. **Octopress sports a clean responsive theme** written in semantic HTML5, focused on readability and friendliness toward mobile devices.
2. **Code blogging is easy and beautiful.** Embed code (with [Solarized](http://ethanschoonover.com/solarized) styling) in your posts from gists, jsFiddle or from your filesystem.
3. **Third party integration is simple** with built-in support for Twitter, Pinboard, Delicious, GitHub Repositories, Disqus Comments and Google Analytics.
4. **It's easy to use.** A collection of rake tasks simplifies development and makes deploying a cinch.
5. **Ships with great plug-ins** some original and others from the Jekyll community &mdash; tested and improved.


## Notes

Cheat sheet:

* Generate/preview locally:
	* rake preview
* deploy to Github:
	* rake deploy
* Create a new page

	> rake new_page[super-awesome]
	> # creates /source/super-awesome/index.markdown
	>
	> rake new_page[super-awesome/page.html]
	> # creates /source/super-awesome/page.html
	

