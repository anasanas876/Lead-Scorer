# Lead-Scorer
This repo contains a code for Qualifiying Leads Autonomously.

Project Description: This workflow qualifies incoming Leads Autonomously without calling LLM or any external API. It uses weights of Pre-Trained ML Models Trained on **lead X Education Dataset**. The original dataset contains more than 30 features but the model was trained only on 4 Features.
**Number of Visits
Time Spent on Page
Interaction
Contact**

These things are recorded via javascript code and then passed to model weights for scoring.
As these features are fundamental and same for any Sales Team, this workflow can be used by any sales team without being domain specific.

**Workflow:**
leads are recieved via Webhook.

Incoming Leads and their corresponding details are passed to Model weights for scoring after Normalization process done through the custom Python code.

Only Hot or High Potential Leads are saved in Google Sheets.

**How to Deploy?**

Make account on n8n.io.

download the My-Workflow.JSON file from the repo.

Import the File in n8n.


**You are Ready to Execute**
