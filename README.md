# framingham-ms
Framingham Heart Study data multi-state model using four states: No disease, Hypertension, Cardiovascular disease, and Death (absorbing).
Censorship indicated by state 99 for those who ended the study alive.
Retained covariates include age, sex, diabetes & cursmoke.
Ages updated to reflect calculated transition times.
msm package by Christopher H. Jackson, 2011 - Multi-State Models for Panel Data: The msm Package for R, Journal of Statistical Software 38(8) 1-28
