baseURL = "https://karthiktiwari.vercel.app"
languageCode = "en-US"
title = "Karthik Tiwari"
theme = "hugo-bearblog"
author = "Karthik Tiwari"
enableRobotsTXT = true
copyright = "Copyright © 2025, Karthik Tiwari."

disableKinds = ["taxonomy"]
ignoreErrors = ["error-disable-taxonomy"]

# Custom permalinks: blog posts appear at /blog/my-post/
[permalinks]
  blog = "/:slug/"
  tags = "/blog/:slug"

[params]
  title = "Karthik Tiwari"
  description = "AI Engineer. Systems Builder. Creative Technologist."
  favicon = "images/favicon.png"
  images = ["images/share.png"]
  # hideMadeWithLine = true
  # dateFormat = "2006-01-02"

[menu]

  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"
    weight = 1

  [[menu.main]]
    identifier = "blog"
    name = "Blog"
    url = "/blog/"
    weight = 2

  [[menu.main]]
    identifier = "projects"
    name = "Projects"
    url = "/projects/"
    weight = 3

[markup]
  [markup.highlight]
    style = "friendly"
    lineNos = true
    lineNumbersInTable = false
    codeFences = true
