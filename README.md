<h1 align="center">Bidirectional Reasoning Supervision for Multilingual Financial Decision Making</h1>
<h4 align="center">📄 Accepted at <strong>EMNLP 2025 (Industry Track)</strong></h4>

This work introduces a **bidirectional reasoning supervision** mechanism that leverages both *positive* and *negative rationales* to enhance financial decision-making across multiple languages. The method significantly improves interpretability, robustness, and cross-lingual generalization in financial NLP tasks.

🔗 **Paper**: https://aclanthology.org/2025.emnlp-industry.111/  
🔗 **Code**: https://github.com/muhammadrafsan/FinR-M


## Methodology
<img width="1000" height="580" alt="image" src="https://github.com/user-attachments/assets/cdbe43eb-9dd8-4cf2-a7bd-60d8d5db7ece" />
**Figure:** Overview of three fine-tuning approaches: **(a)** Fine-tuning using Label, **(b)** Fine-tuning using Label + Unidirectional Reason, and **(c)** Fine-tuning using Label + Bidirectional Reason (Ours). The novel third approach enhances classification performance by supervising the model’s output with the classification label (Y), positive reason (R+), and negative reason (R−), providing a more comprehensive and context-aware training framework.
