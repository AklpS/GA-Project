Clinical Dataset of the CYP-GUIDES Trial
Cytochrome Psychotropic Genotyping Under Investigation for Decision Support Data

Context

CYP-GUIDES (Cytochrome Psychotropic Genotyping Under Investigation for Decision Support) is a randomized controlled trial (RCT) comparing 2 outcomes in hospitalized patients with severe depressive disorders treated according to the patient's CYP2D6 genotype and functional status versus standard psychotropic therapy. The primary outcome was hospital Length of Stay (LOS) and the secondary outcome was the Re-Admission Rate (RAR) 30 days after discharge.

The trial setting was the Institute of Living at Hartford Hospital. CYP2D6 genotyping was implemented to characterize the functional status of the CYP2D6 enzyme with sub-normal, normal, or supra-normal function. The electronic medical record (EMR) was utilized to transmit clinically actionable drug prescribing guidance based on the patient's CYP2D6 function to the physician.

Content

The RCT recruited 1500 patients, genotyped CYP2D6 in 1459, and randomized 477 to standard therapy (Group S), for whom treatment-as-usual guidance was delivered without consideration of patient CYP2D6 genotype, and 982 to genetically-guided therapy (Group G) where CYP2D6-based treatment recommendations were provided via EMR to physicians. For inpatients in Group G whose CYP2D6 function was sub- or supra-normal, medications primarily metabolized by the CYP2D6 enzyme were proscribed.

The RCT developed a database of potential benefits to the field. The pharmacologic, clinical course, and pharmacogenetic therapeutic guidance is being published in a related article. These data should enable various investigators to assess effeeffects of clinical decision support on resource utilization and psychotropic therapy during psychiatric hospitalizations.



Data Analysis using Pandas

1. Determine which Assignment group shows better result
2. Difference between EMR C: traditional vs EMR E: system
3. To compare by Diagnosis, the result (stay length) for each Assignment group
4. Considering additional parameters (age and gender)
5. Check relationship between # Psychotropic Medications and # Administrations
