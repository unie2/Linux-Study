## ✔ 다운로드 방법 - wget
- `wget`을 사용하여 URL을 통한 파일 다운로드를 할 수 있다.
#### "파일 다운로드 및 확인"
```bash
# -O를 통해 파일 이름 지정
wget -O paris.jpeg http://unsplash.com/photos/8V8qCIIo554/download

ls
```

![wget](https://user-images.githubusercontent.com/54324782/190590260-62ce79ed-d586-4abe-8234-52849f2ebcc8.png)

- - -
## ✔ 다운로드 방법 - git
- git: 버전 관리 시스템이라 하는 카테고리에 속하는 구체적인 제품 중에 하나
  - git은 리눅스 뿐만 아니라 윈도우, MAC 등에서도 사용이 가능하므로 특정 운영체제에 종속된 프로그램은 아니다.

#### "git 다운로드"
```bash
sudo apt-get install git
```
#### "오픈소스 프로젝트를 복제"
- 파일 뿐만 아니라 변경 사항들을 모두 복제

```bash
git clone https://github.com/unie2/Linux-Study.git linux_src

ls
```

![git](https://user-images.githubusercontent.com/54324782/190592952-618af285-2c78-48d6-bc8c-c0879e5991a5.png)
