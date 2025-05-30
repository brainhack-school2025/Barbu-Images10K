# Brainhack School Project: Images10K
My name is Sara and I'm currently finishing my undergraduate degree in Cognitive Neuroscience and will soon begin a Master’s program in Psychology at the University of Montreal, where I will be conducting research in the Montembeault Laboratory. As part of this Brainhack project, I am working with the Images10K dataset, a large collection of annotated naturalistic images. My goal is to deepen my understanding of data organization, management, and visualization, particularly through the use of interactive tools that make complex datasets more accessible. Through this project, I’m hoping to build a strong foundation in data handling and reproducible workflows that I can apply in my upcoming research projects.


## Project Background & Goal
Many studies in cognitive neuroscience still use really simplified or artificial images, like objects on plain backgrounds.That can limit ecological validity and create a disconnect between what you see in the lab and real world perception. In contrast to that, Images10K provides naturalistic scenes, showing objects in their natural environments, which makes it easier to study how people understand visual scenes in real-world contexts. This approach fits with recent work that emphasizes the importance of using more realistic images in research (Hosu, Lin, Szirányi, & Saupe, 2019).

This project is based on the **Images10K** dataset — containing over 8,000 naturalistic images, annotated by human participants on the [Zooniverse](https://www.zooniverse.org/) platform. The overall goal is to provide a well-organized and richly annotated image set (8,382 images, 15 semantic categories) that can be reused for training visual recognition models in AI and neuroscience.

## My Objective
My personal contribution focuses on:
- Organizing the dataset
- Visualizing the images and their associated metadata
- Building an interactive site to showcase the categories and image properties


## Tools to learn
- **GitHub** for version control and collaborative development of the project
- **DataLad** to manage the dataset and ensure reproducible data access
- **Python scripts** to access and filter the images
- **Jupyter Notebooks** for data exploration and basic image visualization
- **Dash Bootstrap Components** to build interactive feathers, such as carrousel, dropdowns, etc
- **MyST Markdown** to structure an interactive website and write clear, reusable documentation
- Gain deeper experience using Python on the terminal to manipulate files, run scripts, and debug visualizations
  

##  The Data
The dataset includes:
- Thousands of images stored in semantically organized folders
- Associated labels (e.g., category, subcategory, path)
- Semantic classification (living/non-living, natural/artificial)
- Rich metadata such as number of participant responses, agreement levels, license types, etc


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
