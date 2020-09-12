<h1>11399 ATM</h1>
 
https://www.acmicpc.net/problem/11399

<h2>How to solve</h2>
<ol>
<li>결국엔 누적합을 구하는 문제</li>
<li>오름차순으로 배열 정렬</li>
<li>새로운 배열 ac_p를 만든 뒤 ac_p i-1 들어있는 값을 현재 P i 값과 더해서 ac_p[i]에 저장</li>
<li>이걸 배열 끝(n)까지 반복</li>
<li>ac_p 배열 모든 인덱스마다 들어있는 값의 합계를 출력</li>
</ol>