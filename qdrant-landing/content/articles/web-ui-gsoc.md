---
title:  Google Summer of Code 2023 - Web UI for Visualization and Exploration
short_description: Gsoc'23 Web UI for Visualization and Exploration
description: My journey as a Google Summer of Code 2023 student working on the "Web UI for Visualization and Exploration" project for Qdrant.
preview_dir: /articles_data/web-ui-gsoc/preview
small_preview_image: /articles_data/web-ui-gsoc/icon.svg
social_preview_image: /articles_data/web-ui-gsoc/preview/social_preview.jpg
weight: -1
author: Kartik Gupta
author_link: https://kartik-gupta-ij.vercel.app/
date: 2023-08-22T08:00:00+03:00
draft: false
keywords: 

    - vector reduction
    - console 
    - gsoc'23 
    - vector similarity
    - exploration
    - recommendation
---



## Introduction

Hello everyone! My name is Kartik Gupta, and I am thrilled to share my coding journey as part of the Google Summer of Code 2023 program. This summer, I had the incredible opportunity to work on an exciting project titled "Web UI for Visualization and Exploration" for Qdrant, a vector search engine. In this blog, I will take you through my experience, challenges, and achievements during this enriching coding journey.

## Project Overview

Qdrant is a powerful vector search engine widely used for similarity search and clustering. However, it lacked a user-friendly web-based UI for data visualization and exploration. My project aimed to bridge this gap by developing a web-based user interface that allows users to easily interact with and explore their vector data.

## Milestones and Achievements

The project was divided into six milestones, each focusing on a specific aspect of the web UI development. Let's go through each of them and my achievements during the coding period.

1. Making a User-Friendly UI on Figma I started by designing the user interface on Figma, ensuring it was easy to use, visually appealing, and responsive on different devices. I focused on usability and accessibility to create a seamless user experience.
    
2. Developing a Layout In this milestone, I built the layout The layout route served as a landing page with an overview of the application's features and navigation links to other routes.
    
3. Developing a View Collection Route I created a collection view route, enabling users to view a list of collections available in the application. Users could click on a collection to see more details, including the data and vectors associated with it.
    
4. Developing a Data Page with Find Similar Functionality using Recommendation API I implemented a data page where users could search for data and find similar data using a recommendation API. The recommendation API suggested similar data based on the Data's selected ID, providing valuable insights.
    
5. Developing the Query Editor Page Libraries This milestone involved creating a query editor page that allowed users to write queries in a custom language. The editor provided syntax highlighting, autocomplete, and error-checking features for a seamless query writing experience.
    
6. Developing a Route for Visualizing Vector Data point This is done by the reduction of n-dimensional vector in 2-D points and they are displayed with their respective payloads.
    

## Challenges and Learning

Throughout the project, I encountered a series of challenges that stretched my engineering capabilities and provided unique growth opportunities. From mastering new libraries and technologies to ensuring the user interface (UI) was both visually appealing and user-friendly, every obstacle became a stepping stone toward enhancing my skills as a developer. However, each challenge provided an opportunity to learn and grow as a developer. I acquired valuable experience in vector search and dimension reduction techniques.

The most significant learning for me was the importance of effective project management. Setting realistic timelines, collaborating with mentors, and staying proactive with feedback allowed me to complete the milestones efficiently.

### Technical Learning and Skill Development

One of the most significant aspects of this journey was diving into the intricate world of vector search and dimension reduction techniques. These areas, previously unfamiliar to me, required rigorous study and exploration. Learning how to process vast amounts of data efficiently and extract meaningful insights through these techniques was both challenging and rewarding.

### Effective Project Management

Undoubtedly, the most impactful lesson was the art of effective project management. I quickly grasped the importance of setting realistic timelines and goals. Collaborating closely with mentors and maintaining proactive communication proved indispensable. This approach enabled me to navigate the complex development process and successfully achieve the project's milestones.

### Overcoming Technical Challenges

#### Autocomplete Feature in Console

One particularly intriguing challenge emerged while working on the autocomplete feature within the console. Finding a solution was proving elusive until a breakthrough came from an unexpected direction. My mentor, Andrey, proposed creating a separate module that could support autocomplete based on OpenAPI for our custom language. This ingenious approach not only resolved the issue but also showcased the power of collaborative problem-solving.

#### Optimization with Web Workers

The high-processing demands of vector reduction posed another significant challenge. Initially, this task was straining browsers and causing performance issues. The solution materialized in the form of web workers—an independent processing instance that alleviated the strain on browsers. However, a new question arose: how to terminate these workers effectively? With invaluable insights from my mentor, I gained a deeper understanding of web worker dynamics and successfully tackled this challenge.

#### Console Integration Complexity

Integrating the console interaction into the application presented multifaceted challenges. Crafting a custom language in Monaco, parsing text to make API requests, and synchronizing the entire process demanded meticulous attention to detail. Overcoming these hurdles was a testament to the complexity of real-world engineering endeavours.

#### Codelens Multiplicity Issue

An unexpected issue cropped up during the development process: the codelen (run button) registered multiple times, leading to undesired behaviour. This hiccup underscored the importance of thorough testing and debugging, even in seemingly straightforward features.

### Key Learning Points

Amidst these challenges, I garnered valuable insights that have significantly enriched my engineering prowess:

**Vector Reduction Techniques** : Navigating the realm of vector reduction techniques provided a deep understanding of how to process and interpret data efficiently. This knowledge opens up new avenues for developing data-driven applications in the future.

**Web Workers Efficiency** : Mastering the intricacies of web workers not only resolved performance concerns but also expanded my repertoire of optimization strategies. This newfound proficiency will undoubtedly find relevance in various future projects.

**Monaco Editor and UI Frameworks** : Working extensively with the Monaco Editor, Material-UI (MUI), and Vite enriched my familiarity with these essential tools. I honed my skills in integrating complex UI components seamlessly into applications.

## Areas for Improvement and Future Enhancements

While reflecting on this transformative journey, I recognize several areas that offer room for improvement and future enhancements:

1. Enhanced Autocomplete: Further refining the autocomplete feature to support key-value suggestions in JSON structures could greatly enhance the user experience.
    
2. Error Detection in Console: Integrating the console's error checker with OpenAPI could enhance its accuracy in identifying errors and offering precise suggestions for improvement.
    
3. Expanded Vector Visualization: Exploring additional visualization methods and optimizing their performance could elevate the utility of the vector visualization route.
    

## Conclusion

Participating in the Google Summer of Code 2023 and working on the "Web UI for Visualization and Exploration" project has been an immensely rewarding experience. I am grateful for the opportunity to contribute to Qdrant and develop a user-friendly interface for vector data exploration.

I want to express my gratitude to my mentors and the entire Qdrant community for their support and guidance throughout this journey. This experience has not only improved my coding skills but also instilled a deeper passion for web development and data analysis.

As my coding journey continues beyond this project, I look forward to applying the knowledge and experience gained here to future endeavours. I am excited to see how Qdrant evolves with the newly developed web UI and how it positively impacts users worldwide.

Thank you for joining me on this coding adventure, and I hope to share more exciting projects in the future! Happy coding!