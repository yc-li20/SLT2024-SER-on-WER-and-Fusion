# SER-on-WER-and-Fusion
Bimodal fusion code for paper "Speech Emotion Recognition with ASR Transcripts: A Comprehensive Study on Word Error Rate and Fusion Techniques"

- The bimodal fusion techniques in our paper are all in ```fusions_bimodal.py```. Feel free to use it.
- The emotion recognition backbone model is simply a two-layer feed forward network. You can easily build it thus omitted here.
- The **ASR error correction** model is from ```https://github.com/yc-li20/Crossmodal_AEC```
- The **Modality-gated fusion** is adapted from ```https://arxiv.org/abs/2305.13583```
