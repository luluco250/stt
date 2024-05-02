# stt: Simple speech-to-text Bash script using whisper.cpp

Just run it, press Q when done speaking and it'll be copied to your clipboard.

You can download models using the script in `models/`:

```sh
cd models
./download-ggml-model.sh base.en
```

Currently hardcoded to the base model, easy to change.
