---
layout: post
title:  "Basic Assessment of Jekyll"
date:   2018-02-08
categories: jekyll assessment
---

Jekyll seenms to have all of the capabilities we need. 

- We can use Jekyll to create pages, posts, or any item via our own definition.

- We can 'tag' our pages. `categories: jekyll, assessment`

- We create a search 
1. create a json file on the fly with jekyll looping
2. use javascript search that json file return results


- We can easily insert images of cats or screens, flows, etc. with markdown `![alt text](/img/cat1.jpg)`:

![cat1](img/cat1.jpg) > ![cat2](img/cat2.jpg) > ![cat3](img/cat3.jpg)

- We can link to Octagon components (see [Octagon page](https://tripwire.github.io/octagon/#!/PaginationControl) in nav).

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

To build the site using `jekyll serve` and if desired some aliases can be created for any common CLI tasks.
`alias jrun="jekyll serve"`
