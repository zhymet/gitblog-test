# gitblog-test

## gitblog repository format
There are two options for configuring the layout of a repository default and custom. 
In both cases, the `.gitblog` folder must exist and must contain a `config.json` file.
All other paths are configurable via the config.json file. When linking
or creating a new blog this folder structure will be initially added:
```
repo-root/
  .gitblog/
    config.json
    about.md
    posts/
```

## gitblog config.json schema
``` json
{
  "version": 1,
  "title": "Github Repo Title",
  "brief": "",

  "postsDir": ".gitblog/posts",
  "aboutFile": ".gitblog/about.md",
}
```
