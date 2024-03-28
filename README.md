# Hyde

**Hyde** is an archive of The Phoenix Chronobiology Projects' original website, at `phoenix.tc-ieee.org`. That site was retired when the host site was refactored.

The archived content deployed with <a href="https://jekyllrb.com" target="_blank">Jekyll</a>, a static site generator.

## Building the site

### Production build

The site is built and deployed by GitHub from the main branch. A build is triggered by any push to that branch.

> The repository currently places minimal constraints on change. Anyone with write access may directly `push` content from a local repository to the GitHub repository. Expect more robust change management as the number of contributors grows. 

### Local build

>   The following is derived from [docs.github.com / "Text site locally with Jekyll"](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll). If you have problems with the following instructions then see the GitHub docs.

1. Set up `git`

    See <a href="https://git-scm.com/downloads" target="_blank">https://git-scm.com/downloads</a>.

1. Install Ruby and Jekyll.

    See <a href="https://jekyllrb.com/docs/installation/" target="_blank">https://jekyllrb.com/docs/installation/</a>.

1. Checkout repository

    ```
    git clone https://github.com/phoenix-chronobiology/hyde.git
    cd hyde
    ```

1. Run `bundle install`.

1. Run your Jekyll site locally.

    ```
    $ bundle exec jekyll serve
    > Configuration file: /Users/octocat/hyde/_config.yml
    >            Source: /Users/octocat/hyde
    >       Destination: /Users/octocat/hyde/_site
    > Incremental build: disabled. Enable with --incremental
    >      Generating...
    >                    done in 0.309 seconds.
    > Auto-regeneration: enabled for '/Users/octocat/hyde'
    > Configuration file: /Users/octocat/hyde/_config.yml
    >    Server address: http://127.0.0.1:4000/hyde/
    >  Server running... press ctrl-c to stop.
    ```

1. Open the local site.

    In your web browser, navigate to <a href="http://127.0.0.1:4000/hyde/" target="_blank">http://127.0.0.1:4000/hyde/</a>.
