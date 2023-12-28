# Predicting toxicity of molecules from [Tox21](https://tripod.nih.gov/tox/) dataset

## Comparison of different RobustMultitaskClassifier model parameters

| Test score  | Train score  | Layer sizes  |  Batch size |
|---|---|---|---|
|  0.676 |  0.965 |  [1000] |  100 |
| 0.694  |  0.937 |  [1000] |  512 |
|  0.70 |  0.896 |  [100] |  100 |