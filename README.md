Github page for localizing Pathfinder:Kingmaker 

This page is for co-working place to localize Pathfinder:Kingmaker. 

There is 6 .po format files for Pathfinder:Kingmaker Korean version. The files are source for compiling. 


----------How to localize these files---------------
1. Fork this page

2. Clone or download this page at your repository.

3. Edit files between result 1 to 6. (Some files are already filled so you should find what you want any without Korean strings.) 
   (po format file editor : https://poedit.net/)

4. Upload files you edited on your repository.

5. Pull request your repository.

----------How to fork, clone, request a repository.
Check this site below.

<br/>https://guides.github.com/activities/hello-world/


---------------Files Status(2019. 12. 05)------------
1. result1 
  Total: 10712 (Strings)
  Translated: 1361 (Strings) 
  Rested: 9351 (Strings)
2. result2
  Total: 14614 (Strings)
  Translated: 2374 (Strings)
  Rested: 12240 (Strings)
3. result3
  Total: 12466 (Strings)
  Translated: 12466 (Strings)
  Rested: 0 (Strings)
4. result4
  Total: 11722 (Strings)
  Translated: 11722 (Strings)
  Rested: 0 (Strings)
5. result5
  Total: 11095 (Strings)
  Translated: 3664 (Strings)
  Rested: 7431 (Strings)
6. result6
  Total: 335 (Strings)
  Translated: 335 (Strings)
  Rested: 0 (Strings)

---------------------한국어------------------------------

이곳은 패스파인더:킹메이커를 한글화하기 위한 깃허브 페이지입니다.

이 페이지는 패스파인더:킹메이커를 한글화하기 위해 협력하는 공간입니다.

여기에 패스파인더:킹메이커 한글 버전을 만들기 위한 6개의 po포멧 형식의 파일이 있습니다. 파일들은 한글화 파일을 위한 소스파일입니다.

-----------파일들을 한글화하는 방법-------------------------
1. 이 페이지를 포크합니다.

2. 포크한 레포지토리로 가서 파일들을 다운로드합니다.

3. 1번부터 6번까지 파일을 수정합니다. (일부 파일은 이미 쓰여있어서 영어 스트링만 있는 부분을 찾아 한글을 입력하시면 됩니다.)
   (po 포맷 파일 에디터 : https://poedit.net/)
   
4. 포크했던 레포지토리에 수정한 파일을 업로드합니다.

5. 레포지토리에서 풀리퀘스트를 진행합니다.

------------------------한글화 룰-------------------------
1. 스트링 내 존대와 하대는 존재하지 않습니다. (단 발레리는 예외로 합니다.)

2. 스트링의 모든 해석을 요구하지 않습니다. (게임 플레이에 필요한 정보를 담을 정도를 요구합니다.)

3. {}를 사용한 property는 생략해도 괜찮습니다. 단 {n}{/n}은 생략하지 않습니다.

   생략하는 property:
   {mf|baron|baroness|king|queen}, {mf|he|she}
   
   사용할 수 있는 property:
   {name}, {g}{/g}
   
4.  포함해야 하는 것들:
    \"\", []    
    
--------------------------한글화된 스트링 예제------------------------
{n}No one made it out without at least a few burns and wounds, especially {Name} {mf|him|her}self.{/n}

->{n}특히 {name}의 상처가 가장 심했습니다.{/n}

\"This is indeed the baron{mf||ess} of {kingdomname}. Show respect...\"

->\"이 녀석은 이 곳의 지배자다. 예의를 보이지 않으면...\"
