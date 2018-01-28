# Funerama

This project use `pug`, `mdl` and `gulp`.
## Dependencies
[Node](https://nodejs.org/en/)
[NPM](https://www.npmjs.org/)
[Gulp v4](https://github.com/gulpjs/gulp/tree/4.0)

## Instalation
Go to "Initial Setup" - [Confluence documentation](https://mobystudio.atlassian.net/wiki/spaces/FUN/pages/175767577/FE+UI.)

## Running the site
```sh
$ docker run --name funerama-landing -it --rm -v $(pwd):/usr/src/app:rw -p3000:3000 iarguello/yeoman-mdl:v2 npm run start
```

## Gulp tasks
`npm run start` : Render a debug version of your project in your browser and start watching over file changes.
`npm run build` : Build a distribution version of the website in a `dist` folder.
`gulp serve:dist` : Build a distribution version of the website in a `dist` and render it a browser.

## Html templates - PUG
Pug - [Docs](https://pugjs.org/api/getting-started.html)
Conversor - [jade2html2jade](http://jumplink.github.io/jade2html2jade/)

## Email templates - MJM
MJML - [mjml.io](https://mjml.io/).
DOCS - [Confluence](https://mobystudio.atlassian.net/wiki/spaces/FUN/pages/179109904/Emails+-+MJML).                