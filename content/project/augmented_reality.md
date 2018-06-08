+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Augmented Reality for Surgery"

# Project summary to display on homepage.
summary = "Bringing augmented reality environments to surgery."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "AR_1.PNG"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["augmented-reality","orthopedics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "AR.PNG"
caption = "Augmented reality environment from a bystander's and the user's perspective."

+++

**Virtual monitors**: During traditional image-guided interventions, images are displayed on designated monitors that cannot be positioned optimally due to sterility and spatial constraints. With the aid of optical see-through head-mounted display, we present a novel *virtual* monitor system that displays medical images in real-time in a mixed reality visualization, which can potentially alleviates the occlusion problem, improves hand-eye coordination, and reduces neck fatigue. The *virtual* monitor system consists of a medical imaging modality, a frame grabber, an image processing framework, a data transfer network, and a head-mounted display. We identify the clinical requirements of such system for the targeted clinical usecase and consider medical image properties, visualization mode, perceptual quality, and surgery duration to materialize *virtual* monitor systems appropriate for the respective clinical task.

**Unprepared environments**: We present an on-the-fly surgical support system that provides guidance using Augmented Reality and can be used in quasi-unprepared operating rooms. The proposed system builds upon a multi-modality marker and simultaneous localization and mapping technique to co-calibrate an optical see-through head mounted display to a C-arm fluoroscopy system. Then, annotations on the 2-D X-ray images can be rendered as virtual objects in 3-D providing surgical guidance.

**Dynamic calibration**: In percutaneous orthopedic interventions the surgeon attempts to reduce and fixate fractures in bony structures. The complexity of these interventions arises when the surgeon performs the challenging task of navigating surgical tools percutaneously only under the guidance of 2D interventional X-ray imaging. Moreover, the intra-operatively acquired data is only visualized indirectly on external displays. In this work, we propose a flexible Augmented Reality paradigm using optical see-through head mounted displays. The key technical contribution of this work includes the marker-less and dynamic tracking concept which closes the calibration loop between patient, C-arm and the surgeon. This calibration is enabled using Simultaneous Localization and Mapping of the environment, i.e. the operating theater. In return, the proposed solution provides 
*in situ* visualization of pre- and intra-operative 3D medical data directly at the surgical site.