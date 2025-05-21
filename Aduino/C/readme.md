# C 언어 6단계 학습 가이드

---

## ✅ 1단계: C 언어 기초 이해

- C 언어란?
  - 저수준 접근이 가능하면서도 이식성이 높은 고급 언어
- 개발 환경 예시
  | 플랫폼 | 컴파일러/IDE       |
  |--------|--------------------|
  | Windows| Code::Blocks, gcc  |
  | macOS  | gcc, VSCode        |
  | Linux  | gcc, Vim, VSCode   |
- 기본 구조
  ```c
  #include <stdio.h>

  int main() {
      printf("Hello, World!\n");
      return 0;
  }
