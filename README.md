# socvr-website-content

This repository holds the content that is displayed at [socvr.org][1].

If you have a question about the contents ask one of the RO's in the [SOCVR chat room][2].

## Pages

The pages folder contains all the markdown and navigation files (i.e. the main content). 

The path of a markdown file relative from the `pages` folder is the URL path for that item. `index.md` is a special file name that can only appear directly inside the `pages` folder.

For example, this is how file translations are done:

<pre>
# Path in repo                 # translated url
/pages/index.md                socvr.org/
/pages/my-page.md              socvr.org/my-page
/pages/dir1/second-page.md     socvr.org/dir1/second-page
/pages/dir1/dir2/page-page.md  socvr.org/dir1/dir2/page-page
</pre>

### Navigation Files

Navigation files (named `_nav.csv`) are comma-delimited value files that hold data for site navigation. It is required to have one `_nav.csv` file in **every** folder inside and including the `pages` directory.

While it is not a requirement, it is strongly suggested that all links specified in navigation files be absolute (start with `/`).

## Styles

Right now, the server supports only a single file named `main.css` inside the `styles` folder. This might change in future versions based on need.

This css file will be applied to every page on the site.


[1]: https://socvr.org
[2]: http://chat.stackoverflow.com/rooms/41570/so-close-vote-reviewers
