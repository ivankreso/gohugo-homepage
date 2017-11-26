+++
title = "Ladder-style DenseNets for Semantic Segmentation of Large Natural Images"
date = "2017-11-22"

authors = ["Ivan Krešo", "Josip Krapac", "Siniša Šegvić"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *International Conference on Computer Vision (ICCV2017)*, IEEE."
publication_short = "In *ICCV*"

# Abstract and optional shortened version.
abstract = "Recent progress of deep image classification models provides a large potential to improve state-of-the-art performance in related computer vision tasks. However, the transition to semantic segmentation is hampered by strict memory limitations of contemporary GPUs. The extent of feature map caching required by convolutional backprop poses significant challenges even for moderately sized PASCAL images, while requiring careful architectural considerations when the source resolution is in the megapixel range. To address these concerns, we propose a DenseNet-based ladder-style architecture which is able to deliver high modelling power with very lean representations at the original resolution. The resulting fully convolutional models have few parameters, allow training at megapixel resolution on commodity hardware and display fair semantic segmentation performance even without ImageNet pre-training. We present experiments on Cityscapes and Pascal VOC 2012 datasets and report competitive results."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
#url_pdf = "http://ivankreso.github.io/static/pdf/kreso17iccv.pdf"
url_pdf = "files/pdf/kreso17iccv.pdf"
#url_preprint = "http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf"
url_code = "https://github.com/ivankreso/ladder-densenet"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++
