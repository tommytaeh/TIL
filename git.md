# git

# Goals
- git을 사용하기 위해 CLI와 Vim을 다룬다.
- git은 소스를 관리하기 위해 사용된다.
- git을 통해 협업이 가능하다.

## 210820
- ~ : 로그인된 최상위 폴더
- 로그인한 유저@컴퓨터
- $ : bash가 명령받을 준비가 되었다.
- ls : list segment
- Flag : 어떤 옵션이 켜지거나 꺼지거나 하는 기능(- 뒤에 활성화하는 단어를 입력한다)
- ls -l : line by line (한줄씩 적으면서 부가정보까지 표출해라
- ls -a : 파일이름 폴더이름 앞에 .(dot)이 붙어져 있음
- clear : 화면 정리
### CLI와 GUI
- CLI(Command Line Interface)
git bash를 띄우기 전은
- GUI(Graphic User Interface)
### cd
- cd : change directory(폴더를 더블클릭한 것과 같은 말)
- 그냥 cd는 최상위 폴더로 이동
- cd ./ : 현재 디렉토리
- cd ../: 상위 디렉토리
- cd ../.. : 두 단계로 올라가고 싶다

### mkdir
- mkdir : make directory
- 항상 실행하고 나서 표현이 안되기 때문에 확인해야 한다(CUI와 GUI의 차이)

### 파일
- mv : move
- mv : 이름바꿀 때도 사용
하단의 폴더로 이름 바꾸면서 파일 옮기기
$ mv writeme.md bin/readme.txt

복사하면서 이름 바꾸기
cp readme.txt ./hello.py

하위폴더에 있는 파일을 상위로 옮기기
mv bin/hello.py ./bye.py

- remove : remove는 논리적으로 삭제하는 거고 delete는 파일을 그냥 삭제하는 거임

- 폴더를 삭제할 때 rm을 사용할 수 없다.
- 폴더는 경로를 의미할 뿐/ 파일은 실존

### vi
shell에서 프로그램을 실행할 때 vim 파일을 만들면 새로운 창이 열림
마우스 역할을 하는 걸 키보드로 다 할 수 있음
- normal mode : 명령어 실행
- insert mode : 파일 편집 기능
- i를 누르면 insert 모드로 변경
- normal mode로 전환하려면 esc를 누르면 됨

#### skills
- shift + y(yank) : 현재 라인 복사하기
- p : 복사(paste)
- u : 뒤로(undo)
- Y2j : 아래 두줄까지 복사
- dd : 현재 라인 지우기
- d2j : 아래 2줄까지 지우기
- dd하고 나서 p 하면은 다시 살아난다.

### Markdown
헤딩마크 # 1개부터 6개까지 붙을 수 있다.

리스트는 ul, ol이 있음
- ul(unordered list)는 -를 사용
- ol(ordered list)는 1. 2.를 사용

리스트는 []()
이미지는 ![]()

### 저장
- w: write
- q: quit
- wq: write & quit


