# blog.rustfest.eu

This repo contains the blog of RustFest.eu

## local build

To build the blog locally with docker run the following command:
```
docker run --rm --volume=$(pwd):/srv/jekyll -p 35729:35729 -p 4000:4000 -it jekyll/jekyll jekyll serve
```

Do not forget to clear the image every now and then:
```
docker rmi jekyll/jekyll
```
