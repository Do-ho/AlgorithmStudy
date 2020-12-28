# :fire: week12

## :ballot_box_with_check: 백준 11399

- 시간순으로 정렬하여 쉽게 풀 수 있었다.

## :ballot_box_with_check: 백준 17609

1. 우선 펠린드롬인지 확인한다.
   - 맞다면 0을 반환한다.
   - 아니라면 펠린드롬을 깨지게 만든 index를 반환하고 다음 단계로 넘어간다.
2. 왼쪽 단어(index)를 하나 삭제하여 펠린드롬인지 확인한다.
   - 맞다면 1을 반환한다.
   - 아니라면 다음 단계로 넘어간다.
3. 오른쪽 단어(length-index)를 하나 삭제하여 펠린드롬인지 확인한다.
   - 맞다면 1을 반환한다.
   - 아니라면 2를 반환한다.