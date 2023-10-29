# Image Segmentation SAM

This project showcases the implementation of the Segment Anything Model for text-based image segmentation, specifically for menu card categorization.

## Project Overview

This trial project aims to utilize the Segment Anything Model for the purpose of text-based image segmentation. The model has been trained to categorize menu card images into the following categories:

1. Starters/Appetizers
2. Main Courses
3. Sides
4. Desserts
5. Beverages/Drink

## Update - October 28th, 2023

In this update, we have achieved the following milestones:

- **Image Labeling:** Five menu card images have been meticulously labeled for the aforementioned categories.
- **Data Export:** The annotated images have been exported to JSON format, providing easy access to the labeled bounding box data. The exported data can be found in the file "image_boundingbox_data.json".
- **COCO Format Export:** Additionally, we have exported the annotated images to the COCO format, ensuring compatibility with various machine learning pipelines. The COCO dataset can be accessed in the file "cloalih5z052b070574fn3uny_coco_dataset.json".

## Project Files

- **image_boundingbox_data.json:** Contains the annotated bounding box data in JSON format.
- **cloalih5z052b070574fn3uny_coco_dataset.json:** Includes the COCO formatted dataset for machine learning applications.

## Requirements

To utilize the data and scripts, ensure that you have the following dependencies installed:

- Python 3.7+
- Segment Anything Model
- COCO API (if necessary)
- Any other specific dependencies mentioned in the codebase or documentation