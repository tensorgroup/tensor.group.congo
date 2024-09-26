Tensor Group
===============
This is the static site generator content for https://tensor.group

It's a Hugo site with Congo theme, using hugo modules

[![Netlify Status](https://api.netlify.com/api/v1/badges/7ea596dd-fd29-4c82-a65a-625061e85597/deploy-status)](https://app.netlify.com/sites/sad-volhard-6934d2/deploys)

### Hugo commands

* https://gohugo.io/getting-started/quick-start/

    git submodule init
    git submodule update

    hugo new post/hello-beautiful/index.md
    hugo server -D

* or

    hugo mod init github.com/billzajac/tensorgroup-hugo
    hugo mod tidy

* update theme

    hugo mod get -u

Primary Tech
---------------
* https://gohugo.io/
* https://app.netlify.com/
* https://github.com/
* https://analytics.google.com/


Themes
---------------
* https://github.com/QIN2DIM/awesome-hugo-themes?tab=readme-ov-file

* https://themes.gohugo.io/themes/blowfish/
* https://themes.gohugo.io/themes/congo/
* https://themes.gohugo.io/themes/gohugo-theme-ananke/

* https://themes.gohugo.io/themes/hugo-papermod/
* https://themes.gohugo.io/themes/blox-tailwind/


Analytics Options
---------------
* https://docs.hugoblox.com/reference/analytics/
* https://umami.is/


Gallery
---------------
* https://themes.gohugo.io/themes/galleriesdeluxe/



Blowfish Theme
--------------

* Install bun (npm alternative)

    curl -fsSL https://bun.sh/install | bash

* Install blowfish-tools

    bun blowfish-tools

* Use blowfish-tools to build a new hugo site with the blowfish theme installed

    blowfish-tools new tensorgroup-hugo.2024-09-25


