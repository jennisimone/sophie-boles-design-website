# Building to github pages

First you need to run the following to compile your changes to github.
`ng build --base-href "https://jennisimone.github.io/sophie-boles-design-website/"`

Secondly, this command will push up the new build
`npx angular-cli-ghpages --dir=dist/sophie-boles-design-website`