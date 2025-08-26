# UBS Internal Communications Predictor

## Overview

The Internal Communications Predictor is a web-based application designed to forecast the viewership of internal communications articles using machine learning. It provides  communications professionals with a user-friendly interface to input article metadata and receive data-driven predictions on expected audience engagement.

## Purpose

- **Empower Internal Communications:** Help teams optimize their messaging by predicting which articles will reach the largest audience.
- **Data-Driven Decisions:** Leverage machine learning to inform content strategy, timing, and targeting.
- **User Accessibility:** Provide an intuitive, modern UI for both technical and non-technical users.

## Key Components

### 1. User Interface (UI)
- **Header & Branding:** UBS-branded header with clear application title and description.
- **Step-by-Step Workflow:** Four-step process guiding users from article configuration to results.
- **Toggle Switches:** For classifying article types (e.g., Org Announcement, Top Story) with clear visual feedback.
- **Dropdowns & Multi-Selects:** For selecting authors, months, weekdays, and multiple topic tags.
- **Progress Bar:** Visual indicator of workflow progress.

### 2. Core Functionalities
- **Article Metadata Input:** Users enter details such as author, month, weekday, and select relevant tags.
- **Article Classification:** Toggle switches allow users to specify article types, with immediate visual feedback.
- **Prediction Engine:** On submission, the app uses a machine learning model (or simulation) to predict viewership.
- **Results Display:** Predicted metrics are shown in a results grid and as a viewership timeline chart.
- **Export Options:** Users can export results to Excel for further analysis.

### 3. Output Examples

#### Example 1: Results Grid
| Metric                | Value   |
|-----------------------|---------|
| Predicted Views       | 1,250   |
| Engagement Rate (%)   | 42.5    |
| Top Audience Segment  | EMEA    |
| Predicted Shares      | 37      |

#### Example 2: Viewership Timeline Chart
A line chart showing predicted daily views over a selected period (e.g., 30 days after publication).

#### Example 3: Excel Export
A downloadable `.xlsx` file containing all prediction results and input parameters for offline analysis.

## What the Application Can Do
- Predict viewership for internal articles based on metadata and classification.
- Visualize results in both tabular and chart formats.
- Allow users to experiment with different article configurations to see how predictions change.
- Export results for reporting and further analysis.

## What the Application Cannot Do
- Does not access or process real-time internal data (unless connected to a backend).
- Does not send or publish articles; it is strictly for prediction and analysis.
- The accuracy of predictions depends on the quality and recency of the underlying ML model.

## Who Should Use This Application?
- **Business Analysts:** To forecast communication impact and optimize content strategy.
- **Internal Communications Teams:** To plan and refine messaging.
- **Junior Engineers:** To understand the structure and flow of a modern ML-powered web application.

## Getting Started
1. Open the application in a web browser.
2. Follow the step-by-step workflow:
   - Configure article details and classification.
   - Enter publication metadata.
   - Select relevant topic tags.
   - Generate and review predictions.
3. Export results as needed.

## Code Structure (Key Files)
- `Article_predictor_v&.html`: Main application file (UI, logic, and styling).
- `styles.css`: (If present) Additional styling.
- `README.md`: This documentation file.

## Support & Further Development
For questions, improvements, or to connect the app to real data sources, contact the Internal Communications Analytics team or your local IT support.

---

*This application is a prototype and should be validated with real data and business requirements before production use.*
