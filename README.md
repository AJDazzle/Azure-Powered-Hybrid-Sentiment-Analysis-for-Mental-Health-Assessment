# Azure-Powered-Hybrid-Sentiment-Analysis-for-Mental-Health-Assessment

📌 Overview



In today’s digital landscape, the expression of emotions has evolved beyond traditional text, incorporating emojis, sarcasm, and implicit cues that pose significant challenges for conventional sentiment analysis systems.

This project proposes a hybrid architecture leveraging Azure Sentiment Analysis and Azure Custom Text Classification to perform a two-layer sentiment and mental health assessment:

Primary Layer: Classifies user-submitted sentences into Positive, Neutral, or Negative categories using Azure Sentiment Analysis.

Secondary Layer: Sentences identified as Negative undergo deeper analysis with Azure Custom Text Classification to detect clinical sentiments related to mental health.

💡 Key Highlights:




Handles nuanced expressions including emojis and sarcastic phrases for improved accuracy.

Integrates a User Complaint Tracking System to identify recurring issues and provide technicians with previous responses for faster resolution.

Secure data storage ensures clinical referencing and long-term trend analysis.

Comparative analysis demonstrates superior accuracy and contextual understanding compared to existing models.

Supports early detection and mental health support, making it a valuable advancement in intelligent emotional computing and healthcare AI solutions.

📊 System Evaluation


Tables 1, 2, and 3 in our paper represent customized system performance scores generated from our architecture. These are proprietary results based on our experimental setup, and thus, no external references are applicable for them.

Table 4 presents comparative performance with existing models, supported by published works as follows:

| Model & Reference | Source | Reported Accuracy | Notes |
|-------------------|--------|-------------------|-------|
| **Logistic Regression** | Mawardi, V. C., & Darmaja, E. (2023). *Logistic Regression Method for Sentiment Analysis application on Google PlayStore*. International Journal of Application on Sciences Technology and Engineering, 1(1), 241–247. [DOI](https://doi.org/10.24912/ijaste.v1.i1.241-247) | **88%** | Used as baseline; our tool outperformed this score. |
| **BERT** | Bello A, Ng SC, Leung MF. (2023). *A BERT Framework to Sentiment Analysis of Tweets*. Sensors (Basel), 23(1), 506. [DOI](https://doi.org/10.3390/s23010506) | **92%** | Advanced transformer-based approach. |
| **RoBERTa** | Tan, K. L., Lee, C. P., & Lim, K. M. (2023). *A Survey of Sentiment Analysis: Approaches, Datasets, and Future Research*. Applied Sciences, 13(7), 4550. [DOI](https://doi.org/10.3390/app13074550) | **94%** | Highest among surveyed models before our approach. |


🏆 Why This Work Stands Out



Beyond Words: Decodes sarcasm, emojis, and implicit sentiment, which most existing models fail to address effectively.

Dual-Layer Intelligence: Combines general sentiment analysis with mental health-focused classification for deeper insights.

Practical Benefits: Integrated complaint tracking ensures real-world usability in healthcare and support systems.

Proven Superiority: Demonstrated improved accuracy over leading models including Logistic Regression, BERT, and RoBERTa.

🔍 References 

Mawardi, V. C., & Darmaja, E. (2023). Logistic Regression Method for Sentiment Analysis application on Google PlayStore. International Journal of Application on Sciences Technology and Engineering, 1(1), 241–247. https://doi.org/10.24912/ijaste.v1.i1.241-247

Bello A, Ng SC, Leung MF. (2023). A BERT Framework to Sentiment Analysis of Tweets. Sensors (Basel), 23(1), 506. https://doi.org/10.3390/s23010506

Tan, K. L., Lee, C. P., & Lim, K. M. (2023). A Survey of Sentiment Analysis: Approaches, Datasets, and Future Research. Applied Sciences, 13(7), 4550. https://doi.org/10.3390/app13074550

Note : Other references has been provided in the Paper
