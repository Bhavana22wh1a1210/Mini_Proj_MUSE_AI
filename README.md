# Mini_Project

#Title : MUSE_AI: Transforming words into Melodies

**Mini_Proj_MUSE_AI** is an AI-based music generation system that transforms a text prompt into a full **melodic song** — including poetic lyrics, a piano-style background melody, and a realistic singing voice using TTS.



## 🚀 Features

- ✨ Text-to-lyrics generation using GPT-2
- 🎼 Piano-style background music generation using NumPy
- 🗣️ Singing voice generation using gTTS
- 🎧 Combines voice + melody into a final song
- 📊 Visualizes waveform like heartbeat lines (Matplotlib)


## 📁 Project Structure

Mini_Proj_MUSE_AI/

├── src/

│   ├── core.py           # All main functions

│   └── run.py            # Runs the entire pipeline

├── output/               # (Auto-created) for audio files

├── requirements.txt      # All Python dependencies

├── .gitignore            # Files to exclude

└── README.md             # Project overview (this file)



🛠️ Technologies Used
Python 3.10+

Transformers (HuggingFace GPT-2)

NumPy, SciPy

gTTS

Pydub

Matplotlib


📝 Future Improvements
🎤 Refining the Voice Quality
Improve the naturalness and clarity of the generated voice output.

🎙️ Voice as Input Option
Allow users to input their own voice to be combined with generated music.

🎸 Add Instrument Layers
Incorporate more instruments like Guitar, Violin, or Drums in the background.

🧠 Emotion-Aware Music Generation
Use emotion detection from lyrics to control melody mood (e.g., sad, happy, inspiring).



## 🎧 Sample Output

Listen to the generated song below:

<audio controls>
  <source src="https://github.com/Bhavana22wh1a1210/Mini_Proj_MUSE_AI/blob/main/audio_output.wav?raw=true" type="audio/wav">
  Your browser does not support the audio element.
</audio>

