# Audio Read

- `pyaudio` is somewhat poorly documented; could't figure out what `stream.read()` returned exactly
- `stream.read()` is a blocking operation... do I really need to use threading for this?
- `audiostream` seemed like a good audio recorind library that integrates with Kivy... until I found out it only supports Android/iOS

# Audio recording device

- tried to use my android device as the microphone with `WOMic`, and it didn't work (`micclient` fails to connect to BlueTooth)
