baseURL = "https://naseer.github.io/" # Change 'naseer' to your username
languageCode = "en-us"
title = "Random Bits" # Change to your site name
theme = "hugo-coder"

[params]
  author = "Your Name"
  description = "My personal blog"
  avatarURL = "" # Add a link to a profile pic if you want

[[params.social]]
  name = "GitHub"
  icon = "fa-brands fa-github"
  url = "https://github.com/your-username"

[menu]
  [[menu.main]]
    name = "Blog"
    weight = 1
    url = "posts/"
  [[menu.main]]
    name = "About"
    weight = 2
    url = "about/"
