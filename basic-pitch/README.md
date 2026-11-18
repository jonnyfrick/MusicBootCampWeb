# Basic Pitch model

`nmp.onnx` is the model of Spotify's Basic Pitch (https://github.com/spotify/basic-pitch,
`basic_pitch/saved_models/icassp_2022/nmp.onnx`), Copyright 2022 Spotify AB, licensed under the
Apache License 2.0 (`LICENSE`), unmodified. The web app loads it in a worker with onnxruntime-web
for the recognition with a learned model (see `NoteModelRecognizer`).
