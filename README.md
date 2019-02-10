# 5 minute chill

The source code of the website [5 Minute Chill](http://5minutechill.com). Contributions are welcome.

# Installation
## Local installation and development
Make sure you have Angular CLI installed and the latest NodeJS. Start the lite server using `npm run start` and you are good to go.

## Deploying to production
Build the application in production mode with the comamnd `npm run build:prod`. Notice the generated /dist folder after the build. Just copy the contents of that folder to production.

## Deploying to GitHub pages

- `ng  build --prod --output-path docs`
- `git pull --rebase`
- `git commit` && `git push`
- Make sure no changes are present in https://github.com/Dzhuneyt/5minutechill.com/settings
