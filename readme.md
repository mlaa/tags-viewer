**TAGS Viewer** allows users to browse, explore, and search a *Twitter* archive. As a backend, it requires Martin Hawksey’s [Twitter Archive Google Spreadsheet (TAGS)][1]. TAGS provides a free, non-technical method of archiving tweets for a given hashtag, which can be particularly useful for capturing a conference’s [backchannel][2].

This application is contained in a single HTML file and has no server dependencies, which makes it easy to host anywhere: just upload a single file (this one!) and you’re done. Or, if you don’t need to share it with anyone, just double-click the file on your hard drive to open it in your Web browser. Configuration is as simple as supplying a Google Spreadsheet URL.

### Demo
[**Try the demo**][3] (bring your own TAGS URL) or take a look at [an ongoing archive of #mla13][4]. **New:** You can now specify the key of your own TAGS spreadsheet in a querystring, like so:

**http://mlaa.github.com/tags-viewer/?0AueHfws2ZtlKdGlxSlp6UExKa2hid1VwVW9RWmx6eGc**

This means you can use the demo to display your own archive, no set up necessary!

### About
TAGS Viewer is a JavaScript application using [jQuery][5], [Underscore.js][6], [Moment.js][7], [jQuery Hashchange][7], [Bootstrap][9], and [Sheetrock][10].

This work is licensed under a [Creative Commons Attribution-NonCommercial 3.0 Unported License][11].

<img src="http://i.creativecommons.org/l/by-nc/3.0/88x31.png" width="88" height="31" alt="Creative Commons License" />

[1]: http://mashe.hawksey.info/2012/01/twitter-archive-tagsv3/
[2]: http://en.wikipedia.org/wiki/Backchannel
[3]: http://mlaa.github.com/tags-viewer
[4]: http://hashtag.mla13.org
[5]: http://jquery.com
[6]: http://underscorejs.org
[7]: http://momentjs.com
[8]: http://benalman.com/projects/jquery-hashchange-plugin/
[9]: http://twitter.github.com/bootstrap/
[10]: https://github.com/chriszarate/Sheetrock
[11]: http://creativecommons.org/licenses/by-nc/3.0/