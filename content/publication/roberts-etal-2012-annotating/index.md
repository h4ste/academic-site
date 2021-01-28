---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Annotating Spatial Containment Relations Between Events
subtitle: ''
summary: ''
authors:
- Kirk Roberts
- Travis Goodwin
- Sanda M Harabagiu
tags: []
categories: []
date: '2012-05-01'
lastmod: 2021-01-27T18:35:25-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-01-28T17:24:30.418302Z'
publication_types:
- '1'
abstract: "A significant amount of spatial information in textual documents is hidden\
  \ within the relationship between events. While humans have an intuitive understanding\
  \ of these relationships that allow us to recover an object's or event's location,\
  \ currently no annotated data exists to allow automatic discovery of spatial containment\
  \ relations between events. We present our process for building such a corpus of\
  \ manually annotated spatial relations between events. Events form complex predicate-argument\
  \ structures that model the participants in the event, their roles, as well as the\
  \ temporal and spatial grounding. In addition, events are not presented in isolation\
  \ in text; there are explicit and implicit interactions between events that often\
  \ participate in event structures. In this paper, we focus on five spatial containment\
  \ relations that may exist between events: (1) SAME, (2) CONTAINS, (3) OVERLAPS,\
  \ (4) NEAR, and (5) DIFFERENT. Using the transitive closure across these spatial\
  \ relations, the implicit location of many events and their participants can be\
  \ discovered. We discuss our annotation schema for spatial containment relations,\
  \ placing it within the pre-existing theories of spatial representation. We also\
  \ discuss our annotation guidelines for maintaining annotation quality as well as\
  \ our process for augmenting SpatialML with spatial containment relations between\
  \ events. Additionally, we outline some baseline experiments to evaluate the feasibility\
  \ of developing supervised systems based on this corpus. These results indicate\
  \ that although the task is challenging, automated methods are capable of discovering\
  \ spatial containment relations between events."
publication: "*Proceedings of the Eighth International Conference on Language Resources\
  \ and Evaluation (LREC'12)*"
url_pdf: http://www.lrec-conf.org/proceedings/lrec2012/pdf/1091_Paper.pdf
---
