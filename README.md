**JavaScript Diverging Bar Chart for LA Lakers Win-Loss Record**

**Introduction**

This document provides a comprehensive overview of a JavaScript-based diverging bar chart that visualizes the win-loss record of the LA Lakers over a span of 20 years, specifically during the tenure of Kobe Bryant from 1996 to 2016. The chart utilizes the AnyChart library to create an interactive and visually appealing representation of the data.

**Key Concepts**

The diverging bar chart is a powerful visualization tool that allows for the comparison of two related datasets—in this case, wins and losses. The chart is designed to display the number of wins and losses for each year, with wins represented on one side and losses on the other. Key concepts include:

1. Data Representation: The chart uses a range bar format to depict wins and losses.

2. Tooltips: Interactive tooltips provide additional information about the data points.

3. Customization: The chart can be customized in terms of colors, axes, and legends to enhance readability and aesthetics.

**Code Structure**

The code is structured into several key sections:
1. HTML Structure: Defines the basic layout and includes the AnyChart library.

2. CSS Styles: Ensures that the chart container occupies the full width and height of the viewport.

3. JavaScript Logic: Contains the logic for creating the chart, including data preparation, series creation, and chart customization.

**Code Exceution Output:** 

![image](https://github.com/user-attachments/assets/c443a305-59f2-48a6-91d6-5001a8c7bd6a)


**Explanation of Key Sections:**

1. Data Preparation: The winlossData array holds the win-loss records for each year. Each entry consists of wins, losses, and the corresponding year.
2. Series Creation: The createSeries function generates the data series for wins and losses, calculating the percentage for tooltips.
3. Chart Customization: The chart is customized with titles, axes settings, tooltips, and a color palette to enhance user experience.
