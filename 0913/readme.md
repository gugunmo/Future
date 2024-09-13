이번시간에는 wsl 설치를 한 것을 기준으로 합니다.

시작함에있어서 여러가지 명령어를 알아보고 시작을 해봅시다.

wsl 에는 네트워크 관련 명령어, 사용자 설정 명령어, 디렉토리 확인 명령어 등 많은 명령어들이 있습니다.
오늘 배울것을 제외하고 man {궁금한 명령어} 를 입력하면 어떤 명령어인지 어떤 옵션이 있는지 나오게 됩니다.

예시로 ls 에 대한 다양한 옵션들을 보고싶다면
아래 사진처럼

![스크린샷(64)](https://github.com/user-attachments/assets/37ca69fa-9eec-4880-9bbb-dd250233ed8e)

man ls 를 입력하고 Enter 키를 눌러주면


![스크린샷(63)](https://github.com/user-attachments/assets/395fb6b9-01c3-4329-bc2c-8ca27d45cf47)

위 사진처럼 ls 명령어의 옵션, 사용방법이 나오게 됩니다.

여기서 나올때는 q 키를 눌러주면

![스크린샷(62)](https://github.com/user-attachments/assets/ecff3725-6e26-41ef-9865-efa87a1c5d61)

사진처럼 나와지게 됩니다.

처음으로 확인할 명령어들은 기초적인 명령어들만 해봅시다.
pwd, rmdir, mkdir, cd 명령어들을 간단하게 알아봅시다

cd는 디렉토리를 원하는 위치로 이동하는 명령어이다.
pwd는 현재의 디렉토리의 위치 확인하는 명령어이다.
mkdir는 파일의 생성하는 명령어이다.
rmdir는 디렉토리삭제를 하는 명령어이다.

위 명령어 사용예시를 보여드리겠습니다.
(사진에서 사용하는 트리는 sudo apt install tree 명령어를 입력하고 나면 사용가능합니다.)
우선 기본 환경에서 mkdir OS 를 입력해 OS 라는 디렉토리를 생성해줍니다.

![스크린샷(65)](https://github.com/user-attachments/assets/95b864f4-e570-46b6-9361-f3fdeb24618b)

다음으로는 cd OS 를 입력해 OS 디렉토리로 이동해줍시다.
그 후 mkdir Linux 를 입력해 Linux 디렉토리를 생성해주고 tree 를 입력하면 OS 하위 디렉토리인 Linux 가 있는걸 볼수 있습니다.

![스크린샷(66)](https://github.com/user-attachments/assets/a7ae1be4-0436-4ea9-a4c6-a00f69590c85)

이제 삭제하는 명령어를 사용해봅시다. 
rmdir OS 를 그냥 입력하면 아래 사진과 같은 메시지가 나오는데

![스크린샷(70)](https://github.com/user-attachments/assets/79273186-272d-4385-97fa-1098061eceef)

이 메시지는 OS 내부의 디렉토리가 비워지지않았기에 나오는 메시지입니다.
이에따라 cd OS 를 입력 해준다음 rmdir Linux, rmdir Windows 를 입력해주고
cd 를 입력한후 tree를 입력하면 아래 사진과 같은 결과가 나옵니다.

![스크린샷(71)](https://github.com/user-attachments/assets/7c675d0a-13ec-4953-8658-665353cbed82)

이제 rmdir OS 를 해주면 디렉토리가 삭제됬음을 확인할수 있습니다.

![스크린샷(74)](https://github.com/user-attachments/assets/39c820a1-89e0-4726-b04d-3709c3a6a110)


그 다음 알아볼 명령어들은 
rm, mv, ls 명령어들 입니다.

rm는 파일 삭제를 해주는 명령어이며, 옵션으로 -r 을 하게되면 하위 파일들 역시도 삭제됩니다.(복구도 안되니 주의하며 사용합시다.)
mv는 파일의 이동을 해주는 명령어입니다.
ls 디렉토리 내의 파일을 확인하는 명령어입니다.

이 코드들 역시도 실습을 해봅시다.
우선 ls 먼저 확인을 하기위해 아래 사진과 같이 디렉토리 생성을 먼저 해줍시다.

![스크린샷(69)](https://github.com/user-attachments/assets/8af8c96f-f3d5-4712-b096-b8ab5003bb82)

생성이 끝나면 디렉토리 위치는 OS 에서 ls 를 입력해보면 

![스크린샷(75)](https://github.com/user-attachments/assets/85cecd14-c8d2-46a4-8ebc-a143c2fc8e7a)

위 사진과 같은 결과가 나오게 됩니다.

다음으로 rm 을 해봅시다. 디렉토리 위치는 OS에서 rm Windows -r 을 입력해 주시면 

![스크린샷(76)](https://github.com/user-attachments/assets/be82db2c-28b5-49e4-a398-3890ce121407)

사진처럼 삭제 된것을 볼수 있습니다.

Windows 를 삭제시켰다면 mv를 이용해 봅시다.
cd 를 입력해 상위 디렉토리로 이동하고 난후 mkdir Windows 를 "home/username/" 위치의 하위 디렉토리로 만들어 줍시다.

![스크린샷(67)](https://github.com/user-attachments/assets/6cc806ee-6e8b-4931-8d6d-26fea219e289)

이제 여기서 mv Windows /home/(사용자명)/을 입력하여서 위치를 옮겨줍시다.

![스크린샷(68)](https://github.com/user-attachments/assets/36522660-4228-4650-b732-ad442666304f)

이번시간은 여기까지 알아보도록 합시다.
