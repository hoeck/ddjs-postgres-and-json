# Short incomplete presentation about Postgres and JSON

Made with [spectacle](https://github.com/FormidableLabs/spectacle).

[postres-and-json.pdf](./postgres-and-json.pdf)

Install:
```
npm install --global spectacle-cli
```

Run the server with:

```
spectacle-cli -s slides/deck.mdx -t slides/theme.js
```

and then open the slides at
[localhost:3000](http://localhost:3000)
and the presenter screen in the same browser at
[localhost:3000/?presenterMode=true](http://localhost:3000/?presenterMode=true)
.

At
[localhost:3000/?exportMode=true](http://localhost:3000/?exportMode=true)
you can view a print-to-pdf friendly version of the slides.


Build the slides with:

```
spectacle-cli -s slides/deck.mdx -t slides/theme.js -a build
```
