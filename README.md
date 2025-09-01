# DOM 퀴즈 정답 가이드

이 폴더는 DOM 조작과 관련된 다양한 퀴즈 문제들의 정답과 사용된 개념들을 정리한 것입니다.

## 📋 문제 목록

### 01. Basic Events (기본 이벤트)
- **사용된 개념**: `addEventListener`, `click` 이벤트
- **핵심 내용**: 버튼 클릭 시 텍스트 변경, 색상 변경
- **학습 포인트**: 이벤트 리스너 등록과 기본적인 DOM 조작

### 02. Mouse Events (마우스 이벤트)
- **사용된 개념**: `mouseenter`, `mouseleave`, `mousedown`, `mouseup`
- **핵심 내용**: 마우스 호버 효과, 드래그 시뮬레이션
- **학습 포인트**: 다양한 마우스 이벤트 처리

### 03. innerHTML vs textContent
- **사용된 개념**: `innerHTML`, `textContent` 속성
- **핵심 내용**: HTML 태그 포함 여부에 따른 텍스트 처리 차이
- **학습 포인트**: 두 속성의 차이점과 보안 고려사항

### 04. Keyboard Events (키보드 이벤트)
- **사용된 개념**: `keydown`, `keyup`, `keypress`
- **핵심 내용**: 키 입력 감지, 특정 키 조합 처리
- **학습 포인트**: 키보드 이벤트 처리와 키 코드 활용

### 05. Attribute Manipulation (속성 조작)
- **사용된 개념**: `getAttribute`, `setAttribute`, `removeAttribute`
- **핵심 내용**: HTML 속성 추가/수정/제거
- **학습 포인트**: DOM 요소의 속성 동적 변경

### 06. Style Manipulation (스타일 조작)
- **사용된 개념**: `style` 속성, CSS 속성 직접 조작
- **핵심 내용**: 인라인 스타일 변경, CSS 클래스 토글
- **학습 포인트**: JavaScript로 CSS 스타일 제어

### 07. Class Manipulation (클래스 조작)
- **사용된 개념**: `classList.add()`, `classList.remove()`, `classList.toggle()`
- **핵심 내용**: CSS 클래스 추가/제거/토글
- **학습 포인트**: 클래스 기반 스타일링과 상태 관리

### 08. Element Creation (요소 생성)
- **사용된 개념**: `document.createElement()`, `createTextNode()`
- **핵심 내용**: 새로운 DOM 요소 동적 생성
- **학습 포인트**: 요소 생성과 텍스트 노드 생성

### 09. Element Addition (요소 추가)
- **사용된 개념**: `appendChild()`, `insertBefore()`, `append()`
- **핵심 내용**: DOM에 새 요소 추가, 특정 위치에 삽입
- **학습 포인트**: 다양한 요소 추가 방법

### 10. Element Removal (요소 제거)
- **사용된 개념**: `removeChild()`, `remove()`, `parentNode`
- **핵심 내용**: DOM 요소 제거, 부모 노드 참조
- **학습 포인트**: 요소 제거와 부모-자식 관계

### 11. DOM Traversal (DOM 순회)
- **사용된 개념**: `parentNode`, `childNodes`, `nextSibling`, `previousSibling`
- **핵심 내용**: DOM 트리 구조 탐색
- **학습 포인트**: 노드 간 관계와 순회 방법

### 12. Form Validation (폼 검증)
- **사용된 개념**: `form` 요소, `input` 이벤트, 유효성 검사
- **핵심 내용**: 사용자 입력 검증, 에러 메시지 표시
- **학습 포인트**: 폼 데이터 처리와 사용자 경험

### 13. Local Storage (로컬 스토리지)
- **사용된 개념**: `localStorage.setItem()`, `localStorage.getItem()`
- **핵심 내용**: 브라우저에 데이터 저장/불러오기
- **학습 포인트**: 클라이언트 사이드 데이터 저장

### 14. Timer & Counter (타이머와 카운터)
- **사용된 개념**: `setInterval()`, `clearInterval()`, `setTimeout()`
- **핵심 내용**: 시간 기반 기능, 카운터 구현
- **학습 포인트**: 타이머 함수와 비동기 처리

### 15. Modal Popup (모달 팝업)
- **사용된 개념**: `display` 스타일, `z-index`, 이벤트 위임
- **핵심 내용**: 모달 창 표시/숨김, 배경 클릭 처리
- **학습 포인트**: 오버레이 UI와 사용자 인터랙션

### 16. Todo List (할 일 목록)
- **사용된 개념**: 배열 조작, 동적 요소 생성, 이벤트 위임
- **핵심 내용**: 할 일 추가/삭제/완료 처리
- **학습 포인트**: 복합적인 DOM 조작과 상태 관리

### 17. Carousel (캐러셀)
- **사용된 개념**: 인덱스 관리, 이미지 전환, 자동 재생
- **핵심 내용**: 이미지 슬라이드 쇼, 네비게이션 컨트롤
- **학습 포인트**: 복잡한 UI 컴포넌트 구현

### 18. Drag & Drop (드래그 앤 드롭)
- **사용된 개념**: `dragstart`, `dragover`, `drop` 이벤트
- **핵심 내용**: 요소 드래그, 드롭 영역 처리
- **학습 포인트**: HTML5 드래그 앤 드롭 API

## 🎯 학습 목표

이 퀴즈들을 통해 다음을 학습할 수 있습니다:

1. **DOM 조작의 기본**: 요소 선택, 생성, 수정, 제거
2. **이벤트 처리**: 다양한 사용자 인터랙션 처리
3. **상태 관리**: 애플리케이션 상태의 동적 변경
4. **사용자 경험**: 직관적이고 반응성 있는 UI 구현
5. **실전 개발**: 실제 웹 애플리케이션에서 사용되는 패턴들

## 📚 참고 자료

- [MDN Web Docs - DOM](https://developer.mozilla.org/ko/docs/Web/API/Document_Object_Model)
- [MDN Web Docs - 이벤트](https://developer.mozilla.org/ko/docs/Web/Events)
- [W3Schools - DOM Tutorial](https://www.w3schools.com/js/js_htmldom.asp)

## 💡 팁

- 각 문제를 풀기 전에 HTML 구조를 먼저 파악하세요
- 브라우저 개발자 도구의 Console을 활용하여 디버깅하세요
- 문제 해결 후 정답과 비교하여 더 나은 방법을 찾아보세요
- 실제 프로젝트에 적용할 수 있는 아이디어를 생각해보세요
