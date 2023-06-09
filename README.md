<p align='center'>
  <img src='https://github.com/prasunroy/openpose-pytorch/raw/master/assets/image_1.jpg' />
</p>

# OpenPose PyTorch
**OpenPose api wrapper in PyTorch.**

## 설치 방법
#### 사전 준비
Torch 를 깔아줍니다
```
pip3 install torch torchvision torchaudio
```


#### Option 1: pip을 통해 설치
```
pip install git+https://github.com/prasunroy/openpose-pytorch.git
```
#### Option 2: source를 통해 설치
```
git clone https://github.com/prasunroy/openpose-pytorch.git
cd openpose-pytorch
python setup.py install
```

## 실행 examples
프로젝트 root에서 아래 command를 차례대로 실행합니다.
```
cd examples
python image_demo.py //사진 example 생성
python video_demo.py //비디오 example 생성
```

## 결과
```
python image_demo.py
```
위 코드 실행시<br>

![image](https://github.com/Team-Lucky2022/openpose_pytorch/assets/74056843/9b2fe93d-de7c-44c1-bdaf-2bab69665a1d)

```
python video_demo.py
``` 
위 코드 실행시<br>
![image](https://github.com/Team-Lucky2022/openpose_pytorch/assets/74056843/698e3c58-b113-4760-9842-a3dd04850c63)

위와 같은 결과가 나오면 examples 실행 성공입니다.

## References
* [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)
* [PyTorch OpenPose](https://github.com/Hzzone/pytorch-openpose)
* https://github.com/Team-Lucky2022/openpose_pytorch

## License
* [OpenPose License](https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/LICENSE)
* [OpenPose PyTorch License](https://github.com/prasunroy/openpose-pytorch/blob/master/LICENSE)

<br />
<br />

