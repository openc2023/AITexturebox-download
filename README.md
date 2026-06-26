# AITexturebox Download

AITexturebox is a portable Windows tool for extracting perspective texture regions from AI-generated images and arranging them as UV atlas islands.

Created by **Tian Han** for students.

## Download

Go to **Releases** and download:

- `AITexturebox-0.1.0-portable.exe`
- optional Blender add-on: `aitexturebox_live_link.py`

Release page:

https://github.com/openc2023/AITexturebox-download/releases/tag/v0.1.0

## 한국어 안내

AITexturebox는 AI 이미지에서 보이는 입체 박스, 제품 면, 캐릭터 텍스처 영역을 선택해서 UV atlas처럼 정리할 수 있는 Windows portable 프로그램입니다.

설치가 필요 없습니다. `AITexturebox-0.1.0-portable.exe`를 다운로드한 뒤 실행하면 됩니다.

현재 논문 작성과 실험 정리를 위해 소스코드는 임시로 비공개 상태입니다. 이 저장소는 학생과 테스트 참여자가 프로그램을 다운로드하기 위한 배포용 저장소입니다.

## Main Features

- Drag or paste images into the Source area
- Select four source points or drag a rectangle
- Convert selected regions into UV islands
- Move, rotate, scale, and stretch UV islands
- Press `S` to center-scale the selected UV island
- Save and reopen `.aitex` project files
- Export atlas PNG at 512, 1024, 2048, or 4096
- Optional Blender Live Link add-on

## Blender Add-on

Download `aitexturebox_live_link.py` from Releases.

In Blender:

1. Open `Edit > Preferences > Add-ons`.
2. Click `Install...`.
3. Choose `aitexturebox_live_link.py`.
4. Enable `AITexturebox Live Link`.
5. Use the `AITexturebox` tab in the 3D View sidebar.

The add-on can live-refresh the texture and save a final named PNG using `Save Final Texture`.

## License

Temporary binary-only distribution during the paper-writing stage. Source availability may change after publication or experiment completion.
