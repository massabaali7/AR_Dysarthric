# Arabic Dysarthric Speech Recognition Using Adversarial and Signal-Based Augmentation

- Our goal is to build an Arabic dysarthric automatic speech recognition through a multi-stage augmentation approach. We first propose a signal-based approach to generate dysarthric Arabic speech from healthy Arabic speech by modifying its speed and tempo. We also propose a second stage Parallel Wave Generative adversarial model that is trained on an English real dysarthric dataset. We propose a fine-tuning and text-correction strategiesfor Arabic Conformer at different dysarthric speech severity levels.

- Step 1: Prepare the data 
- Step 2: Use rubberband to modify the speed and tempo of the healthy Arabic speech
- Step 3: Train Parallel Wav GAN model to mimic the fine-grained temporal features of dysarthric speech  
- Step 4: Build ASR model using MGB2 dataset 
- Step 5: Finetune the pre-trained model on our synthetic dysarthric dataset
- Step 6: Build text-correction module by employing a weighted Jaccard distance

- Go to this link to read the paper: https://arxiv.org/pdf/2306.04368.pdf
- Go to this link to download the dataset: https://mailaub-my.sharepoint.com/:u:/g/personal/mab87_mail_aub_edu/EXgc2xw1schBqW4KS6f8w9MB322YhGTuJGdEd52s17AiGg?e=uDjcpE
