오늘은 윈도우에서 WSL2로 리눅스 설치 및 윈도우 터미널 설치를 하였습니다.

우선 WSL2를 설치를 해야하는데 WSL2는 윈도우 10 기준으로 20H1, 20H2, 21H1 혹은 그 보다 높은버전에서 WSL2 를 사용할수있습니다.
버전을 확인하고 싶으시면 Windows + S 키를 입력하고 그 후 PC정보 를 검색해주시면 아래 화면과 같은 결과가 나옵니다.
![스크린샷(23)](https://github.com/user-attachments/assets/518c3171-d85f-4e96-97aa-592f0c917734)

PC정보를 실행해주면 정보가 나오게 됩니다.
(아래는 실행사진 예시)
![스크린샷(24)](https://github.com/user-attachments/assets/908beab7-b99a-4a30-bc63-6e81f0b079d8)

여기서 보셔야할껀 Windows 사양을 보셔야 합니다.
예시를 기준으로 Windwos 사양에 에디션 바로 아래에 버전이 있습니다.

이제 WLS2 설치로 넘어와서

Windwos + S 키를 입력하고 그 후 Windows Powershell 를 실행시켜줍시다.
그 다음 "wsl --install" 를 입력해서 우분투를 다운받아봅시다.
이제 아래 사진처럼 "시스템을 다시 시작하면 변경 사항이 적용됩니다." 라는 말이 나올텐데 나오면 이제 재시작해주면 됩니다.
![스크린샷(26)](https://github.com/user-attachments/assets/5c886e3a-81bc-4b9f-88d6-3bd009e745fd)

그 다음으로는
