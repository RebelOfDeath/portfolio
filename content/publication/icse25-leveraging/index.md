---
title: 'Leveraging Large Language Models for Enhancing the Understandability of Generated Unit Tests'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-09-27T00:00:00Z'
doi: '10.48550/arXiv.2408.11710'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '*International Conference on Software Engineering (ICSE)*'
publication_short: '*ICSE*'

abstract: Automated unit test generators, particularly search-
  based software testing tools like EvoSuite, are capable of generat-
  ing tests with high coverage. Although these generators alleviate
  the burden of writing unit tests, they often pose challenges for
  software engineers in terms of understanding the generated tests.
  To address this, we introduce UTGen, which combines search-
  based software testing and large language models to enhance
  the understandability of automatically generated test cases. We
  achieve this enhancement through contextualizing test data,
  improving identifier naming, and adding descriptive comments.
  Through a controlled experiment with 32 participants from
  both academia and industry, we investigate how the understand-
  ability of unit tests affects a software engineer’s ability to perform
  bug-fixing tasks. We selected bug-fixing to simulate a real-world
  scenario that emphasizes the importance of understandable test
  cases. We observe that participants working on assignments with
  UTGen test cases fix up to 33% more bugs and use up to 20%
  less time when compared to baseline test cases. From the post-test
  questionnaire, we gathered that participants found that enhanced
  test names, test data, and variable names improved their bug-
  fixing process.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - "Software Engineering"
  - "Natural Language Processing"
  - "Software Testing"
  - "Large Language Models"
  - "Unit Testing"
  - "Automated Test Generation"
  - "Amirhossein Deljouyi"
  - "Maliheh Izadi"
  - "Andy Zaidman"
  - "Readability"
  - "Understandability"

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2408.11710'
url_code: 'https://github.com/amirdeljouyi/UTGen'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'UTGen Architecture'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - Understandable-Test-Generation

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}