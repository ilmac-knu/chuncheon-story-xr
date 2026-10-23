# 추억 속의 춘천여행 — 스토리텔링형 XR

기존 VR·AR·MR 체험을 **용산역 출발 → 소양강 처녀상 탐방 → 내 공간에 3D 추억 남기기**라는 하나의 이야기로 연결한 웹 기반 XR 학습 프로젝트입니다.

## 체험 페이지

- **스토리텔링형 XR:** https://ilmac-knu.github.io/chuncheon-story-xr/ (GitHub Pages 배포 후 접속)
- **저장소:** https://github.com/ilmac-knu/chuncheon-story-xr

## 여행의 세 장면

| 순서 | 기술 | 내용 | 체험 주소 | 원본 저장소 |
|---|---|---|---|---|
| 1 | VR | 용산역 집합장소 및 ITX-청춘 | https://ilmac-knu.github.io/Yongsan-ITX-GuideVR/ | https://github.com/ilmac-knu/Yongsan-ITX-GuideVR |
| 2 | AR | 소양강 처녀상 이미지 인식 및 설명판 | https://ilmac-knu.github.io/soyanggang-cheonyeo-ar/ | https://github.com/ilmac-knu/soyanggang-cheonyeo-ar |
| 3 | MR | 소양강 처녀상 3D 배치 및 손가락 조작 | https://ilmac-knu.github.io/soyanggang-cheonyeo-mr/ | https://github.com/ilmac-knu/soyanggang-cheonyeo-mr |

## 기존 통합 선택형과 차이

- **통합 선택형:** https://ilmac-knu.github.io/chuncheon-travel-xr/ — 세 체험을 원하는 순서로 선택
- **스토리텔링형:** 여행 이야기에 따라 VR → AR → MR을 순서대로 체험하고 각 단계를 직접 완료 체크

> XR은 VR, AR, MR을 포괄하는 개념입니다. 이 프로젝트는 세 기술을 하나의 이야기로 연결하는 학습용 웹 안내 페이지이며, 각 XR 기능은 별도 사이트에서 실행됩니다. 기술 간 객체나 공간 상태를 자동 전달하는 기능은 포함하지 않습니다.

## 파일 구조

```text
chuncheon-story-xr/
├── index.html    # 화면, 스타일, 진행 관리 JavaScript
└── README.md     # 프로젝트 설명
```

## 설치 및 공개

1. 이 저장소의 루트에 `index.html`과 `README.md`를 업로드합니다.
2. GitHub **Settings → Pages → Build and deployment**에서 **Deploy from a branch**, **main**, **/(root)**를 설정하고 저장합니다.
3. 배포가 완료되면 https://ilmac-knu.github.io/chuncheon-story-xr/ 로 접속합니다.

## 사용 방법

1. 각 단계의 **체험 열기**를 누르면 새 탭에서 원본 VR·AR·MR 페이지가 열립니다.
2. 체험을 마친 뒤 원래 탭으로 돌아옵니다.
3. 완료 확인란을 직접 체크하면 다음 장면으로 이동할 수 있습니다.
4. 진행 상태는 같은 브라우저의 `localStorage`에 저장되므로 새로고침해도 유지됩니다. 다른 기기에는 동기화되지 않습니다.
5. 마지막 장면까지 완료하면 여행 완료 화면이 나타납니다.

## 체험 시 주의 사항

- AR은 카메라 권한 및 **별도로 표시하거나 인쇄한 소양강 처녀상 인식 이미지**가 필요합니다.
- MR의 현실 공간 배치는 지원되는 스마트폰·브라우저에서만 작동할 수 있습니다.
- 단계 완료는 자동 판정이 아닌 사용자의 직접 체크 방식입니다.
- 외부 이미지나 추가 라이브러리 없이 `index.html` 단일 파일로 시작할 수 있습니다.

## 교육 활용

전자책의 XR 통합 사례, 스마트폰 기반 확장현실 학습, 여행·관광 스토리텔링 실습에 활용할 수 있습니다.
