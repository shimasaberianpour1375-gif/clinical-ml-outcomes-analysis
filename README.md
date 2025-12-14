# clinical-ml-outcomes-analysis
Clinical Outcome Analysis on Real World Musculoskeletal Data

## Overview
This repository contains the analysis and modelling work for my MSc dissertation in Data Analytics. The project focuses on analysing a large real world musculoskeletal clinical dataset to understand and predict patient outcomes. The emphasis was on interpretability, statistical validity, and decision making under real data constraints rather than maximising model accuracy.

## Problem Context
Clinical datasets are often noisy and complex, and even when structurally clean, they require careful reasoning to avoid over interpretation. In this project, the dataset had been previously curated for research use within the department, which meant it was structurally consistent and well prepared. This shifted the focus of the work away from heavy preprocessing and toward statistical reasoning, feature understanding, and responsible interpretation of results.

## Key Constraints
- Real world clinical data with inherent domain assumptions
- Class imbalance across outcome variables
- Need for interpretability and transparency
- Risk of over confidence in statistically significant but clinically weak patterns
- Statistical validity was as important as predictive performance

## Approach
The project followed an end to end analytical workflow with an emphasis on reasoning and trade offs rather than tool driven optimisation.

- Exploratory analysis to understand distributions, relationships, and assumptions
- Statistical testing to validate meaningful associations
- Use of interpretable baseline models as reference points
- Comparison with more complex models to understand performance trade offs
- Application of explainability techniques to interpret model behaviour

Model choice was guided by suitability to the problem context rather than raw performance metrics.

## Key Decisions and Trade Offs
- Simpler, interpretable models were prioritised when performance gains from complex models were marginal
- Model evaluation focused on robustness and reliability rather than headline accuracy
- Feature understanding and statistical validity had more impact than increasing model complexity
- Explainability was treated as a requirement, not an optional add on

## Outcomes and Learnings
The final outcome was an analysis designed to support informed reasoning rather than optimise a single metric. A key learning was that even with clean data, the main risk lies in over interpretation and misplaced confidence. This reinforced the importance of aligning analytical decisions with the context in which results are used.

## Repository Structure
- data_preprocessing  
  Scripts and notebooks for preparation and validation

- analysis  
  Exploratory analysis and statistical testing

- models  
  Model training and comparison workflows

- evaluation  
  Performance evaluation and interpretability outputs

## Notes
Raw data is not included due to sensitivity. This repository focuses on the analytical workflow and modelling decisions. The full dissertation document can be shared if useful.

