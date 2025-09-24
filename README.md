# Tallinn Conference Trip Itinerary

This repository contains a detailed itinerary for the **ENBEL 2025 Conference: Connecting Health and Climate Change** in Tallinn, Estonia, October 16-18, 2025.

## Overview

The itinerary is designed to provide a well-rounded experience for attending the ENBEL 2025 transdisciplinary conference on climate change and health research. It includes:

*   A detailed 3-day conference schedule with verified information
*   Professional transportation and venue navigation visualizations
*   Research on Tallinn attractions, restaurants, and practical travel information
*   Interactive conference maps and schedule guides
*   Current developments in Estonia (2024-2025) for context

## Folder Structure

*   `itinerary/`: Contains the daily schedule in Markdown files
*   `conference_info/`: Contains verified ENBEL 2025 conference information, schedule, and attendees
*   `research/`: Contains comprehensive research about Tallinn including attractions, restaurants, transportation
*   **Transportation Visualizations:**
    *   `tallinn_transportation_overview.svg` - Complete transportation map and guide
    *   `conference_transportation_guide.svg` - Step-by-step airport-to-venue routing
    *   `daily_transportation_planner.svg` - Schedule-integrated transport planning
*   **Conference Navigation Visualizations:**
    *   `enbel_2025_venue_floor_plan.svg` - Professional venue layout and navigation
    *   `enbel_2025_schedule_grid.svg` - Interactive 3-day schedule visualization  
    *   `enbel_2025_navigation_guide.svg` - Complete conference navigation reference
*   `estonia_current_developments_2024-2025.md` - Current Estonian context and news

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
