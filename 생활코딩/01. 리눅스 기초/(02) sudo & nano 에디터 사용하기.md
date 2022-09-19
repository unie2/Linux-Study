## ✔ sudo (super user do)
: super 유저가 하는 일
- 유닉스 계열의 운영체제들은 중요한 특징 중 하나가 `다중 사용자 시스템`이다.
  - 하나의 컴퓨터를 여러 사람들이 함께 사용한다.
  - 이로 인해 A라는 사람이 만든 파일을 B라는 사람이 마음대로 열고 쓰는 문제가 발생
- `permission`을 고안하여 각각의 사용자마다 할 수 있는 일과 할 수 없는 일을 구분하였다.

![sudo](https://user-images.githubusercontent.com/54324782/189337448-5192b955-a4d8-45ca-ae38-ff5c3f6a960e.png)

- 권한이 없으면 명령을 실행할 수 없다.
- sudo를 포함시켜 git이라고 하는 프로그램을 설치할 수 있다.


- - -
## ✔ nano 에디터 사용하기
### 1. 새 파일 생성

| (1) nano 명령어 실행 | (2) 파일 내용 작성 |
|:--------:|:--------:|
| ![nano](https://user-images.githubusercontent.com/54324782/189340151-2821fd8e-ee79-4fdf-98d9-0fb65bffe812.png) | ![파일 내용 작성](https://user-images.githubusercontent.com/54324782/189339831-ef734fd8-0302-4af8-94e9-5d8d7318a0ad.png) |

| (3) Write Out & 파일명 작성 | (4) 파일 생성 확인 |
|:--------:|:--------:|
| ![Wrtie Out & 파일명 작성](https://user-images.githubusercontent.com/54324782/189339986-f90313d6-5888-4473-8e07-c4578d262045.png) | ![파일 생성 확인](https://user-images.githubusercontent.com/54324782/189340241-582b6649-089a-4993-9a13-946fb19cb62c.png)

### 2. 파일 수정

| (1) nano 명령어 실행 | (2) 파일 내용 추가 |
|:--------:|:--------:|
| ![nano 수정](https://user-images.githubusercontent.com/54324782/189341589-86fb6aaf-a18b-48d4-9787-8f1822f248e5.png) | ![내용 수정](https://user-images.githubusercontent.com/54324782/189341910-09a1a972-fc74-4d83-8a4a-780bffc48c36.png)

| (3) Cut (Ctrl + K) | (4) UnCut (Ctrl + U) |
|:--------:|:--------:|
| ![Ctrl&K](https://user-images.githubusercontent.com/54324782/189342004-15ffba78-4330-4617-bfbe-6c8270f86279.png) | ![Ctrl&U](https://user-images.githubusercontent.com/54324782/189342347-e3339245-5353-46ad-b912-e06ee1f22507.png)

| (5) Ctrl + 6 & 블럭 지정 | (6) Ctrl + K & 뒤쪽 이동 후 Ctrl + U |
|:--------:|:--------:|
| ![Ctrl&6&블럭지정](https://user-images.githubusercontent.com/54324782/189342641-28ca2393-bb09-4714-bc6c-70e72712fc17.png) | ![Ctrl&K, 뒤쪽 이동 후 Ctrl&U](https://user-images.githubusercontent.com/54324782/189342853-57a90ef2-90b6-442a-8854-4d68410731ef.png)

### 3. 내용 검색

| (1) Ctrl + W | (2) 검색어 입력 (body) |
|:--------:|:--------:|
| ![Ctrl&W](https://user-images.githubusercontent.com/54324782/189343628-47224bb9-5847-4539-8ac7-31459dc99d4b.png) | ![검색어 입력](https://user-images.githubusercontent.com/54324782/189343716-3a419555-94b7-46c5-acf4-2106ec9f5112.png)
