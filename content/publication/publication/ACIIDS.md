+++
title = "Alpha-N: Shortest Path Finder Automated Delivery Robot with Obstacle Detection and Avoiding System"

# Date first published.
date = "2020-03-23"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Asif Ahmed Neloy", "Rafia Alif Bindu", "Sazid Alam", "Ridwanul Haque", "Md Saif Ahammod Khan", "Nasim Mahmud Mishu", "Shahnewaz Siddique"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["6"]

# Publication name and optional abbreviated version.
publication = "*12th Asian Conference on Intelligent Information and Database Systems*"
publication_short = "*ACIIDS'2020*"

# Abstract and optional shortened version.
abstract = """<div align="justify"> 

Alpha-N - A self-powered, wheel-driven Automated Delivery Robot (ADR) is presented in this paper. The ADR is capable of navigating autonomously by detecting and avoiding objects or obstacles in its path. It uses a vector map of the path and calculates the shortest path by Grid Count Method (GCM) of Dijkstra’s Algorithm. Landmark determination with Radio Frequency Identification (RFID) tags are placed in the path for identification and verification of source and destination, and also for the re-calibration of the current position. On the other hand, an Object Detection Module (ODM) is built by Faster R-CNN with VGGNet-16 architecture for supporting path planning by detecting and recognizing obstacles. The Path Planning System (PPS) is combined with the output of the GCM, the RFID Reading System (RRS) and also by the binary results of ODM. This PPS requires a minimum speed of 200 RPM and 75 s duration for the robot to successfully relocate its position by reading an RFID tag. In the result analysis phase, the ODM exhibits an accuracy of 83.75%, RRS shows 92.3% accuracy and the PPS maintains an accuracy of 85.3%. Stacking all these 3 modules, the ADR is built, tested and validated which shows significant improvement in terms of performance and usability comparing with other service robots. </div>

"""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://www.researchgate.net/publication/339669338_Alpha-N_Shortest_Path_Finder_Automated_Delivery_Robot_with_Obstacle_Detection_and_Avoiding_System"
url_preprint = "https://arxiv.org/abs/2002.11913"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://link.springer.com/chapter/10.1007/978-3-030-41964-6_18"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "icrae.png"
#caption = "Sigma-3 Body Design"

+++