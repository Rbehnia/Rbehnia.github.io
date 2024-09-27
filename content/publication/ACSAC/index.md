---
title: 'Efficient Secure Aggregation for Privacy-Preserving Federated Machine Learning'
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin 
  - Arman Riasi
  - Mohammadreza Ebrahimi 
  - Sherman S. M. Chow 
  - Balaji Padmanabhan 
  - Thang Hoang

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2024-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: Accepted to ACSAC 2024

abstract: "Secure aggregation protocols ensure the privacy of users' data in the federated learning settings by preventing the disclosure of users' local gradients. Despite their merits, existing aggregation protocols often incur high communication and computation overheads on the participants and might not be optimized to handle the large update vectors for machine learning models efficiently. This paper presents e-SeaFL, an efficient, verifiable secure aggregation protocol taking one communication round in aggregation. e-SeaFL allows the aggregation server to generate proof of honest aggregation for the participants. Our core idea is to employ a set of assisting nodes to help the aggregation server, under similar trust assumptions existing works placed upon the participating users. For verifiability, e-SeaFL uses authenticated homomorphic vector commitments. Our experiments show that the user enjoys five orders of magnitude higher efficiency than the state of the art (PPML 2022) for a gradient vector of a high dimension up to 100,000."

# Summary. An optional shortened abstract.
summary: 

tags:
  - eseaFL

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2304.03841'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
