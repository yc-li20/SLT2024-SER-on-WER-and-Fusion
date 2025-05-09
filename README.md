# SER-on-WER-and-Fusion
Bimodal fusion code for paper "Speech Emotion Recognition with ASR Transcripts: A Comprehensive Study on Word Error Rate and Fusion Techniques"

- All bimodal fusion techniques are in ```fusions_bimodal.py```. You may modify ```main_text.py``` by loading your audio features and incorporating any fusion approach.
- The **ASR error correction** model is from [Crossmodal ASR Error Correction with Discrete Speech Units](https://github.com/yc-li20/Crossmodal_AEC)
- The **Modality-gated fusion** is adapted from [Cross-Attention is Not Enough: Incongruity-Aware Dynamic Hierarchical Fusion for Multimodal Affect Recognition](https://arxiv.org/abs/2305.13583)

You may kindly cite

```
@inproceedings{li2024speech,
  title={Speech emotion recognition with asr transcripts: A comprehensive study on word error rate and fusion techniques},
  author={Li, Yuanchao and Bell, Peter and Lai, Catherine},
  booktitle={2024 IEEE Spoken Language Technology Workshop (SLT)},
  pages={518--525},
  year={2024},
  organization={IEEE}
}
```
