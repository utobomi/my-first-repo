# 과제 제출 저장소

## 1. 프로젝트 개요
이 프로젝트는 CLI, Docker, Git/GitHub의 기본 사용법을 실습하고,
Dockerfile을 작성하여 컨테이너 환경에서 애플리케이션을 실행한 뒤,
그 결과를 GitHub 저장소에 정리하는 것을 목표로 한다.

주요 목표는 다음과 같다.

- 터미널에서 기본 명령어 사용
- Docker 이미지 빌드 및 컨테이너 실행
- Dockerfile 작성
- 포트와 볼륨 개념 실습
- Git을 이용한 버전 관리
- GitHub 저장소를 통한 산출물 제출

## 2. 실행 환경

| 항목 | 내용 |
|---|---|
| OS | Microsoft Windows 11 Pro |
| 쉘/터미널 | PowerShell5.1 |
| Docker 버전 | Docker version 29.9.2 |
| Git 버전 | git version 2.56.0. |

## 3. 수행 항목 체크리스트

- [x] 터미널 기본 명령어 사용
- [] 권한 문제 확인
- [] Docker 버전 확인
- [] Dockerfile 작성
- [] 포트 매핑 실습
- [] 볼륨 마운트 실습
- [] Git commit 생성
- [] GitHub 저장소 push


## 4. 검증 방법 및 결과

| 검증 항목 | 사용 명령어 | 확인 내용 | 결과 위치 |
|---|---|---|---|
| OS 확인 | `uname -a` 또는 `systeminfo` | 운영체제 정보 확인 | [os-info.txt](./results/os-info.txt) |
| Docker 버전 확인 | `docker --version` | Docker 설치 및 버전 확인 | [docker-version.txt](./results/docker-version.txt) |
| Git 버전 확인 | `git --version` | Git 설치 및 버전 확인 | [git-version.txt](./results/git-version.txt) |
| Docker 이미지 빌드 | `docker build -t my-app .` | Dockerfile 기반 이미지 생성 확인 | [docker-build-result.txt](./results/docker-build-result.txt) |
| Docker 컨테이너 실행 | `docker run -p 8080:80 my-app` | 컨테이너 실행 및 포트 연결 확인 | [docker-run-result.txt](./results/docker-run-result.txt) |
| GitHub 업로드 | `git push origin main` | GitHub 저장소 반영 확인 | [git-push-result.txt](./results/git-push-result.txt) |

---

## 5. 트러블슈팅

### 문제 1. 여기에 문제 제목 작성

#### 문제
어떤 문제가 발생했는지 작성한다.

#### 원인 가설
문제의 원인으로 예상한 내용을 작성한다.

#### 확인
어떤 명령어 또는 방법으로 확인했는지 작성한다.

```bash
여기에 확인 명령어 작성
```

#### 해결/대안
문제를 어떻게 해결했는지 작성한다.

---

### 문제 2. 여기에 문제 제목 작성

#### 문제
어떤 문제가 발생했는지 작성한다.

#### 원인 가설
문제의 원인으로 예상한 내용을 작성한다.

#### 확인
어떤 명령어 또는 방법으로 확인했는지 작성한다.

```bash
여기에 확인 명령어 작성
```

#### 해결/대안
문제를 어떻게 해결했는지 작성한다.

---

## 6. 요약

이 저장소는 CLI, Docker, Git/GitHub 실습 과정을 정리한 과제 제출용 저장소이다.

README.md에는 프로젝트 개요, 실행 환경, 수행 항목, 검증 방법, 트러블슈팅을 정리했다.
검증 결과 파일은 `results/` 디렉터리에 저장했으며,
저장소 링크만으로 전체 산출물을 확인할 수 있도록 구성했다.
