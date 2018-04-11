## Running Locally

1. Install Hugo
2. `hugo serve -wv`
3. `gulp` in another terminal

## Adding new epsidoes

Simply run:

1. `hugo new episodes/201X-XX-XX-episode-XX-episode-title-here.md`

You can just create this file by hand in the filesystem, but the above command will use the
`archetypes/episodes.md` template to populate all the necessary front matter.

## Adding new pages

This probably won't happen often, but if needed, simply run:

1. `hugo new somepage.md`

### Kudos

- http://danbahrami.io/articles/building-a-production-website-with-hugo-and-gulp-js/
- https://regisphilibert.com/blog/2018/02/hugo-the-scope-the-context-and-the-dot/