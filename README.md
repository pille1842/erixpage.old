# erixpage
Jekyll sources for my personal website. I am currently using Jekyll 2.5 to
build this. Upgrading to Jekyll 3 is planned.

Build instructions
------------------
1. Copy the `pre-commit` script to `.git/hooks/` to enable automatic updating
   of page modification dates. Make sure the YAML front matter of every file
   you wish to use this feature on contains an "updated: " field. When committing,
   the script will change this line to reflect the time of commit. The "updated"
   field is used to display a modification date in the footer.
2. Set the `baseurl` in `_config.yml` according to your needs.
3. Run `jekyll build` and have a lot of fun. :)

Licensing
---------
All contents of this repository are licensed under the terms of 
[Creative Commons Attribution-Share Alike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/),
including any and all blog posts and media unless noted otherwise.

The RSS icons in the assets/ folder have been released into the public
domain by Mozilla Foundation.