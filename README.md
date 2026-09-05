This repository has three notebook files for (1) Minimum Seed Analysis, (2) Loc specific augmentation study, and (3) Global augmentation study which will be presented at WI-IAT 2026 conference.
The following is the abstract for the conference. 
Wafer map defect classification is essential in semiconductor manufacturing for yield analysis and process monitoring, 
but practical deployment is challenged by severe class imbalance and large variation among defect patterns. 
This study presents an empirical analysis of data efficiency and augmentation policies on the WM-811K dataset using a ResNet-18 classifier. 
A Minimum Seed Analysis examines how performance changes as the number of real training examples per class increases. 
Under the evaluated protocol, macro-F1 improves rapidly up to roughly 40 real samples per class and then increases more gradually, 
with substantial class-to-class differences. An Augmentation Policy Study then compares five composite policies, first globally and then only for the Loc class. 
Mild augmentation yields the highest observed mean macro-F1 in both settings (0.930 globally and 0.931 in the Loc-specific experiment), 
but the differences among Base, Mild, and Moderate are small relative to run-to-run variability and are therefore interpreted descriptively rather 
than as statistically significant superiority. The Loc-specific experiment also shows that the overall macro-F1 gain does not correspond to an improvement 
in Loc F1 itself, indicating that changing one class's augmentation can alter cross-class decision boundaries. 
Overall, the results are consistent with the hypothesis that preserving spatial defect structure is important, 
especially for localized and fine-structure classes; however, morphology is interpreted qualitatively rather than measured directly. 
These findings provide practical guidance for data-efficient wafer-map classification and motivate future morphology-aware evaluation.
