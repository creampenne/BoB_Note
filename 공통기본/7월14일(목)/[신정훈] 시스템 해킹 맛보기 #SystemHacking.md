# [신정훈] 시스템 해킹 맛보기 #SystemHacking
**07/14/2022**  

## Buffer overflow
- 적절하지 않은 메모리 공간 검증 또는 검증 누락으로 인해 공격자가 훨씬 더 긴 메모리 영역에 접근하거나 덮어쓸 수 있는 취약점
- 주로 할당된 메모리 구역(region)에 따라 Heap base, Stack based로 분류

## Buffer overflow - Stack Anary

## Buffer overflow - Heap based

## Integer overflow
- 해당 type이 표현할 수 있는 최대값을 overflow 하여 0또는 음수값을 가지게 하여 프로그램 비정상 작동 유발
  - MAX INT (2147483647) + 1?
    - -2147483648
  - MAX UNSIGNED INT(4294967295) + 1?
    - 0
  - size_t 표현할 수 있는 크기는?
  - unsigned long 표현할 수 있는 크기는? 리눅스 : 8바이트, 윈도우 : 4바이트

## Type Confusion

## Use after Free
