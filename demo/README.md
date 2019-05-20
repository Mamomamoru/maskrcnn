# Mask R - CNN demonstration

## Install
- ### Get the source code of Mask R-CNN and set it up
```
# get source frmo git
cd ~/maskrcnn/demo
git clone https://github.com/matterportMask_RCNN.git

# get library
cd ~/maskrcnn/demo/Mask_RCNN
pip install -r requirements.txt

# run setup.py
cd ~/maskrcnn/demo/Mask_RCNN
run -i setup.py install
```

- ### Get and set up COCO API source code
```
# Get the source for COCO
cd ~/maskrcnn/demo/
git clone https://github.com/waleedka/coco.git

# Install the API for python
cd ~/maskrcnn/demo/coco/PythonAPI
run -i setup.py build_ext --inplace
run -i setup.py build_ext install
```

## Model Files
- mask_rcnn_coco.h5

## Directory Structure
```
.
├── LICENSE
├── README.md
├── demo
│   ├── README.md
│   ├── for_image.ipynb
│   └── for_video
│       ├── local_video.ipynb
│       ├── using_camera.ipynb
│       └── using_camera_at_colab.ipynb
├── maskrcnn.gif
└── presentation
    ├── __latexindent_temp.tex
    ├── figures
    │   ├── anchor.png
    │   ├── fast_rcnn1.png
    │   ├── fast_rcnn2.png
    │   ├── faster_rcnn.png
    │   ├── feature_map.png
    │   ├── framework.png
    │   ├── keypoint_coco.png
    │   ├── mask1.png
    │   ├── mask2.png
    │   ├── one_hot_mask.png
    │   ├── pool_vs_align.png
    │   ├── rcnn1.png
    │   ├── rcnn2.png
    │   ├── resluts_coco.png
    │   ├── roi_align.png
    │   └── roi_pool.png
    ├── mask.aux
    ├── mask.fdb_latexmk
    ├── mask.fls
    ├── mask.log
    ├── mask.nav
    ├── mask.pdf
    ├── mask.snm
    ├── mask.tex
    └── mask.toc

4 directories, 34 files
```
