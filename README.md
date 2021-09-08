# 1. Feature Generation Model(Acoustic Model)
- FastPitch: Parallel Text-to-speech with Pitch Prediction[[paper](https://arxiv.org/abs/2006.06873)][[code](https://fastpitch.github.io/)]
- EATS: End-to-End Adversarial Text-to-Speech[[paper](https://arxiv.org/abs/2006.03575)][[code](https://deepmind.com/research/publications/End-to-End-Adversarial-Text-to-Speech)]
- Glow-TTS: A Generative Flow for Text-to-Speech via Monotonic Alignment Search[[paper](https://arxiv.org/abs/2005.11129)][[code](https://jaywalnut310.github.io/glow-tts-demo)]
- Flowtron: an Autoregressive Flow-based Generative Network for Text-to-Speech Synthesis[[paper](https://arxiv.org/abs/2005.05957)][[code](https://nv-adlr.github.io/Flowtron)]
- Tacotron2+DCA: Location-Relative Attention Mechanisms For Robust Long-Form Speech Synthesis [[paper]()][[code]()]
- GAN-TTS: High Fidelity Speech Synthesis with Adversarial Networks [[paper]()][[code]()]
- Multi-lingual Tacotron2: Learning to Speak Fluently in a Foreign Language: Multilingual Speech Synthesis and Cross-Language Voice Cloning[[paper]()][[code]()]
- MelNet: A Generative Model for Audio in the Frequency Domain[[paper]()][[code]()]
- ParaNet: Parallel Neural Text-to-Speech[[paper]()][[code]()]
- Transformer-TTS - Neural Speech Synthesis with Transformer Network[[paper]()][[code]()]
- Multi-speaker Tacotron2 - Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis[[paper]()][[code]()]
- Tacotron2+GST - Style Tokens: Unsupervised Style Modeling, Control and Transfer in End-to-End Speech Synthesis[[paper]()][[code]()]


## 1.1 Autoregressive Model
- Tacotron: Towards End-to-End Speech Synthesis[[paper]()][[code]()]
- Tacotron2: Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions[[paper]()][[code]()]


## 1.2 Non-Autoregressive Model
- FastSpeech: Fast, Robust and Controllable Text to Speech[[paper]()][[code]()]
- FastSpeech 2: Fast and High-Quality End-to-End Text to Speech[[paper](https://arxiv.org/abs/2006.04558)][code]



## 1.3 Alignment Study
- Monotonic Attention★: Online and Linear-Time Attention by Enforcing Monotonic Alignments (ICML 2017)
- Monotonic Chunkwise Attention★: Monotonic Chunkwise Attention (ICLR 2018)
- Forward Attention in Sequence-to-sequence Acoustic Modelling for Speech Synthesis (ICASSP 2018)
- RNN-T for TTS: Initial investigation of an encoder-decoder end-to-end TTS framework using marginalization of monotonic hard latent alignments (2019)
- Location-Relative Attention Mechanisms For Robust Long-Form Speech Synthesis (ICASSP 2020)
- Non-Attentive Tacotron: Robust and Controllable Neural TTS Synthesis Including Unsupervised Duration Modeling (under review ICLR 2021)
- EfficientTTS: EfficientTTS: An Efficient and High-Quality Text-to-Speech Architecture (2020-12)
- VAENAR-TTS: VAENAR-TTS: Variational Auto-Encoder based Non-AutoRegressive Text-to-Speech Synthesis (2021-07)

## 1.4 Data Efficiency
- Semi-Supervised Training for Improving Data Efficiency in End-to-End Speech Synthesis (2018)
- Almost Unsupervised Text to Speech and Automatic Speech Recognition (ICML 2019)
- Unsupervised Learning For Sequence-to-sequence Text-to-speech For Low-resource Languages (Interspeech 2020)
- Multilingual Speech Synthesis: One Model, Many Languages: Meta-learning for Multilingual Text-to-Speech (Interspeech 2020)
- Low-resource expressive text-to-speech using data augmentation (2020-11)
- DenoiSpeech: DenoiSpeech: Denoising Text to Speech with Frame-Level Noise Modeling (ICASSP 2021)


# 2. Vocoder Model
## 2.1 Autoregressive Model 
- WaveNet: WaveNet: A Generative Model for Raw Audio (2016)
- WaveRNN: Efficient Neural Audio Synthesis (ICML 2018)
- WaveGAN: Adversarial Audio Synthesis (ICLR 2019)
- LPCNet: LPCNet: Improving Neural Speech Synthesis Through Linear Prediction (ICASSP 2019)
- Towards achieving robust universal neural vocoding (Interspeech 2019)
- GAN-TTS: High Fidelity Speech Synthesis with Adversarial Networks (2019)
- MultiBand-WaveRNN: DurIAN: Duration Informed Attention Network For Multimodal Synthesis (2019)

## 2.2 Non-Autoregressive Model 

- MelGAN: Generative Adversarial Networks for Conditional Waveform Synthesis. NIPS 2019 [[paper](https://arxiv.org/abs/1910.06711)][[code]()]
- Parallel-WaveNet: Parallel WaveNet: Fast High-Fidelity Speech Synthesis (2017)
- Parallel WaveGAN: A fast waveform generation model based on generative adversarial networks with multi-resolution spectrogram. ICASSP 2020 [[paper](https://arxiv.org/abs/1910.11480)][[code]()]
- Parallel-WaveGAN (New): Parallel waveform synthesis based on generative adversarial networks with voicing-aware conditional discriminators (2020-10)
- Multi-band MelGAN: Faster Waveform Generation for High-Quality Text-to-Speech. Interspeech 2020 [[paper](https://arxiv.org/abs/2005.05106)][[code]()]


# 3. TTS towards Stylization
## 3.1 Expressive TTS
- ReferenceEncoder-Tacotron★: Towards End-to-End Prosody Transfer for Expressive Speech Synthesis with Tacotron (ICML 2018)
- GST-Tacotron★: Style Tokens: Unsupervised Style Modeling, Control and Transfer in End-to-End Speech Synthesis (ICML 2018)
- Predicting Expressive Speaking Style From Text In End-To-End Speech Synthesis (2018)
- GMVAE-Tacotron2★: Hierarchical Generative Modeling for Controllable Speech Synthesis (ICLR 2019)
- BERT-TTS: Towards Transfer Learning for End-to-End Speech Synthesis from Deep Pre-Trained Language Models (2019)
- (Multi-style Decouple): Multi-Reference Neural TTS Stylization with Adversarial Cycle Consistency (2019)
- (Multi-style Decouple): Multi-reference Tacotron by Intercross Training for Style Disentangling,Transfer and Control in Speech Synthesis (Interspeech 2019)
- Mellotron: Mellotron: Multispeaker expressive voice synthesis by conditioning on rhythm, pitch and global style tokens (2019)
- Flowtron (flow based): Flowtron: an Autoregressive Flow-based Generative Network for Text-to-Speech Synthesis (2020)
- (local style): Fully-hierarchical fine-grained prosody modeling for interpretable speech synthesis (ICASSP 2020)
- Controllable Neural Prosody Synthesis (Interspeech 2020)
- GraphSpeech: GraphSpeech: Syntax-Aware Graph Attention Network For Neural Speech Synthesis (2020-10)
- BERT-TTS: Improving Prosody Modelling with Cross-Utterance BERT Embeddings for End-to-end Speech Synthesis (2020-11)
- (Global Emotion Style Control): Controllable Emotion Transfer For End-to-End Speech Synthesis (2020-11)
- (Phone Level Style Control): Fine-grained Emotion Strength Transfer, Control and Prediction for Emotional Speech Synthesis (2020-11)
- (Phone Level Prosody Modelling): Mixture Density Network for Phone-Level Prosody Modelling in Speech Synthesis (ICASSP 2021)
- PeriodNet: PeriodNet: A non-autoregressive waveform generation model with a structure separating periodic and aperiodic components (ICASSP 2021)
- Towards Multi-Scale Style Control for Expressive Speech Synthesis (2021-04)
- Learning Robust Latent Representations for Controllable Speech Synthesis (2021-05)
- Diverse and Controllable Speech Synthesis with GMM-Based Phone-Level Prosody Modelling (2021-05)
- Improving Performance of Seen and Unseen Speech Style Transfer in End-to-end Neural TTS (2021-06)
- DeepRapper: DeepRapper: Neural Rap Generation with Rhyme and Rhythm Modeling (ACL 2021)


## 3.2 MultiSpeaker TTS
- Meta-Learning for TTS: Sample Efficient Adaptive Text-to-Speech (ICLR 2019)
- SV-Tacotron: Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis (NeurIPS 2018)
- Deep Voice 3: Scaling Text-to-Speech with Convolutional Sequence Learning (ICLR 2018)
- Zero-Shot Multi-Speaker Text-To-Speech with State-of-the-art Neural Speaker Embeddings (ICASSP 2020)
- MultiSpeech: MultiSpeech: Multi-Speaker Text to Speech with Transformer (2020)
- SC-WaveRNN: Speaker Conditional WaveRNN: Towards Universal Neural Vocoder for Unseen Speaker and Recording Conditions (Interspeech 2020)
- MultiSpeaker Dataset: AISHELL-3: A Multi-speaker Mandarin TTS Corpus and the Baselines (2020)
- Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis. NIPS,2018.
- INVESTIGATING ON INCORPORATING PRETRAINED AND LEARNABLE SPEAKER REPRESENTATIONS FOR MULTI-SPEAKER MULTI-STYLE TEXT-TO-SPEECH
- VOICE CLONING: A MULTI-SPEAKER TEXT-TO-SPEECH SYNTHESIS APPROACH BASED ON TRANSFER LEARNING
- ZERO-SHOT MULTI-SPEAKER TEXT-TO-SPEECH WITH STATE-OF-THE-ART NEURAL SPEAKER EMBEDDINGS

# 4 Adaptive TTS
- ADASPEECH: ADAPTIVE TEXT TO SPEECH FOR CUSTOM VOICE. ICLR 2021.
- BOFFIN TTS: FEW-SHOT SPEAKER ADAPTATION BY BAYESIAN OPTIMIZATION. 2020
- Attentron: Few-Shot Text-to-Speech Utilizing Attention-Based Variable-Length Embedding
- StrawNet: Self-TrainingWaveNet for TTS in Low-Data Regimes
- SAMPLE EFFICIENT ADAPTIVE TEXT-TO-SPEECH. ICLR 2019. 

# 5. Controllable TTS (Disentangled Representations)
- Style Tokens: Unsupervised Style Modeling, Control and Transfer in End-to-End Speech Synthesis
- (Conversational Speech Synthesis): Controllable Context-aware Conversational Speech Synthesis (Interspeech 2021)
- 

# 6. Grapheme-To-Phoneme
- 


# SDK Package
## Python SDK Package
- gTTS(Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate's text-to-speech API. [[link](https://pypi.org/project/gTTS/)]
- pyttsx3, Text to Speech (TTS) library for Python 2 and 3. Works without internet connection or delay. Supports multiple TTS engines, including Sapi5, nsss, and espeak.[[link](https://pypi.org/project/pyttsx3/)]
- win32com.client: Convert Text to Speech in Python using win32com.client [[link](https://www.geeksforgeeks.org/convert-text-speech-python-using-win32com-client/)]


# English Pre-trained Model
## pretrained feature generation model 
- Tacotron [donwload](https://drive.google.com/open?id=1lFfeyewyOsxaNO-DEWy9iSz6qB9ZS1UR)  
- Transformer [donwload](https://drive.google.com/open?id=1z8KSOWVBjK-_Ws4RxVN4NTx-Buy03-7c)  
- FastSpeech [donwload](https://drive.google.com/open?id=1P9I4qag8wAcJiTCPawt6WCKBqUfJFtFp)  


## pretrained vocoder model
- Parallel WaveGAN [donwload](https://drive.google.com/open?id=1Grn7X9wD35UcDJ5F7chwdTqTa4U7DeVB)  
- MelGAN [donwload](https://drive.google.com/open?id=1_a8faVA5OGCzIcJNw4blQYjfG4oA9VEt) 
- Multi-band MelGAN [donwload](https://drive.google.com/open?id=1rGG5y15uy4WZ-lJy8NPVTkmB_6VhC20V) 


# Chinese Pre-trained Model 
## pretrained feature generation model 
- Transformer [donwload](https://drive.google.com/open?id=1bTSygvonv5TS6-iuYsOIUWpN2atGnyhZ)  
- FastSpeech [donwload](https://drive.google.com/open?id=1T8thxkAxjGFPXPWPTcKLvHnd6lG0-82R)  


## pretrained vocoder model
- Parallel WaveGAN [donwload](https://drive.google.com/open?id=10M6H88jEUGbRWBmU1Ff2VaTmOAeL8CEy)  

# Dataset
- [Chinese Standard Mandarin Speech Copus](https://www.data-baker.com/open_source.html): Mandarin female speaker
- [LJSpeech0](https://keithito.com/LJ-Speech-Dataset/):  English female speaker  
- [VCTK](https://datashare.ed.ac.uk/handle/10283/2950): English multi-speaker
- [LibriTTS](https://arxiv.org/abs/1904.02882): English multi-speaker

# Demo
- Real-time TTS demo with ESPnet1 [Web Site](https://colab.research.google.com/github/espnet/notebook/blob/master/tts_realtime_demo.ipynb)
- Real-time TTS demo with ESPnet2 [Web Site](https://colab.research.google.com/github/espnet/notebook/blob/master/espnet2_tts_realtime_demo.ipynb)

# Reference
- https://github.com/seungwonpark/awesome-tts-samples
- https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers#Speaker-Verification
- https://github.com/xcmyz/speech-synthesis-paper



