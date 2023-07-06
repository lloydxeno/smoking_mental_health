
This contains the code for the survival models in the paper "Using polygenic risk scores to investigate the evolution of smoking and mental health outcomes in UK Biobank participants"

The data file is originally in wide format (one record per person), until the records are split at each failure event to deal with non-proportionality. The variables and their descriptions are:

id-->Subject identifier

state1-->	                    Smoking status at birth (constant: 1 = non-smoker)

age1-->	                      Set to 0 for all records

state2-->	                    Smoking initiation state

age2-->	                      Age started smoking

state3-->	                    Smoking cessation state

age3-->	                      Age stopped smoking

state4-->	                    Mental health hospitalization

age4-->	                      Age at first mental health hospitalization

smok3cat-->	                  Last smoking status:

prs_evsmk-->	                  Polygenic risk score for ever smoking

Neur_prs-->	                  Polygenic risk score for neuroticism

Prs_pkyrs-->	                  Polygenic risk score for pack-years of smoking

Cov_smk	-->                    Polygenic risk score for smoking covariates

Male-->	                      Indicator variable (Male =1, Female = 0)

Assess_age-->                Age at assessment

n_22009_0_1–n_22009_0_10-->	  These are 10 genetic principal component variables
