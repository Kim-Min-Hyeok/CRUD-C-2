# project1 #
오픈소스소프트웨어 프로젝트 1 (범죄자 관리 시스템)
## 프로젝트 사용법 ##
1. 다음 프로젝트를 Local Repository에 clone하여 makefile을 이용하여 실행파일을 만드시오.
2. makefile 사용 예시
    * make main > 일반 실행 파일 생성
    * make main_debug > 디버그 모드 실행 파일 생성 (어떻게 실행 파일이 돌아가는지 자세시 알기 위해)
    * make clean > make를 통한 생성 파일 모두 삭제
3. ./main이나 생성된 실행파일 직접 접근하여 프로그램 실행
4. 프로그램 사용법에 대해서는 다음 설명을 읽으시오.
## 프로그램 기능 ##
* Create
  * 범죄자 레코드 생성 (이름, 나이, 거주지역, 성별, 범죄분류)
* Read
  * all
    * 모드 레코드 정보 출력
  * name
    * 이름 별로 검색하기
  * age
    * 나이대 별로 검색하기
  * sex
    * 성 별로 검색하기
  * city
    * 거주지역 별로 검색하기
  * category
    * 범죄 분류 별로 검색하기
  * save file
    * 현재 레코드 정보에 따라 Criminal_List파일 저장
  * Quit
    * Read 메뉴 종료
* Update
  * 범죄자 레코드 수정 & 범죄 항목 추가
* Delete
  * 범죄자 레코드 삭제
* Read_file
  * Criminal_list 파일과 Criminal_Wicked 파일 읽어오기
* Read_Report
  * Criminal_Report 파일 읽어오기
* Save_Wicked
  * 현재 레코드 정보를 통하여 Criminal_Wicked 파일 수정하여 저장
* Optimize_record
  * 비어 있는 레코드들 앞으로 당겨주기
* Sort_Record
  * 이름 순서대로 레코드 정렬하기
* Create_user
  * 프로그램 사용자 추가 (아이디, 비밀번호)
* Quit
  * 프로그램 종료
