Personal website built using Github Pages and Jekyll.

To install and test locally:

1. Install Ruby and the Ruby DevKit
    https://rubyinstaller.org/downloads/
2. Run in terminal:
    gem install jekyll bundler
3. Create Gemfile file with the following content :
    source 'https://rubygems.org'
    gem 'github-pages', group: :jekyll_plugins
4. Run in terminal:
    bundle exec jekyll serve --watch
    The website is now visible in http://localhost:4000