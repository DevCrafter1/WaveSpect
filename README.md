# WaveSpect

Real Dataset: To collect real data, we gathered audio data from YouTube. We searched for different playlists related to education, news, entertainment, and philosophy to collect authentic audio for our dataset. Typically, speech datasets consist of single-channel audio data sampled at 16kHz. However, since our data comes from various sources, the sampling rate of the audio ranges between 8kHz and 44kHz. To standardize the data, we used the Librosa library to resample all audio to 16kHz.

Synthetic Dataset: We generated synthetic audio samples using eight different TTS systems. Below, we introduce these models: Bark, xTTS2, ChatTTS, EmotiVoice, GPT-SoVITs, MeloTTS, OpenVoice, and Vall-X-E are the eight speech synthesis models, each with distinct characteristics, covering areas from natural language processing and emotional expression to voice transformation and the integration of music and speech. 
Bark is an advanced text-to-speech (TTS) model capable of generating natural, high-fidelity speech, supporting multilingual synthesis and emotional expression. 
xTTS2 is an extended version, focusing on providing higher speech generation quality and flexible voice style customization, suitable for personalized voice needs. 
ChatTTS is designed specifically for conversational systems and can generate natural conversational speech based on context and emotional shifts, making it ideal for intelligent assistants and customer service systems. 
EmotiVoice focuses on emotional expression and can generate emotionally rich speech, commonly used in emotional dialogues and multimedia content creation. 
GPT-SoVITs combines Generative Pretrained Transformers (GPT) with sound-variable intelligible transformations (SoVITs), primarily for voice conversion and advanced speech synthesis, suitable for music production and voice modification. 
MeloTTS integrates music with speech synthesis, capable of generating speech with musical elements, making it useful for music creation and entertainment content. 
OpenVoice, as an open TTS platform, provides a variety of voice models and configurations, emphasizing scalability and community contributions, making it ideal for developers and researchers. 
Vall-X-E, based on a large-scale pre-trained model, uses a transformer architecture to generate high-quality speech, excelling in speech naturalness and diversity, and is suitable for voice assistants, content generation, and language translation applications.

