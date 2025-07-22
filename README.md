# Video_subtitles_generator

## Auto-Subtitled-Video-Generator

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)


#### About this project
- This project is an automatic speech recognition application that takes a YouTube video link or a video file as input to generate a video with subtitles.
- You can also upload an audio file to generate a transcript as .txt, .vtt, .srt files.
- The application performs 2 tasks:
  - Detects the language, transcribes the input video in its original language.
  - Detects the language, translates it into English and then transcribes.
- Downloaded the video of the input link using [pytube](https://github.com/pytube/pytube).
- Generated a transcription of the video using the [OpenAI Whisper](https://openai.com/blog/whisper) model.
- Saved the transcriptions as .txt, .vtt and .srt files.
- Generated a subtitled version of the input video using [ffmpeg](https://github.com/FFmpeg).
- Displayed the original video and the subtitled video side by side.
- Built a multipage web app using [Streamlit](https://streamlit.io) and hosted on [HuggingFace Spaces](https://huggingface.co/spaces).
- You can download the generated .txt, .vtt, .srt files and the subtitled video.


![](auto-sub.gif)
