# Rails-Project-Analysis-and-Automated-Classification-of-GitHub-Issues 
This project aims to analyze the issues related to the Rails project hosted on [GitHub](https://github.com/rails/rails/issues). The analysis includes investigating the evolution of the number of issues over time, identifying periods with higher issue counts, determining the top reporters, and finding the most popular issue category.

## Overview

The project involves collecting and analyzing the last 500 issues from the Rails project. Various questions are addressed, and the issues are classified based on their descriptions using a model from HuggingFace.

## Questions Explored

1. **Evolution of Issues:**
   - How do the number of issues evolve over time?

2. **Periods with Higher Issues:**
   - Are there any periods in which we get more issues?

3. **Top Reporters:**
   - Is there anyone who reports more issues than others?

4. **Popular Issue Category:**
   - What is the most popular category (label)?

5. **Issue Classification:**
   - Can the issues be classified based on their descriptions?

## Methodology

### Data Collection
- The script collects the last 500 issues from the Rails project on GitHub.

### Data Analysis
- The evolution of issues over time is visualized using plots.
- Statistical methods are used to identify periods with higher issue counts.
- The top reporters and most popular issue category are determined based on label counts.

### Issue Classification
- Descriptions of issues are used as input to DistilBERT model for automatic classification.

## Results

The integration of a powerful DistilBERT-based multi-label classification model further exemplifies the project’s prowess in leveraging advanced technologies for automated issue categorization,
demonstrating its capacity to handle diverse problem domains. 
