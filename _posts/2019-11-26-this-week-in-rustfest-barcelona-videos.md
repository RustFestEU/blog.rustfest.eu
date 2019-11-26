---
layout: post
title: "This Week in RustFest - Video releases"
description: "Lessons learned from the streaming and the recordings."
socialImageSrc: "/assets/posts/barcelona/video-releases.png"
authors:
  - dns2utf8
  - badboy
---

## RustFest Barcelona recordings available!

We are happy to announce that the first talk recordings of RustFest Barcelona are available today!
We will release the recordings of all talks over the next couple of days.

TODO: insert iframe with playlist

## Lightning talks & workshop material

This year we used one of the workshop slots for a round of lightning talks.
On Sunday afternoon we had a total of 13 different short talks in front of a filled room,
with topics such as Rust RFCs, code discussions, interesting crates and making music using Rust.

You can find the list of topics and the discussed projects [on the workshop detail page](https://barcelona.rustfest.eu/sessions/bring-your-topic).
We also added links to the material for other workshops where we have it available. Check out the [list of all workshops](https://barcelona.rustfest.eu/workshops/).

## Lessons learned

### The microphones

We had stick and headset microphones.
They are of good quality but not perfect, so there is always some background noise.

Headset microphones have a very prominent side effect with beards: rustling

Stick microphones have two challenges:

1. People making tap noises when switching hands, especially if they wear a ring.
2. The speakers have to hold the microphone at a good distance, making adjustments in volume necessary in some cases.

To combat the rustling, clicking as well as the noise the sound system has a noise suppression function.
The resulting sound was something like this:

![Audio cut offs](/assets/posts/barcelona/video-releases-audio-cut-offs.png)

The noise was gone but the total silence between very little pause and sentence was perfect for the people in the auditorium.
However, it made it really hard to listen to the talks as a recording or stream.


### Fixing the sound

After some thinking Stefan had an idea: What if we added natural noise?

The first noise sample was recorded in a room filled with people holding their breath for five seconds.

TODO: explain the process some more

### The stream

This year we streamed directly from the auditorium to youtube.

We tested the whole setup on Saturday before the talks.

On Sunday we had a small addition:

* One speaker ([Niklas Reppel - Amp Up Web Audio Applications with Rust and WebAssembly](https://barcelona.rustfest.eu/sessions/amp-up-web-audio)) generated audio on stage to 3.5mm audio jack cable.

We tested the audio in the room but forgot to add the channel to the recording and the stream.

Lucky us, our awesome audience recorded the performance and we were able to reconstruct most of the performance.
