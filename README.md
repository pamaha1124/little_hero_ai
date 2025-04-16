# little_hero_ai
@pamaha1124:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=GH_TOKEN
@pamaha1124:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=GH_TOKEN
npm publish
docker build -t ghcr.io/pamaha1124/little_hero_ai:latest .
docker push ghcr.io/pamaha1124/little_hero_ai:latest
