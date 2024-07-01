<body>
    <h1>Fine-tuning SpeechT5 for Urdu TTS</h1>
    <p>This project focuses on fine-tuning the SpeechT5 model to generate male Urdu speech. Below are the detailed steps involved in the process.</p>
 <h2>Step 1: Dataset Collection</h2>
  <p>We collected a custom dataset consisting of 300 voice samples from male Urdu speakers. These samples were recorded in a controlled environment to ensure high-quality audio, which is crucial for training the TTS model effectively.</p>
 <h2>Step 2: Data Preprocessing</h2>
    <p>To prepare the dataset for the SpeechT5 model, we performed several preprocessing steps:</p>
    <ul>
        <li><strong>Normalization:</strong> The audio files were normalized to ensure consistent volume levels.</li>
        <li><strong>Trimming:</strong> Silence at the beginning and end of each audio file was trimmed to focus on the speech content.</li>
        <li><strong>Resampling:</strong> The audio files were resampled to 16kHz, the preferred sample rate for the SpeechT5 model.</li>
    </ul>
   <h2>Step 3: Transcription</h2>
    <p>Each audio sample was transcribed to create a corresponding text dataset. This transcription process was manual to ensure accuracy, capturing the exact spoken words in Urdu.</p>
    <h2>Step 4: Phonetization and Transliteration</h2>
    <p>To make the dataset compatible with the SpeechT5 model, the transcribed Urdu text needed to be phonetized and transliterated into English:</p>
    <ul
    <li><strong>Phonetization:</strong> The Urdu text was converted into its phonetic representation, breaking down words into individual sounds.</li>
    <li><strong>Transliteration:</strong> The phonetic Urdu text was transliterated into English using web scraping techniques to map Urdu phonemes to English characters.</li> </ul>
    <h2>Step 5: Fine-tuning the Model</h2>
    <p>We fine-tuned the SpeechT5 model using the processed dataset. The fine-tuning process involved the following steps:</p>
    <ul>
    <li><strong>Model Initialization:</strong> The pre-trained SpeechT5 model was initialized with the default parameters.</li>
    <li><strong>Training Setup:</strong> The dataset was split into training and validation sets to monitor the model's performance during training.</li>
    <li><strong>Fine-tuning:</strong> The model was trained for 32,000 steps, adjusting the weights to learn the nuances of Urdu speech.</li>
    </ul>
<h2>Step 6: Model Evaluation</h2>
<p>After fine-tuning, the model was evaluated to assess its performance. The evaluation metrics included:</p>
<ul>
<li><strong>Accuracy:</strong> The accuracy of the generated speech was measured against the original audio samples.</li>
<li><strong>Naturalness:</strong> Human evaluators rated the naturalness and clarity of the synthesized speech.</li>
</ul>
    

https://github.com/Hammad-Bangash/Urdu-Text-to-Speech-TTS-for-Male-Voice/assets/129145452/9a640156-62d2-45d2-b275-3e6eeae5c6fd


    <h2>Telegram Interface</h2>
    <p>We utilized a Telegram interface for model inference, making it easy to interact with the model and get real-time results.</p>
    <h2>Data Requests</h2>
    <p>Due to privacy and storage limitations, we won't be uploading the dataset audios and other files. If you are interested in accessing the dataset, please email us at <a href="mailto:hammadraza12304@gmail.com">hammadraza12304@gmail.com</a>.</p>
<h2>Microsoft SpeechT5 Model</h2>
    <p>For more information on the Microsoft SpeechT5 model, visit the official page: <a href="https://github.com/microsoft/SpeechT5">Microsoft SpeechT5</a>.</p>
</body>
