##5585 거스름돈
https://www.acmicpc.net/problem/5585

### How to solve
1. 1000엔에서 입력받은 n을 빼서 n에 다시 저장 => 거슬러줘야하는 총 액수
2. arr에 잔돈을 큰 수부터 저장
3. arr[0]부터 n보다 작거나 같은지 검사
    * n보다 작거나 같다면, n을 arr로 나눈 몫을 cnt에 저장
    * n을 arr로 나눈 나머지를 다시 n에 저장
 