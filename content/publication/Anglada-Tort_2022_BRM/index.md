---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "REPP: A robust cross-platform solution for online sensorimotor synchronization experiments"
authors: [Manuel Anglada-Tort, Peter M.C. Harrison, Nori Jacoby]
date: "2022-02-11T00:00:00Z"
doi: "https://doi.org/10.3758/s13428-021-01722-2"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-11T14:18:51+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "_Behavior Research Methods_"
publication_short: ""

abstract: >
  Sensorimotor synchronization (SMS), the rhythmic coordination of perception and action, is a fundamental human skill that supports many behaviors, including music and dance (Repp, 2005; Repp & Su, 2013). Traditionally, SMS experiments have been performed in the laboratory using finger tapping paradigms, and have required equipment with high temporal fidelity to capture the asynchronies between the time of the tap and the corresponding cue event. Thus, SMS is particularly challenging to study with online research, where variability in participants’ hardware and software can introduce uncontrolled latency and jitter into recordings. Here we present REPP (Rhythm ExPeriment Platform), a novel technology for measuring SMS in online experiments that can work efficiently using the built-in microphone and speakers of standard laptop computers. In a series of calibration and behavioral experiments, we demonstrate that REPP achieves high temporal accuracy (latency and jitter within 2 ms on average), high test-retest reliability both in the laboratory (r = .87) and online (r = .80), and high concurrent validity (r = .94). We also show that REPP is fully automated and customizable, enabling researchers to monitor experiments in real time and to implement a wide variety of SMS paradigms. We discuss online methods for ensuring high recruiting efficiency and data quality, including pre-screening tests and automatic procedures for quality monitoring. REPP can therefore open new avenues for research on SMS that would be nearly impossible in the laboratory, reducing experimental costs while massively increasing the reach, scalability, and speed of data collection.

# Summary. An optional shortened abstract.
summary: "We present and validate REPP, a novel technology to perform online sensorimotor synchronization experiemnts."

tags:
categories: 
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://link.springer.com/content/pdf/10.3758/s13428-021-01722-2.pdf.
url_code: https://gitlab.com/computational-audition/repp
url_dataset: https://osf.io/r2pxd/
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: REPP: A robust cross-platform solution for online SMS experiments. (a) REPP uses a free-field recording approach that works efficiently using common laptops. (b) REPP comprises five main steps. (c) REPP uses a unique frequency range for each audio element in the recording. (d) Output of the performance analysis after the signal processing steps.
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [music cognition, massive online experiments]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
Code, documentaiton, and data available [here](https://gitlab.com/computational-audition/repp).

