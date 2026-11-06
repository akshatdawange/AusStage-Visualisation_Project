# Kelley Abbey's Victorian Stage Contribution & Collaboration Network

An interactive network visualisation exploring **Kelley Abbey's contribution to Victoria's performing arts industry** and the professional collaborations formed throughout her career.

Built using **D3.js, JavaScript, HTML and CSS**, this project visualises the relationships between stage productions, contributors and collaborators, providing insights into the structure of the Victorian performing arts network.

## Project Overview

This project presents two interconnected network visualisations based on Kelley Abbey's contributor profile from AusStage – The Australian Live Performance Database.

The visualisation explores:
- The stage productions Kelley Abbey contributed to across Victoria.
- The contributors and creative professionals involved in these productions.
- The collaboration relationships between individual contributors.
- The frequency of professional collaborations, represented through weighted network connections.

## Key Features

### 1. Event Contribution Network
Visualises the relationship between stage productions and their contributors.

- **Event nodes:** Represent individual stage productions, displayed as yellow squares.
- **Contributor nodes:** Represent individuals involved in productions, displayed as circles.
- **Gender-based colours:** Male contributors are represented in blue and female contributors in pink.
- **Dynamic node sizing:** Contributor node sizes are proportional to their number of collaborators.

### 2. Collaboration Network
Transforms the event contribution network into a contributor-to-contributor collaboration network.

- Displays professional relationships between contributors.
- Highlights Kelley Abbey's position within the collaboration network.
- Uses weighted edges to represent the frequency of collaborations.
- Thicker connections indicate more frequent collaborations.

### 3. Interactive Exploration
The visualisation incorporates several interactive features:

| Feature | Functionality |
|---|---|
| Network Toggle | Switch between event contribution and collaboration networks. |
| Zoom & Pan | Explore the network by zooming in and out. |
| Node Dragging | Move individual nodes to investigate network structures. |
| Interactive Tooltips | Hover over nodes to view detailed contributor or event information. |
| Node Highlighting | Highlight connected nodes and relationships while dimming unrelated elements. |
| Dynamic Layout | Uses force-directed simulation to position nodes and maintain network structure. |

## Technology Stack

- **HTML5** – Webpage structure and visualisation layout.
- **CSS3** – Styling, positioning and visual presentation.
- **JavaScript (ES6)** – Data processing and interactive functionality.
- **D3.js (v7)** – Network visualisation, force simulation, SVG rendering, dragging and zooming.
- **JSON** – Structured storage and retrieval of network nodes and edges.

## Data Sources

The project uses publicly available data from:

**AusStage – The Australian Live Performance Database**

- [Kelley Abbey – AusStage Contributor Profile](https://www.ausstage.edu.au/pages/contributor/234951)

The visualisation retrieves two pre-processed network datasets:

1. [Event Contribution Network](https://github.com/gavjmooney/FIT5147_S1_2025_PE3_Data/blob/main/event_contribution_network.json)
2. [Collaboration Network](https://github.com/gavjmooney/FIT5147_S1_2025_PE3_Data/blob/main/collaboration_network.json)

The datasets are loaded dynamically from GitHub using D3.js.

## How to Run the Project

### Prerequisites
- A modern web browser (Google Chrome, Firefox, Safari or Edge).
- Python installed (for running a local development server), or another local HTTP server.

## Understanding the Visualisation

The project provides two different perspectives on the same professional network:

**Event Contribution Perspective**

Shows how individual contributors are associated with different stage productions, revealing the composition of production teams and the extent of participation across events.

**Collaboration Perspective**

Focuses on relationships between contributors, revealing recurring professional partnerships and the interconnected nature of Victoria's performing arts community.

Together, these perspectives demonstrate how network visualisation can be used to explore professional relationships, participation patterns and collaboration structures within the creative industries.

## Project Context

This project was developed as part of **FIT5147 – Data Exploration and Visualisation (Semester 1, 2025), Project Exercise 3 (PE3)**.

It demonstrates the application of interactive network visualisation techniques to real-world cultural and performing arts data.

---

**Developed by:** Akshat Dawange

**Technologies:** D3.js | JavaScript | HTML | CSS | JSON

**Data Source:** AusStage – The Australian Live Performance Database
