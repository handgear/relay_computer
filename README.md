# 4-Bit Relay Computer(processor)


폰노이만 구조를 따르고 있으며 데이터라인은 4비트, 주소라인은 8비트로 제작하였습니다.
7가지 연산이 가능한 ALU, 3개의 범용레지스터(A,B,C), 8비트 PC와 메모리주소 레지스터, 디코더 등 대부분이 릴레이로 만들어졌고 
일부 릴레이로 구현하기 어려운 부분은 반도체칩을 사용했습니다.(클락 생성을 위해 555 timer, MEMORY로 ROM-AT28C64B을 사용) 

datasheet 폴더의 파일들은 만드는데 들어가거나 참고한 부품의 datasheet 입니다(본 기기의 datasheet가 아님).


# Video link
CLCD에 문자열을 출력하는 영상
[![relay computer](https://raw.githubusercontent.com/handgear/relay_computer/master/readme%20video%20thumbnail.jpg)](https://youtu.be/8RUoAekYkRA "relay computer")
