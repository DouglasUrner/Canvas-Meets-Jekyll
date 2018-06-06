# Jekyll Theme for Canvas

Ideas for a custom [Jekyll][] theme for use with content for Canvas classes hosted on GitHub (or GitLab).

[jekyll]: <https://jekyllrb.com>

## Developing / Modifying a Jekyll Theme

My goal is to have a Jekyll theme that can be hosted on GitHub along with the toolchain necessary to test it locally. The individual pages will be able to reference it like this:

```yaml
remote_theme: owner/name
```

For example:

```yaml
remote_theme: douglasurner/canvas
```

[Customizing CSS and HTML in your Jekyll theme](https://help.github.com/articles/customizing-css-and-html-in-your-jekyll-theme/)

[Use any theme with GitHub Pages](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)

[Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)

Official Jekyll [Theme docs](https://jekyllrb.com/docs/themes/)

[Using Sass with Jekyll](http://markdotto.com/2014/09/25/sass-and-jekyll/)

## Theme Ideas

**Tabbed layout for assignment pages** - use big colorful tabs like these:

* [W3schools: Tab Headers](https://www.w3schools.com/howto/howto_js_tab_header.asp)
* [HTML Dog: CSS Tabs](http://htmldog.com/techniques/tabs/)

So that it is easy to see at a glance where students are. Fix tabs to top of page, so they don't scroll off.

**Use _display_ and _summary_ tags to let students see the big picture and focus on individual tasks.**

**Add checkboxes for completed steps (to preserve context between classes).**

[HTML Checkbox Code](http://www.html.am/html-codes/forms/html-checkbox-code.cfm)

**Sticky Footer**

[This](https://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/) works nicely.
