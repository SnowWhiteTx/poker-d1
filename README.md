# poker44-behavioral-detector

Behavioral chunk-level bot detector for Poker44 (SN126).

A miner for Bittensor subnet 126 (Poker44). Loads a trained detector from `models/current.joblib` and scores incoming hand-chunk payloads.

## Run
```
bash scripts/run.sh
```

## Model
Trained on released Poker44 benchmark data; weights in `models/current.joblib` (sha in `model_manifest.json`).
