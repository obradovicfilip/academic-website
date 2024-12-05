---
title: "Binary Classifiers as Dilations"
summary: "with [Gabriel Ziegler](https://www.gabriel-ziegler.com/)."

date: "2022-09-24T00:00:00Z"
lastmod: "2024-02-09T00:00:00Z"

Type: working_papers

# Optional external URL for project (replaces project detail page).
share: false
external_link: ""
weight: 4
image:
  focal_point: Center

url_code: ""
url_pdf: ""
url_appendix: ""
url_pdf: "https://filipobradovic.com/uploads/Obradovic_Ziegler.pdf"
# url_slides: "https://www.dropbox.com/s/39x3crbir04ri8h/slides.pdf?dl=0"
url_video: ""

# custom_style: jmp

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

Author: Filip Obradović, Gabriel Ziegler

---

Joint with [Gabriel Ziegler](https://www.gabriel-ziegler.com/).

**Abstract**: Seidenfeld and Wasserman (1993) define the phenomenon of *dilation*. When a dilation occurs, any additional information only *increases* the *uncertainty* about the true state of the world. In this paper, we show that dilation may manifest in real-world scenarios when information is provided by binary classifiers, such as diagnostic tests and predictive algorithms. This can happen when classifier performance measures are partially identified due to an imperfect reference classifier, which is common in practice. We characterize when a dilation occurs and develop corresponding inference procedures based on methods for subvector inference in moment inequality models. We apply the approach to diagnostic procedures for COVID-19 detection, using CT chest scans evaluated by radiologists and AI algorithms. We cannot reject the hypothesis that the radiologists' assessments exhibit a dilation, thus showcasing a potential real-world instance of a dilation. We additionally illustrate the broader applicability of our methodology by rejecting the hypothesis that data-mining techniques for predicting the riskiness of credit card applications are non-informative in the sense of dilation.
