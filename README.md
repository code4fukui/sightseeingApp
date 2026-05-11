# Fukui Prefecture Tourist Survey Map (sightseeingApp)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An interactive map application that visualizes tourist survey comments for Fukui Prefecture, Japan. This tool plots feedback from visitors on a map, color-coded by satisfaction level, to provide insights into tourist experiences across different areas.

**Live Demo: [https://code4fukui.github.io/sightseeingApp/](https://code4fukui.github.io/sightseeingApp/)**

## Features

-   **Interactive Map:** Visualizes survey responses as points on a map of Fukui Prefecture.
-   **Color-Coded Satisfaction:** Markers are colored to represent the reported satisfaction level:
    -   🔵 **Blue:** Satisfied / Very Satisfied
    -   🟡 **Yellow:** Neutral
    -   🔴 **Red:** Dissatisfied / Very Dissatisfied
-   **Detailed Popups:** Click on any marker to view the full survey response, including timestamp, visitor demographics, satisfaction reasons, and comments on transportation and facilities.
-   **Area Selector:** A dropdown menu allows you to quickly zoom to a specific tourist area.
-   **Dynamic Filtering:** Use checkboxes to show or hide markers based on satisfaction level.
-   **Jittered Points:** Marker locations are slightly randomized within their designated area to prevent overlap and improve visibility.

## Usage

This is a static web application that runs entirely in the browser. No build process or server is needed.

1.  Clone the repository.
2.  Open the `index.html` file in your web browser.

## Data Source and Credits

This application is powered by open data.

-   **Primary Data Source:** [福井県観光アンケートオープンデータ (Fukui Tourism Survey Open Data)](https://github.com/code4fukui/fukui-kanko-survey/)
-   **Icon Attribution:** [マーカー icon by Icons8](https://icons8.com/icon/OBmVbH2qOGwK/%E3%83%9E%E3%83%BC%E3%82%AB%E3%83%BC)
-   This project is related to the [Fukui Tourism data Analizing System (FTAS)](https://www.fuku-e.com/feature/detail_266.html).

## Technology Stack

The application is built with vanilla HTML, CSS, and JavaScript (ES Modules) and utilizes the following libraries via CDN:

-   [OpenLayers](https://openlayers.org/): For rendering the interactive map.
-   [OLMap.js](https://github.com/eiichimiyagawa/OLMap): A wrapper library for simplifying OpenLayers usage.
-   [CSV.js](https://github.com/code4fukui/js.sabae.cc): A lightweight library for parsing CSV data fetched from the source.

## License

This project is available under the [MIT License](LICENSE).