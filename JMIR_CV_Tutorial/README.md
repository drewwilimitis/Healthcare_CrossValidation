# Analytical Design and Results from CV Experiments
___

We are releasing this open-source code base alongside a manuscript we hope to publish soon that covers cross-validation and model evaluation methods while offering an applied demonstration using best cross-validation practices using the widely available MIMIC-III dataset. <br>

As we await manuscript review and our code base requires further polishing, we refer users to a list of sources at the bottom of our root directory.

First we apply two Python scripts from open-source github repos to avoid the time and frustration of obsessing over the vast and often incompregensible values found within the MIMIC-III csv files.

By using the ref directory files, we found expert validated ranges for feature values that we used to impute missing data via a cutoff or floor value for patients outside those range values.

