# A Unified Framework for Real-Time Concatenation-Driven Convolution

Supplementary materials for *A Unified Framework for Real-Time Concatenation-Driven Convolution*, submitted to DAFx26.

## Overview

The Concatenation-Driven Convolution (CDC) framework unifies concatenative synthesis and real-time convolution into a single audio processing architecture. A corpus of audio segments is organized via a self-organizing map (SOM) and navigated through user gestures, generating continuously evolving impulse responses that are injected directly into a partitioned convolution engine with frequency-domain kernel interpolation.

![Architecture](https://github.com/user-attachments/assets/a6cbd7dd-b553-4f40-899f-cff6af819246)

<img width="3067" height="1745" alt="GUI" src="https://github.com/user-attachments/assets/db03e847-f540-4d06-9e28-799173fb993b" />

&nbsp;

> For the best viewing and listening experience, visit the [supplementary materials page](https://concatenationdrivenconvolution.github.io/concatenation-driven-convolution/).

## Demo

Live exploration of several corpora with guitar input, showing real-time SOM navigation and continuous IR morphing.

[![Demo Video](https://img.youtube.com/vi/H5r1GEx5O_I/maxresdefault.jpg)](https://www.youtube.com/watch?v=H5r1GEx5O_I)

## Audio Examples

Each input source (piano, synth, snare) is convolved with five different corpora: measured impulse responses, water recordings, struck metals, vocal textures, and plastics. These demonstrate the range of the framework — from conventional reverb design to timbral processing and cross-synthesis.

### Piano

https://github.com/user-attachments/assets/f417fa48-bf74-4b44-8bcc-f1aa12fdefaf

https://github.com/user-attachments/assets/2f7b9339-5654-4465-86c8-d2c406d268e4

https://github.com/user-attachments/assets/0fa5d7f9-7b74-4db3-a31c-35e8e2a8cca3

https://github.com/user-attachments/assets/db35014d-eb08-4216-9c7d-453be02e89ea

https://github.com/user-attachments/assets/0b063694-c6e9-4761-a248-946abca29539

### Synth

https://github.com/user-attachments/assets/489d9450-d002-4a8a-82a7-8e332182e16a

https://github.com/user-attachments/assets/83739632-88aa-4916-860f-8f1ce7bc63ab

https://github.com/user-attachments/assets/cf9ff98d-6287-40bf-b2cc-cf822acf8e4e

https://github.com/user-attachments/assets/8a1d0eba-cc29-48ca-94f5-a6cea649689d

https://github.com/user-attachments/assets/f5f02bc5-1c5c-4cd9-9416-bb171edd75c7

### Snare

https://github.com/user-attachments/assets/fc789001-2fec-467f-8536-c543fe4f23be

https://github.com/user-attachments/assets/b8f3fddc-b324-4986-80c6-8f0965ac2c88

https://github.com/user-attachments/assets/0fc0b289-6813-46c3-94bd-e801d707534f

https://github.com/user-attachments/assets/d3a4b229-1c31-46af-8d74-e37f0bc17027

https://github.com/user-attachments/assets/f0afe392-6268-403f-8d93-0ae90869dd18

## Evaluation Data

The `tests/` directory contains raw CSV data and visualization plots from the comparative evaluation (CPU performance and RMS energy stability) described in the paper.
