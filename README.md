

A Github Pages template for academic websites. 
This is forked from https://academicpages.github.io/, which was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

## To run locally (not on GitHub Pages, to serve on your own computer), using Linux Ubuntu 18.04

1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

## Changes I added to the https://academicpages.github.io/

1. Added a 'Research' page to list research one has done or is currently doing.
1. Working on a markdown_generator for research.md files
1. Changed the layout/design: 
	- added an horizontal line to separate titles and content
	- removed the sitemap and feed links in the footer
	- replaced the CV content by an embedded cv.pdf 


