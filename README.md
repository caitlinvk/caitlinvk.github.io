# Treat

Food/baking blog template for Jekyll.

## Setup

1. Add your site and author details in `_config.yml`.
2. Add your Google Analytics, Disqus and MailChimp keys to `_config.yml`.
3. Add your details to `_data/sidebar.yml`
4. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Treat was built with [Jekyll](http://jekyllrb.com/) version 3.4.3, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

### Posts/Recipes

* Add, update or remove a post in the *Posts* collection.
* The recipes page is organised by categories.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

