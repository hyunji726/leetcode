# 🔑 Hash Map (해시 맵)

### 개념
- **Key-Value (키-값)** 쌍으로 데이터를 저장하는 자료구조입니다.
- 키(Key)를 통해 값(Value)에 접근하는 속도가 **$O(1)$**로 매우 빨라 데이터 탐색이나 빈도수 카운팅에 유용합니다.

### 언제 사용하나요?
- 데이터의 존재 여부를 빠르게 확인해야 할 때 (`containsKey()`)
- 각 요소의 빈도수(개수)를 세야 할 때 (`getOrDefault()`)
- 두 집합 간의 매핑이나 중복 제거가 필요할 때

### Java 유용한 메서드
- `map.put(key, value)` : 데이터 추가 / 수정
- `map.get(key)` : 데이터 조회
- `map.getOrDefault(key, defaultValue)` : 키가 존재하면 해당 값, 없으면 기본값 반환
- `map.containsKey(key)` : 해당 키가 존재하는지 확인 ($O(1)$)
- `map.keySet()` : 모든 키를 순회할 때 사용
