# waybackmachine-snapshot-fix

⚠️ Due to CORS, script will fail unless this itself is archived by Way Back Machine!

Fortunately, you can request to be crawled via "Save Page Now" on https://web.archive.org/

## TODO

- [ ] ~Replace all `link` hrefs~ (although not needed with js_ url)
- [ ] ~Replace all `script` srcs~ (although not needed with js_ url)
- [ ] Replace all inline CSS calls with URLs (i.e. background-image)
- [ ] Replace all `a` hrefs with proper links (local vs absolute, mailto: etc)
- [ ] Replace all `img` srcs with appropriate URL (Append /web/TIMESTAMPim_/)