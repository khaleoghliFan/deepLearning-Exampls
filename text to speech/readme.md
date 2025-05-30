# Text-to-Speech Model Training with FastSpeech2
### Description:
Trained a custom text-to-speech (TTS) model using the FastSpeech2 architecture on the LJSpeech dataset. The model converts English text into natural-sounding human speech.

Technologies Used:
Python, Coqui TTS (v0.10.0), FastSpeech2, Mel Spectrograms, Google Colab, LJSpeech Dataset

### Highlights:

* Preprocessed over 13,000 voice samples using AudioProcessor

* Configured and fine-tuned FastSpeech2 hyperparameters (sampling rate, mel bins, batch size)

 * Trained and validated model using Coqui’s Trainer module with evaluation every few epochs

* Achieved high-quality speech synthesis output suitable for downstream TTS applications

* Output model saved and ready for deployment or further fine-tuning with vocoders like HiFi-GAN
