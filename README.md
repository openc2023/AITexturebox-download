# AITexturebox Download

AITexturebox is a simple texture-making tool for students. It helps students extract flat texture areas from AI-generated images, product images, package mockups, or reference images, then arrange them as UV-like texture islands.

Author: **Tian Han**

## 다운로드

Releases 페이지에서 아래 파일을 다운로드하세요.

- `AITexturebox-0.1.0-portable.exe`
- Blender 연동이 필요하면 `aitexturebox_live_link.py`

다운로드 페이지:

https://github.com/openc2023/AITexturebox-download/releases/tag/v0.1.0

설치가 필요 없습니다. exe 파일을 실행하면 바로 사용할 수 있습니다.

## 학생들을 위한 목적

AITexturebox는 3D 모델링이나 UV 작업을 처음 배우는 학생들이 더 쉽게 텍스처를 만들 수 있도록 만든 도구입니다.

AI 이미지나 제품 이미지에는 원근감이 있는 면이 많습니다. 이 프로그램은 그런 면을 네 점으로 선택한 뒤 평평한 텍스처처럼 펼쳐서 UV atlas 영역에 배치할 수 있게 합니다.

이 도구의 목표는 복잡한 전문 UV 편집기를 대체하는 것이 아니라, 학생들이 수업과 실습에서 빠르게 텍스처를 만들고 결과를 확인할 수 있게 하는 것입니다.

## 주요 기능

- Source 영역으로 이미지 드래그 앤 드롭
- 복사한 이미지를 붙여넣어 불러오기
- 네 점 선택 또는 사각형 드래그로 텍스처 영역 선택
- 원근감이 있는 면을 평평한 UV island로 변환
- UV island 이동, 회전, 확대/축소, 가로/세로 늘리기
- `S` 키로 선택한 UV island를 중심 기준으로 등비 확대/축소
- `Seamless texture` 옵션으로 가장자리 연결 보정
- `.aitex` 프로젝트 저장 및 다시 열기
- 512, 1024, 2048, 4096 크기의 atlas PNG 저장
- Blender Live Link Add-on 지원

## Blender Add-on

Blender에서 실시간으로 텍스처를 확인하려면 Releases에서 `aitexturebox_live_link.py`를 다운로드하세요.

Blender 사용 순서:

1. `Edit > Preferences > Add-ons`를 엽니다.
2. `Install...`을 클릭합니다.
3. `aitexturebox_live_link.py`를 선택합니다.
4. `AITexturebox Live Link` Add-on을 활성화합니다.
5. 3D View 오른쪽 Sidebar의 `AITexturebox` 탭을 사용합니다.

Add-on은 live texture를 자동 갱신할 수 있고, `Save Final Texture` 기능으로 최종 PNG를 이름을 지정해 저장할 수 있습니다.

## 사용 제한

현재 AITexturebox는 논문 심사 및 실험 정리 단계에 있습니다.

AITexturebox는 학생과 테스트 참여자에게 무료로 제공됩니다. 단, 상업적 사용은 허용되지 않습니다.

이 기간 동안 다음 행위는 허용되지 않습니다.

- 상업적 사용 또는 판매
- 프로그램을 수정한 버전으로 재배포
- 이름이나 UI만 바꾼 파생 버전 배포
- 파일을 뜯어 고쳐 다른 소프트웨어처럼 공개
- 논문 연구 결과와 혼동될 수 있는 2차 수정본 공개

학생과 테스트 참여자는 다운로드한 프로그램을 수업, 실습, 개인 학습, 비상업적 연구 참여 목적으로 무료 사용할 수 있습니다. 단, 수정 버전이나 파생 버전은 논문 심사 단계가 끝나기 전까지 공개하지 말아 주세요.

## English Notice

AITexturebox is a simple texture-making tool designed for students. It helps users extract perspective texture regions from AI-generated images and arrange them as UV-like islands.

Author: **Tian Han**

The software is free for students and testers for non-commercial class practice, personal learning, and research participation. Commercial use is not permitted.

The source code is temporarily private while the related paper is under review. During this review period, modified versions, derivative versions, renamed copies, or redistributed edited builds are not permitted. Please do not publish modified or derivative versions until the paper review stage is complete.
