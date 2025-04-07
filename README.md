### Real Time Traffic Monitoring using Darknet ( YOLO ) 

![REALTIME_TRAFFIC_MONITORING](demo.gif)

#### SYSTEM REQUIREMENT
    1. Ubuntu 16.04
    2. NVIDIA 384
    3. CUDA 8
    4. Python 3
    5. OpenCV 3.4
    
#### SETUP & INSTALLATION [ CPU VERSION ]
   
    1. Make sure you have installed Python 3 and OpenCV 3.4
    
    2. Compile darknet source with gpu
            $./compile_cpu.sh

    3. Run(test) Realtime object detection with your webcam [ performance will be very low, try GPU setup for better performance ]
            $./run_cpu.sh


####            ( OR )

#### SETUP & INSTALLATION [ GPU VERSION ] 

    1. Make sure you have installed Python 3 and OpenCV 3.4

    2. Install suitable NVIDIA Driver for your GPU and CUDA ToolKit. 
       For my case it is Nvidia 384 and CUDA 8 [ which can be installed by executing the following script]
            $cd ./scripts
            $./install_nvidia_cuda_ubuntu16.04.sh
            $cd ..

    3. Compile darknet source with gpu
            $./compile_gpu.sh

    4. Run(test) Realtime object detection with your webcam
            $./run_gpu.sh

#### Things planned as part of this project

    1. Number of cars crossing a signal 
    2. Number of persons crossing a signal 
    3. Detect anomalies in traffic
    4. Planned to do various statistical information on live traffic [ Stay Tuned! ]


#### DATASET

1. Microsoft COCO



#### REFERENCE

    1. https://pjreddie.com/darknet/
    2. http://cocodataset.org/#home



