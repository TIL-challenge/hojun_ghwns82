# 백준 문제 풀이

https://www.acmicpc.net/problem/12728



## 알게된 사실

\[
(3 + \sqrt{5})^N \text{을} \ a + b \times \sqrt{5} \ \text{이라고 하면}
\]

\[
(3 - \sqrt{5})^N \text{은 켤레무리수이므로} \ a - b \times \sqrt{5} \text{가 된다.}
\]

우리가 구하고자 하는 값은

\[
(3 + \sqrt{5})^N \text{이고}
\]

이 값은 켤레무리수인 \( (3 - \sqrt{5})^N \) 의 N승을 더하면,

\[
(3 + \sqrt{5})^N + (3 - \sqrt{5})^N \text{이 되고 이 값을 a, b로 표현하면} \ 2a \text{가 된다.}
\]

이 때 \( (3 - \sqrt{5}) \) 은 \( \sqrt{5} \) 가 2.236… 이므로 1보다 작은 실수이고, 즉 \( (3 - \sqrt{5})^N \) 또한 1보다 작은 실수이다.

즉, \( (3 + \sqrt{5})^N \text{의 정수부는} \ 2a - 1 \text{이다.}
\]
