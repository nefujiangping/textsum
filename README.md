# textsum
These codes are forked from [tensorflow-models](https://github.com/tensorflow/models/tree/master/research/textsum), with some modifications for my own use.
## Main modifications
- delete functions using GPU, instead deteminating the 'gpu_no' as a input parameter(--gpu_no)
- add input parameter 'batch_size'(--batch_size)
## Some tips
This repo is for python2, also, if you want to run it on python3, some modifications are necessary(see the comment in source code):
- function defination 'SnippetGen' in data.py line 175
- 'open(.,.)' function in data.py line 45
