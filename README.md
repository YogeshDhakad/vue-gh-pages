# vue-gh-pages"

build
npm run build

navigate into the build output directory
cd dist

git init git add -A git commit -m 'deploy'

git push -f https://github.com/YogeshDhakad/vue-gh-pages.git master:gh-pages OR git push -f git@github.com:/.git master:gh-pages
