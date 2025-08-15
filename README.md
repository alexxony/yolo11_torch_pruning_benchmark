# yolo11_torch_pruning_benchmark
This is benchmark of torch pruning on yolo11s with fire_1 dataset

I Used Torch-pruning method on https://github.com/VainF/Torch-Pruning, and YOLO11 model on https://github.com/heyongxin233/YOLO-Pruning-RKNN.
Since Official YOLO reposit did not fit with Torch-pruning method,maybe some blocks don't exit on official one, I used heyongxin233's.
There are some errors such as export to different format, So I could not practice onnx-slim and performance on Orange pi which use RockchipNPU

For Solving the problem above, I applied other repo (https://github.com/laugh12321/ultralytics-prune). It can vary severl diffrent pruning method, type and so on. Also converting to other format is possible.


