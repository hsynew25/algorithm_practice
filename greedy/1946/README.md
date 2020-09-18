## 1946 신입사원

https://www.acmicpc.net/problem/1946

### How to solve
1. 무슨 짓을 해도 시간초과가 남 => import sys 사용해서 해결(input()으로 입력받아 생긴 문제)
2. 다른 지원자보다 시험,면접 성적 모두 낮다 => 탈락
3. 시험성적 순으로 정렬
4. standard에 기준이 되는 인덱스의 면접성적 저장(arr[0][1])
5. standart보다 수가 작으면 cnt++, standard에 현재 인덱스의 면접성적 저장