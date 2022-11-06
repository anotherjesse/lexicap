# Lexicap: Lex Fridman Podcast Whisper captions

[https://karpathy.ai/lexicap/](https://karpathy.ai/lexicap/)

> These are transcripts for Lex Fridman episodes. First we get all the episodes in the [playlist](https://www.youtube.com/playlist?list=PLrAXtmErZgOdP_8GztsuKi9nrraNbKKp4) (ty youtubesearchpython), see their docs. 
> Then we download the audio for all of them (ty [yt-dlp](https://github.com/yt-dlp/yt-dlp))) `yt-dlp -x --audio-format mp3 -o {mp3_file} -- {youtube_video_id}`
> Then we transcribe them (ty [OpenAI Whisper](https://github.com/openai/whisper)): `whisper --language en --model large -o {out_dir} -- {mp3_file}`

The original files from Karpathy are checked into the `vtt` folder