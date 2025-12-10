# Read Me - Choose Your Own Hypothesis Final Project

### Cally Minner, SEIS 631, Fall 2025


For this project, I used data from the HYPERAKTIV: An Activity Dataset from Adult Patients with
Attention-Deficit/Hyperactivity Disorder (ADHD) (Hicks et al., 2021) research article.

After creating a master dataframe and cleaning the data, I focused on 5 key columns: ADHD, Bipolar, Unipolar (also known as major depressive disorder), Anxiety, and Substance (meaning substance use). I did a comparison of ADHD with each of the other four diagnoses, permuting the ADHD column too see if there is a relationship between having ADHD and also having another one of these diagnoses, followed by a Chi-Square test of significance. Essentially, what are common comorbidities with ADHD, if any? Because I compared ADHD against four other diagnoses and not just one, I then used the Bonferroni Correction to adjust the p-values.