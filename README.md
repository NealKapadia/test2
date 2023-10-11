
# Overview

This is a new curated subset of our OpenOrca data. This release provides an efficient means of reaching performance on-par with using larger slices of our data, while only including ~500k GPT-4 completions.

The key change in this dataset is that we've done an additional pass, using GPT-4 to remove answers which appear wrong based on the human annotations from the FLAN dataset.
This reduces the dataset size to only ~500k entries, allowing training to a similar quality level to our previous releases with 2/3 the compute requirement.


# Demo Models

* https://huggingface.co/openaccess-ai-collective/jackalope-7b
* https://huggingface.co/Open-Orca/Mistral-7B-SlimOrca