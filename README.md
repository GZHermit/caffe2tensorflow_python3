# caffe2tensorflow_python3
The code is adapted to python3.x and the version of tensorflow >= 1.2

The address of the basic code is:https://github.com/ethereon/caffe-tensorflow

run this order to convert .caffemodel to .npy:
> python caffe2npy.py /path/to/deploy/prototxt --caffemodel /path/to/caffemodel --data-output-path /where/to/save/numpy/weights

run this order to convert .npy to .ckpt:
> python npy2ckpt.py --npy_path /path/to/npy_path --save_dir /where/to/save/ckpt/weights
