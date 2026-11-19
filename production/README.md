# Narration production

All visible scripts and speech forms are in af-heart/scenes.json. Kokoro v1.0 ONNX, af_heart, speed 1.0, paragraph pauses of 0.65 seconds. Raw WAVs are local build products. Run the separately obtained record-demo tts.py against production/af-heart, then production/encode_audio.py. Model SHA-256 checks and licenses are preserved from the authorized template. Encoding uses mono AAC, 48 kHz, 160 kbps, -16 LUFS and -1.5 dB true-peak target. Ten continuous chapter listening tracks are also produced.

Run scripts/screen_narration.py for full independent transcription and additional small.en checks of flags plus chapter samples. Inspect discrepancies and phonemes, regenerate material errors, and retain the review hashes. Reports are in qa/. Automated transcript agreement and waveform checks are not human listening approval.
