```markdown
# GitHub 사용법 1차시 교육 자료

## 1. 교육 개요
- **주제**: GitHub 기초 사용법 이해
- **대상**: Git 및 GitHub 입문자
- **목표**
  - Git과 GitHub의 개념 이해
  - 저장소(Repository) 생성 및 관리
  - 기본적인 협업 흐름 이해

---

## 2. Git과 GitHub 개념

### 2.1 Git이란?
- 분산 버전 관리 시스템(Version Control System)
- 파일의 변경 이력을 관리
- 협업 시 코드 충돌 방지 및 이력 추적 가능

### 2.2 GitHub란?
- Git을 기반으로 한 **원격 저장소 서비스**
- 코드 공유 및 협업 플랫폼
- 주요 기능:
  - 코드 저장 및 버전 관리
  - 협업 (Pull Request, Issue)
  - 프로젝트 관리

---

## 3. GitHub 시작하기

### 3.1 회원가입 및 로그인
1. GitHub 홈페이지 접속
2. 회원가입(Sign up)
3. 이메일 인증 후 로그인

### 3.2 주요 화면 구성
- Repository: 프로젝트 저장소
- Issues: 작업/문제 관리
- Pull Requests: 코드 병합 요청
- Actions: 자동화 기능

---

## 4. Repository 생성하기

### 4.1 새 저장소 만들기
1. "New Repository" 클릭
2. 저장소 이름 입력
3. Public / Private 선택
4. README 파일 생성 체크
5. "Create Repository" 클릭

### 4.2 Repository 구성 요소
- README.md: 프로젝트 설명 문서
- .gitignore: 추적 제외 파일 설정
- License: 라이선스 설정

---

## 5. Git 기본 개념

### 5.1 작업 흐름
```

Working Directory → Staging Area → Repository

````

### 5.2 주요 용어
- **Clone**: 원격 저장소 복제
- **Commit**: 변경 사항 저장
- **Push**: 로컬 → 원격 업로드
- **Pull**: 원격 → 로컬 다운로드

---

## 6. 기본 명령어 실습

### 6.1 저장소 복제
```bash
git clone https://github.com/username/repository.git
````

### 6.2 파일 추가 및 커밋

```bash
git add .
git commit -m "첫 번째 커밋"
```

### 6.3 원격 저장소 업로드

```bash
git push origin main
```

---

## 7. 협업 기본 개념

### 7.1 Branch (브랜치)

* 독립적인 작업 공간
* 기능별 개발 가능

### 7.2 Pull Request

* 작업 내용을 병합 요청
* 코드 리뷰 및 협업 핵심 기능

---

## 8. 실습 과제

1. GitHub 계정 생성
2. Repository 생성
3. README.md 수정
4. Commit & Push 수행
5. 결과 공유

---

## 9. 정리

* Git은 버전 관리 도구
* GitHub는 협업 플랫폼
* 기본 흐름:

  ```
  수정 → add → commit → push
  ```
* 협업의 핵심: Branch & Pull Request

---

## 10. 다음 차시 예고

* Branch 전략
* Pull Request 실습
* 협업 프로젝트 진행

---

```
```
