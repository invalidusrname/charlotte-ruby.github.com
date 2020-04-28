# charlotte-ruby.github.com

Charlotte Ruby User Group Website

## Getting Started

    git clone git@github.com:charlotte-ruby/charlotte-ruby.github.com.git
    cd charlotte-ruby.github.com
    git checkout master
    bundle
    bundle exec jekyll s

At this point you should be able to see preview the site at
[http://localhost:4000](http://localhost:4000)

## Adding a New Page or Post

    touch _posts/$(date +"%Y-%m-%d")_name_of_my_post.md
    git add _posts/*
    git commit -m "added new post"
    bundle exec jekyll s

## Contributing

    git checkout -b my-new-branch
    git add new-stuff
    git commit -m "I added new stuff"
    git push -u origin my-new-branch
    gh pr

## Deploying changes

TODO
