# Development Environment

## Local Development Machine

- Host OS: Windows
- Linux Environment: WSL2
- Distribution: Ubuntu 22.04.5 LTS
- Architecture: x86_64
- Python: 3.10.12
- Project Path: `/mnt/g/PROJECTS/adaptive-intelligent-mobility`

## GPU

- GPU: NVIDIA GeForce RTX 3060
- VRAM: 12 GB
- NVIDIA Driver: 610.43.02
- CUDA UMD Version: 13.3

## AI Framework

- PyTorch: 2.5.1+cu121
- PyTorch CUDA Runtime: 12.1

## GPU Verification

CUDA availability was verified using PyTorch.

A 4096 × 4096 matrix multiplication was successfully executed on the NVIDIA GPU.

Result:

- CUDA available: True
- GPU detected: NVIDIA GeForce RTX 3060
- VRAM detected: 12.0 GB
- GPU computation: SUCCESS
