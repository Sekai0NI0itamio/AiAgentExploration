# opencode-go farm — encrypted bot bundles

4 concurrent opencode-go bots (beam-free, hy4-flash-free, longcat-2.5-free,
iceman-contributor-free) each work in a virtual workspace with 4 years of
COMPLETE 4H/1H/15m bars for all 15 coins. Goal: $28 + $28/month -> $1,000,000 in
12 months with no losing month.

Every log/chat/bot file is AES-GCM encrypted with the `ENCRYPTION_KEY` secret
before it is pushed here. The plaintext never leaves the local machine.

Decrypt locally:
```
python farm/decrypt.py bundles/<ts>/<bot>__chat.jsonl.enc
```
