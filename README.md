# Internship-Project
## Project Title:
 Exploratory Data Analysis on Drugs, Side Effects, and Medical Conditions
 ### 1. Objective
 The goal is to analyze the relationships between drugs, their side effects, and the
 medical conditions they treat, as well as to explore the ratings and reviews
 associated with these drugs.
 ### 2. Dataset Overview
 The dataset contains the following columns:
 
 ● drug_name: Name of the drug.
 
 ● medical_condition: The condition the drug is used to treat.
 
 ● side_effects: Common side effects of the drug.
 
 ● generic_name: The generic name of the drug.
 
 ● drug_classes: The class of the drug (e.g., antibiotic, antihistamine).
 
 ● brand_names: Brand names under which the drug is sold.
 
 ● activity: The activity of the drug (e.g., active, inactive).
 
 ● rx_otc: Indicates if the drug is prescription (Rx) or over-the-counter (OTC).
 
 ● pregnancy_category: The drug's pregnancy risk category.
 
 ● csa: Controlled Substances Act schedule, if applicable.
 
 ● alcohol: Interactions with alcohol.
 
● related_drugs: Other drugs related to the primary drug.

 ● medical_condition_description: A brief description of the medical
 condition.
 
 ● rating: Average user rating of the drug.
 
 ● no_of_reviews: Number of user reviews.
 
 ● drug_link: URL link to more information about the drug.
 
 ● medical_condition_url: URL link to more information about the medical condition.
 ## About Dataset
 Data contains details of various drugs (used for conditions like Acne, Cancer,Heart Disease, etc. ) and their side effects
 Drugs detail URLs were collected from following dataset
 
 Major Column Descriptors:
 generic_name:
 The chemical name of the drug (not brand name)
 
 drug_classes:
 The drug belongs to which drug class, i.e a drug class is a set of medications and other compounds that have a similar chemical structure, the same
 mechanism of action (i.e. binding to the same biological target), a related mode of action, and/or are used to treat the same disease.
 
 brand_names:
 brand names in which the drugs are being sold or available in the market.
 
 activity:
 Activity is based on recent site visitor activity relative to other medications in the
 list. Data was gathered from https://www.drugs.com
 
 rx_otc:
 Rx-to-OTC switch is the transfer of proven prescription drugs to
 nonprescription, where
 
 OTC(Over-the-counter) = Medication that can be purchased without a medical
 prescription
 
 Rx =Prescription Needed
 Rx/OTC = Prescription or Over-the-counter.
 
 pregnancy_category:
 A=Adequate and well-controlled studies have failed to demonstrate a risk to the
 fetus in the first trimester of pregnancy (and there is no evidence of risk in later
 trimesters).
 
 B=Animal reproduction studies have failed to demonstrate a risk to the fetus and there are no adequate and well-controlled studies in pregnant women.
 
 C=Animal reproduction studies have shown an adverse effect on the fetus and there are no adequate and well-controlled studies in humans, but potential
 benefits may warrant use in pregnant women despite potential risks.
 
 D=There is positive evidence of human fetal risk based on adverse reaction data from investigational or marketing experience or studies in humans, but
 potential benefits may warrant use in pregnant women despite potential risks.
 
 X =Studies in animals or humans have demonstrated fetal abnormalities and/or there is positive evidence of human fetal risk based on adverse reaction data
from investigational or marketing experience, and the risks involved in use in pregnant women clearly outweigh potential benefits.

 N=FDAhasnotclassified the drug.
 
 csa:
 Controlled Substances Act (CSA) Schedule
 M=Thedrug has multiple schedules. The schedule may depend on the exact dosage form or strength of the medication.
 U=CSASchedule is unknown.
 
 N=Is not subject to the Controlled Substances Act.
 
 1 =Hasahigh potential for abuse. Has no currently accepted medical use in
 treatment in the United States. There is a lack of accepted safety for use under
 medical supervision.
 
 2 =Hasahigh potential for abuse. Has a currently accepted medical use in
 treatment in the United States or a currently accepted medical use with severe
 restrictions. Abuse may lead to severe psychological or physical dependence.
 
 3 =Hasapotential for abuse less than those in schedules 1 and 2. Has a
 currently accepted medical use in treatment in the United States. Abuse may
 lead to moderate or low physical dependence or high psychological
 dependence.
 
 4 =Hasalowpotential for abuse relative to those in schedule 3. It has a
 currently accepted medical use in treatment in the United States. Abuse may
 lead to limited physical dependence or psychological dependence relative to
 those in schedule 3.
 
 5 =Hasalowpotential for abuse relative to those in schedule 4. Has a currently
 accepted medical use in treatment in the United States. Abuse may lead to
 limited physical dependence or psychological dependence relative to those in
 schedule 4.
 
alcohol:
 X =Interacts with Alcohol.
 rating:
 For ratings, users were asked how effective they found the medicine while
 considering positive/adverse effects and ease of use (1 = not effective, 10 = most
 effective).
 
 #### 3. Tools Required
 ● Python: The primary programming language for data analysis.
 
 ● Pandas: For data manipulation and analysis.
 
 ● Matplotlib/Seaborn: For data visualization.
 
 ● Jupyter Notebook: To write and run Python code.
