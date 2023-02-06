# Conda-Environments

## Pytorch 1.12.1 + ROCm 5.4 + Python 3.8
```
conda create -n pytorch1.12.1_rocm5.4_py3.8 python==3.8
```
```
conda activate pytorch1.12.1_rocm5.4_py3.8
```
```
pip3 install --no-cache-dir torch==1.12.1 torchvision==0.13.1 -f https://repo.radeon.com/rocm/manylinux/rocm-rel-5.4/
```

## Pytorch 1.12.1 + ROCm 5.4.1 + Python 3.7
```
conda create -n pytorch1.12.1_rocm5.4.1_py3.7 python==3.7
```
```
conda activate pytorch1.12.1_rocm5.4.1_py3.7
```
```
pip3 install --no-cache-dir torch==1.12.1 torchvision==0.13.1 -f https://repo.radeon.com/rocm/manylinux/rocm-rel-5.4.1/
```
## Pytorch 1.13.1 + ROCm 5.2 + Python 3.8
```
conda create -n torch1.13.1_rocm5.2 python==3.8
```
```
conda activate torch1.13.1_rocm5.2
```
```
pip3 install --no-cache-dir torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/rocm5.2
```
