# vdsr_pytorch_lms
VDSR PyTorch Implementation using LMS

## Requirement
`torch`
`torchvision`
`python-tk` (or `python3-tk`)

## Download dataset
DF2K dataset

## Usage
### use lms
```
$ python main.py --dataset DF2K --cuda --gpuids 0 1 2 3 --lms --upscale_factor 2 --crop_size 256 --batch_size 128 --test_batch_size 32
```

### no use lms
```
$ python main.py --dataset DF2K --cuda --gpuids 0 1 2 3 --upscale_factor 2 --crop_size 256 --batch_size 128 --test_batch_size 32
```
