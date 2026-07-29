> [简体中文](../README.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# AutoX CAN

> CAN / CAN FD 로그 분석을 위한 Windows 데스크톱 도구입니다. 로그와 프로토콜 정의를 가져오고 신호를 선택하면, 대화형으로 조작할 수 있으며 오프라인으로 공유할 수 있는 HTML 분석 보고서를 생성합니다.

[**Windows V1.2.0 다운로드**](https://github.com/hsj521/AutoX-CAN-Releases/releases/download/v1.2.0/AutoX_CAN_Setup_1.2.0.exe) · [모든 릴리스 보기](https://github.com/hsj521/AutoX-CAN-Releases/releases)

## AutoX CAN의 장점

- **완전한 로컬 처리**: 로그, 프로토콜 파일 및 보고서는 모두 PC에서 처리됩니다. 서비스를 시작하지 않고, 데이터를 업로드하지 않으며, 네트워크에 접근하지 않습니다.
- **일반적인 차량 로그 형식 지원**: Vector ASC 및 BLF 로그를 읽고 클래식 CAN 및 일반적인 CAN FD 로그를 지원합니다.
- **프로토콜 기반 디코딩**: DBC 또는 XLSX 정의를 읽어 원시 프레임을 물리값 신호로 디코딩합니다.
- **다중 CAN 채널 재생**: CAN 1–8 채널을 선택하여 서로 다른 채널에서 동일한 CAN ID를 가진 프레임이 함께 디코딩되는 것을 방지합니다.
- **복합 분석에 적합한 표시**: 선택한 각 신호에 독립적인 색상 Y축을 제공하여 단위와 값 범위가 다른 신호를 쉽게 비교할 수 있습니다.

## 3단계로 로그 분석

1. `.dbc` / `.xlsx` 프로토콜 정의와 `.asc` / `.blf` CAN 로그를 가져옵니다.
2. 재생 채널을 선택한 후 분석할 신호를 검색하여 추가합니다.
3. 하나의 독립형 HTML 보고서를 생성합니다. 브라우저에서 확대, 이동, 값 확인 또는 오프라인 공유가 가능합니다.

## 주요 기능

| 기능 | 설명 |
| --- | --- |
| ASC / BLF 분석 | ASC 및 BLF 로그를 읽고 두 형식 간에 로컬 변환을 지원합니다. |
| DBC / XLSX 디코딩 | Intel / Motorola 바이트 순서, 부호 있는 값, 스케일, 오프셋 및 기본 멀티플렉스 신호를 지원합니다. |
| 신호 검색 | 신호명, 메시지명 또는 CAN ID로 검색하고 여러 신호를 함께 분석할 수 있습니다. |
| 대화형 보고서 | HTML 보고서에서 확대, 이동, 공유 호버 값, 시간 범위 선택 및 Y축 조정이 가능합니다. |
| 2점 측정 | 두 샘플을 선택해 시간 간격을 비교하고 동일 신호의 값 차이도 확인할 수 있습니다. |
| Windows 데스크톱 UI | 고 DPI 다크 인터페이스를 제공하며 F11 전체 화면과 Esc 종료를 지원합니다. |

## 다운로드 및 설치

현재 정식 버전: **V1.2.0**

1. [`AutoX_CAN_Setup_1.2.0.exe`](https://github.com/hsj521/AutoX-CAN-Releases/releases/download/v1.2.0/AutoX_CAN_Setup_1.2.0.exe)를 다운로드합니다.
2. 설치 프로그램을 두 번 클릭하고 설치 마법사의 안내를 따릅니다.
3. 설치 후 시작 메뉴 또는 바탕 화면 바로 가기에서 AutoX CAN을 실행합니다.

SHA256 체크섬과 릴리스 노트는 [V1.2.0 Release 페이지](https://github.com/hsj521/AutoX-CAN-Releases/releases/tag/v1.2.0)에서 확인할 수 있습니다.

## 피드백

설치 또는 사용 중 문제가 발생하면 AutoX CAN 버전, Windows 버전 및 재현 절차를 포함하여 [Issues](https://github.com/hsj521/AutoX-CAN-Releases/issues)에 등록해 주세요.

---

이 저장소는 설치 프로그램, 릴리스 노트 및 체크섬만 배포합니다. **AutoX CAN 소스 코드는 포함하지 않습니다.**