+++
title = "Robust Semantic Segmentation with Ladder-DenseNet Models"
date = "2018-06-09"

authors = ["Ivan Krešo", "Marin Oršić", "Petra Bevandić", "Siniša Šegvić"]

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
publication = "In *Conference on Computer Vision and Pattern Recognition (CVPR2018)*, IEEE."
publication_short = "In *CVPR ROB*"

# Abstract and optional shortened version.
abstract = "We present semantic segmentation experiments with a model capable to perform predictions on four benchmark datasets: Cityscapes, ScanNet, WildDash and KITTI. We employ a ladder-style convolutional architecture featuring a modified DenseNet-169 model in the downsampling datapath, and only one convolution in each stage of the upsampling datapath. Due to limited computing resources, we perform the training only on Cityscapes Fine train+val, ScanNet train, WildDash val and KITTI train. We evaluate the trained model on the test subsets of the four benchmarks in concordance with the guidelines of the Robust Vision Challenge ROB 2018. The performed experiments reveal several interesting findings which we describe and discuss."

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
url_pdf = "https://arxiv.org/abs/1806.03465"
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
