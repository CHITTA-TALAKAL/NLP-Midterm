| Model | Params | Train Loss | Validation Loss | Val Perplexity | Val Bits/Char | Training Time (s) | Generated Text Quality | Notes |
|---|---:|---:|---:|---:|---:|---:|---|---|
| Bigram | 4,225 | 2.4570 | 2.4810 | 11.95 | 3.579 | 4.6 | Low | Matches the closed-form count bigram (2.486) |
| LSTM | 946,625 | 1.2567 | 1.4876 | 4.43 | 2.146 | 74.0 | High | Best loss; largest train–val gap |
| Transformer | 826,433 | 1.4401 | 1.6373 | 5.14 | 2.362 | 96.0 | Medium | Loss still falling at step 3,000 |

Device: cuda; 3000 steps, batch 64, context 128.
