# Tableau
Dashboard created for Interview sample

Copyright (c) 2024 Brad Stafford

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



📊 Telecommunications Outage Analysis Dashboard
This project presents a streamlined Tableau dashboard built to analyze telecommunications outage data with performance in mind.

🔍 Custom Dataset Creation
The dataset was manually constructed based on real-world interview scenarios and synthesized outage patterns in the telecom industry. This allowed for full control over data quality and structure to support efficient reporting.

🧹 Data Cleaning with Python & Jupyter
The raw dataset was cleaned and prepared using Python in Jupyter Notebooks, incorporating:

Pandas for preprocessing and transformations

Statistical techniques for anomaly detection and outlier handling

Lightweight ML models to identify and smooth unusual patterns

This approach ensured a clean and insightful dataset that supports effective visualization and analysis.

⚙️ Performance Tuning in Tableau
A key focus of this dashboard is performance tuning—optimizing Tableau's speed and responsiveness for large datasets. Techniques implemented:

FIXED Level of Detail (LOD) Expressions: Used to pre-aggregate data at key levels, reducing the load during runtime.

Context Filters: Applied to limit the scope of data before any dependent filters execute, significantly reducing query volume.

These methods collectively eliminate the dreaded “loading circle,” providing a supercharged user experience.

🎯 Purpose
This simplified report was intentionally designed to:

Highlight best practices in Tableau performance optimization

Provide a reference for using FIXED LODs and Context Filters effectively

Serve as a teaching tool for new developers and data analysts

