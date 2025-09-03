---
title: 'UmetaFlow: an untargeted metabolomics workflow for high-throughput data processing
  and analysis'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Eftychia E Kontou
- Axel Walter
- Oliver Alka
- Julianus Pfeuffer
- Timo Sachsenberg
- Omkar S Mohite
- Matin Nuhamunada
- Oliver Kohlbacher
- Tilmann Weber

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-05-12'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-03T04:32:37.765442Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: 10.1186/s13321-023-00724-w

abstract: Metabolomics experiments generate highly complex datasets, which are time
  and work-intensive, sometimes even error-prone if inspected manually. Therefore,
  new methods for automated, fast, reproducible, and accurate data processing and
  dereplication are required. Here, we present UmetaFlow, a computational workflow
  for untargeted metabolomics that combines algorithms for data pre-processing, spectral
  matching, molecular formula and structural predictions, and an integration to the
  GNPS workflows Feature-Based Molecular Networking and Ion Identity Molecular Networking
  for downstream analysis. UmetaFlow is implemented as a Snakemake workflow, making
  it easy to use, scalable, and reproducible. For more interactive computing, visualization,
  as well as development, the workflow is also implemented in Jupyter notebooks using
  the Python programming language and a set of Python bindings to the OpenMS algorithms
  (pyOpenMS). Finally, UmetaFlow is also offered as a web-based Graphical User Interface
  for parameter optimization and processing of smaller-sized datasets. UmetaFlow was
  validated with in-house LC-MS/MS datasets of actinomycetes producing known secondary
  metabolites, as well as commercial standards, and it detected all expected features
  and accurately annotated 76% of the molecular formulas and 65% of the structures.
  As a more generic validation, the publicly available MTBLS733 and MTBLS736 datasets
  were used for benchmarking, and UmetaFlow detected more than 90% of all ground truth
  features and performed exceptionally well in quantification and discriminating marker
  selection. We anticipate that UmetaFlow will provide a useful platform for the interpretation
  of large metabolomics datasets.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Analysis
- High-throughput workflow
- Processing
- Software
- Untargeted metabolomics

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: http://dx.doi.org/10.1186/s13321-023-00724-w
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
