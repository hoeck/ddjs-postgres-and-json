# Short incomplete presentation about Postgres and JSON

Slides: [postres-and-json.pdf](./postgres-and-json.pdf)

## Building the Slides

Made with [spectacle](https://github.com/FormidableLabs/spectacle).

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

## DresdenJS Meetup

Join us every 2nd Thursday of each month to listen and chat about exciting talks like this one.

MeetUp: https://www.meetup.com/DresdenJS-io-JavaScript-User-Group/

Slack: https://slackin-dresdenjs.herokuapp.com
