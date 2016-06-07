# What is it?

This framework allows for the implementation of three individual page styles, a "default" _(contents of `/core`)_ and additionally a "fixed" and "fluid" option to add to your pages.

Think of it like having options for your pages to be fixed/centered, fluid/filling the whole page, or an entirely different structure, simply by changing one word on one line of code in one file.

### Please take note of my unique structure.
```
/templates/
├── blog.html.twig
├── core
│   ├── body.html.twig
│   ├── doctype.html.twig
│   ├── fixed
│   │   ├── body.html.twig
│   │   ├── doctype.html.twig
│   │   ├── footer.html.twig
│   │   └── header.html.twig
│   ├── fluid
│   │   ├── body.html.twig
│   │   ├── doctype.html.twig
│   │   ├── footer.html.twig
│   │   └── header.html.twig
│   ├── footer.html.twig
│   └── header.html.twig
├── default_fixed.html.twig
├── default_fluid.html.twig
├── default.html.twig
└── partials
    ├── base_fixed.html.twig
    ├── base_fluid.html.twig
    ├── base.html.twig
```

---

If you follow the framework correctly when building your theme, you will be able to create your desired page styles in your Grav theme by modeling the following pages to retrieve the required templates:

```
├── default_fixed.html.twig
├── default_fluid.html.twig
├── default.html.twig
```

I've populated some example content in the theme's core files to demonstrate how to structure your own framework.

This is code taken from Grav's official [Theme Tutorial](https://learn.getgrav.org/themes/theme-tutorial).
