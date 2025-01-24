STEdgeAI Core v9.0.0 (X-CUBE-AI v9.0.0)
Python version : 3.9.13
Numpy version : 1.23.0
TF version : 2.12.0
ONNX version : 1.10.2
ONNX RT version : 1.15.0

파이썬을 통해 3개의 Dense Layer를 사용하여 sin_wave model
y=sin(x)//x:입력, y: 예측
x값 입력에 따라 -1~1사이의 y값을 예측할 수 있는 모델을 만들 수 있습니다.
이 sin_wave model을 사용하여 STM32MX에서 미드웨어 패키지에서 
X-CUBE-AI를 사용하여 sin_wave.tflite 모델을 불러와서 
f411re 보드에 On Device할 수 있습니다.


자료사용 출처:
https://www.digikey.kr/en/maker/projects/tinyml-getting-started-with-stm32-x-cube-ai/f94e1c8bfc1e4b6291d0f672d780d2c0
https://gist.github.com/ShawnHymel/79237fe6aee5a3653c497d879f746c0c
