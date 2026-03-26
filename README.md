<h1 align="center">Bidirectional Reasoning Supervision for Multilingual Financial Decision Making</h1>
<h4 align="center">📄 Accepted at <strong>EMNLP 2025 (Industry Track)</strong></h4>

This work introduces a **bidirectional reasoning supervision** mechanism that leverages both *positive* and *negative rationales* to enhance financial decision-making across multiple languages. The method significantly improves interpretability, robustness, and cross-lingual generalization in financial NLP tasks.

🔗 **Paper**: https://aclanthology.org/2025.emnlp-industry.111/  
🔗 **Code**: https://github.com/muhammadrafsan/FinR-M


## Methodology
<h4 align="center"><img width="850" height="480" alt="image" src="https://github.com/user-attachments/assets/cdbe43eb-9dd8-4cf2-a7bd-60d8d5db7ece" /></h4>

**Figure:** Overview of three fine-tuning approaches: **(a)** Fine-tuning using Label, **(b)** Fine-tuning using Label + Unidirectional Reason, and **(c)** Fine-tuning using Label + Bidirectional Reason (Ours). The novel third approach enhances classification performance by supervising the model’s output with the classification label (Y), positive reason (R+), and negative reason (R−), providing a more comprehensive and context-aware training framework.

## Experimental Results
<h4 align="center"><img width="761" height="682" alt="image" src="https://github.com/user-attachments/assets/b54d9d92-85b7-4500-8783-3d820f35a956" /></h4>

## Citation

If you wish to cite this work, feel free to use this [BibTeX](http://www.bibtex.org/) reference:

```bibtex
@inproceedings{kabir2025bidirectional,
  title={Bidirectional Reasoning Supervision for Multilingual Financial Decision Making},
  author={Kabir, Muhammad Rafsan and Ahad, Jawad Ibn and Krambroeckers, Robin and Ahmed, Silvia and Elahi, MM Lutfe and Mohammed, Nabeel and Rahman, Shafin},
  booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing: Industry Track},
  pages={1576--1587},
  year={2025}
}
```
