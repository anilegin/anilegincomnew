---
title: "Now You See Me, Now You Don't: A Unified Framework for Expression Consistent Anonymization in Talking Head Videos"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Andrea Tangherloni
  - Antitza Dantcheva

# Author notes (optional)
author_notes:
  - "INRIA, Université Côte d'Azur, France"
  - "Bocconi University, Italy"
  - "INRIA, Université Côte d'Azur, France"

date: '2025-10-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops*
publication_short: In *ICCV 2025 · CV4BIOM*

abstract: Face video anonymization is aimed at privacy preservation while allowing for the analysis of videos in a number of computer vision downstream tasks such as expression recognition, people tracking, and action recognition. We propose a novel unified framework referred to as AnonNET, streamlined to de-identify facial videos while preserving age, gender, race, pose, and expression of the original video. Specifically, we inpaint faces by a diffusion-based generative model guided by high-level attribute recognition and motion-aware expression transfer. We then animate de-identified faces by video-driven animation, which accepts the de-identified face and the original video as input. Extensive experiments on VoxCeleb2, CelebV-HQ, and HDTF demonstrate the effectiveness of AnonNET in obfuscating identity while retaining visual realism and temporal consistency.

# Summary. An optional shortened abstract.
summary: AnonNET de-identifies talking-head videos with a diffusion-based pipeline that preserves expression and key attributes while strongly reducing re-identification risk.

featured: true

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2025W/CV4BIOM/html/Egin_Now_You_See_Me_Now_You_Dont_A_Unified_Framework_ICCVW_2025_paper.html'
url_code: 'https://github.com/anilegin/AnonNET'
url_dataset: ''
url_poster: ''
url_project: 'https://anilegin.github.io/AnonNET-project/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'AnonNET'
  focal_point: ''
  preview_only: false
---

Oral presentation at the **IEEE/CVF ICCV 2025** workshop on Computer Vision for Biometrics, Identity & Behaviour (**CV4BIOM**), Hawaii, USA.
