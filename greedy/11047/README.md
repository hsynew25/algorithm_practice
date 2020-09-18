## 11047 동전 0

https://www.acmicpc.net/problem/11047

### How to solve

1. n개의 동전가치 arr입력받아 내림차순으로 정렬
2. k보다 크지않은 동전가치 중 가장 큰 것(arr[i])으로 k나눠서 몫을 cnt에 더함
3. k를 arr[i]로 나눈 나머지를 다시 k에 저장
4. k가 0이면 for문 중단
5. k가 0이 아니면 다시 반복하면서 0을 만듦