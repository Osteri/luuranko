# Simple hugo theme.

## You need to have site where you test this theme, let's create one.

- Make sure you have hugo binary in your path
- Run `hugo new site new-blog` for creating a new site
- Go to your blog `cd new-blog`
- Add `theme = "luuranko"` to your config.toml file
- Go to theme folder `cd themes`
- Clone this theme `git clone https://github.com/Osteri/luuranko.git`
- `hugo -t luuranko`
- Create 1st test post `hugo new post/first.md`
- Create 2nd test post `hugo new post/second.md`
- Run test server `hugo server -D`
- Go to the IP
