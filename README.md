# UbiGEM 빌드 & 배포

---

## 1. UbiGEM 빌드 절차

> 사전 조건: `BIN\ConfuseEx` 폴더가 존재해야 합니다.

1. 탐색기에서 `UbiSam.Sources.Revision.sln` 실행
2. **`UbiSam.KeyLock` 빌드**
3. **`UbiCom.Net.Automata.SECS2` 빌드**
4. **`UbiSam.KeyLock` 빌드**<br>
   : 'UbiCom.Net.Automata.SECS2' 빌드 후, 난독화 과정을 거치므로
     'UbiGEM.Net' 빌드 전 반드시 'UbiSam.KeyLock'을 한번 더 빌드해야됨   
5. **`UbiGEM.Net` 빌드**
   - 빌드 완료 후 `BIN\Confused` 폴더가 생성됨
6. `BIN\Confused` 폴더 내 **4개 파일**을  
   `Setup\BIN Data\UbiGEM\BIN` 폴더로 복사
7. `Setup\UbiGEM` 폴더에서 `UbiGEM.sln` 실행
8. **`UbiGEM` 빌드**
9. `Setup\Setup Files\` 폴더 내 생성된 **`UbiGEM.msi`** 를 압축(zip)하여 배포용 패키지 생성

---

## 2. UbiGEM 배포 방식 (현재 운영 방식)

현재는 위의 **1) ~ 8) 빌드 과정을 수행하지 않고**,  
아래 ZIP 파일을 그대로 고객에게 제공하고 있습니다.

- Repository: `com.ubisam.projects.ubigem.dist`
- 배포 파일: **`UbiGEM_20211221.zip`**

---

## 3. UbiCOM 빌드 & 배포

1. **UbiCOM은 제공된 소스 기준으로 빌드 및 배포 가능**
2. `Setup\UbiCOM` 폴더에서 `UbiCOM.sln` 실행 후 빌드

---

## 4. UbiGEM.PAC

- **UbiGEM.PAC 소스 및 빌드 절차는 구미 쪽 추가 확인 필요**

---

## 5. KeyLock (키락) 생성

- **장석주 부장님을 통해 KeyLock 1.0 생성**
- UbiGEM / UbiGEM.PAC 판매 시, 키락 생성 및 발송 절차는  
  장석주 부장님을 통해 진행
