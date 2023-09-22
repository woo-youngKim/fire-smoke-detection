# fire-smoke-detection
 fire and smoke detection using Detectron2(Mask R-CNN)

# Usage
## Virtual environment settings
`conda create -n detecron2 python==3.8 -y`

`conda activate detectron2`
 * This is a virtual environment construction step for developing the Detectron2 model and is not essential.

## Install pytorch
`conda install pytorch==1.10.2 torchvision==0.11.3 torchaudio cudatoolkit=11.3 -c pytorch -y`

## Install Detectron2
`python -m pip install detectron2 -f\ https://dl.fbaipublicfiles.com/detectron2/wheels/cu113/torch1.10/index.html`

## Install other options
`pip install opencv-python`
`pip install -U git+https://github.com/facebookresearch/fvcore.git`

## Reference
 - https://detectron2.readthedocsio/en/latest/tutorials/install.html
