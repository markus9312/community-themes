# WordPress Community Themes

Welcome to the repository for Block Themes built by the WordPress community.

## About

WordPress is in a new era of theming and site creation. This repo encourages both experienced and new  WordPress contributors to create more themes — demonstrating what can be done and how. This way we learn from and inspire each other.

The aim of this repo is to submit the block themes to the WordPress.org themes directory under the WordPress user, ensuring the quality of the code and design of said themes. This initiative will help more users without prior theming knowledge or who don't code to create high quality themes by themselves using the new site building tools.

### Getting Started

To get started with development you have a couple of options. You can set up a local environment or you can use the new [WordPress Playground](https://developer.wordpress.org/playground/) and build your theme online without needing to install anything at all on your machine.

**If you prefer to use the Playground:**

1. Visit the [Playground](https://playground.wordpress.net/?theme=twentytwentythree&plugin=gutenberg&plugin=create-block-theme&url=/wp-admin/index.php). This instance has the Create Block Theme plugin installed.
1. Go to Appearance/Site Editor and build your theme!
2. Export it using the Create Block Theme plugin under Appearance/Create Block Theme

The Playground has a few limitations and you won't be able to add new fonts to your theme using it.

**If you want to work locally:**

1. Set up a WordPress instance, here is a [handy guide to install WordPress locally](https://wordpress.org/support/article/installing-wordpress-on-your-own-computer/)
2. Clone / download this repository into your `/wp-content/themes/` directory
3. You may want to install the [Create Block Theme plugin](https://wordpress.org/plugins/create-block-theme/) to help you generate the theme files if you want to build your Theme directly on the Site Editor.

If it's your first time building a Block Theme, we suggest checking the Resources links for more information.

#### Requirements for local setup

- WordPress 6.1+
- PHP 5.6+
- License: [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html) or later

### How to contribute a new theme

You can contribute with code, designs or discussion.

To submit a theme design, include a Figma link or a zip file of your theme created using the Create Block Theme plugin. You can use the [Twenty Twenty-Three Figma Mockups](https://www.figma.com/community/file/1139275543113752375) as a reference.

We will kickstart this initiative by building child themes of Twenty Twenty-Three. The themes can include as many or as few templates as you prefer, and the rest will be inherited from the parent theme.


### Guidelines for new themes

When in doubt, check the [guidelines for the WordPress.org Themes repository](https://make.wordpress.org/themes/handbook/review/required/)!

As a reminder, some of the things to keep in mind when building a theme usually are:

- Paying attention that all strings are translatable. The best way to do this right now is to use block patterns for the areas of your theme that have strings on them. If you don't want that pattern to show in the inserter, you can do this like [TT3 does it for its 404 page](https://github.com/WordPress/twentytwentythree/blob/trunk/patterns/hidden-404.php).
- When deciding a name for your theme, consider [these guidelines](https://make.wordpress.org/themes/2013/02/26/clarifying-guidelines-for-theme-name/). If you want to make sure that the name you chose is available, have a look at the [list of themes on svn](https://themes.svn.wordpress.org/) for the repo.

### Theme Utilities
We have a node script which you can use to updated patterns ready for deployment. It does the following steps:
1. Updates text strings to be wrapped in i18n functions.
2. Changes image paths so that they point to the directory that the theme is installed in.

## Resources

- [Twenty Twenty-Three Figma Mockups](https://www.figma.com/community/file/1139275543113752375)
- [Twenty Twenty-Three Project kickoff post](https://make.wordpress.org/design/2022/08/10/twenty-twenty-three-default-theme-project-kickoff/)
- [Setting up a development environment](https://developer.wordpress.org/block-editor/handbook/tutorials/devenv/)
- [Create Block Theme plugin](https://github.com/WordPress/create-block-theme)
- [Block Theme documentation](https://developer.wordpress.org/block-editor/how-to-guides/themes/block-theme-overview)
- [Global Styles & theme.json documentation](https://developer.wordpress.org/block-editor/how-to-guides/themes/theme-json/)
- [Simple Site Design with Full Site Editing Course](https://learn.wordpress.org/course/simple-site-design-with-full-site-editing/)
- [Low-Code Block Theme Course](https://learn.wordpress.org/course/develop-your-first-low-code-block-theme/)
- [A Developer's guide to Block Themes](https://learn.wordpress.org/course/a-developers-guide-to-block-themes-part-1/)
