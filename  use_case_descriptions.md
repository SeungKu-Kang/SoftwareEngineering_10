**Use case description: 설문 등록**

| Actor Action | System Response |
| :--- | :--- |
| 1. 설문 등록 메뉴를 선택한다. | 2. 설문 제목, 설문 설명, 설문 문항, 응답 항목, 설문 시작 시각, 설문 마감 시각을 입력할 수 있는 화면을 출력한다. |
| 3. 설문에 필요한 정보들을 입력하고 등록 버튼을 클릭한다. | 4. 등록 완료 메시지를 화면에 출력한다. |

**Alternative Courses**
None.

<br>

**Use case description: 설문 리스트 조회**

| Actor Action | System Response |
| :--- | :--- |
| 1. 설문 리스트 조회 메뉴를 선택한다. | 2. 등록된 모든 설문 리스트를 화면에 출력한다. |

**Extensions**
After step 2, 관리자는 리스트에서 특정 설문 항목을 선택하여 상세 내용을 팝업 창으로 조회한다. (설문 상세정보 조회-팝업)
After step 2, 관리자는 리스트에서 특정 설문 항목을 선택하여 삭제한다. (특정 설문 삭제)

<br>

**Use case description: 설문 상세 정보 조회-팝업**

| Actor Action | System Response |
| :--- | :--- |
| 1. 설문 리스트 화면에서 특정 설문 항목을 선택(클릭)한다. | 2. 선택한 설문의 상세 내용(설문 제목, 설문 설명, 설문 문항, 응답 항목, 시작/마감 시각 등)을 팝업 창으로 출력한다. |
| 3. 팝업 창 닫기 버튼을 클릭한다. | 4. 팝업 창을 닫고 기존 설문 리스트 화면을 유지한다. |

**Alternative Courses**
None.

<br>

**Use case description: 특정 설문 삭제**

| Actor Action | System Response |
| :--- | :--- |
| 1. 설문 리스트 화면에서 특정 설문 항목을 선택하여 삭제를 요청한다. | 2. 특정 설문의 삭제 완료 메시지를 출력하고, 해당 항목이 제외된 갱신된 설문 리스트 화면을 출력한다. |

**Alternative Courses**
None.