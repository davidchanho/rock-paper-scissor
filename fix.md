requirements:

- terminal - git
- npm from node

1. Install SASS

```
npm install
```

- note: node-sass is no long supported.

1. Compile SASS

```
npm run sass
```

npm run sass

```
"sass": "sass --watch styles/scss/index.scss styles/index.css",
```

note: Normally the scss and css should be in different folders. 

note: A build tool like gulp/grunt is normally used to compile scss files. If you want to also compile pug into html and typescript into javascript along with scss, it can do all of that at once. Since this is a small project , it's fine not to use gulp.
