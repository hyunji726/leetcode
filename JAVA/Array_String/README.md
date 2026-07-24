# 🧩 Array & String (배열 및 문자열)

### 개념
- 모든 알고리즘 문제 해결의 기본이 되는 **연속된 데이터 구조(Array)**와 **문자열(String)** 관련 문제 모음입니다.
- 인덱스 접근, 문자열 조작, 슬라이싱, 회전 등 기본적인 구현 능력을 다룹니다.

### 주요 패턴 & 테크닉
- **인덱스 활용**: 임의 접근($O(1)$) 및 빈도수 배열 만들기 (예: 알파벳 개수 카운팅 `int[26]`)
- **String 조작**: Java의 String은 불변(Immutable) 객체이므로 수정이 많을 땐 `StringBuilder` 활용
- **투 포인터 / 슬라이딩 윈도우**: 문자열 내 부분 문자열(Substring) 탐색 시 활용

### Java 핵심 팁
- `str.charAt(i)` : 특정 인덱스의 문자에 접근
- `str.toCharArray()` : String을 `char[]` 배열로 변환
- `String.valueOf(charArray)` : `char[]`을 다시 String으로 변환
- `StringBuilder` 사용: `sb.append()`, `sb.reverse()`, `sb.toString()`
