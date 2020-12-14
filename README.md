# cheatsheet
cheatsheet code

Disable tensorflow GPU:
import os
os.environ["CUDA_VISIBLE_DEVICES"] = "-1"

Show username and GPU usage in commands:
ps -up `nvidia-smi |tee /dev/stderr |tail -n +16 | head -n -1 | sed 's/\s\s*/ /g' | cut -d' ' -f3`
or 
nvidia-smi

Image dataset zoo
https://github.com/deepinsight/insightface/wiki/Dataset-Zoo#ms1m-retinaface
