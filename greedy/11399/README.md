## 11399 ATM

https://www.acmicpc.net/problem/11399

### How to solve
1. 결국엔 누적합을 구하는 문제
2. 오름차순으로 배열 정렬
3. 새로운 배열 ac_p를 만든 뒤 ac_p i-1 들어있는 값을 현재 P i 값과 더해서 ac_p[i]에 저장
4. 이걸 배열 끝(n)까지 반복
5. ac_p 배열 모든 인덱스마다 들어있는 값의 합계를 출력