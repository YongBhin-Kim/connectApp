# connectApp<br>

사용자들을 연결시켜주는 앱<br>

**[use]** 
- flutter
- android studio
- firebase ----- DB


**[지원 플랫폼]**
- android
- iOS


<h2>[Project Firebase연동]</h2>

[ios] <br>
Apple 앱에 Firebase 추가 <br>
<img width="658" alt="image" src="https://user-images.githubusercontent.com/98372474/181906150-fecb9f69-1482-4e5b-b120-099d24e6fbb8.png"> <br>
<br>

XCode로 프로젝트를 열면 identifier에서 번들 이름 확인이 가능하다. <br>
<img width="841" alt="image" src="https://user-images.githubusercontent.com/98372474/181906127-d8cf14a7-7eb0-452d-b5ed-66fb07febf4b.png"> <br>
<br>

<img width="833" alt="image" src="https://user-images.githubusercontent.com/98372474/181906221-f6598614-2613-4429-ac23-f7357e332bc9.png"> <br>

`GoogleService-Info.plist` 다운로드 후 xcode의 'Runner' 폴더 내부에 삽입 <br>
<img width="1053" alt="image" src="https://user-images.githubusercontent.com/98372474/181906340-97fd0b5c-5a12-44a0-a7bb-50fef2927983.png"> <br>
<img width="264" alt="image" src="https://user-images.githubusercontent.com/98372474/181906355-84b843cc-6958-41ed-a3e8-7b0a947fc251.png"> <br>

`GoogleService-Info.plist` 클릭 후 `REVERSED_CLIENT_ID`의 value를 복사하여 다음 위치에 삽입 <br>
<img width="1053" alt="image" src="https://user-images.githubusercontent.com/98372474/181906444-dbe7a021-b97d-4246-9265-93c5a5aae6ab.png"><br>




