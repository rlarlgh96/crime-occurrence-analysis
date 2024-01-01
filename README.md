# 범죄 발생 시간대 및 요일 분석

## 개요
일반적으로 사람들은 늦은 밤이나 새벽 시간이 범죄에 취약할 것이라는 통념이 있다. 이에 따라 범죄 발생에 취약한 시간대와 요일을 알아보고자 한다.

## 데이터 수집
* 공공데이터포털에서 경찰청이 제공하는 2019년 범죄 발생 시간대 및 요일 데이터를 사용했다.

## 데이터 전처리
* 이 프로젝트에서는 범죄 발생 시간 및 요일을 특정할 수 있는 세 가지 범죄 유형(강력범죄, 절도범죄, 폭력범죄)을 대상으로 분석을 진행했다.
* 데이터 셋에서 위 세 가지 범죄 유형에 대한 데이터를 추출하고, 이를 유형별로 합산했다.

## 분석 방법
* 전처리한 데이터를 사용해 시간대와 요일별 범죄 발생 횟수를 나타내는 그래프로 데이터를 시각화했다.
* 그래프를 바탕으로, 시간대와 요일별 범죄 발생 횟수 및 분포를 분석하여 결과를 도출했다. 

## 결과
첫째, 요일의 경우 세 가지 유형의 범죄의 경우 모두 토요일에 가장 많이 발생했다.하지만 다른 요일과 비교했을 때 발생횟수의 차이가 근소하여, 범죄 발생이 특정 요일과 관계있다고 보기 어려웠다.
둘째, 시간대의 경우 범죄 유형마다 다른 양상을 보였는데, 강력범죄와 폭력범죄의 경우 21시00분-23시59분에 가장 많이 발생했고, 절도범죄의 경우 15시00분-17시59분에 가장 많이 발생했다. 각 시간대별 발생횟수의 분포를 살펴보면 강력범죄와 폭력범죄의 경우 주로 유동인구가 없는 저녁이나 새벽 시간대에 발생했고, 절도범죄의 경우 주로 유동인구가 많은 아침이나 오후 시간대에 발생했다. 또, 강력범죄의 경우 03시00분-05시59분에 두번째로 많이 발생했는데, 이는 인적이 드문 시간대가 특히 강력범죄 발생에 취약하다 볼 수 있었다.
따라서, 범죄의 유형마다 다르겠지만 일반적으로 늦은 밤이나 새벽 시간이 범죄에 취약하다는 통념은 어느정도 일리 있는 사실이며, 범죄발생이 특정 요일과 관계되지 않았다.
