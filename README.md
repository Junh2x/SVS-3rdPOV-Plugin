# SVS-3rdPOV-Plugin

*** Test Version ***
테스트 버전입니다.  
테스팅 및 피드백을 위해 우선 배포하며, 플러그인 및 리드미 업데이트 예정입니다.  

개요  
SVS 3인칭 시점 모드는 Summer Vacation Scrambled(SVS) 게임에 3인칭 시점 카메라 모드를 도입하는 플러그인입니다.  

주요 기능  
F4키 입력을 통한 3인칭 / 맵 뷰 전환  
F5키 입력을 통한 시점 대상 NPC 전환  
마우스 휠 클릭 + 드래그: x, y축 조정  
마우스 좌 클릭 + 우클릭 + 드래그: z축 조정  
마우스 우클릭 + 드래그: 기준점에 대한 카메라 상대 위치 조정  
마우스 휠 업 / 다운: 확대 및 축소  
플레이어 캐릭터 자동 추적  

주의사항  
- 반드시 설치 전 백업해주세요.  
- 테스트 버전이므로 오류 및 버그가 있을 수 있습니다. 관련 채널로 피드백, 버그 제보를 해주세요.
- 3인칭 시점은 외부 맵에서만 실행됩니다.

알려진 이슈  
- 다른 맵에 있는 NPC로 시점을 전환할 경우, 맵과 NPC가 렌더링 되지 않는 문제 (플레이어 NPC가 맵 이동할 경우, 렌더링 됨.)  
- 3인칭 시점 모드에서는 맵 이동 버튼 UI가 비활성화되지만, 대화 및 이벤트 후 다시 생성되는 문제 (임시 조치: F4 토글을 다시 실행해 제거 가능)  

설치 방법  
1. Release 탭(<a href="https://github.com/Junh2x/SVS-3rdPOV-Plugin/releases">다운로드</a>)에서 모드 압축 파일을 다운로드 받고 압축 해제합니다.  
2. 게임 폴더 내 "BepInEx\plugins\"폴더로 ThirdPOV.dll 파일을 옮깁니다.  
3. 게임 실행 후, map 씬에서 F4키로 Toggle하고, F5키로 타겟 NPC를 전환합니다.  

기타  
- 본 개발자는 유니티 개발자가 아니며, 버그 및 최적화 이슈가 발생할 수 있습니다.  
- 공부 및 모드 개발, 개선을 위해 소스 코드와 자료, 정보가 필요하신 경우 관련 채널을 통해 요청주시면 모두 제공할 예정입니다.
