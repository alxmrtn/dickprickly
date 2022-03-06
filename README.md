### Local Development
```
docker run --rm \
  --volume="$PWD/docs:/srv/jekyll" \
  --publish 4000:4000 \
  jekyll/jekyll \
  jekyll serve
  ```