## 2178 미로탐색

https://www.acmicpc.net/problem/2178

### How to solve
1. "최소"를 보고 BFS로 결정
2. 개행문자 '\n'삭제 원할 시 strip() 사용
    * arr.append(list(map(int,input().strip())))