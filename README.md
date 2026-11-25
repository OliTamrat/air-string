# Air Strings

A browser instrument: draw strings in the air with your hands and play them. One page, webcam only, no install, no server. The camera picture is processed on the device and never leaves it.

Live: https://olitamrat.github.io/air-string/

## Playing

- **Draw**: pinch thumb and index finger, drag, release. Up to 8 strings.
- **Pluck**: flick a fingertip quickly across a string. Sweep across several for a chord.
- **Stretch**: pinch a string and pull it sideways; the pitch rises. Let go and it snaps back.
- **Clear**: hold an open palm still for 2 seconds.
- **Touch or mouse**: drag in open space to draw, swipe across strings to pluck, press on a string and pull to stretch.

Songbook mode retunes to a song's notes, plays the melody once, then scores your pass over a bass and drum backing.

## Files

- `index.html`: the whole app.
- `vendor/tasks-vision/`: MediaPipe Tasks Vision 0.10.14 (Apache-2.0), served locally. The hand model itself is fetched from Google's model storage on first use.

## Status

Synthesis, gesture logic (with simulated hand landmarks), song mode, recording and touch input are tested in headless Chrome. Real-camera hand tracking and gesture thresholds still need tuning on real devices.
