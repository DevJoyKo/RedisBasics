# RedisBasics
<hr>

### 1. Redis Structure

- KEY-VALUE 형식
- KEY의 설계! 가 중요

### 2. Redis Anti-pattern / Cautions
1) Key 길이가 크면 메모리, 연산 비효율 증가. 1K(1024) 넘지 않도록
2) 길 수 밖에 없다면, hashing 사용. (SHA1, SHA256 등)
3) 키의 최대 사이즈는 512MB
4) 키의 길이가 줄어들면 도움이 되지만, 의미를 명확하게 하는 것이 더 중요.
5) 클러스터 분산처리 기준: Key. 따라서 고른 분산을 위해서 설계방식 일관성 있게 유지해야 한다.  





