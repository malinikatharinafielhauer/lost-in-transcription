# lost-in-transcription
Benchmarking ASR toolkits on challenging real-world speech — noise analysis, WER breakdown, and RTF comparison across Whisper and wav2vec 2.0.

# lost in transcription

Benchmarking ASR toolkits on challenging real-world speech — noise analysis, WER breakdown, 
and RTF comparison across Whisper and wav2vec 2.0.

## Overview

This project evaluates two state-of-the-art ASR systems on noisy, real-world speech data.
Beyond simple accuracy, we dig into *where* and *why* models fail — and how robust they 
are when conditions get tough.

## What's Inside

- **Transcription pipelines** for OpenAI Whisper and wav2vec 2.0 (HuggingFace)
- **Error analysis**: WER with substitution / insertion / deletion breakdown
- **Hyperparameter experiments**: temperature, beam size and their effect on accuracy
- **Performance profiling**: Real-Time Factor (RTF) and memory usage comparison
- **Noise robustness**: audio degradation experiments at varying SNR levels (e.g. 20 dB)

## Tech Stack

`Python` · `OpenAI Whisper` · `HuggingFace Transformers` · `jiwer` · `librosa` · `torchaudio`

## Results Snapshot

| Model | WER ↓ | RTF ↓ | Memory |
|---|---|---|---|
| Whisper (medium) | TBD | TBD | TBD |
| wav2vec 2.0 | TBD | TBD | TBD |

> Full results and analysis in the presentation (`presentation/`).

## Repo Structure
