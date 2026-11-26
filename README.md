# Warq · ورق

Public home of **Warq**, a calm reader for the EPUB and PDF books you own.

- Website and privacy policy: https://ibaadnaeem.github.io/warq-site/ (`privacy.html`)
- Questions and bug reports: [Issues](https://github.com/ibaadnaeem/warq-site/issues)

This repository holds the website and the files the app downloads. It does not contain the app's source code.

## Natural voice download

The [`voice-v1` release](https://github.com/ibaadnaeem/warq-site/releases/tag/voice-v1) hosts `kitten-micro-en-v0_8.tar.bz2`, the offline voice Warq downloads when you turn on the natural voice. It is redistributed unchanged from the [sherpa-onnx project](https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models):

- The **KittenTTS** voice model is licensed under the Apache License 2.0 (the `LICENSE` file inside the archive). Upstream: https://github.com/KittenML/KittenTTS
- The bundled **espeak-ng-data** folder is part of [eSpeak NG](https://github.com/espeak-ng/espeak-ng), licensed under the GNU General Public License v3. Its source code is available at https://github.com/espeak-ng/espeak-ng.

SHA-256 of the archive: `85faaea7511ca9d1d2f251fed0a4553bdf0d1ee046102fa60ddd8046c751f76f`
