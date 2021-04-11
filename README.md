'ICU Requirement Prediction for Covid Patients' was built by 'The Tech Toddlers' as a part of SheHacks DTU 2021 conducted by CLIMB DTU

**Problem Statement**

The model predicts whether a covid patient admitted to a hospital will require ICU treatment. Additionally, it shows show correlation between patient’s attributes (age, sex, comorbidities, etc.) and predicted ICU requirement.

**Impacts**

The COVID-19 pandemic impacted the whole world, overwhelming healthcare systems which are unprepared for such intense and lengthy requests for ICU beds, professionals, PPE and healthcare resources. There is urgency in obtaining accurate data to better prepare healthcare systems and avoid collapse.

Our model does this by enabling hospitals to manage their resources efficiently, since huge demand and short supply of resources like ICU beds has led to a resource crunch. Based on the individual clinical data, our model predicts (at early stages of hospital admission) whether patients will need ICU support. This helps in the following ways:

1. Hospitals allocate ICU resources efficiently and make sure there is no shortage. This enables more targeted patient care to avoid high-risk patients’ deterioration and consequent need for ICU admission.
2. Hospitals can discharge stable patients confidently if the model predicts low risk for ICU admission, thus freeing up resources for those who need them.
3.  Smaller hospitals will be able to gauge the number of ICUs required, based on the hospital’s patient database. This lead to an efficient allocation of ICUs throughout healthcare system. 

**Dataset**

An open-source dataset from Hospital Sírio-Libanês’s individual patient database with labelled data (target variable-ICU admission) was used. It has 1925 entries, 231 attributes of the following normalised data fields:

Patient demographic info (3), previous disease history (9),  various blood test readings (36), vital signs (6), window of admission, etc.

**Technologies used**

Logistic Regression, Pandas, Scikit-learn, Seaborn, Bootstrap, HTML, JavaScript, CSS

https://icuprediction.netlify.app/

