---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How to Update Blog"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-03-21T08:43:15+09:00
lastmod: 2020-03-21T08:43:15+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Just note to self.


1. hugo new post/title.md
2. ./deploy.sh

When private email warning appears, make sure to check your email is not private:
```
git config --local user.email
```

If you've committed with your private email, change history by
```
git filter-branch -f --env-filter "GIT_AUTHOR_NAME='yourname'; GIT_AUTHOR_EMAIL='9999+userid@users.noreply.github.com'; GIT_COMMITTER_NAME='yourname'; GIT_COMMITTER_EMAIL='9999+userid@users.noreply.github.com';" HEAD
```

'yourname' is checked by 'git log' command. '999+userid' can be found in your github setting.

### reference
https://www.d-wood.com/blog/2019/05/24_11229.html

