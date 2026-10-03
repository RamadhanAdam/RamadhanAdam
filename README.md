### Ramadhan Adam Zome

```
$ xxd -l 16 hello.exe
00000000: 4d5a 9000 0300 0000 0400 0000 ffff 0000  MZ..............
```

I'm a master's student in AI and Machine Learning at PAUSTI in Nairobi, and until January 2027 a special research
student in the Dependable Systems Laboratory at Hiroshima University. I work on malware detection that can tell when it
is looking at a family it has never seen, and I like knowing what a program looks like at the byte level.

**What I'm working on**

- **Open-world malware detection** (master's thesis). A byte-level encoder that reads Windows programs by their PE
  structure, pretrained without labels on SOREL-20M, with family prototypes that let it reject files it doesn't know.
  The code is private until the thesis is done.
- **[GraMa](https://github.com/RamadhanAdam/grama)**. Federated intrusion detection for in-vehicle networks, with a
  graph attention network over the ECUs, a Mamba model over time, and HDBSCAN on the server to keep poisoned clients out.

**Things I've built**

- [raw-pe](https://github.com/RamadhanAdam/raw-pe): a Win64 executable written byte by byte in NASM, no linker
- [sco-pe](https://github.com/RamadhanAdam/sco-pe): a PE parser in C, with bounds checks for malformed files
- [deepfake-rag](https://github.com/RamadhanAdam/deepfake-rag): an Xception deepfake detector that explains itself with retrieval ([demo](https://deepfake-rag.vercel.app))
- [phish-transformer](https://github.com/RamadhanAdam/phish-transformer): a 45K-parameter URL classifier behind a Chrome extension
- [ml_deployment_project](https://github.com/RamadhanAdam/ml_deployment_project): a FastAPI model on GKE with CI/CD, Postgres and Prometheus, Grafana and Loki
- [buildneural](https://github.com/RamadhanAdam/buildneural): neural networks from scratch, one lesson at a time

**Writing**

I write on [Medium](https://medium.com/@ramadhanzome4), mostly about PE internals, GPU hardware and how models learn.
Recent: [I Wrote a Windows PE File From Scratch, in Assembly](https://medium.com/@ramadhanzome4/i-wrote-a-windows-pe-file-from-scratch-in-assembly-d011cb0097cb) ·
[RWX Memory in Windows](https://medium.com/@ramadhanzome4/rwx-memory-in-windows-what-read-write-and-execute-really-mean-4897c49d3b76) ·
[GPU DRAM Architecture, Explained Simply](https://medium.com/genaitrail/gpu-dram-architecture-explained-simply-a4eb4c4d8dcb)

[ramadhanadam.github.io](https://ramadhanadam.github.io) · [Hugging Face](https://huggingface.co/RamadhanZome) · ramadhanzome4@gmail.com
