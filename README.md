Campaign website for Chris Tuck

## Docker Instructions
### Official Jekyll Image

docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve