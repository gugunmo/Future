이번 시간에는 0830 과정에서 더 나아가서 명령어 시작까지 해보도록 하겠습니다.

![7](https://github.com/user-attachments/assets/38f4cb2e-0424-4dae-a96c-4d4f1cbdb83f)

까지 진행되었으면 이제 여기서 wsl 을 입력해주시면 

아래 사진과 같이 나오게 되면서 로그인이 됩니다 (0830 과정을 거치면서 계정을 만든경우)

![스크린샷(77)](https://github.com/user-attachments/assets/32eb6b71-f5e7-4157-8816-a7c1f1e12544)

명령어를 입력하기 전에 현재의 디렉토리 위치를 보면
/mnt/c/Users/(사용자 이름) 으로 되있는걸 확인할수 있습니다.

여기서 cd 를 입력하여 주시면 
/mnt/c/Users/(사용자 이름) 이 없어진 것을 볼수 있습니다
이 상태에서 명령어인 pwd 를 입력하시면

![스크린샷(79)](https://github.com/user-attachments/assets/ec94eb86-2631-4e73-8d0f-5ff0b6bafca0)

사진과 같이 /home/(사용자이름) 이 결과로 나오는 것을 알 수 있습니다.

이제 다음부터 사용할 tree 라는 명령어를 사용하기 위해 0830 파일에서 했던
sudo apt upgrade, sudo apt update 를 입력해줍시다.
업데이트가 끝난 후에는 
sudo apt install tree 를 입력해서 설치해줍시다.

설치가 끝난 후에 tree를 입력하면 비어있는 것을 확인할수 있습니다.
![스크린샷(80)](https://github.com/user-attachments/assets/51dd01e0-c985-4811-9423-6cd48cd73b8f)

tree 는 현재의 디렉토리에서 하위 디렉토리와, 파일들을 확인할수 있게해주는 명령어임으로
현재 사용하고 있는 위치인 /home/(사용자이름) 에는 아무것도 진행하지 않았기에 안나오는 것이 맞습니다.
