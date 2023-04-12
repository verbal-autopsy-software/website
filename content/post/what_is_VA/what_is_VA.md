---
title: 'What is Verbal Autopsy?'
subtitle: 'Explaining the what, when, who, and where'
summary: Understanding Verbal Autopsy.
authors:
- admin
tags:
- Verbal Autpsy, VA, OpenVA
categories: []
date: "2023-04-11T00:00:00Z"
lastmod: "2023-04-11T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# image: 
#   placement: 1
#   caption: ''
#   focal_point: "Center"
#   preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# # Set captions for image gallery.
# gallery_item:
# - album: gallery
#   caption: Default
#   image: theme-default.png
# - album: gallery
#   caption: Ocean
#   image: theme-ocean.png
# - album: gallery
#   caption: Forest
#   image: theme-forest.png
# - album: gallery
#   caption: Dark
#   image: theme-dark.png
# - album: gallery
#   caption: Apogee
#   image: theme-apogee.png
# - album: gallery
#   caption: 1950s
#   image: theme-1950s.png
# - album: gallery
#   caption: Coffee theme with Playfair font
#   image: theme-coffee-playfair.png
# - album: gallery
#   caption: Strawberry
#   image: theme-strawberry.png
---

# What?

Verbal autopsy (VA) is a survey-based tool widely used to infer cause of death (COD) in regions without complete-coverage civil registration and vital statistics systems ([Li et al. 2023](https://openva.net/publication/li2021openva/)). 

# When?

"after a suitable bereavement interval ([Chandramohan et al. 2021](https://openva.net/publication/chandramohangha2021/))" after a death has occured

# Who?

the interview based on the questionaire is administered "to the family or caregivers of the deceased after a suitable bereavement interval ([Chandramohan et al. 2021](https://openva.net/publication/chandramohangha2021/))."

# Where?

List of Countries that use Verbal Autopsy (as of Apr. 2022)

{{< rawhtml >}}
<div>
    {{ $figure := resources.Get "/static/img/va_list.html" }}
    {{ $figure.Content | safeHTML }}
</div>
{{< /rawhtml >}}