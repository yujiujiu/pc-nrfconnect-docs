# Developer documentation for nRF Connect for Desktop

This repository documents how to develop nRF Connect for Desktop: If you want to
create a new app for it, modify an existing app or modify the core of nRF
Connect for Desktop itself.

This documentation can be read online at
https://NordicSemiconductor.github.io/pc-nrfconnect-docs/.

## Modifying the documentation

If you want to preview any changes locally before submitting them to the repo
you should set up Jekyll locally. You can read and follow the
[instructions on how to set up GitHub Pages site locally with Jekyll](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll)
but they mainly boil down to these steps:

1. Make sure you have a recent ruby.
2. If you have not already bundler installed, run `gem install bundler`.
3. Run `bundle install` once inside this repo folder.
4. Each time you want to view your local files run `bundle exec jekyll serve`
   and go to `http://localhost:4000`.

## Gotcha

When creating a new markdown page, you should include the Jekyll’s “Front
matter”: Two lines with three dashes like this at the beginning:

    ---
    ---

Sometimes Jekyll does not process the markdown files correctly without that and
[the GitHub Pages documentation also says they are required](https://help.github.com/en/articles/configuring-jekyll#front-matter-is-required),
so just include them, like in any other documentation file in this project.

## Contributing

See the
[infos on contributing](https://nordicsemiconductor.github.io/pc-nrfconnect-docs/contributing)
for details.
