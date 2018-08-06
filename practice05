""" 문제 5-1
두값의 평균을 구하는 함수"""
def myaverage(a, b):
    average = (a + b)/2
    return average
""" 문제 5-2
 리스트 내에 있는 모든 정수 값에 대한 최댓값과 최솟값을 반환하는 함수"""
def get_max_min(data_list):
    Min = min(data_list)
    Max = max(data_list)
    return ( Min, Max)

""" 문제 5-3
 절대 경로를 입력받은 후 해당경로에 있는
 *.txt 파일의 목록을 파이썬 리스트로 반환하는 함수를 작성하세요."""
def get_txt_list(path):
    import os
    for x in os.listdir(path):
        if x.endswith('txt'):
            print(x)

"""문제 5-4
체질량 지수(BMI; Body Mass Index)는 인간의 비만도를 나타내는 지수로서 체중과 키의 관계로 아래의 수식을 통해 계산합니다.
여기서 중요한 점은 체중의 단위는 킬로그램(kg)이고 신장의 단위는 미터(m)라는 점입니다.

BMI=체중(kg)신장(m)2
일반적으로 BMI 값에 따라 다음과 같이 체형을 분류하고 있습니다.

BMI <18.5, 마른체형
18.5 <= BMI < 25.0, 표준
25.0 <= BMI < 30.0, 비만
BMI >= 30.0, 고도 비만
함수의 인자로 체중(kg)과 신장(cm)을 받은 후 BMI 값에 따라 ‘마른체형’, ‘표준’, ‘비만’, ‘고도 비만’ 중 하나를 출력하는 함수를 작성하세요."""
    
def cal_bmi(weight, height):
    bmi = weight/ (height**2)
    if bmi < 18.5:
        result = '마른체형'
    elif 18.5 <= bmi < 25:
        result = '표준'
    elif 25.0 <= bmi < 30.0:
        result = '비만'
    elif bmi >=30.0:
        result = '고도 비만'
    return (bmi, result)

