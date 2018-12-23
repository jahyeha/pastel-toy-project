
## KoNLPy 설치 (Windows)

<img src="https://github.com/jahyeha/pastel-toy-project/blob/master/2/logo.png" width="15%">

### 1. JDK 설치 (본인 pc의 운영체제 비트수에 맞게 e.g. 32비트/64비트)
  - jdk-11.0.1_windows-x64_bin.exe 설치 (최신버전/64비트용)
  - 설치 링크: https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html
  - (참고) OS 비트수 확인 방법: 내 pc 마우스 오른쪽 클릭> 속성> 컴퓨터 기본 정보에서 "시스템 종류" 부분 확인

### 2. JAVA_HOME 설정
  - 내 PC에서 마우스 오른쪽 클릭 후 "속성" 클릭
  - 화면 왼쪽에 "고급 시스템 설정"에서 "환경변수" 클릭
  - 시스템 변수에서 "JAVA_HOME" 클릭
  - "변수값"에 "C:\Program Files\Java\jdk-11.0.1" (JDK software가 설치된 위치) 추가

### 3. JPype1 (>=0.5.7) 설치
  - 설치 링크: https://www.lfd.uci.edu/~gohlke/pythonlibs/#jpype
  - 유의사항: OS의 비트수와 일치해야 함
    * e.g.) JPype1‑0.6.3‑cp27‑cp27m‑win_amd64.whl : 파이썬 버전 2.7 & OS 64비트
    * e.g.) JPype1‑0.6.3‑cp37‑cp37m‑win32.whl : 파이썬 버전 3.7 & OS 32비트

### 4. cmd 창에서 아래 실행 (Anaconda Prompt창)
  - 가상환경 접속 (activate pastel)
  - cd 명령어를 통해 JPype1이 설치된 위치로 이동 (만약 바탕화면에 설치됐다면, cd desktop)
  - pip install JPype1-0.6.3-cp36-cp36m-win_amd64.whl
  
  ```
  * Exmaple 
    >(base) C:\Users\Jahye Ha> activate pastel
    >(pastel) C:\Users\Jahye Ha>cd desktop
    >(pastel) C:\Users\Jahye Ha\Desktop>
    >(pastel) C:\Users\Jahye Ha\Desktop>pip install --upgrade pip
    >(pastel) C:\Users\Jahye Ha\Desktop>pip install JPype1-0.6.3-cp36-cp36m-win_amd64.whl
  ```

### 5. KoNLPy 설치
  ```
    >pip install konlpy
  ```
  
### 6. KoNLPy 작동 확인 

<img src="https://github.com/jahyeha/pastel-toy-project/blob/master/2/__.png" width="80%">
