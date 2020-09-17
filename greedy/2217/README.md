##2217 로프
https://www.acmicpc.net/problem/2217

### How to solve
1. n개의 로프 입력받아 arr에 저장
2. arr 내림차순 정렬
3. arr 각 인덱스마다 arr[인덱스]*(인덱스+1) 저장
    * 만약 arr=[80,20,10] 이면 80하나만 쓰는게 최대 중량
    * 만약 arr=[80,70,10] 이면 80과 70을 사용해 140이 최대 중량
    * 만약 arr=[80,40,39] 이면 모두 사용해 117이 최대 중량
    * (결론) 모든 인덱스마다 최대 중량을 구해보는 게 답
4. arr 재정렬
5. 가장 큰 값 출력