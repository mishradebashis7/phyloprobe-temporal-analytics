# PHYLOPROBE: Advanced Temporal Hierarchy Engine

**PHYLOPROBE** is a high-fidelity web-based visualization platform designed to solve the "Black Box" problem of complex hierarchical systems. While standard tree diagrams show structure, PHYLOPROBE visualizes **Evolutionary Vitality**—allowing researchers to observe how the internal health and data metrics of individual nodes shift over time.

## 🚀 Live Demonstration
[**Access the Interactive Seminar Dashboard Here**](https://mishradebashis7.github.io/phyloprobe-temporal-analytics/)

---

## 🧐 What is PHYLOPROBE?
PHYLOPROBE is a **Temporal Hierarchy Engine**. It is designed for analysts and researchers who need to visualize not just a static organization, but a "moving movie" of a system's history. By combining structural mapping with time-series data, it allows for the identification of decay, growth patterns, and bottlenecking across complex networks.

### The Research Objective
The primary goal is to achieve **Temporal Clarity**. We aim to allow an operator to "scrub" through time (T-0 to T-20) and observe how a parent node’s state affects its descendants. This is critical for high-stakes environments like federal budgeting, software reliability, and social network analysis.

---

## 📚 Theoretical Foundations
This engine is built upon two major academic pillars in the field of Information Visualization:

### 1. Contact Trees (Khulusi et al., 2016)
Inspired by botanical metaphors, this framework suggests that nodes should be viewed as "containers" of interactions. 
* **Application:** In PHYLOPROBE, nodes are not just labels; they are composite entities holding a **5x5 Matrix** of internal "contacts" or sub-metrics.

### 2. TreeVersity (Gomez et al., 2012)
This theory focuses on **Change Detection** and **Variance**. 
* **Application:** PHYLOPROBE utilizes dynamic sparklines and comparative metric bars to show the *trajectory* of change between time intervals, rather than just raw values.

---

## 🧪 Detailed Case Studies (Domains)
PHYLOPROBE includes three pre-configured research environments:

### 🌐 Social Network Mode (Interaction Density)
* **Focus:** Tracking relationship decay and community engagement.
* **Key Metrics:** Engagement Rate (Interaction frequency) and Tie Strength (Durability).
* **Visual Insight:** A "dimming" 5x5 matrix reveals a social group losing cohesion even if the structural link remains.

### 💰 Finance Mode (Budget & Variance)
* **Focus:** Visualizing the flow of capital and allocation efficiency.
* **Key Metrics:** Actual vs. Planned Spending and Allocation Velocity.
* **Visual Insight:** Red-line spikes in the sparklines indicate emergency mid-quarter funding shifts.

### 💻 Software Architecture (Microservice Health)
* **Focus:** Monitoring system reliability and operational bottlenecks.
* **Key Metrics:** Latency (ms) and Error Rate percentages.
* **Visual Insight:** High-density indigo clusters in the matrix indicate a shared resource failure affecting multiple services.

---

## 🛠 Component Breakdown

| Component | Technical Function | Seminar Value |
| :--- | :--- | :--- |
| **5x5 Matrix** | Data Fingerprinting | Provides an "Internal DNA" view of node health at a glance. |
| **T-Slider** | State Management | Acts as a "Time Machine" for the entire hierarchy. |
| **Bezier Branches** | SVG Pathing | Ensures 100% accurate structural connection regardless of zoom. |
| **Sparklines** | Trend Analysis | Visualizes the "Heartbeat" (vibrancy vs. stability) of a node. |

---

## ⚙️ Technical Stack
* **Engine:** React 18 (Functional Components)
* **Styling:** Tailwind CSS (Enterprise-grade UI)
* **Graphics:** Custom SVG deterministic anchoring system
* **Data Layer:** Decoupled JSON architecture for modular research loading

---

## 👨‍🔬 Technical Implementation Note
The branching logic in this engine utilizes a **Flex-Relative Anchor System**. Unlike standard libraries that often fail at high zoom levels, PHYLOPROBE calculates the vertical midpoint of parent-to-child stacks to ensure pixel-perfect Bezier curves that never disconnect from the node ports.

---
© 2025 PHYLOPROBE Project | Senior UI/UX Research Dashboard
