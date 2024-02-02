# Abnormal Infant Movement Detection
 Abnormal Infant Movement Detection from Accelerometer data

Cerebral Palsy (CP) affects approximately 1 in 400 individuals in the United Kingdom,
underscoring its prevalence and societal impact. The significance of early CP diagnosis cannot
be overstated, as interventions during infancy capitalise on heightened brain plasticity,
yielding substantial improvements. Presently, diagnostic methods for CP in infants involve
costly scans and Movement Assessment, the latter demanding extensive clinician training and
being susceptible to subjectivity and observer fatigue. The integration of machine learning
techniques for automated analysis of infant movement data emerges as a promising avenue,
offering an alternative means to identify infants at risk of developing developmental disorders
like CP, thereby contributing to diagnostic processes.

This project involves a dataset with 21 Typically Developing Infants and 13 infants at risk of
developing CP due to Perinatal Stroke (confirmed via MRI). Axivity WAX9 IMU sensors were
placed on wrists and ankles, recording monthly data from term age to 6 months. Sessions involved
ten-minute recordings with infants lying supine with each trial annotated by a clinician with
movement assessment results. In this project we aim to develop models which can automatically
predict movement assessment results from sensor data, and we will use the collected data to train
and test our models.
