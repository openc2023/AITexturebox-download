# TexPeel Lite Download

TexPeel Lite는 학생들이 투시가 있는 이미지에서 텍스처 영역을 쉽게 추출하고, UV island처럼 배치해 3D 모델 텍스처 제작을 연습할 수 있도록 만든 무료 학습용 도구입니다.

Author: **Tian Han**

## 다운로드

GitHub Releases 페이지에서 최신 파일을 다운로드하세요.

[TexPeel Lite v0.1.0 다운로드](https://github.com/openc2023/TexPeel-download/releases/tag/v0.1.0)

포터블 EXE:

- `TexPeel-Lite-0.1.0-portable.exe`

Live Link 플러그인:

- `TexPeel_Blender_Live_Link-0.1.0.zip`
- `TexPeel_Maya_Live_Link-0.1.0.zip`

설치 과정은 필요하지 않습니다. EXE 파일을 실행하면 바로 사용할 수 있습니다.

## 학생들을 위한 목적

TexPeel Lite는 3D 모델링과 UV 작업을 처음 배우는 학생들이 더 쉽게 텍스처를 만들 수 있도록 만든 도구입니다.

AI 이미지, 제품 이미지, 패키지 목업, 참고 이미지에는 투시가 있는 면이 많습니다. TexPeel Lite는 그런 면을 네 점으로 선택한 뒤 평평한 텍스처 조각으로 보정하고, UV atlas 공간에 배치할 수 있게 도와줍니다.

이 도구의 목적은 전문 UV 편집기를 대체하는 것이 아니라, 학생들이 수업과 실습에서 빠르게 텍스처를 만들고 결과를 확인할 수 있게 하는 것입니다.

## 주요 기능

- Source 영역으로 이미지 드래그 앤 드롭
- 복사한 이미지를 붙여넣어 불러오기
- 여러 이미지를 프로젝트 안에 함께 관리
- 네 점 선택 또는 사각형 드래그로 텍스처 영역 선택
- 투시가 있는 면을 평평한 UV island로 변환
- UV island 이동, 회전, 확대/축소, 가로/세로 스케일 조정
- `S` 키로 선택한 UV island를 중심 기준으로 등비 확대/축소
- Edge Blend로 가장자리 연결 보정
- Heal Area로 작은 로고, 창문, 얼룩, 반복 텍스처 영역 보정
- 이미지/텍스트 overlay layer 추가
- `.aitex` 프로젝트 저장 및 다시 열기
- 512, 1024, 2048, 4096 크기의 atlas PNG 저장
- PNG 배경을 투명 또는 지정 색상으로 선택
- Blender Live Link 및 Maya Live Link 지원
- 익명 CSV 작업 로그 내보내기

## Blender Live Link

Blender에서 실시간으로 텍스처를 확인하려면 Releases에서 `TexPeel_Blender_Live_Link-0.1.0.zip`을 다운로드하세요.

기본 사용 순서:

1. Blender에서 `Edit > Preferences > Add-ons`를 엽니다.
2. `Install...`을 클릭합니다.
3. ZIP 안의 `texpeel_live_link.py`를 선택합니다.
4. `TexPeel Live Link` Add-on을 활성화합니다.
5. 3D View 오른쪽 Sidebar의 `TexPeel` 패널을 사용합니다.

## Maya Live Link

Maya에서 실시간으로 텍스처를 확인하려면 Releases에서 `TexPeel_Maya_Live_Link-0.1.0.zip`을 다운로드하세요.

ZIP 안의 `texpeel_maya_live_link.py`와 README 안내를 사용하세요.

## 사용 제한

현재 TexPeel Lite는 논문 심사 및 실험 정리 단계에 있습니다.

TexPeel Lite는 학생과 테스트 참여자에게 무료로 제공됩니다. 단, 상업적 사용은 허용되지 않습니다.

이 기간 동안 다음 행위는 허용되지 않습니다.

- 상업적 사용 또는 판매
- 프로그램을 수정한 버전으로 재배포
- 이름이나 UI만 바꾼 파생 버전 배포
- 파일을 뜯어 고쳐 다른 소프트웨어처럼 공개
- 논문 연구 결과와 혼동될 수 있는 2차 수정본 공개

학생과 테스트 참여자는 다운로드한 프로그램을 수업, 실습, 개인 학습, 비상업적 연구 참여 목적으로 무료 사용할 수 있습니다.

## English Notice

TexPeel Lite is a lightweight texture extraction and UV atlas layout tool designed for students. It helps users extract perspective texture regions from AI-generated images, product images, package mockups, and reference images, then arrange them as UV-like islands.

Author: **Tian Han**

The software is free for students and testers for non-commercial class practice, personal learning, and research participation. Commercial use is not permitted.

The source code is temporarily private while the related paper is under review. During this review period, modified versions, derivative versions, renamed copies, or redistributed edited builds are not permitted. Please do not publish modified or derivative versions until the paper review stage is complete.
