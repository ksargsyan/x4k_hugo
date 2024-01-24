---
title: Density Estimation Framework for Model Error Assessment
authors: ["Khachik Sargsyan, Jason Bender, Habib Najm, Roger Ghanem"]
event: 13th US National Congress on Computational Mechanics
event_url: http://13.usnccm.org/
location: San Diego, CA
summary: Talk
abstract: "In this work we highlight the importance of model error assessment in physical<br>model calibration studies. Conventional calibration methods often assume the<br>model is perfect and account for data noise only. Consequently, the estimated<br>parameters typically have biased values that implicitly compensate for model<br>deficiencies. Moreover, improving the amount and the quality of data may not<br>improve the parameter estimates since the model discrepancy is not taken into account. <br>In state-of-the-art methods model discrepancy is explicitly accounted for<br>by enhancing the physical model with a synthetic statistical additive term,<br>which allows appropriate parameter estimates. However, these statistical<br>additive terms do not increase the predictive capability of the model in general<br>because they are tuned for particular output observables. Further, the arbitrary<br>use of standard additive statistical model error terms on model observables may<br>well violate physical constraints, unless particular care is taken to build in<br>requisite statistical structure to avoid this.<br>In order to address these challenges, we introduce a framework in which model<br>errors are captured by allowing variability in specific model components and<br>parameterizations for the purpose of achieving meaningful predictions that are<br>both consistent with the data spread, and can potentially disambiguate model and<br>data errors. To achieve this, select existing or proposed model parameters are<br>cast as random variables, representing model error, thereby casting the<br>calibration problem within a density estimation framework. When parameters of<br>the joint input density are difficult to estimate due to computational expense<br>or degeneracy of exact likelihoods, we employ Approximate Bayesian Computation<br>(ABC) to build prediction-constraining approximate likelihoods.  We demonstrate<br>the key strengths of the method on synthetic cases, as well as on two practical<br>applications of interest, from chemical kinetics and atmospheric transport<br>modeling.<br>"
date: "2015-07-29"
publishDate: "2015-07-29"
tags:  []
all_day:  false
featured:  false
math:  true
url_pdf: "files/talks/2015_07_usnccm.pdf"
loc: "$WW/repos/talk_dist/usnccm15/talk_merr"
---
