Aspire Ghost Theme
==================
##Introduction

**Aspire Theme** is a clean, lightweight, responsive theme for Ghost (http://www.ghost.org), the emerging Node.js blogging platform. This theme was developed consistent with the principles with which the Ghost platform was built - simplicity and intuitiveness. This theme was developed for Ghost v0.4, and although some assumptions may be made about the future development of Ghost being backwards compatible, no guarantees can be made that this theme will continue to work with future Ghost versions. Aspire Ghost Theme was modeled after Casper, the default Ghost theme, and was built using Bootstrap v3.1.1 (http://getbootstrap.com), taking full advantage of the Express 3 handlebars template engine. Some assets and elements were retained from Casper, to make some of the look and feel consistent with the platform defaults.

##Elements

###Top Post
The most recent post is highlighted inside a Bootstrap jumbotron, which by default is empty. Should you add a cover image to your blog, it will be used inside the jumbotron as a background image, with a dark layer over it so as to make the text over it more legible.

###List of Posts
All other posts are displayed in a flexible grid that will expand and collapse responsively depending on the device that's accessing the page. Small bits of meta information about posts are included to provide more details, but styled in a way so as not to demend too much attention from the user, making sure that the content is the main emphasis.

###Featured Post
Whenever the author features a post in Ghost, the post will move up in order to the top, and the look/feel will be adjusted to differentiate from regular posts.

###Partials
The layouts were put together in a modular fashion utilizing partials (components) to make it easier to make site-wide changes from single locations. Since various elements have a single source, the time it takes to customize the theme to your preferences and custom settings is trivial. Having to make changes in fewer places also adds the benefit of having consistent information across the site. Here are the various partials (located under `/partials/`) and their usage instructions:

<table>
    <tr>
        <td>File</td>
        <td>Description</td>
    <tr>
        <td>author-brief.hbs</td>
        <td>Brief author info pulled from the admin section (including gravatar)</td>
    </tr>
    <tr>
        <td>header.hbs</td>
        <td>The blog header for home page</td>
    </tr>
    <tr>
        <td>header-mini.hbs</td>
        <td>The blog mini header for all other pages aside from home page</td>
    </tr>
    <tr>
        <td>pagination.hbs</td>
        <td>The custom pagination implementation</td>
    </tr>
    <tr>
        <td>post-author.hbs</td>
        <td>The very brief "Written by" author copy</td>
    </tr>
    <tr>
        <td>post-date.hbs</td>
        <td>The very brief post date copy</td>
    </tr>
    <tr>
        <td>post-tags.hbs</td>
        <td>The very brief post tags copy</td>
    </tr>
    <tr>
        <td>social-profiles.hbs</td>
        <td>This includes links to social media profiles. This file needs to be adjusted with your own social media profile URLs.</td>
    </tr>
    <tr>
        <td>social-share.hbs</td>
        <td>This is the social media sharing component. To include other services, adjust accordingly.</td>
    </tr>
</table>

####Social Media
Aspire Theme also includes social media integration. Simply adjust social-profiles.hbs with your own social media profile URLs. Social sharing is also included for each post towards the bottom of each post. Currently the following services are included:
* Twitter
* Facebook
* Google Plus

### Additional Information
For additional information about Ghost and its features please refer to the Ghost website: http://www.ghost.org


