# SVS-3rdPOV-Plugin
## 한국어

***Test Version***  
테스트 버전입니다. 아직 부족한 점과 버그가 있을 수 있습니다. 테스트와 피드백을 위해 배포합니다.
<br><br>

## 개요  
SVS 3인칭 시점 모드는 **Summer Vacation Scrambled(SVS)** 게임에 3인칭 시점 카메라 모드를 도입하는 플러그인입니다.
<br><br>

## 주요 기능  
- **F4키**: 3인칭 시점과 맵 뷰 전환  
- **F5키**: 시점 대상 NPC 전환  
- **마우스 휠 클릭 + 드래그**: X, Y축 조정  
- **마우스 좌클릭 + 우클릭 + 드래그**: Z축 조정  
- **마우스 우클릭 + 드래그**: 기준점에 대한 카메라 상대 위치 조정  
- **마우스 휠 업/다운**: 카메라 확대 및 축소  
- **캐릭터 이동**: W, A, S, D키 이동 / Left Shift 달리기  
<br><br>

## 주의사항  
- **백업 필수**: 설치 전 반드시 게임 파일을 백업해주세요.  
- 테스트 버전이므로 오류 및 버그가 있을 수 있습니다. 피드백 및 버그 제보는 관련 채널을 통해 부탁드립니다.  
- 3인칭 시점은 **외부 맵에서만** 실행됩니다. (앞으로 출시될 커스텀 모드 맵들과 호환을 위해 검토중입니다.)
- 이동 및 조작은 플레이어 NPC만 가능합니다.
<br><br>

## 알려진 이슈  
- 다른 맵에 있는 NPC로 시점을 전환할 경우, 맵과 NPC가 렌더링되지 않는 문제  
  (플레이어 NPC가 맵 이동 시 렌더링 정상화)
<br><br>

## 설치 방법  
1. [Release 탭](https://github.com/Junh2x/SVS-3rdPOV-Plugin/releases)에서 모드 압축 파일을 다운로드하고 압축을 해제합니다.  
2. 게임 폴더 내 **`BepInEx\plugins\`** 폴더에 **ThirdPOV.dll** 파일을 옮깁니다.  
3. 게임을 실행한 후, **map** 씬에서 **F4** 키로 3인칭 시점을 토글하고, **F5** 키로 타겟 NPC를 전환합니다.
<br><br>

## 기타  
- 본 개발자는 유니티 전문 개발자가 아니므로, 최적화 문제나 버그가 있을 수 있습니다.  
- 공부 또는 모드 개발, 개선을 위해 소스 코드와 관련 자료가 필요하신 경우, 관련 채널을 통해 요청 주시면 모두 제공 가능합니다.

---

## English

***Test Version***  
This is a test version. It may have bugs or missing features, and it is released for testing and feedback purposes.
<br><br>

## Overview  
The SVS 3rd Person View Mode is a plugin that introduces a third-person camera mode to the **Summer Vacation Scrambled (SVS)** game.
<br><br>

## Main Features  
- **F4 Key**: Toggle between 3rd person view and map view  
- **F5 Key**: Switch NPC for camera focus  
- **Mouse Wheel Click + Drag**: Adjust X and Y axis  
- **Left + Right Click + Drag**: Adjust Z axis  
- **Right Click + Drag**: Adjust camera position relative to the target  
- **Mouse Wheel Up/Down**: Zoom in/out  
- **Character Movement**: Move with W, A, S, D keys / Run with Left Shift
<br><br>

## Notes  
- **Backup Required**: Please backup your game files before installing the plugin.  
- As this is a test version, it may contain bugs and issues. Please report any bugs or provide feedback through the appropriate channels.  
- The 3rd person mode only works in **outdoor map scenes**. (We are currently reviewing this for compatibility with upcoming custom mod maps.)
- Only player NPCs can move and manipulate.
<br><br>

## Known Issues  
- When switching focus to an NPC in a different map, the map and NPC may not render properly  
  (Fixed when the player NPC moves to the map)  
<br><br>

## Installation Instructions  
1. Download the mod from the [Release tab](https://github.com/Junh2x/SVS-3rdPOV-Plugin/releases) and extract the files.  
2. Move the **ThirdPOV.dll** file to your game's **`BepInEx\plugins\`** folder.  
3. Run the game and toggle the 3rd person view with the **F4** key in the **map** scene. Use **F5** to switch the target NPC.
<br><br>

## Additional Information  
- The developer is not a Unity expert, so there may be performance issues or bugs.  
- If you need the source code or any related materials for learning or improving the mod, feel free to request them through the appropriate channels.
