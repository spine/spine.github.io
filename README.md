# spine.github.io

Official Spine.js website.

Looking to contribute? Documentation is always a great place to start!

## Contribution Guide

We are using an basic template format of [Wintersmith](http://wintersmith.io/) which is a Node.js based static site generator.

To contribute a change you'll want to edit the files (md or jade etc.) in the `src` dir of this repo.

To get that change to propagate to the HTML that actually gets published you need to use Wintersmith.


`npm install -g wintersmith`

In the `src/` directory of this reop:
`npm install .`

#### To test your changes locally you can do the following:

change the url in `config.json ` to something like: "http://localhost:8000", if you do that then when you run `wintersmith preview` you will be able to see the rendered content [in your browser](localhost:8000/)

When you have everything looking good (in `src/`) you can shut down wintersmith

If you changed the url in `config.json` then change it back:

generate the new static site using `wintersmith build`

That's the stuff! Pull Request AHOY!
