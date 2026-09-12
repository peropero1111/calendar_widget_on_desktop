# calendar_widget_on_desktop

### 이 calendar_widget_on_desktop 은 codex 의 도움이 들어갔습니다.  
</br>


[exe 파일링크](https://drive.google.com/drive/folders/1IbY2NH5m0-zS1GZNa5uw_mFJOuiKGH03?usp=sharing) 로 실행할때의 사용법은 글 하단에 있습니다.
</br>
</br>
사용하시기전에 다음 절차를 따라 주십시오.
</br>
아래에 더욱 쉬운 이해를 위한 이미지가 있습니다. 

### 목차
[1. 설치](#1-설치)  
[2. Google Calendar 연결](#2-google-calendar-연결)    
[3. 작업스케쥴러 등록 (선택사항) (py 버젼)](#3-작업스케쥴러-등록-선택사항-py-버젼)  
[4. 작업스케쥴러 등록 (선택사항) (exe 버젼)](#4-작업스케쥴러-등록-선택사항-exe-버젼)  
[5. 기능 소개](#5-기능-소개)

## 1. 설치
&nbsp;&nbsp;&nbsp;&nbsp;1.1 적당한 폴더에 calendar_widget_on_desktop 속 내용물을 다운 받아 주십시오.


&nbsp;&nbsp;&nbsp;&nbsp;1.2 calendar_widget_on_desktop 속 calendar.py 에서 다음 명령어를 각각 입력하여 주십시오.
```powershell
python -m pip install requests
python -m pip install icalendar
python -m pip install recurring-ical-events
python -m pip install tzdata
python -m pip install winotify
```
</br>

## 2. Google Calendar 연결

&nbsp;&nbsp;&nbsp;&nbsp;2.1. 브라우저에서 Google Calendar를 엽니다.  
&nbsp;&nbsp;&nbsp;&nbsp;2.2. 오른쪽 위 톱니바퀴 아이콘에서 `설정`으로 들어갑니다.  
&nbsp;&nbsp;&nbsp;&nbsp;2.3. 왼쪽에서 `내 캘린더의 설정`을 선택한 후 선택할 계정을 고릅니다.  
&nbsp;&nbsp;&nbsp;&nbsp;2.4. `캘린더 통합` 을 선택한 후 암호화 형식인 `iCal 형식의 비공개 주소`를 복사합니다.  
&nbsp;&nbsp;&nbsp;&nbsp;2.5. calendar.py를 처음 실행하면 생기는 `calendar_widget_config.json` 파일을 열고 `input_ical_urls`에 붙여 넣습니다.

</br>

## 3. 작업스케쥴러 등록 (선택사항) (py 버젼) 
&nbsp;&nbsp;&nbsp;&nbsp;3.1 작업스케줄러를 실행시킨후 작업만들기를 클릭하여 주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212029.png" width="450" height="450"/>  
</br>

&nbsp;&nbsp;&nbsp;&nbsp;3.2 처음뜨는 창 (일반 메뉴) 에서 이름을 정해 주시고 `사용자가 로그온 할때만 실행` 으로 설정해 주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30 212122.png" width="450" height="450"/> 
</br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;3.3 트리거 메뉴로 넘어가서 새로만들기를 눌러주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212201.png" width="450" height="450"/> 
</br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;3.4 작업시작을 `로그온 할떄`, 지연시간에 체크해 주시고 30초 로 체크해 주십시오

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212231.png" width="450" height="450"/> 
</br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;3.5 cmd 혹은 powershell 을 관리자 권한으로 실행시켜서 ```  where pythonw  ``` 라고 검색 해 주십시오.
</br>&nbsp;&nbsp;&nbsp;&nbsp;( 저는 python 을 기존에 다운 하여서 두번째 경로가 있는데 대부분의 사람들은 첫번째 경로 밖에 없을 것입니다. 무엇으로 하여도 결과에 큰 지장은 없습니다. )

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20215110.png" width="450" height="450"/> 
<br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;3.6 나온 경로를 기억하고 있다가 동작 메뉴로 넘어가서 새로만들기를 눌러 주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212311.png" width="450" height="450"/> 
<br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;3.7 `프로그램`에 나온 경로를 입력하여 주십시오. 
</br>&nbsp;&nbsp;&nbsp;&nbsp;3.8 `인수 추가` 에 다음과 같이 입력하여 주십시오 `"C:\Users\~ run_widget.py 를 놓은 폴더 경로 주소 ~ \run_widget.py"`
</br>&nbsp;&nbsp;&nbsp;&nbsp;3.9 `시작 위치` 에 다음과 같이 입력하여 주십시오  `C:\Users\~ run_widget.py 를 놓은 폴더 경로 주소 ~`

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212838.png" width="450" height="450"/> 
<br>
</br>

## 4. 작업스케쥴러 등록 (선택사항) (exe 버젼) 

&nbsp;&nbsp;&nbsp;&nbsp;4.1 작업스케줄러를 실행시킨후 작업만들기를 클릭하여 주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212029.png" width="450" height="450"/>  
</br>

&nbsp;&nbsp;&nbsp;&nbsp;4.2 처음뜨는 창 (일반 메뉴) 에서 이름을 정해 주시고 `사용자가 로그온 할때만 실행` 으로 설정해 주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30 212122.png" width="450" height="450"/> 
</br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;4.3 트리거 메뉴로 넘어가서 새로만들기를 눌러주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30 212201.png" width="450" height="450"/> 
</br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;4.4 작업시작을 `로그온 할떄`, 지연시간에 체크해 주시고 30초 로 체크해 주십시오

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212231.png" width="450" height="450"/> 
</br>
</br>

&nbsp;&nbsp;&nbsp;&nbsp;4.6 동작 메뉴로 넘어가서 새로만들기를 눌러 주십시오.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20212311.png" width="450" height="450"/> 
<br>
</br>


&nbsp;&nbsp;&nbsp;&nbsp;4.7 `프로그램`에 exe 파일의 경로를 입력하여 주십시오. 
</br>&nbsp;&nbsp;&nbsp;&nbsp;4.8 `인수 추가` 에 다음과 같이 입력하여 주십시오 `"C:\Users\~ calendar_widget_on_desktop.exe 를 놓은 폴더 경로 주소 ~ \calendar_widget_on_desktop.exe"`
</br>&nbsp;&nbsp;&nbsp;&nbsp;4.9 `시작 위치` 에 다음과 같이 입력하여 주십시오  `C:\Users\~ calendar_widget_on_desktop.exe 를 놓은 폴더 경로 주소 ~`

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-06-30%20224842.png" width="450" height="450"/> 
<br>
</br>


## 5. 기능 소개

&nbsp;&nbsp;&nbsp;&nbsp;5.1 만약 일주일이내에 google calendar 에 등록된 일정이 있다면 그 일정은 붉게 표시 됩니다.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/site/2026-07-11%20143401.png?raw=true" width="450" height="450"/>  
</br>


&nbsp;&nbsp;&nbsp;&nbsp;5.2 당일 일정이 30분 이내로 남았을 경우 우측 하단에 토스트 알립을 보내 줍니다.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/site/2026-07-11%20112150.png?raw=true" width="450" height="450"/> 
</br>
</br>


&nbsp;&nbsp;&nbsp;&nbsp;5.3 우상단의 <code>선택</code>를 누르고 민감한 일정을 고른 후 완료를 누르면 그 일정이 해제 하기 전까지 숨김처리 됩니다.

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-07-03%20181439.png?raw=true" width="350" height="350"/><img src="https://github.com/peropero1111/google_calendar_on_desktop/blob/main/img/2026-07-03%20181643.png?raw=true" width="350" height="350"/> 
</br>
</br>


---

## 라이선스 및 제3자 소프트웨어

`calendar_widget_on_desktop`에서 프로젝트 작성자가 직접 작성하고
저작권을 보유한 원본 소스 코드는 MIT License에 따라 배포됩니다.

자세한 내용은 저장소 루트의 [`LICENSE`](LICENSE) 파일을 참고해 주십시오.

이 프로젝트는 다음과 같은 제3자 Python 패키지를 사용하거나 사용할 수
있으며, 각 패키지에는 프로젝트의 MIT License와 별개의 라이선스가
적용됩니다.

| 패키지 | 라이선스 |
|---|---|
| `requests` | Apache License 2.0 |
| `icalendar` | BSD 2-Clause License |
| `recurring-ical-events` | GNU LGPL v3.0 or later |
| `tzdata` | Apache License 2.0 |
| `winotify` | MIT License |
| `x-wr-timezone` | GNU LGPL v3.0 or later |

제3자 소프트웨어의 고지 및 라이선스 전문은 다음 파일에서 확인할 수
있습니다.

- [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md)
- [`LICENSES/README.md`](LICENSES/README.md)
- [`LICENSES/`](LICENSES/)

위 라이선스들은 해당 제3자 구성요소에 적용되며,
`calendar_widget_on_desktop`의 원본 소스 코드에 적용되는 MIT License를
대체하지 않습니다.

### EXE 배포판에 대한 안내

컴파일되거나 패키징된 EXE 버전에는 위 목록 외에도 Python 런타임 및
추가적인 제3자 의존 패키지가 포함될 수 있습니다.

실제 포함되는 구성요소는 Python 버전, 패키지 버전 및 빌드 환경에 따라
달라질 수 있으며, 각 구성요소에는 각각의 라이선스와 재배포 조건이
적용됩니다.

따라서 새로운 EXE 버전을 배포할 때에는 해당 빌드에 실제로 포함된
제3자 패키지와 라이선스를 별도로 확인하는 것을 권장합니다.

---

## 비공식 프로젝트 및 상표 안내

`calendar_widget_on_desktop`는 비공식 서드파티 오픈소스 프로젝트입니다.

이 프로젝트는 Google LLC와 제휴 관계에 있지 않으며, Google LLC로부터
공식적인 승인, 후원 또는 보증을 받은 프로젝트가 아닙니다.

Google, Google Calendar 및 관련 명칭과 상표는 Google LLC의 상표 또는
자산입니다.

이 프로젝트에서 Google Calendar라는 명칭을 사용하는 것은 지원 대상,
호환성 및 데이터 연동 방식을 설명하기 위한 식별 목적으로만 사용됩니다.

---

## Google Calendar 비공개 iCal 주소에 대한 주의

이 프로그램은 Google Calendar의 `iCal 형식의 비공개 주소`를 사용할 수
있습니다.

이 비공개 주소는 캘린더 데이터에 접근할 수 있게 하는 민감한 정보로
취급하는 것이 좋습니다.

따라서 다음 사항을 권장합니다.

- 비공개 iCal 주소를 GitHub, 공개 게시물 또는 스크린샷에 올리지 마십시오.
- `calendar_widget_config.json`에 비공개 iCal 주소가 저장되어 있다면 해당
  파일을 공개 저장소에 커밋하지 마십시오.
- 가능하면 `calendar_widget_config.json`을 `.gitignore`에 추가하십시오.
- 비공개 iCal 주소가 외부에 노출되었다고 판단되는 경우 Google Calendar
  설정에서 해당 주소를 재설정한 뒤 새 주소를 사용하십시오.

사용자는 이 프로그램에 입력하는 캘린더 주소와 캘린더 데이터에 대해
필요한 접근 권한을 보유하고 있는지 확인할 책임이 있습니다.

---

## 면책조항

이 소프트웨어는 어떠한 종류의 명시적 또는 묵시적 보증 없이
**"있는 그대로(AS IS)"** 제공됩니다.

프로젝트 작성자는 이 프로그램이 모든 환경에서 항상 정상적으로
작동하거나, 표시되는 일정 및 알림 정보가 항상 완전하고 정확하다고
보장하지 않습니다.

사용자는 중요한 일정이나 알림을 이 프로그램에만 의존하지 않고 필요한
경우 원본 캘린더에서도 직접 확인하는 것을 권장합니다.

이 프로젝트의 사용으로 발생하는 결과에 대한 책임은 저장소의
`LICENSE`에 규정된 범위 내에서 제한됩니다.
