---
title: '[pomoc] Podgląd formatowania tekstu'
published: false
body_classes: 'title-center title-h1h2'
---

# UAP Report
## prawda czeka na odkrycie...

Congratulations! You have installed the **Base Grav Package** that provides a **simple page** and the default **Quark** theme to get you started.

!! If you see a **404 Error** when you click `Typography` in the menu, please refer to the [troubleshooting guide](http://learn.getgrav.org/troubleshooting/page-not-found).

### Find out all about Grav

* Learn about **Grav** by checking out our dedicated [Learn Grav](http://learn.getgrav.org) site.
* Download **plugins**, **themes**, as well as other Grav **skeleton** packages from the [Grav Downloads](http://getgrav.org/downloads) page.
* Check out our [Grav Development Blog](http://getgrav.org/blog) to find out the latest goings on in the Grav-verse.

!!! If you want a more **full-featured** base install, you should check out [**Skeleton** packages available in the downloads](http://getgrav.org/downloads).

### Edit this Page

To edit this page, simply navigate to the folder you installed **Grav** into, and then browse to the `user/pages/01.home` folder and open the `default.md` file in your [editor of choice](http://learn.getgrav.org/basics/requirements).  You will see the content of this page in [Markdown format](http://learn.getgrav.org/content/markdown).

### Create a New Page

Creating a new page is a simple affair in **Grav**.  Simply follow these simple steps:

1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `02.mypage`.
2. Launch your text editor and paste in the following sample code:

        ---
        title: My New Page
        ---
        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/02.mypage/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

! NOTE: The page will automatically show up in the Menu after the "Home" menu item. If you wish to change the name that shows up in the Menu, simple add: `menu: My Page` between the dashes in the page content. This is called the YAML front matter, and it is where you configure page-specific options.

! Details on the full capabilities of Spectre.css can be found in the [Official Spectre Documentation](https://picturepan2.github.io/spectre/elements.html)

The [Quark theme](https://github.com/getgrav/grav-theme-quark) is the new default theme for Grav built with [Spectre.css](https://picturepan2.github.io/spectre/) the lightweight, responsive and modern CSS framework. Spectre provides  basic styles for typography, elements, and a responsive layout system that utilizes best practices and consistent language design.

### Headings

# H1 Heading `40px`

## H2 Heading `32px`

### H3 Heading `28px`

#### H4 Heading `24px`

##### H5 Heading `20px`

###### H6 Heading `16px`

```html
# H1 Heading
# H1 Heading `40px`</small>`

<span class="h1">H1 Heading</span>
```

### Paragraphs

Lorem ipsum dolor sit amet, consectetur [adipiscing elit. Praesent risus leo, dictum in vehicula sit amet](#), feugiat tempus tellus. Duis quis sodales risus. Etiam euismod ornare consequat.

Climb leg rub face on everything give attitude nap all day for under the bed. Chase mice attack feet but rub face on everything hopped up on goofballs.

### Markdown Semantic Text Elements

**Bold** `**Bold**`

_Italic_ `_Italic_`

~~Deleted~~ `~~Deleted~~`

`Inline Code` `` `Inline Code` ``

### HTML Semantic Text Elements

<abbr>I18N</abbr> `<abbr>`

<cite>Citation</cite> `<cite>`

<kbd>Ctrl + S</kbd> `<kbd>`

Text<sup>Superscripted</sup> `<sup>`

Text<sub>Subscripted</sub> `<sub>`

<u>Underlined</u> `<u>`

<mark>Highlighted</mark> `<mark>`

<time>20:14</time> `<time>`

<var>x = y + 2</var> `<var>`

### Blockquote

> The advance of technology is based on making it fit in so that you don't really even notice it,
> so it's part of everyday life.
>
> <cite>- Bill Gates</cite>

```markdown
> The advance of technology is based on making it fit in so that you don't really even notice it,
> so it's part of everyday life.
>
> <cite>- Bill Gates</cite>
```

### Unordered List

* list item 1
* list item 2
    * list item 2.1
    * list item 2.2
    * list item 2.3
* list item 3

```markdown
* list item 1
* list item 2
    * list item 2.1
    * list item 2.2
    * list item 2.3
* list item 3
```

### Ordered List

1. list item 1
1. list item 2
    1. list item 2.1
    1. list item 2.2
    1. list item 2.3
1. list item 3

```markdown
1. list item 1
1. list item 2
    1. list item 2.1
    1. list item 2.2
    1. list item 2.3
1. list item 3
```

### Table

| Name                        | Genre                         | Release date         |
| :-------------------------- | :---------------------------: | -------------------: |
| The Shawshank Redemption    | Crime, Drama                  | 14 October 1994      |
| The Godfather               | Crime, Drama                  | 24 March 1972        |
| Schindler's List            | Biography, Drama, History     | 4 February 1994      |
| Se7en                       | Crime, Drama, Mystery         | 22 September 1995    |

```markdown
| Name                        | Genre                         | Release date         |
| :-------------------------- | :---------------------------: | -------------------: |
| The Shawshank Redemption    | Crime, Drama                  | 14 October 1994      |
| The Godfather               | Crime, Drama                  | 24 March 1972        |
| Schindler's List            | Biography, Drama, History     | 4 February 1994      |
| Se7en                       | Crime, Drama, Mystery         | 22 September 1995    |
```

### Notices

The notices styles are actually provided by the `markdown-notices` plugin but are useful enough to include here:

! This is a warning notification

!! This is a error notification

!!! This is a default notification

!!!! This is a success notification

```markdown
! This is a warning notification

!! This is a error notification

!!! This is a default notification

!!!! This is a success notification
```


