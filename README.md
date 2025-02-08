# Animal-Table - Web Application

# Project Overview

This project is a web-based application that dynamically renders three interactive tables displaying information about Big Cats, Dogs, and Big Fish. Each table provides unique functionalities such as sorting, data entry, validation, deletion, and editing. The project is built using HTML, CSS, Bootstrap, and JavaScript/TypeScript following object-oriented programming principles.

Features

Common Features for All Tables

Data Rendering: Displays animal information with fields for Name, Location, Size, and Images.

Add Animals: Users can add new animals with default images and prevent duplicate entries.

Delete Animals: Removes animals from the table.

Edit Animals: Allows editing the details of existing animals.

Image Interaction: Borders are displayed around images. Hovering on images shows the animal name and enlarges the image without using modals or additional components.

# Table-Specific Features

Table 1 (Big Cats)

Sorting: Sortable columns for all fields except images.

Table 2 (Dogs)

Styling: Names are displayed in bold text.

Sorting: Sortable columns for Name and Location.

Table 3 (Big Fish)

Styling: Names are displayed in bold, italic, and blue color.

Sorting: Sortable column for Size only.

# Folder Structure

project-root/
├── index.html
├── styles.css
└── README.md

JSON Data Structure

Each JSON file contains an array of objects representing animal information. Below is a sample structure:

[
  {
    "name": "Lion",
    "location": "Africa",
    "size": "Large",
    "image": "lion.jpg"
  }
]

Fields:

name (string) - The animal's name

location (string) - The animal's common location

size (string) - The size category of the animal

image (string) - Path to the image file

Installation and Setup

Clone the repository:

git clone <repository-url>

Open the project directory:

cd project-root

Install required dependencies (if any for TypeScript compilation).

Compile TypeScript (if applicable):

tsc script.ts

Open index.html in any web browser to run the application.

# Usage Instructions

View Tables: The homepage displays the tables for Big Cats, Dogs, and Big Fish.

Add Animals: Click the "Add" button on any table to input animal details.

Duplicate entries are prevented.

Validations ensure accurate numeric and text inputs.

Edit Animals: Click the "Edit" button to update an animal's information.

Delete Animals: Click the "Delete" button to remove an animal entry.

Hover Interaction: Hover over an animal image to see the name and view an enlarged version.

Development Approach

Object-Oriented Design

Animal Class: Base class representing common properties and methods for animals.

Table Class: Manages the rendering and functionality for each table.

Validation Class: Ensures data integrity.

Event Handlers: Dedicated methods for handling user interactions.

# Technologies Used

HTML/CSS: For structure and styling.

JavaScript: For Functionality

# Future Improvements

Implement search functionality for each table.

Enhance the image enlargement interaction with animations.

Store and retrieve data using a backend service.

Include pagination for large datasets.

# License

Copyright 2024-25 - Developed By Bharath Kumar



Deploy Link : https://animal-table-one.vercel.app/
