# Learn Git - Git 학습용 리포지토리

## 프로젝트 개요
**Learn Git**은 Git 사용법을 배우기 위한 연습용 저장소입니다.
이 프로젝트는 Git의 기본 개념과 명령어를 익히고, 실습을 통해 Git을 활용하는 방법을 익히는 것을 목표로 합니다.

## 포함된 파일
- **`hello.py`**: Python `Hello, World!` 프로그램
- **`.gitignore`**: Git에서 제외할 파일 목록
- **`LICENSE`**: 프로젝트 라이선스 파일

## Git 기본 사용법
### 1. Git 저장소 복제
```bash
git clone <repository-url>
```

### 2. 변경 사항 추가 및 커밋
```bash
git add .
git commit -m "Commit message"
```

### 3. 원격 저장소로 푸시
```bash
git push origin main
```

## Git 병합 충돌 해결 방법
1. 충돌 발생 확인
    ```bash
    git status
    ```
2. 충돌된 파일을 열어 수동으로 수정
3. 수정 완료 후 변경 사항 저장
    ```bash
    git add <파일명>
    git commit -m "Resolve merge conflict"
    ```
4. 다시 푸시
    ```bash
    git push origin main
    ```

## 프로젝트 실행 방법
1. **Python 실행 환경 설정**
    ```bash
    python hello.py
    ```

## 기여 방법
1. 본 레포지토리를 포크합니다.
2. 새로운 브랜치를 생성합니다.
3. 변경 사항을 커밋하고 푸시합니다.
4. Pull Request를 생성하여 기여합니다.

## 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.

