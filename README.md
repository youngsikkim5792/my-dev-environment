# My Development Environment

## 1. 프로젝트 목적
Windows 환경에서 개발에 필요한 도구를 설치하고 사용법을 익히기 위한 프로젝트입니다.

## 2. 개발 환경
- 운영체제: Windows 11 Pro
- 터미널: Windows PowerShell
- Linux 환경: WSL 2 / Ubuntu
- 버전 관리: Git
- 코드 편집기: Visual Studio Code
- 컨테이너 환경: Docker (설치 예정)

## 3. 진행 체크리스트
- [x] Git 설치
- [x] Git 사용자 이름 및 이메일 설정
- [x] GitHub 저장소 생성
- [x] VS Code 프로젝트 폴더 생성
- [x] 로컬 Git 저장소 초기화
- [x] GitHub 원격 저장소 연결
- [x] README.md 파일 생성
- [ ] WSL 2 정상 작동 확인
- [ ] Docker 설치 및 실행 확인
- [ ] Hello World 컨테이너 실행
- [ ] Ubuntu 컨테이너 실행
- [ ] Dockerfile로 NGINX 웹 서버 구성
- [ ] 포트 매핑 및 브라우저 접속 확인
- [ ] Bind Mount로 실시간 파일 변경 확인
- [ ] Docker Volume 데이터 유지 확인
- [ ] 문제 해결 사례 및 보안 점검 기록

## 4. 자주 사용하는 명령어

### Git
```powershell
git status
git add .
git commit -m "설명"
git push -u origin main
```

### WSL
```powershell
wsl -l -v
wsl --status
```

### Docker
```powershell
docker --version
docker run hello-world
docker ps
docker ps -a
```

## 5. 문제 해결 기록
문제가 발생하면 증상, 원인, 해결 방법을 기록합니다.

## 6. 보안 주의사항
- 비밀번호와 액세스 토큰을 파일에 저장하지 않습니다.
- API 키 및 개인 인증 정보를 GitHub에 올리지 않습니다.
- GitHub에 올리기 전에 개인정보가 포함되어 있지 않은지 확인합니다.
