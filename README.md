# Video_subtitles_generator

## Auto-Subtitled-Video-Generator

#### About this project
- This project is an automatic speech recognition application that takes a video file as input to generate a video with subtitles.
- You can also upload an audio file to generate a transcript as .txt, .vtt, .srt files.
- The application performs 2 tasks:
  - Detects the language, transcribes the input video in its original language.
  - Detects the language, translates it into English and then transcribes.
- Generated a transcription of the video using the [OpenAI Whisper](https://openai.com/blog/whisper) model.
- Saved the transcriptions as .txt, .vtt and .srt files.
- Generated a subtitled version of the input video using [ffmpeg](https://github.com/FFmpeg).
- Displayed the original video and the subtitled video side by side.
- Built a multipage web app using [Streamlit](https://streamlit.io) and hosted on [HuggingFace Spaces](https://huggingface.co/spaces).
- You can download the generated .txt, .vtt, .srt files and the subtitled video.

