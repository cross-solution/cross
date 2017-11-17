---
title: 'the world is our home'
sections:
    - icon: pencil
      title: Eingabe Stellenanzeigen
      text: Eingabe einer Stellenanzeige im eigenen Layout.
    - icon: rocket
      title: Multiposting
      text: Einfach eine Stellenanzeige auf vielen Stellenbörsen veröffentlichen.
    - icon: newspaper-o
      title: Bewerbungs&shy;formular
      text: Minimale Hürden für den Bewerber. Anbindung an Xing, LinkedIn und Facebook
    - icon: comments
      title: Bewerber&shy;management
      text: Eingegangene Bewernung einfach bearbeiten. In Team bewerten. Bewerber einladen oder absagen.
metadata:
    keywords: 'Open Source, Human Resources, HR'
content:
    items: '@self.modular'
    order:
        by: date
        dir: desc
---

# Let's work remote
## we can show you **how** to do

Congratulations! You have installed the **Base Grav Package** that provides a **simple page** and the default **antimatter** theme to get you started.

!!! If you want a more **full-featured** base install, you should check out [**Skeleton** packages available in the downloads](http://getgrav.org/downloads).

### Find out all about Grav

* Learn about **Grav** by checking out our dedicated [Learn Grav](http://learn.getgrav.org) site.
* Download **plugins**, **themes**, as well as other Grav **skeleton** packages from the [Grav Downloads](http://getgrav.org/downloads) page.
* Check out our [Grav Development Blog](http://getgrav.org/blog) to find out the latest goings on in the Grav-verse.

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
