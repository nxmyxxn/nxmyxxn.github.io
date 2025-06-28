
설치 오류

관련 파일 다 지우고 재설치하는데 지울 게 많음
https://velog.io/@ka0ka0ka/Oracle-%EC%99%84%EC%A0%84-%EC%82%AD%EC%A0%9C-%ED%9B%84-%EC%9E%AC-%EC%84%A4%EC%B9%98-%ED%95%98%EA%B8%B0 



윈도우+r -> regedit 접속
레지스트리에 접속해서 oracle 관련된 것 삭제
1) HKEY_CLASSES_ROOT -> ora _로 시작하는 레지스트리 삭제  
2) HKEY_LOCAL_MACHINE\SOFTWARE -> oracle 폴더 삭제  
3) HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node -> Ora_ 삭제  
4) HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services -> ora* 로 시작하는 폴더 삭제

oracle 설치 폴더 삭제
C:\app  
C:\Oracle or ORACLE_BASE  
C:\Program Files\Oracle C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Oracle - OraDB19Home1

![[Pasted image 20250524110909.png]]

![[Screenshot 2025-05-24 110219.png]]

![[Pasted image 20250524151910.png]]

설치 오래걸림
![[Pasted image 20250524111743.png]]


![[Pasted image 20250524113129.png]]

![[Pasted image 20250524114421.png]]


안되서 환경변수 설정까지 해보고 하는데 bin이 없어서 이건 잘못됐다 싶어 또 다시 다ㅏㅏㅏ 삭제 후 재설치
하.. 아까보다 더 오래걸렸는데 아무것도 안하고 설치 완료하자마자 connection 성공
![[Pasted image 20250524155023.png]]


![[Pasted image 20250524161417.png]]


하아 ㅋㅋㅋㅋ 이번엔 이클립스가 안열려 ㅋㅋㅋㅋ
eclipse.ini 파일에서 jdk 경로 추가해주고 실행하니 됨
1.8 버전이 왜 갑자기 깔려서 그걸로 열고있었음

#### Registry
Window Registry는 window os 자체의 설정과 선택 항목을 담고 있는 데이터베이스, 모든 hardware, os software, 사용자 pc 선호 등에 대한 정보와 설정값이 들어있음.