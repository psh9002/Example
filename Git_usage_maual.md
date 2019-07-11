github 명령어 정리
=================

* $ git config --global user.name "이름"
* $ git config --global user.email "깃허브 메일주소" // 매번 물어보는 귀찮음을 피하기 위해 설정.
* $ mkdir ~/MyProject    // 로컬 디렉토리 만들고
* $ cd ~/myproject       // 디렉토리로 들어가서
* $ git init             // 깃 명령어를 사용할 수 있는 디렉토리로 만든다.
* $ git status           // 현재 상태를 훑어보고
* $ git add 파일명.확장자 // 깃 주목 리스트에 화일을 추가하고 or
* $ git add .            // 이 명령은 현재 디렉토리의 모든 화일을 추가할 수 있다.
* $ git commit -m "(언급할 내용 작성)” // 언급할 내용을 ""안에 작성한다.
* $ git remote add origin https://github.com/username/myproject.git // 로컬과 원격 저장소를 연결한다.
   * $ git remote remove origin // 기존 repository를 바꾸고 싶다면 입력 후, 위 코드를 이용하여 새로운 주소 입력
   * 또는 기존 원격 저장소 URL을 변경하기 위해 $ git remote set-url 명령어를 사용<br>$ git remote set-url origin URL입력
* $ git remote -v // 연결상태를 확인한다.
* $ git push // 깃허브로 푸시한다.<br>
(내 저장소의 master 브랜치를 지정하도록 하려면 git push origin master로 입력할 수 있다)


# 세줄요약 (git에 올릴 위치에 있는 상태)
1. $ git init
2. $ git add 파일명.확장자 (또는 git add .)
3. $ git push



출처: https://nolboo.kim/blog/2013/10/06/github-for-beginner/


기타 참고사항
https://www.pigno.se/barn/tutorial-git/docs/#/

추천 자료: https://rogerdudler.github.io/git-guide/index.ko.html
[마크다운 사용법 정리][https://heropy.blog/2017/09/30/markdown/]<br>
[SSH 등록 & GitHub][https://bsh9002.blogspot.com/2019/07/ssh-github.html]
