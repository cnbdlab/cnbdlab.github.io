---
title: "Software"
description: "We develop open-source software tools to analyze neuroimaging and behavioral measurements to help scientists conduct research with greater efficiency, reproducibility, and transparency."
layout: "feature"
badge: "Development"
badgeColor: "#16a34a"
#features:
#  - title: "Component System"
#    description: "Modular component architecture makes it easy to build and maintain your website. Reuse components across pages while maintaining consistency."
#  - title: "Easy Customization"
#    description: "Clear configuration files and well-organized code make it simple to customize any aspect of your site. No deep Hugo knowledge required."
#  - title: "Clean Code"
#    description: "Well-structured, documented code following best practices. Makes maintenance and updates straightforward for any developer."
#  - title: "Detailed Documentation"
#    description: "Comprehensive documentation covers everything from setup to advanced customization. Includes examples and best practices."
#demo:
#  description: "See how our developer-friendly architecture makes building websites a breeze."
#  image: "/images/feature-3.svg"
---


## Functional MRI Data Analysis

Software tools developed for processing, analyzing or visualizing raw and derived fMRI data

### BrainCAP (under development)
<div style="display: flex; align-items: flex-start; gap: 30px; margin-bottom: 2em;">
  <!-- Left: large image -->
  <div style="flex: 0 0 40%; max-width: 500px;">
    <img src="/images/main-3.png" 
         alt="Functional Neuroimaging Illustration" 
         style="width: 100%; height: auto; border-radius: 8px;"/>
  </div>
  <!-- Right: publication list -->
  <div style="flex: 1;">
The analysis of moment-to-moment changes in co-activation patterns (CAPs) in functional MRI (fMRI) has been useful for studying dynamic properties of neural activity. This method is based on clustering fMRI time-frames into several recurrent spatial patterns within and across subjects. Studies have also focused on quantifying properties of the temporal organization of CAPs, such as fractional occupancy and dwell time. The analyses of co-activations are computationally intensive, requiring the clustering of high-dimensional data concatenated over subjects. Further, while a variety of analytic choices are involved in studying CAPs, the field lacks a unified open-source platform to allow a robust feature selection required for reproducible mappings of brain and behavioral measurements. We are currently developing BrainCAP, an open-source Python-based toolkit for quantifying CAPs from fMRI data in cross-sectional and longitudinal studies.<br><br>
<a href="https://github.com/Kangjoo/BrainCAP/tree/develop">Our GitHub Repository</a>
  </div>
</div>







{{< faq >}}
{
    "title": "Common Questions",
    "description": "Find answers to frequently asked questions about our software tools.",
    "questions": [
        {
            "question": "Are these tools free to download and use?",
            "answer": "Yes, these tools are developed as an open-source codes and free to use for research and non-commercial purposes."
        },
        {
            "question": "What should I do when I find bugs or have suggestions?",
            "answer": "Thank you very much for spotting an issue! Please contact the main developer(s) of our tools or directly send an e-mail to Dr. Lee."
        }
    ]
}
{{< /faq >}}
