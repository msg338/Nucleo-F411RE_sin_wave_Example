# VERSION
STEdgeAI Core v9.0.0 (X-CUBE-AI v9.0.0) / Python version : 3.9.13 / Numpy version : 1.23.0 / TF version : 2.12.0 / ONNX version : 1.10.2 / ONNX RT version : 1.15.0

# Example

![image](https://github.com/user-attachments/assets/fbb78414-2fef-4118-ba61-dfec28a1d03c)
![image](https://github.com/user-attachments/assets/146f80df-4a3b-4a93-9427-03e20b37c1a0)

파이썬을 통해 3개의 Dense Layer 층를 사용하여 sin_wave model
y=sin(x) (x:입력, y: 예측)
x값 입력에 따라 -1~1사이의 y값을 예측할 수 있는 모델을 만들 수 있습니다.
이 sin_wave model을 사용하여 STM32MX에서 미드웨어 패키지에서 
X-CUBE-AI를 사용하여 sin_wave.tflite 모델을 불러와서
f411re 보드에 On Device할 수 있습니다.

# UART
![image](https://github.com/user-attachments/assets/acdfe4ae-4665-4f1a-a2bc-a7bf6a74e554)

# Midware Package
![image](https://github.com/user-attachments/assets/16bbdcf0-3b95-46ab-8201-f115b48989ad)

# CLK
![image](https://github.com/user-attachments/assets/de90ef0f-2e48-4dd7-99e1-dd4cc93d5606)

# Tera Term 출력

![image](https://github.com/user-attachments/assets/54b6ef14-4aa1-459e-9045-23626f9ab24b)

처음 시작은 모델의 번호 및 모델의 이름이 출력되며, 모델의 입출력 형태를 확인할 수 있습니다. (Reset 버튼을 눌러보세요.)
계산값과 예측값을 계산해 보니 오차률 2.8%로 나타납니다.

내가 만든 sin_wave examples Project를 zip파일로 첨부했습니다.
사용하실 경우 IDE에서 미드웨어 패키지 -> X-CUBE-AI 모델 업로드를 다시해주셔야 합니다. / 추가로 sin_wave.tflite 모델도 첨부했습니다.

# 자료사용 출처:
https://www.digikey.kr/en/maker/projects/tinyml-getting-started-with-stm32-x-cube-ai/f94e1c8bfc1e4b6291d0f672d780d2c0
https://gist.github.com/ShawnHymel/79237fe6aee5a3653c497d879f746c0c
