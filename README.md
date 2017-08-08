# mbp-report

This is basic wraper around [pandoc](http://pandoc.org/index.html) tool with extra bits.

## Quick start

- get a copy of markdown template `mbp-report templ`
- make html report from your markdown template `mbp-report mkrep report.md`

## Setup

- symlinked `mbp-report` script into `/usr/local/bin` for system wide availability
- We need `css` and `images` directories to see in hostable place. I've symlinked them into `/usr/share/nginx/html/mbp-report`
