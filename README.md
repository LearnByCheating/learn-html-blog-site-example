# Overview
This repository shows how to build a blog website using just HTML and CSS. It mimicks the Bootstrap front-end framework's styling using the same class names (with some exceptions for the grid section). You code the CSS Bootstrap classes by hand. This allows you to learn CSS and Bootstrap simulaneously. This Blog Site example mostly follows the styling of the Bootstrap blog page example https://getbootstrap.com/docs/5.2/examples/blog


# Video tutorials
This repository goes with a ten part series of Video and written tutorials you can view at https://www.learnbycheating.com/subjects/html-css. 


# Accompanying CheatSheet and Flashcards
There is an accompanying  HTML/CSS CheatSheet and FlashCards set available for the CheatSheet & FlashCards desktop application. It is both a reference and memorization tool. The app allows you to download existing CheatSheet & Flashcard modules such as this one. Each module is completely editable so you can add your own flashcards or modify it in any way that's helpful to you, adding your favorite code snippets for future reference. You can create your own CheatSheets as well for any topic. It costs $25. You can decide if the time you save with such a tool is worth it (I personally use it every day).
* Mac Version: https://apps.apple.com/us/app/cheatsheets-flashcards/id1492777748
* Windows Version: https://apps.microsoft.com/store/detail/cheatsheets-flashcards/9PP8R1C8GTNS


## Launch the app locally with VS Code and Live Server
There are 10 versions of this app that correspond with the 10 video/written tutorials.

There is a separate folder for each version called blog-site-v1 through -v10.

To launch each version with Live Server, you must:

1. Stop the current Live Server session by opening the page you want to launch in the editor. Right click anywhere in the editor. Select "Stop Live Server". 
2. Go to the .vscode/settings.json file. Then change the root file from "/blog-site-v1" to "blog-site-vX" changing X to the version number you are on. So version 2 would look like the below: 

``` json
{
  "liveServer.settings.port": 5500,
  "liveServer.settings.root": "/blog-site-v2"
}
```

3. Then right click on the index.html page > select Open With Live Server.
4. It will open the page in your default browser to http://127.0.0.1:5500/index.html


## Versions:
- blog-site-v1 - HTML Introduction
- blog-site-v2 - CSS and Bootstrap introduction. Add Stylesheet. Add Bootstrap CDN
- blog-site-v3 - Working with colors. Add color to site.
- blog-site-v4 - Grid layout.
- blog-site-v5 - Spacing.
- blog-site-v6 - Text.
- blog-site-v7 - Lists and Tables.
- blog-site-v8 - Links and Navbar.
- blog-site-v9 - Images
- blog-site-v10 - Forms and Buttons
