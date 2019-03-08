# media_peer_value

This repository includes data and R-code needed to reproduce analyses published in 
C. Scholz, B.P. Doré, N. Cooper, E.B. Falk (2019). Neural Valuation of Anti-Drinking Campaigns and Risky Peer Influence in Daily Life. Health Psychology.

## Data file

Naming conventions for variables:

- _fp: "_fp" in variable names denotes variables collected during the field period
- _bl: "_bl" in variable names denotes variables collected in the baseline questionnaire
- _c: "_c" in variable names denotes variables that were grand-mean centered
- _log: "_log" in variable names denotes variables that were log-transformed

Participant-level variables:
- pID: Participant ID 
- alc_att_bl: Attitudes towards alcohol collected at baseline, raw scores
- alc_att_bl_c:	Attitudes towards alcohol collected at baseline, grand-mean centered
- binges_bl: Frequency of binge drinking occasions in the last 12 months, reported at baseline (10-point scale)
- mean_valence_fp: Average valence of conversations about alcohol, reported during field period	
- mean_valence_fp_c: Average valence of conversations about alcohol, reported during field period; grand-mean centered
- typ_drinking_occasions_bl:	Number of drinking occasions in a typical month in the last 12 months, reported at baseline (10-point scale)
- typ_nr_drinks_fp: Number of drinks at a typical drinking occasion in the last 12 months; 11-point scale
- typ_nr_drinks_bl_log_c: Number of drinks at a typical drinking occasion in the last 12 months; 11-point scale; logged, grand-mean centered	


Daily reports collected during the field period:
- conv_fp: Occurence of conversations about alcohol, field period	
- date_fp: Day of data collection during the field period (1=first day of data collection) 
- gender: Participants' gender, dichotomous (2=female)	
- gender_c: Gender, grand-mean centered	
- nr_drinks_fp: number of alcoholic drinks within the last 24 hours, reported during the field period
- nr_drinks_fp_log_c: number of alcoholic drinks within the last 24 hours, reported during the field period, log-transformed, grand-mean centered	
- ynr_drinks_fp_log_c: number of alcoholic drinks within the last 24 hours, reported during the field period, 1-day lagged, log-transformed, grand-mean centered
- peer_pres_fp: Whether the participant was in the presence of a peer who drank alcohol within the last 24 hours (1=yes) during the field period
- peer_pres_fp_c:	Whether the participant was in the presence of a peer who drank alcohol within the last 24 hours (1=yes) during the field period, grand-mean centered
- valence_fp: Valence of conversations about alcohol (7=very positive towards alcohol)	
- valence_fp_c: Valence of conversations about alcohol (7=very positive towards alcohol); grand-mean centered	
- yvalence_fp_c: Valence of conversations about alcohol (7=very positive towards alcohol); 1-day lagged, grand-mean centered	

Percent signal change in regions of interest:
- bartra_VMPFC_cons_c: Percent signal change in the VMPFC portion of the value ROI, extracted from the message-consistant contrast, grand-mean centered
- bartra_VMPFC_derog_c:	Percent signal change in the VMPFC portion of the value ROI, extracted from the message-derogation contrast, grand-mean centered
- bartra_VS_cons_c:	Percent signal change in the VS portion of the value ROI, extracted from the message-consistant contrast, grand-mean centered
- bartra_VS_derog_c: Percent signal change in the VS portion of the value ROI, extracted from the message-derogation contrast, grand-mean centered
- bartra_cons_c:	Percent signal change in the value ROI, extracted from the message-consistant contrast, grand-mean centered
- bartra_derog_c:	Percent signal change in the value ROI, extracted from the message-derogation contrast, grand-mean centered
- omnibus_condeff_cons_c: Percent signal change in the cognitive-regulation ROI, extracted from the message-consistant contrast, grand-mean centered
- omnibus_condeff_derog_c: Percent signal change in the cognitive-regulation ROI, extracted from the message-derogation contrast, grand-mean centered

