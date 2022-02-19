+++
title = "An Algorithmic Framework for Fairness Elicitation"
date = 2020-10-30

[extra]
speaker = "Logan Stapleton"
+++

{{ image(image="participants.png") }}

# Abstract
We consider settings in which the right notion of fairness is not captured by simple mathematical definitions (such as equality of error rates across groups), but might be more complex and nuanced and thus require elicitation from a collection of stakeholders. We introduce a framework in which pairs of individuals can be identified as requiring (approximately) equal treatment under a learned model, or requiring ordered treatment such as “applicant Alice should be at least as likely to receive a loan as applicant Bob”. We provide a provably convergent and oracle efficient algorithm for learning the most accurate model subject to the elicited fairness constraints, and prove generalization bounds for both accuracy and fairness. This algorithm can also combine the elicited constraints with traditional statistical fairness notions, thus “correcting” or modifying the latter by the former. We report preliminary findings of a behavioral study of our framework using human-subject fairness constraints elicited on the COMPAS criminal recidivism dataset.

# About the speaker
Logan is a second-year PhD working with Profs. Zhiwei Steven Wu and Maria Gini.  His research interests are: 1) algorithmic fairness, including both theoretical ML and qualitative HCI research around fairness; and 2) algorithmic economics.
