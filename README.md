# metafake
State-of-the-art framework for creating single-shot deepfakes by face swapping, face reenactment, face attribute editing, and face super resolution. Metafake is the first software framework that allows you to combine face swapping and face attribute editing simultaneously. Think of this as RefaceApp+FaceApp on steroids.

## Features
Numerous face swapping models that have been optimized and improved 
- [[SimSwap]](https://github.com/neuralchen/SimSwap)
- [[FaceShifter]](https://github.com/ocastan/FaceShifter)
- [[SberSwap]](https://github.com/ai-forever/sber-swap)
- [[MegaFS]](https://github.com/zyainfal/One-Shot-Face-Swapping-on-Megapixels)
- [[FaceSwapper]](https://github.com/liqi-casia/FaceSwapper)
- [[HifiFace]](https://github.com/mindslab-ai/hififace)
- [[FewShot]]()
- More models coming soon!

Supported attributes:
- Hair color
- Hair style
- Age
- More attributes coming soon!

Misc:
- Complete code re-wrtite. Shrunk code base by orders of magnitude, and made it readable. Elimination of dead code, and optimization of code in general.
- Created a new, user-friendly API for multiface swapping. 
- Added ability to process an entire folder of destination images/videos. 
- Added ability to swap with multiple-selected models in same program execution
- Removed temporaily writing images to disk. All image processing is performed in memory.
- Added config option to output intermediate images into a temporay folder
- Support for face upscaling models: [GFPGANCleanv1-NoCE-C2|GFPGANv1|GFPGANv1.3|GFPGANv1.4|RestoreFormer|GPEN-BFR-512]
- Optional replacement of mouth in face mask. 
- 

## Dependencies
- python 3.6+
- pytorch 1.9.0
- torchvision 0.10.0
- opencv-python==4.5.2.52
- pillow==8.0.1
- numpy
- imageio== 2.9.0
- moviepy
- insightface==0.2.1
- munch
- Ninja
- pytorch_lightning
- onnxruntime-gpu==1.8.0
- tqdm==4.51.0
- keras
- tensorflow-gpu
- mxnet
- scikit-image
- requests==2.18.4
- kornia==0.5.4
- dill
- wandb
- onnx==1.9.0

## Usage 

coming soon

## TODO

coming soon

## License

coming soon 
