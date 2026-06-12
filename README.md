# MedWeb Checklist Dataset

This repository provides the initial release of the **MedWeb Checklist Dataset**, a counterfactual evaluation resource for assessing the robustness of symptom-detection models applied to social media text.

The dataset contains minimally contrasting text variants designed to evaluate whether a model responds appropriately to surveillance-relevant attributes:

* type of symptom evidence;
* timing of occurrence;
* recovery status; and
* uncertainty of expression.

Each counterfactual set contains nine variants derived from a shared base text. The current release includes **337 counterfactual sets** and **3,033 texts** covering eight symptom or disease categories from the MedWeb task: cold, cough, diarrhea, fever, hay fever, headache, influenza, and runny nose.

This initial release focuses on the checklist dataset and its basic documentation. Prompt templates, evaluation scripts, and additional reproducibility resources may be added in future updates.

## Publication

The dataset was developed as part of the following study:

**Concept-Aware Learning Framework for Detecting Common Symptoms in Social Media Text: Model Development and Evaluation Study**

The study introduces the Concept-Aware Learning Framework (CALF), a method for improving the robustness of symptom-detection models to data-specific and spuriously correlated features. The MedWeb Checklist Dataset was developed to evaluate model sensitivity to selected surveillance-relevant attributes.

![Overview of CALF and the MedWeb Checklist](Images/Figure%201%20-%20updated.png)

Citation details will be updated following publication. A preprint version is currently available [here](https://preprints.jmir.org/preprint/94769).

## Data

The original MedWeb training and test datasets can be downloaded from the [NTCIR website](https://research.nii.ac.jp/ntcir/permission/ntcir-13/perm-en-MedWeb.html). Please cite the original MedWeb publication when using those datasets.

The MedWeb Checklist Dataset is available in the [`Data`](Data) folder of this repository.
