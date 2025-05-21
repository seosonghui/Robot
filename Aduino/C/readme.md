# C 언어 6단계 학습 가이드

C 언어를 처음 접하는 사람도 체계적으로 익힐 수 있도록 6단계로 나누어 학습 내용을 정리했습니다.

---

## ✅ 1단계: C 언어 기초 이해

- C 언어란 무엇인가?
  - 고급 프로그래밍 언어이며 시스템/임베디드 개발에 적합
- 개발 환경 구축
  - Visual Studio Code, gcc, Code::Blocks, Replit 등
  - 예시 컴파일: `gcc hello.c -o hello`
- 기본 구조
  ```c
  #include <stdio.h>

  int main() {
      printf("Hello, World!\n");
