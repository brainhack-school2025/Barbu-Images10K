# Brainhack School Project: Image10K
My name is Sara, and I'm currently completing my undergraduate degree in Cognitive Neuroscience. I will begin a Master’s program in Psychology at the University of Montreal, where I’ll be conducting research in the Montembeault Laboratory.

As part of Brainhack School, I created an interactive web-based showcase for the **Images10k dataset** — a large collection of behaviorally validated, naturalistic object images spanning over 15 semantic categories. The goal of my project was to explore how we can make rich, complex datasets more accessible and meaningful to both researchers and the public.

Through the site, I present the dataset in an interactive and structured format:

- Visitors can browse the image collection using carousel galleries
- Explore scrollable previews of image-level metadata
- View interactive visualizations and analyses drawn from the dataset

This project allowed me to deepen my skills in data organization, visualization, and reproducible workflows, using tools like Jupyter Book, MyST Markdown, and Python. More broadly, it helped me engage with a growing challenge in cognitive neuroscience and AI — how to bridge ecological validity and computational modeling through large-scale, behaviorally grounded datasets.


## Project Background & Goal
Many studies in cognitive neuroscience still use really simplified or artificial images, like objects on plain backgrounds.That can limit ecological validity and create a disconnect between what you see in the lab and real world perception. In contrast to that, Images10K provides naturalistic scenes, showing objects in their natural environments, which makes it easier to study how people understand visual scenes in real-world contexts. This approach fits with recent work that emphasizes the importance of using more realistic images in research (Hosu, Lin, Szirányi, & Saupe, 2019).

This project is based on the **Images10K** dataset — containing over 8,000 naturalistic images, annotated by human participants on the [Zooniverse](https://www.zooniverse.org/) platform. The overall goal is to provide a well-organized and richly annotated image set (8,382 images, 15 semantic categories) that can be reused for training visual recognition models in AI and neuroscience.

## My Objective
My personal contribution to this project focuses on creating a clear, structured, and interactive way to explore the Images10K dataset. Specifically, I worked on:

- **Organizing the dataset:**  
  I used **Datalad** to retrieve and manage the dataset in a reproducible way. I then cleaned and structured the image-level metadata to ensure consistency and ease of access. This involved preparing files for web-based display, grouping images into their semantic categories, and excluding any redundant or problematic entries to keep the dataset clean and reusable.

- **Visualizing the images and their associated metadata:**  
  I developed interactive components that allow users to explore the dataset visually. This includes scrollable metadata tables, filtered views, and category-wise displays that make the data more intuitive and engaging to work with.

- **Building an interactive site to showcase the categories and image properties:**  
  Using tools like **Jupyter Book**, **MyST Markdown**, and **Python**, I created a static web-based showcase that integrates image carousels, scrollable data previews, and exploratory visualizations. The goal was to present the dataset in a way that is both accessible and informative for researchers, students, and collaborators from different disciplines.


## Tools I used
- **GitHub** for version control and to organize the project in a clear, collaborative, and shareable format.
- **DataLad** to retrieve and manage the dataset in a reproducible way.
- **Python scripts** to filter images by category, convert metadata formats, and prepare image paths for display.
- **Jupyter Notebooks** to explore the metadata, test visualizations, and generate previews of the dataset.
- **Dash Bootstrap Components** to build interactive UI elements like carousels and dropdown menus for browsing images.
- **MyST Markdown** to structure the content of the interactive website and document the project cleanly within Jupyter Book.
- **Ubuntu terminal** to navigate the file system, run scripts, and better understand how to work with files and folders at the command line.


##  The Data
The dataset includes:
- Over 8,000 naturalistic images, stored in semantically organized folders based on object categories
- Annotated labels for each image, including category, subcategory, and file path
- High-level semantic classifications (e.g., living vs. non-living, natural vs. artificial)
- Rich image-level metadata such as:
  - Number of participant annotations (via Zooniverse)
  - Inter-participant agreement scores
  - License information and usage permissions
  - Source URLs and author attributions


##  Concepts to implement
- **Intercative carrousel**: I plan to build a Dash-based image carousel that displays multiple images by category. Each image should show its metadata (e.g., category, label, agreement score)
- **Semantic filtering**: Users will be able to browse images interactively by semantic categories (e.g., “animal,” “object,” “living,” or “non-living”), using dropdowns or similar controls
- **Interactive visualization**: Tools like `matplotlib`, `seaborn`, or `plotly` to generate visual summaries
- **MyST article**: Eventually, the project will be documented and shared as an open-access website using MyST Markdown


##  Delivery
- A structured GitHub repository containing scripts and documentation
- A Jupyter notebook to visualize and explore image annotations
- A web interface to explore images by category or with filters
- Clear documentation using MyST Markdown
  
### Link to view presentation
[here](https://docs.google.com/presentation/d/1INdPO4mDrgXu64EogxEHda7Kbf1mZ-EG5l1t3ICp8UQ/edit?usp=sharing)  

## References
Hosu, V., Lin, H., Szirányi, T., & Saupe, D. (2019). KonIQ-10k: An ecologically valid database for deep learning of blind image quality assessment. arXiv preprint arXiv:1910.06180. https://arxiv.org/abs/1910.06180 
