# spine.github.io

Official Spine.js website.

Looking to contribute? Documentation is always a great place to start!

## Getting Started

We are using an basic template format of [Wintersmith](http://wintersmith.io/) which is a static site generator.

To contribute a change you'll want to edit the files (md or jade etc.) in the `src` dir of this repo.

To get that change to propegate to the html that actually gets published you need to use Wintersmith.


`npm install -g wintersmith`

In the `src/` directory:
`npm install.`

change the url in `config.json ` to something like: "http://localhost:8000", if you do that then when
`wintersmith preview`

[view in browser](localhost:8000/)

When every thing looks good (in `src/`):

If you changed the url in `config.json` then change it back:

`wintersmith build`

That's the stuff!
