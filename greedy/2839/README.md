<h1>2839 설탕배달</h1>
 
https://www.acmicpc.net/problem/2839

<h2>How to solve</h2>
<ol>
<li>봉지를 최대한 적게 사용해야 하기 때문에 5kg 봉지를 먼저 선택
</li>
<li>cnt에 n을 5로 나눈 값을 저장<br>
n에서 5kg*cnt 뺀 값을 m에 저장
</li>
<li>남은 설탕 무게(m)가 3으로 나누어 떨어지지 않으면 cnt를 1씩 줄이고 m에 5씩 더하면서 3으로 나누어 떨어지는지 확인
<li>3으로 나누어 떨어지면 result에 cnt+(m//3)저장</li>
<li>cnt가 0이 되도 m이 3으로 나누어 떨어지지 않으면 result=-1</li> 
</li>
</ol>