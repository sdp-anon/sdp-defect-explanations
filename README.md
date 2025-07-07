# Explanation Files for SDP Study 

This repository contains explanation outputs for 1000 defective instances from a software defect prediction (SDP) dataset. These outputs were generated using interpretable machine learning methods as part of a study on lightweight, rule-based explanations.

# Contents

- lime_explanations.json  
  Rule-based explanations generated using LIME.

- anchor_explanations.json  
  Rule-based explanations generated using the Anchor algorithm.

- intersected_rules.json  
  Reduced explanations representing the intersection of LIME and Anchor rules for each instance. These were used in the study to evaluate fidelity, rule complexity, and interpretability.

Each file contains instance-level explanations, including prediction label, explanation rules, and fidelity score where applicable.

# Purpose

These explanation files support the reproducibility of the experimental results discussed in the paper. The repository is anonymized for blinded peer review. Author identity will be added after acceptance.

# License

This repository is released under the MIT License.
