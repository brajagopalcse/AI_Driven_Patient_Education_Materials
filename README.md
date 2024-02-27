
# Supporting Personalized Pregnancy Care Using Artificial Intelligence: Identifying Online Health Education Materials to Prevent Postpartum Depression Using Natural Language Processing


**Model 1:**
This model is trained to classify articles that are relevant and irrelevant to pregnancy.

Tag "1": Related Articles (These are articles related to Pregnancy)

Tag "4": Unrelated Articles (These are articles that are unrelated to Pregnancy)


**Model 2:**
This model is trained to categorize articles related to Pregnancy: _Diet_, _Exercise_, _Mental Health_, or _other_ (Articles that do not fall into these 3 categories)

Tag "1": Articles related to Diet (Pregnancy-Related)

Tag "0": Articles related to Exercise (Pregnancy-Related)

Tag "3": Articles related to Mental Health (Pregnancy-Related)

Tag "4": Articles related to the broader topic of Pregnancy itself but not related to the above 3 main categories

**One-step:**
This model is trained to identify articles into 5 categories in a single model: _Diet_, _Exercise_, _Mental Health_, _Other_, or _Unrelated_

Tag "1": Articles related to Diet (Pregnancy-Related)

Tag "0": Articles related to Exercise (Pregnancy-Related)

Tag "3": Articles related to Mental Health (Pregnancy-Related)

Tag "4": Articles related to the broader topic of Pregnancy itself but not related to the above 3 main categories

Tag "9": Unrelated Articles (These are articles that are unrelated to Pregnancy)

**Overall or Two-step:**
This model is a combination of Model 1 and Model 2.

## Reference

Please cite the following paper if you find this code is useful.

Patra, Braja Gopal, et al. "Automated classification of lay health articles using natural language processing: a case study on pregnancy health and postpartum depression." *Frontiers in Psychiatry* 14 (2023): 1258887. [link](https://doi.org/10.3389/fpsyt.2023.1258887)


Contact: Braja Gopal Patra (brajagopal[dot]cse[at]gmail[dot]com) or Zhaoyi Sun (zhs4003[at]med[dot]cornell[dot]edu)
