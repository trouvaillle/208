### How to serve locally
```sh
bundle install
bundle exec jekyll serve
```

### How to upload images on post
1. Upload images on path `/assets/img/study/books/...`<br/>
    ex. /assets/img/study/books/data-intensive-applications/${chapter}/${section}/${file_name}`
2. Import images on post markdown.
    ```md
    ![Figure 3-1]({{ "/assets/img/study/books/data-intensive-applications/chapter03/section1/figure3-1.png" | relative_url }})
    ```

### Thanks to
* https://github.com/pages-themes/minimal