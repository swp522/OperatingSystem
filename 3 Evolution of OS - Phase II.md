# Phase 2
## Summary 
- 트랜지스터가 발명되고 집적회로 기술이 발전하여 HW가 발전하기 시작함
- OS의 역할이 과거에는 비싼 진공관으로 만든 CPU가 idle하지 않게 만드는 것에서
  사람들의 생산성 향상으로 목표가 바뀜
- Hardware cheap, humans expensive

## Goal
- Make efficient use of people's time

## Phase 2-1 : intercative time-sharing OS
- Terminals were cheap
- Users interacted with the system again
 + 하나의 CPU와 그 CPU의 시간을 여러 USER들에게 쪼개서 나누어주는 것이 Phase 2 OS의 가장 큰 특징
    "Time Sharing OS" : PC와 USER가 Intercative 함

- Fancy filing systems added to OS
 + Private 정보를 사용자들이 PC에 저장가능하도록 사용자별 File의 소속을 규정하고 접근제어 가능

- Response time and protection became important  
 + Computer System이나 os를 평가하는 Metric이 변화하기 시작함
 + Barch monitor 시기에는 Throughput이 성능 척도 였으나
   Time sharing os 에서는 response time이나 user의 private data의 보호되는 정도가 더 중요해짐


### Terminal 
- 중앙의 computer와 연결되어 data를 I/O 할 수 있는 HW 장치
- ex) DEC VT-100
- 수많은 터미널들이 묶여서 TCU에 의해서 전산센터에 있는 서버 컴퓨터에 연결됨
