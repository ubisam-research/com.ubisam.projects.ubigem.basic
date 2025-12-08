# com.ubisam.projects.ubigem.basic

1. 빌드
    0) BIN\ConfuseEx 폴더는 있어야함
    1) 탐색기에서 UbiSam.Sources.Revision.sln 실행
    2) UbiSam.KeyLock 빌드
    3) UbiCom.Net.Automata.SECS2 빌드
    4) UbiGEM.Net 빌드 -> BIN\Confused 폴더가 생성됨
    5) Confused 폴더 밑에 4개 화일을 Setup\BIN Data\UbiGEM\BIN 폴더에 복사
    6) Setup\UbiGEM 폴더 네 UbiGEM.sln 실행
    7) UbiGEM 빌드
    8) Setup\Setup Files\ 폴더 내 UbiGEM.msi를 압축함
    
2. 배포
    1) 현재는, 1) ~ 6) 실행하지 않고, com.ubisam.projects.ubigem.dist repository에 있는 UbiGEM_20211221.zip 화일을 고객에게 제공함

4. UbiCOM 빌더 & 배포
    0) UbiCOM은 제공된 소스로 빌더 & 배포 가능
    1) Setup\UbiCOM 폴더 네 UbiCOM.sln을 빌더

5. UbiGEM.PAC 소스 & 빌더는 구미에 추가 확인 필요

6. 장석주부장님을 통해 키락 1.0 생성