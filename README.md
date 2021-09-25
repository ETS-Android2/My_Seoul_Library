# My_Seoul_Library
* 2017년 서울시 앱 공모전 출품작 (나의 서울 라이브러리, 나서라) <br> 2017 Seoul App Contest Entry (My Seoul Libray, MSL)
* Made by 문학소녀들
<br> 📓 📕 📗 📘 📙 📔 📒 📚 📖

## Introduction (개요)
This is an android application for Seoul citizens who like to read books and want to go to nearby libraries whenever they want.

* To Read Book List
* Find Libraries & Books in Seoul
  * Search Seoul Libraries by Location
  * Search Seoul Libraries by Name
  * Search Books in Seoul Public Libraries
* Save My Book Reviews
  * Search Book Info
* Share Book Reviews with Others

## Development Environment (개발 환경)
- Android Studio
- PHP

## APIs
- Open API of Seoul Pulbic Library Info ( 서울시 공공도서관 공공데이터 )
- Open API of Korean Library Information System Network ( KOLISNET, 국가자료종합목록 )
- google map ( 구글 맵 )
- API of Aladdin ( 알라딘 API - Book Info 이용 )

## App Diagram

<img src="https://user-images.githubusercontent.com/22439716/134775674-2e4c4a30-3d0d-4eae-bf32-28442683ac67.jpg">
<img src="https://user-images.githubusercontent.com/22439716/134775707-0a5e7d9e-0488-4868-b2b8-39e53b5a4176.jpg">


## Screenshot ( 스크린 샷 )
> #### Start App
<p float='left'>
 <img src="https://user-images.githubusercontent.com/22439716/134764112-96acb13d-5ef5-4844-a9af-ea55897871ec.png" width="200">
</p>

> #### Main (메인 화면)
   \- 링크 된 : 독서 목표 / 책갈피 확인 가능
<p float='left'>
 <img src="https://user-images.githubusercontent.com/22439716/134764114-2369cc2d-eac7-45d4-9364-1e0ea0406482.png" width="200">
</p>


> #### To Read List (도서 체크리스트)
* 1 \) Set reading goal achievement (+ link to MAIN) <br>    독서 목표 설정 ( Main 페이지 연동 )
* 2 \) Add 'To Read Book' List <br> 'To Read Book' 리스트에 추가
<p float='left'>
 <img src="https://user-images.githubusercontent.com/22439716/134764118-b2d9308a-d681-4e85-adfa-c7763b995894.png" width="200">
</p>

> #### Search 
* 1 \) Search Seoul Public Libraries <b> by Nearby Location </b> <br> 서울 공공 도서관 가까운 위치로 검색하기 
<p float='left'>
  <img src="https://user-images.githubusercontent.com/22439716/134764121-ae72d260-dafd-4ce0-9312-ae865035c4b2.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764125-3dd89f4d-fd9c-4a1f-9dff-0a89abf177a7.png" width="200">
</p>

* 2 \) Search Seoul Public Libraries <b> by Name </b> <br> 서울 공공 도서관 이름으로 검색하기 
<p float='left'>
  <img src="https://user-images.githubusercontent.com/22439716/134764126-526ff817-df1e-4f5c-86d9-fb00f5e83eb8.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764127-68f408d2-4b92-4e9b-94f9-0b05c87bcf43.png" width="200">
</p>

* 3 \) Search the Book Name at the Seoul Public Libraries <br> 서울 공공 도서관에서 책 검색하기 📚
<p float='left'>
  <img src="https://user-images.githubusercontent.com/22439716/134764129-3a1ce3bb-b61d-4b13-93b3-58cf6b6d219e.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764131-0c88f2d3-51e3-4851-b869-34b356edfbfb.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764134-b1e0c2a3-bd17-446e-afa6-a69c4c12d026.png" width="200">
</p>


> #### Book 

* 1 \) Write a Book Review by pressing the `+ button` <br> `+ 버튼` 눌러서 독후감 작성하기
  * Book Info can be : 1. directly entered or 2. searched for book information through Aladdin API <br> 책 정보는 : 1. 직접 입력 또는 2. 알라딘 API 통해 도서 정보 검색 가능
  * Setting Bookmark (+ link to MAIN) 📌 <br> 책갈피 설정 (Main 페이지랑 연동) 
<p float='left'>
  <img src="https://user-images.githubusercontent.com/22439716/134764153-2fa1e07b-a261-4297-a8fe-8c9c6acb1e90.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764157-c7b6ebce-153a-42d2-8687-740701be377a.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764160-35ce5f8b-06e7-4bd3-a6e4-f1d5233778df.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764161-64f5537a-f391-4060-b7d5-d841ba60ca05.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764162-aa9611a0-5262-482b-81b0-dcf503b81f07.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764164-0c98d424-c633-4b90-a6d5-d3508cb6e93d.png" width="200">
</p>

* 2 \) Click <b>`'Share button'`</b> : You can share Book Review with others <br> `'공유 버튼'`을 클릭하면 다른 사람들과 독후감 공유 가능
  * 좋아요, 수정, 삭제 가능 
<p float='left'>
  <img src="https://user-images.githubusercontent.com/22439716/134764162-aa9611a0-5262-482b-81b0-dcf503b81f07.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764163-66bd0704-21bd-4955-8317-c9545f515cbc.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764165-bbdc335e-fc3f-4d3b-aefa-0813a8b54e7d.png" width="200">
  <img src="https://user-images.githubusercontent.com/22439716/134764167-0ccf7e82-7d30-4f9f-a93a-a8a1d861e7ac.png" width="200">
</p>

---

### [Result]

예선당선 🏆 


<p float='left'>
  <img src="https://user-images.githubusercontent.com/22439716/134776762-c0247f05-a251-4057-b0b7-b849e923f766.png" width="700">
  <img src="https://user-images.githubusercontent.com/22439716/134776763-d26a5eda-04b9-431f-acda-51b6b2f32cef.png" width="500">
</p>
