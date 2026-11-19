# AiAgentExploration — explorative AI-agent experimentation

An explorative experimentation with AI agents in encased environments: 4 concurrent Hermes free agents each work in a virtual workspace with 4 years of COMPLETE 4H/1H/15m bars for all 15 coins. Goal: $28 + $28/month -> $1,000,000 in 12 months with no losing month.

Every session artifact (agent script, chat log, notes) is AES-GCM encrypted with the `ENCRYPTION_KEY` secret before it is pushed here. Plaintext never leaves the local machine.

Decrypt locally:
```
python farm/decrypt.py sessions/<ts>/<agent>__chat.jsonl.enc
```
