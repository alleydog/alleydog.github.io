A website in a single HTML file. It simply uses the `#anchor` suffix and the `:target` CSS selector to show and hide pages/content.

To create a new page, add a `<section>` with a unique `id`:
```html
<section id="contact">
   Contact me!
</section>
```
Then you could add a link to it inside `<nav>`:
```html
<a href="#contact">Contact</a>
```

[See original](https://github.com/cadars/john-doe)

[More read on Habr](https://habr.com/ru/companies/first/articles/653771/)
