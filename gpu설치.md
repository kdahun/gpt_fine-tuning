## cuda & cuDNN & tensorflow_gpu version 확인
![image](https://github.com/kdahun/gpt_fine-tuning/assets/101082485/70cf15ce-1754-4594-9dbe-1a765469aee1)

***
## CUDA, CuDNN 설치
CUDA : <https://developer.nvidia.com/cuda-toolkit-archive>

![image](https://github.com/kdahun/gpt_fine-tuning/assets/101082485/1465e3c6-7927-4b69-be31-44e8f079bd9f)
![image](https://github.com/kdahun/gpt_fine-tuning/assets/101082485/14ffc70e-cdcc-41ad-a2c2-c9c3d7623a22)
![image](https://github.com/kdahun/gpt_fine-tuning/assets/101082485/15f43d6f-8320-4c33-afc4-228a876dcfb4)

CuDNN : <https://developer.nvidia.com/rdp/cudnn-download>
CuDNN 압축을 풀고 안에 있는 파일을 CUDA에 복사 붙여넣기 하기

```
# tensorflow device 확인
from tensorflow.python.client import device_lib
device_lib.list_local_devices()
```

![image](https://github.com/kdahun/gpt_fine-tuning/assets/101082485/c5e22630-85f3-49f3-bb64-3b5940c0d97c)
이렇게 나오면 성공
