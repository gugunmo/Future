오늘은 윈도우에서 WSL2로 리눅스 설치 및 윈도우 터미널 설치를 하였습니다.

우선 WSL2를 설치를 해야하는데 WSL2는 윈도우 10 기준으로 20H1, 20H2, 21H1 혹은 그 보다 높은버전에서 WSL2 를 사용할수있습니다.
버전을 확인하고 싶으시면 Windows + S 키를 입력하고 그 후 PC정보 를 검색해주시면 아래 화면과 같은 결과가 나옵니다.
![1](https://github.com/user-attachments/assets/89e6ca5f-60e6-442b-93ae-20d249c4c39e)


PC정보를 실행해주면 정보가 나오게 됩니다.
(아래는 실행사진 예시)
![2](https://github.com/user-attachments/assets/376be097-7e6f-4a56-81cf-45732010c941)


여기서 보셔야할껀 Windows 사양을 보셔야 합니다.
예시를 기준으로 Windwos 사양에 에디션 바로 아래에 버전이 있습니다.

이제 WLS2 설치로 넘어와서

Windwos + S 키를 입력하고 그 후 Windows Powershell 를 실행시켜줍시다.
그 다음 "wsl --install" 를 입력해서 우분투를 다운받아봅시다.
이제 아래 사진처럼 "시스템을 다시 시작하면 변경 사항이 적용됩니다." 라는 말이 나올텐데 나오면 
![3](https://github.com/user-attachments/assets/b3bfd276-e9f0-4ae8-b465-b82db3912cf8)

"wsl --set-default-version 2" 이 코드를 입력시켜서 WSL파일의 버전을 바꿔줍니다. 그다음 재시작을 합시다.

재시작을 하고나서는 이제 윈도우 터미널을 설치해야합니다.
윈도우 터미널을 설치하는데 여러 방법이 있지만 이번에 할 방법은 Microsoft Store 에서 다운로드 받아서 사용할 것 입니다.
Windows + S 키를 눌러서 검색창을 띄우고 "Microsoft Store" 를 입력해서 실행시켜줍니다.

이제 검색창에서 "Windows Terminal" 을 검색해줍시다.
![스크린샷(27)](https://github.com/user-attachments/assets/ea0a5ee9-f504-4aa2-a0f0-239cb042f972)

이제 설치가 끝나고나면 Windows + S 키를 눌러서 "Windows Terminal"을 검색하고 실행해봅시다.
*만약 검색에서 안뜬다면 "Microsoft Store" 에서 실행시키거나, 아래 사진처럼 한글로 "터미널" 이라고 됬을수도 있습니다.
![스크린샷(29)](https://github.com/user-attachments/assets/8d15dc33-4dfe-4ddb-bb28-f55556bfdb82)

터미널을 실행시켜줍니다. (실행시켰을때 Windows Powershell 로 실행됩니다.)
![6](https://github.com/user-attachments/assets/e2da872d-2000-44d4-b010-765bbb97e97e)

그다음 터미널에 "wsl --update" 를 입력해서 업데이트를 해줍시다.
![7](https://github.com/user-attachments/assets/c6f690fa-af9c-40df-9d3f-7a3606b02888)

이것으로 마무리 하겠습니다.

