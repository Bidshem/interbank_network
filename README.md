# The effect of the interbank network structure on contagion and common shocks

This project explores a simulative extension of the original paper by Georg (2013), which presents a dynamic, multi-agent model of a banking system with central bank involvement. The model considers banks managing portfolios of risky investments and securing reserves according to their risk, return, and liquidity preferences. It also explores the role of interbank networks and the impact of unpredictable deposit flows on liquidity demands and systemic risk.

## Key Insights and Findings

- **Banking System Model**: The model incorporates central bank involvement, where banks face liquidity demands based on portfolio management and interbank lending.
  
- **Network Structures**: The study compares different interbank network structures, highlighting the resilience of money-centre networks, where a few large banks dominate, versus random networks, particularly during financial crises.

- **Central Bank's Role**: Central bank interventions provide temporary stability in interbank markets by easing liquidity pressures. However, over time, they can increase systemic risk by fostering interbank dependencies.

- **Systemic Risk Dynamics**: The research identifies two main channels of systemic risk: contagion (risk spreading among interconnected banks) and common shocks (affecting all banks simultaneously). Each channel requires distinct policy responses for financial stability.

- **Policy Implications**: The findings underscore the importance of network structure and central bank policies in shaping the stability of the banking system, especially under financial stress.

## Repository Structure
The project is organized as follows:
- **`README.md`**: This file, providing an overview of the project.
- **`Data Folder`**: Contains the dataset or a link to it. Includes data on bank portfolios, liquidity, and interbank networks.
- **`Analysis Folder`**: Contains the code and scripts used to analyze the data.
  - **Code**: Jupyter Notebooks.
  - **Results Folder**: Contains figures of analysis.
- **`Report Folder`**:
  - **Figures Folder**: Contains visualizations used in the report.
  - **Report Source File**: The LaTeX source for the report.
  - **Report File**: The compiled PDF version of the report.
  - **Reference File**: Contains the list of references used in the project (`.bib` file).
- **`Slides Folder`**:
  - **Presentation Source File**: The source file for the presentation (PowerPoint).
  - **Presentation PDF**: The final PDF version of the presentation slides.

## License
This project is licensed under the MIT License.
