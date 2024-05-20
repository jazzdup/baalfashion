# baalfashion
note that the home page text is in assets/README.md according to config.yaml

# if tailwindcss error after cloning, try this before building: 
npm install -D tailwindcss postcss autoprefixer

# build:
cd themes/hugo-theme-luna && npm install postcss-cli -g && npm install --production && cd ../../ && hugo --gc -v --minify --cleanDestinationDir --enableGitInfo


