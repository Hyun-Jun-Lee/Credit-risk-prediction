# Credit-risk

## 신용 위험 예측 모델 만들기

변수 설명

erson_age : 대출 당시 나이
person_income : 연간 소득
person_home_ownership : 주택 소융 유형 (RENT / MORTGAGE / OWN / OTHER)
person_emp_length : 일한 기간(연 단위)
loan_intent : 대출 목적 ( EDUCATION / MEDICAL / VENTURE / PERSONAL/ DEBTCONSOLIDATION)
loan_grade : 대출 등급 (A/B/C/D/E/F/G)
loan_amnt : 대출 총액
loan_int_rate : 이자율
loan_percent_income : 연소득과 대출금의 비율
cb_person_default_on_file : 과거 채무 불이행 여부
cb_person_gist_length : 첫 대출 받은 후 지난 기간(연 단위)
Target

- loan_stats : 0은 Non-default, 1은 default

<데이터 선택 이유>

코로나로 인한 갑작스런 소득 감소와 초저금리 상황으로 가계 대출이 증가했고 대출 만기 연장, 이자 지불 유예 등의 정부 정책으로 인해 신용 부도 위험이 커진 상황이다. 이러한 현 상황에서 직접 부도 위험을 예측해보고 어떤 정보가 가장 상관성이 높은지 알고싶어서 선택했다.

<분석 목표>

이 분석을 통해서 신용 부도 위험을 예측해보고 부도 가능성을 예측하는데 가장 효과적인 지표를 알아본다
