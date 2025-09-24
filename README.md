# Tallinn Conference Trip Itinerary

This repository contains a detailed itinerary for a conference trip to Tallinn, Estonia in October.

## Overview

The itinerary is designed to provide a well-rounded experience, balancing conference attendance with opportunities to explore the city of Tallinn. It includes:

*   A detailed daily schedule.
*   Information about the conference, including the schedule and a list of attendees.
*   Research on Tallinn, including notable attractions and restaurant recommendations.

## Folder Structure

*   `itinerary/`: Contains the daily schedule in Markdown files.
*   `conference_info/`: Contains information about the conference.
*   `research/`: Contains research about Tallinn.

## How to Use

Simply browse the files in this repository to access the itinerary and related information. The daily itineraries in the `itinerary/` directory are the main files to consult for the schedule.

## Converting to Word

These files are in Markdown format (`.md`). If you need to share them with colleagues who prefer Word documents, you can use a tool called **Pandoc** to convert them. Pandoc is a free and open-source document converter.

Once you have installed Pandoc, you can convert a file using a command like this in your terminal:

```bash
pandoc -o output.docx input.md
```

Replace `input.md` with the name of the Markdown file you want to convert, and `output.docx` with the desired name for your Word document.

## How to Upload to GitHub

To upload this project to GitHub, follow these steps:

1.  **Initialise a Git repository:**
    ```bash
    git init
    ```
2.  **Add all files to the repository:**
    ```bash
    git add .
    ```
3.  **Commit the files:**
    ```bash
    git commit -m "Initial commit"
    ```
4.  **Create a new repository on GitHub.**
5.  **Add the GitHub repository as a remote:**
    ```bash
    git remote add origin <your-github-repository-url>
    ```
6.  **Push the files to GitHub:**
    ```bash
    git push -u origin main
    ```
