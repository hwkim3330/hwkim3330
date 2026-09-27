## 김현우 · Hyunwoo Kim

Researcher at **KETI** (Korea Electronics Technology Institute), Seoul.
By day I work on in-vehicle networking for software-defined vehicles — TSN / automotive Ethernet, embedded and FPGA-based network hardware, and robot platforms.
On my own time I build small, measured experiments in:

- **ML systems** — inference cost, distillation, quantization, decoding without generation
- **Neural rendering & world models** — interactive video world models on a single consumer GPU
- **Connectome-driven robotics** — running the FlyWire fruit-fly connectome as a controller, with controls that can show it failing
- **Embedded & automotive networking** — MCUs, CAN/serial protocols, OpenWrt, sensor bridges

I care about saying exactly what was measured: most of my READMEs have a "what did not work" section.

KETI(한국전자기술연구원) 연구원입니다. 업무로는 SDV 차량 내 네트워크(TSN·차량용 이더넷), 임베디드·FPGA 네트워크 장비, 로봇 플랫폼을 다룹니다.
개인적으로는 ML 시스템, 뉴럴 렌더링·월드 모델, 커넥톰 기반 로보틱스, 임베디드·차량 네트워킹을 작은 실험으로 직접 만들고 재 봅니다. 잰 것만 주장하고, 안 된 것도 같이 적습니다.

---

### Selected projects · 대표 프로젝트

| Project | What it is | Demo |
|---|---|---|
| [**flyworker**](https://github.com/hwkim3330/flyworker) | QA fuzzer for browser games: synthetic input, framebuffer-only observation, five deterministic bug rules, replayable HTML reports. One policy is the FlyWire connectome (138,639 neurons) — benchmarked against random baselines, and it loses. | [live](https://hwkim3330.github.io/flyworker/) · [HF Space](https://huggingface.co/spaces/kimhyunwoo/flyworker) |
| [**gta6-world**](https://github.com/hwkim3330/gta6-world) | Driving the Matrix-Game 2.0 world model from one game frame on one RTX 3090: 1-step LoRA distillation (2.08×), upscaling and frame interpolation, plus a list of speedups that turned out not to be real. | — |
| [**model-as-codec**](https://github.com/hwkim3330/model-as-codec) | How much does a shared generative model really save in transmission, and what does it lose? VAE video, EnCodec/DAC audio and MIDI measured against x264/Opus, with the model counted as cost. | — |
| [**pluto-re**](https://github.com/hwkim3330/pluto-re) | Reverse-engineering a binary-only StarCraft: BW AI: a 315M-parameter int8 model (unit transformer + spatial CNN + GRU core) reconstructed from Ghidra decompilation, plus its observation, action and fog-of-war behaviour. | — |
| [**seamcheck**](https://github.com/hwkim3330/seamcheck) | Vesuvius Challenge Open Problem #3: finds where a papyrus surface trace jumped to the wrong sheet, CPU-only, under a second per segment. | — |
| [**micro-x**](https://github.com/hwkim3330/micro-x) | Independently designed 14-servo small biped robot: original CAD, MuJoCo model, measured joint travel, balance and printability checks. Digitally verified; not yet built. | [3D viewer](https://hwkim3330.github.io/micro-x/web/) |

More · 그 밖에:
[nogeneration](https://github.com/hwkim3330/nogeneration) (decisions read from logits, no tokens generated) ·
[micro-cat-fly](https://github.com/hwkim3330/micro-cat-fly) (fixed connectome steering a goal-directed robot command, with controls) ·
[mujoco-unitree](https://github.com/hwkim3330/mujoco-unitree) ([demo](https://hwkim3330.github.io/mujoco-unitree/)) ·
[agilex-scout-mini](https://github.com/hwkim3330/agilex-scout-mini) (CAN/RS232 without the vendor SDK) ·
[openwrt#24707](https://github.com/openwrt/openwrt/pull/24707) (ipTIME A3004NS-M board port, in review) ·
[touchcast](https://github.com/hwkim3330/touchcast) ·
[dynamic-notch](https://github.com/hwkim3330/dynamic-notch) ·
[pincet](https://github.com/hwkim3330/pincet) ([demo](https://hwkim3330.github.io/pincet/)) ·
[serial-web](https://github.com/hwkim3330/serial-web)

---

### Tools · 기술

- **ML** — PyTorch, diffusion / video world models, LoRA distillation, quantization, ONNX / transformers.js, MLX
- **Systems & embedded** — C/C++, Python, Rust, ESP32, STM32, Infineon AURIX, Jetson, OpenWrt, CAN, Zephyr
- **Networking** — IEEE 802.1 TSN (Qbv, Qav, CB), automotive Ethernet
- **Robotics & sim** — MuJoCo (incl. WASM), ROS 2, CARLA, CAD for 3D printing
- **Web** — JavaScript/TypeScript, WebGPU, WebAssembly, Three.js
- **Reverse engineering** — Ghidra, binary and protocol analysis

---

### Links · 연락

[Email](mailto:hwkim3330@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/hwkims/) ·
[Hugging Face](https://huggingface.co/kimhyunwoo) ·
[Kaggle](https://www.kaggle.com/hwkims) ·
[Homepage](https://hwkim3330.github.io/) ·
[Tech blog](https://hwkim3330.github.io/blog/) ·
[Velog](https://velog.io/@hwkims/posts) ·
[Naver Blog](https://blog.naver.com/hwkims) ·
[GitHub @hwkims](https://github.com/hwkims)
