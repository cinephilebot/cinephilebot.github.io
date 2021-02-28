How to download this project

Clone the project `git clone git@github.com:cinephilebot/cinephilebot.github.io.git`

Make the dist folder`mkdir dist`

Link the `dist` folder to the `gh-pages` branch
`git worktree add -B gh-pages dist origin/gh-pages`

`npm install` to download all the dependencies
`npm run build` to build the site
`npm run watch` to start the server with browsersync
