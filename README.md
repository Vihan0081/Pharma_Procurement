# Pharma_Procurement

<img width="2558" height="1465" alt="Screenshot 2025-09-24 164129" src="https://github.com/user-attachments/assets/5cde23ca-3c42-4123-8b72-add23744ae07" />

The Pharmaceutical Materials Analysis Dashboard is an interactive web application built with Streamlit designed for pharmaceutical procurement teams to explore and analyze vendor data comprehensively. It consolidates data from multiple supplier portals such as SAP Ariba, LabNetwork, MolPort, PharmaCompass, ChemSpider, and Alibaba to provide a single platform for examining chemical pricing, vendor performance, and material specifications.

The dashboard allows users to apply multiple filters dynamically, including material type, vendor name, GMP compliance status, price tier, and currency, enabling tailored data views according to user needs. It presents real-time key performance indicators like total material count, average price, price deviation percentages, and GMP compliance ratios, facilitating quick oversight.

Within the dashboard, users can navigate through six distinct analysis sections focusing on price distribution, vendor analytics, material-specific details, temporal trends, currency and portal effects, and detailed tabular data. These sections feature interactive visualizations including box plots, bar charts, scatter plots, time series, and pie charts, which help in understanding complex relationships and trends.

Technically, the dashboard is built using Streamlit for the frontend interface and user interaction, Pandas for data manipulation and filtering, and Plotly for dynamic charting. Optimization features like Streamlit’s caching ensure efficient data loading and responsive performance. The user interface is designed for usability with a wide layout, sidebar filters, export options to CSV, selectable columns, and tooltips for enhanced interactivity.

Data processing includes automatic cleaning such as converting percentage strings to numeric formats, robust parsing of timestamps, and built-in validation to ensure data integrity. The entire system updates dynamically in real time, automatically refreshing metrics and visualization when filters or selections change, providing an interactive and responsive user experience.

Overall, this dashboard provides pharmaceutical teams with an effective tool for procurement data analysis to support informed decision-making, optimize vendor performance, and manage chemical materials pricing and quality compliance all in one place.
