# Blog

Our blog's content.

## How-to
* https://gohugo.io/hosting-and-deployment/hosting-on-github/
  * https://gohugo.io/getting-started/quick-start/
    * https://github.com/kishaningithub/hugo-creative-portfolio-theme

NOTE: it's best to fork the theme being used by hugo so changes can be pushed 
somewhere. Make sure to use the forked repo as the submodule theme. Similarly 
this is why the blog content is it's own repo.


## Making changes
To test locally, simply run:
```sh
hugo server -D
```

Publishing changes is done by GitHub Actions. As long as the changes are present in the main branch, deploying the changes will be done automatically.
