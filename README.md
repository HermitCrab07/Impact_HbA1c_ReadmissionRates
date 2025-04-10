### Impact of Measurement of HbA1c on Hospital Readmission: Diabetes Dataset - Revisiting 2014 Research

#### Overview
This repository aims to complement a diabetes study published in 2014, which highlighted the protective role of HbA1C measurements against early readmission in diabetes patients. Over a decade has passed since the original research publication and significant advancements in AI gives us new tools and perspectives to reassess the data and conclusions drawn at the time. My interest in this data is for two reasons - [1] I've a personal interest in understanding diabetes and its implications [2] The paper raised some interesting questions that I wanted to evaluate, specifically the claim that the measurement of HbA1c was protective against readmission. 

#### Purpose
The primary goal of this research is not to recreate the original paper but to augment it using AI/ML methods, specifically look at the data using the causal lens. This  aims to uncover deeper insights and assess the validity of the study's recommendations with today's advancements. There isn't enough data to recreate the old analyses and I neither have the desire nor the interest to do so. Instead, I use the paper from 2014 more as a springboard to ask a different questions and move it forward from there.

#### Dataset
Description of the Dataset - Each row represents hospitalized patient records diagnosed with diabetes over ten years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information extracted from the database for encounters satisfied the following criteria - (1) It is an inpatient encounter (a hospital admission). (2) It is a diabetic encounter, that is, one during which any kind of diabetes was entered into the system as a diagnosis. (3) The length of stay was at least 1 day and at most 14 days. (4) Laboratory tests performed during the encounter. (5) Medications were administered during the encounter. The data contains attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab tests performed, HbA1c result, diagnosis, number of medications, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

#### Analysis Approach
- **Re-evaluation with Modern Tools**: Applying causal inference and machine learning techniques to the dataset after performing the basics.
- **My Thought Process**: This repository will focus on the thought process of analyzing this dataset and more importantly, doing a deep dive using the simplest of tools. In what follows, I try to articulate my thought process, assumptions, and conclusions drawn from the analysis. It's my way of doing a deep dive. It's simple because that's how I really get a feel of the data. Lot of basic cross-tabs are what I use to get a 'handle' on the data... and only after that, do I move on to more complex analysis.

#### Why This Matters
Even without a background in the medical field, the importance of management plans for conditions like diabetes is obvious to me (and everyone else) but by revisiting this paper with new methods and new perspectives, my hope is to add another aspect to the conversation and potentially validate or refine the strategies for managing diabetes, contributing to improved outcomes. I hope.

#### Contributing
Whether you are a data scientist, a medical professional, or just someone interested in diabetes management, your insights and contributions are always welcome. 

#### License
This project is made available under the [MIT License](LICENSE.md).

#### Contact
For more discussion or to give feedback, please send an email to [asgpss@gmail.com].

---
