---
title: Insect Monitoring Based on Wingbeat Signals Using Deep Learning

event: enbis Conference 2019
event_url: https://enbis.org/media-centre/insect-monitoring-based-on-wingbeat-signals-using-deep-learning/

location: Budapest
address:
  street: Egyetem tér 1-3
  city: Budapest
  region: Budapest
  postcode: '1053'
  country: Hungary

summary: A presentation I gave at enbis-19 conference.
abstract: "Optical sensors with embedded deep learning algorithms can be used to create automatic pest monitoring systems in field that can be a protective and precautionary measure against damaging insects or excessive pesticide use (Potamitis, 2015). We modelled the wingbeat signal of various insect types which was captured using an optoelectronic sensor (van Roy et al, 2014). The sensor consists of two plates, light emitting and light capturing, placed in parallel and is able to record the modulated light produced by insects flapping their wings whilst passing through it. These signals can either be saved locally on an SD card or transferred to a selected server using a low-power microcontroller device. The device also saves the temperature, humidity and timestamp of each signal.

We developed deep learning classification algorithms trained on the optical wingbeat signatures. The input of our models could either be the raw time-series signals captured from the sensor, or spectrogram images constructed from the signals. The data was split in 3 sets, a training set used to tune the model parameters and learn its input, a validation set used to measure its performance during training and a test set to evaluate the true performance of the model.

We employed 1D and 2D convolutional neural networks (CNNs) to model our time-series and spectrogram data, respectively (Wu et al, 2018; Huang et al, 2017). The reported test accuracy scores for the respective data types are 91% and 96% when training CNNs on the “Wingbeats” mosquito database, which consists of 279,566 flight recording signals. Performing the same algorithmic techniques on a custom dataset of Drosophila Melanogaster and Drosophila Zaprionus, that consists of 12,746 flight recording signals in total, we achieved test accuracy scores of 99% for both data types used.
These results indicate that insect biometrics such as the light intensity fluctuations recorded by optical sensors can be efficiently modelled by deep learning algorithms provided with sufficiently rich training data.

Huang, G., Liu, Z., Van Der Maaten, L., & Weinberger, K. Q. (2017). Densely connected convolutional networks. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 4700-4708).

Potamitis, I., Rigakis, I., & Fysarakis, K. (2015). Insect biometrics: optoacoustic signal processing and its applications to remote monitoring of McPhail type traps. PloS one, 10(11), e0140474.

van Roy, J., De Baerdemaeker, J., Saeys, W., & De Ketelaere, B. (2014). Optical identification of bumblebee species: Effect of morphology on wingbeat frequency. Computers and electronics in agriculture, 109, 94-100.

Wu, Y., Yang, F., Liu, Y., Zha, X., & Yuan, S. (2018). A Comparison of 1-D and 2-D Deep Convolutional Neural Networks in ECG Classification. arXiv preprint arXiv:1810.07088."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-09-05T13:00:00Z"
#date_end: "2030-06-01T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/kalfasyan
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
