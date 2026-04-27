# ⚡ GPU & Low-Level ML

CUDA, performance optimization, and what's underneath the framework abstractions.

## CUDA Fundamentals

- **[NVIDIA — Even Easier Introduction to CUDA](https://developer.nvidia.com/blog/even-easier-introduction-cuda/)** — The actual best starting point if you've never written a CUDA kernel.
- **[CUDA Programming Guide](https://docs.nvidia.com/cuda/cuda-programming-guide/)** — Authoritative reference. Read after the intro, not before.

## Framework Internals

- **[PyTorch Internals (Edward Yang)](https://blog.ezyang.com/2019/05/pytorch-internals/)** — Long-form deep dive into PyTorch's architecture. Still the best single explanation.
- **[Ultrascale Playbook (HuggingFace)](https://huggingface.co/spaces/nanotron/ultrascale-playbook)** — Distributed training at scale; tensor/pipeline/data parallelism explained.

## Performance Engineering

- **[Optimizing C++ (Agner Fog)](https://www.agner.org/optimize/optimizing_cpp.pdf)** — Canonical reference for low-level performance tuning.
- **[uops.info](https://uops.info/)** — Instruction-level latency/throughput tables for x86 CPUs. For when you're writing assembly or reading hot loops.
- **[Protobuf Arenas](https://protobuf.dev/reference/cpp/arenas/)** — Memory allocation patterns for high-throughput systems.

## Build-It-Yourself

- **[tensor.h](https://github.com/apoorvnandan/tensor.h/)** — A tensor library implemented in C; great reading for understanding autograd from first principles.
