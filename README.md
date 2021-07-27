# Tensorflow_image_training
참고: https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10/blob/master/translate/README_Korean.md#%EC%86%8C%EA%B0%9C
> Version  

  < tensorFlow-GPI 1.5에는 CUDA 9.0, cuDNN 7.0이 적합 >
1. TensorFlow-GPU 1.5 
2. CUDA Toolkit 9.0
3. cuDNN 7.0
4. Anaconda Python 3.6 

> OS   
 
 windows10 

### 필요한 프로그램 다운로드 

1. Download CUDA ToolKit v9.0 --> 환경변수 추가  
  C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin  
  C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\libnvvp  
  C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\extras\CUPTI\libx64
  
2. Download CUDNN v7.0 --> 환경변수 추가(자신의 경로에 맞게)  
  C:\cuda\bin
  
3. Donwload Anaconda Python 3.x version
   (나는 3.8을 다운로드 후, downgrade 해줌)
~~~
conda install python=3.6
~~~
  환경변수 추가 (자신의 경로에 맞게)  
  (C:\Users\PC)\anaconda3
  (C:\Users\PC)\anaconda3\Scripts
  (C:\Users\PC)\anaconda3\Library
  
4. Download tensorflow-GPU 1.5 (python 버전 맞춰서 진행) 
~~~
conda create -n tensorflow python=3.6
activate tensorflow
pip install --ignore-installed --upgrade tensorflow-gpu==1.5
~~~

