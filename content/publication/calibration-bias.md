+++
title = "Improving the Egomotion Estimation by Correcting the Calibration Bias"
date = "2015-11-20"

authors = ["Ivan Krešo", "Siniša Šegvić"]

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
publication = "In *VISAPP 2015*."
publication_short = "In *VISAPP*"

# Abstract and optional shortened version.
abstract = "We present a novel approach for improving the accuracy of the egomotion recovered from rectified stereoscopic video. The main idea of the proposed approach is to correct the camera calibration by exploiting the known groundtruth motion. The correction is described by a discrete deformation field over a rectangular superpixel lattice covering the whole image. The deformation field is recovered by optimizing the reprojection error of point feature correspondences in neighboring stereo frames under the groundtruth motion. We evaluate the proposed approach by performing leave one out evaluation experiments on a collection of KITTI sequences with common calibration parameters, by comparing the accuracy of stereoscopic visual odometry with original and corrected calibration parameters. The results suggest a clear and significant advantage of the proposed approach. Our best algorithm outperforms all other approaches based on two-frame correspondences on the KITTI odometry benchmark."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/pdf/kreso15visapp.pdf"
url_code = "https://github.com/ivankreso/stereo-vision"

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
