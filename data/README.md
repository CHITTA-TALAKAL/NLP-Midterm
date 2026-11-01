# Dataset

**Tiny Shakespeare**: about 1.1 million characters from Shakespeare's plays (public domain), 65 unique characters. It was collected by Andrej Karpathy for the char-rnn project.

The notebook downloads it automatically to `data/input.txt` on the first run. To download it manually:

```bash
curl -o data/input.txt https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt
```

The first 90% of the characters are used for training and the last 10% for validation.
