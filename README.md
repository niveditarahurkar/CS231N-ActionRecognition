# CS231N-GestureRecognition

This is a course Project for Stanford CS231n:Convolutional Neural Networks for Visual Recognition.
This project aims at evaluating different approaches for recognitizing gestures from videos. Since 3d convs are compute intensive, we decided to explore TSM. 

Dataset: We used UCf-101 dataset. https://arxiv.org/abs/1212.0402
For data preprocessing we used the docker container provided by https://github.com/yjxiong/temporal-segment-networks

For training we followed the TSM module codebase from https://arxiv.org/pdf/1811.08383.pdf and the code base from https://github.com/mit-han-lab/temporal-shift-module
