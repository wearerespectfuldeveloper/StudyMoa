### 5주차
* 일시 : 2019-06-15 (토요일)
* 장소 : 종각역 인근 마이크임팩트 스퀘어
* 참석자 : 윤 철, 박노빈, 신미연
* 주제 : StudyMoa 스토리 보드 정리 및 ERD 설계
* 내용
   1. 스토리보드 종합 정리
   2. ERD 모델링
   3. 스토리보드 툴 : https://ovenapp.io/
   $. ERD 툴 : https://www.draw.io/
* 한 주간 해야할 일
   1. aws에 대해서 학습하기
   2. ERD 모델링 기반 데이터베이스 생성
   3. 각자 필요한 기술 스택 공부
* 다음 주에 할 일
   1. 스토리보드 종합 정리
   2. ERD 설계
   3. 인프라 관련 설정
- - -      
#### 현재까지 완성된 ERD
![ERD_ver_2](/img/ERD_2.PNG)
- - -
#### 스토리 보드 (정리 필요)
아직 정리되지 않음
- - -
#### 스터디보드 종합 정리 회의록
1. 스터디 홍보 메뉴 게시판 삭제

2. 스터디 구해요 메뉴 게시판<br/>
   1. [초대하기] 기능
      * 여러 스터디에 소속되어 있을 경우 방안
      * 팝업창 
      * **SELECT BOX로 구현**
      
3. 내 정보 수정 화면 
   1. 프로필 정보 화면
      * [관심사] 검색 시 INPUT BOX 형태로 검색 (보유기술 > 관심사 로 용어 변경) 
      * 휴대폰 번호 비노출
      
4. 스터디 생성 화면
   1. 모집기간 재설정 - 관리자 영역에서 설정? (X) 
   2. **모집기간 필드 삭제**
   3. **스터디 생성 팝업창 한페이지로 구성** 
   4. **공개 / 비공개 스위치버튼 추가**
   
5. 공통헤더
   1. [내스터디관리] 추가 
   2. 내정보 > 드롭박스를 통해서 선택할 수 있는  [내스터디관리]  메뉴를 공통 헤더 영역에 따로 표시 

6. [알람] 추가 
   1. 스터디 초대 정보 목록 리스트 화면 
      * 수락/거절 기능
      * 상세보기 - 해당 스터디 상세 화면으로 이동 

7. 스터디 목록 화면
   1. 참여 중 스터디 / 주최중 스터디 구분 불필요 -> 하나로 합체
   2. 스터디 개설 버튼 
   3. 정렬 기준 
      * 스터디가 공개 상태일 때
      * 개설일 ? 마감일 ? 수정일? 

8. 스터디 상세 화면
   1. 왼쪽 메뉴 추가
   2. 그룹정보 / 게시판 / 참가요청내용 /참여자정보 / 그룹탈퇴
   3. 참여자정보 
   4. 현재 참여자 
   5. 모집인원 및 참여자 수 정보
   6. 아이디만 보여줌 
   7. 권한 설정 기능 
   8. 직업 필드 삭제
   9. 게시판 
   10. 자유게시판과 화면 구성 동일  
   11. 정렬기준 > 최신순

9. 스터디 그룹 탈퇴기능
   1. 오너
      * [매니저]가 있을 경우에만 오너가 탈퇴 가능 (오너를 양도하고 탈퇴)
      * 모든 팀원이 나가야 오너가 탈퇴 가능
   2. 매니저 및 멤버
      * 제약없이 탈퇴 가능

10. 진행 주차별 스터디 
   1. 오른쪽 버튼 [글쓰기] 기능 > 게시판 추가

11. 참여자 정보 > 왼쪽 메뉴로 이동

12. 구하고 있는 사람들 > 삭제

13. 스터디 그룹 정보의 오른쪽 버튼 3가지 > 삭제 (수정, 탈퇴, 마감기한 버튼)