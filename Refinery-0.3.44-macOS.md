# Refinery 0.3.44

- Microphone capture starts before the speech analyzer finishes preparing. The first audio is buffered, and the start sound and menu bar recording indicator appear when the mic begins capturing.
- Releasing Fn stops capture immediately, including during speech preparation. A short Apple system sound marks the stop before the result is ready.
- The recording icon appears first; the timer expands one second later while counting from the instant capture began.
- Onboarding opens with a plain explanation of Refinery and the setup steps. Repeated subtitles and extra shortcut controls have been removed.
- The onboarding preview runs without a second menu bar item or shortcut listener.
