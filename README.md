# Welcome Module

This module adds over twenty pieces of content, some images, and configuration to help you get started on your website. It also adds a new hero image on the home page. The content added is designed to help you better understand Backdrop CMS and it's features. This module also includes the [User Guide module](https://backdropcms.org/project/user_guide_recipe), which can be installed separately.

## Audience (who is this for)

This module might be useful in the following situations:
- If you are new to Backdrop CMS and would like quickly spin up a new site with more content to help you find your way around the site and learn more about Backdrop. 
- You can use this module as a quick start to a simple site. Enabling this module along with some additional Backdrop recipes is a quick way to get started with a site that you can then edit and customize as much as you wish. 
- If you are building a contributed theme and would like to test your theme with some common and practical content. 

## Instructions

This recipe can be installed like any other module. However, this module does contain configuration and content which can only be deleted manually. Before installing this on your own site, you might want to consider installing this on a [free Demo site at BackdropCMS.org](https://backdropcms.org/demo) (these demo sites only last 24 hours). 

This module requires the following modules (which will be downloaded automatically if you are using the project installer in Backdrop CMS):

- [Video filter](https://backdropcms.org/project/video_filter)
- [Mini layouts](https://backdropcms.org/project/mini_layouts)
- [User guide recipe](https://backdropcms.org/project/user_guide_recipe)

## Details

Specifically, here is a list of the changes that this module makes to your site:

- **We create a new "About" page**, place it in the main menu along with a few sub-menu items. If you already had an About page, we unpublished it. You can still find the old version, if there was one, in the list of content for the site - /admin/content.

- **We generate over 20 pieces of content (nodes)**. The content generated is intended to help you better envision how Backdrop CMS can be used to build a website and to explain some of the features, while linking you to additional resources where you can learn more.
- In addition to generating additional new content, this module has **modified the default content in default post and default page provided by Backdrop core**. The content changes are intended to add useful information and context for someone using Backdrop CMS for the first time. 
- **Enables the User Guide Recipe module** which enabled the Book module (provided by Backdrop Core) and creates a User Guide book that is only accessible to logged in site visitors. The User Guide has general information about Backdrop, but can also be customized and used as a site specific user guide for your site. 
- **Installs and enables the Mini Layouts module**. The Mini Layouts module is a contrib module that allows us to create a layout within a layout. **We are using this module to create a special "footer" layout that we can use throughout the site**. Without this special Footer mini layout, we would have to place footer blocks into each layout individually and edit them in multiple places. With this module enabled, we can create one mini layout and manage it in one place, but use it in many places. 
- **We added a Contact Info block to the footer** that can be modified and reused on this site or deleted. 
- **We added a Recent Content view to the footer** to help showcase how the Views module (in core) works and what you can do with it.
- **Adds a hero image on the front page and makes it a little larger than it would be by default in the Basis theme**. It also changes the message in the front page hero image. 
- **We add a "profile" field to user accounts** and populate that field for the #1 user = admin. 
- **We add a Tags view and place it in the right sidebar of every post or tag taxonomy page**. This provides a quick way to find related content on the site.

## Uninstall or Upgrade Options

It is not currently possible to uninstall or upgrade this recipe. If you no longer wish to keep this functionality, you will need to remove the items added by the recipe manually.

## Feedback

We have been experimenting with a series of Recipe modules that can be used to add specific features or funcationality to your site. Recipes use existing core features and contributed modules to add funcationality and content to your site without adding new functionality that cannot already be found elsewhere.

[We very much appreciate your feedback](https://github.com/backdrop-contrib/welcome/issues/2) on this and all of our recipes.

## Current Maintainers

- [Tim Erickson](https://github.com/stpaultim).

## Credits

- Sponsored by [Simplo](https://www.simplo.site)

## License

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
