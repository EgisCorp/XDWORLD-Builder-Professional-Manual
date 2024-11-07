# - 업데이트 내역 -

### 5.1.12

-   Issues 처리
    -   [issues 85](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/85)
    -   [issues 83](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/83)
    -   [issues 82](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/82)
    -   [issues 77](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/77)
-   기능
    -   지도 저장 기능 수정(xdw -> xdm 변경)
        -   사용자 지도 저장 기능 추가.
        -   저장 구조 변경으로 xdw 파일은 미지원.
    -   건물 LOD Texture 기능 수정
    -   포인트 클라우드 파일 포맷 버전 수정에 따른 기능 변경

### 5.1.11

-   Issues 처리
    -   [issues 84](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/84)
    -   [issues 80](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/80)
    -   [issues 78](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/78)
    -   [issues 76](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/76)
    -   [issues 75](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/75)
-   기능
    -   레이어 다중 삭제 기능 수정.
    -   레이어 명칭 수정 기능 및 관련 기능 추가.
    -   지형 음수 처리 기능.

### 5.1.10

-   레이어 삭제 모듈 수정 (https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/72 처리)
-   POI 가공, 가시화 모듈 수정 (https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/63 처리)
-   선택된 객체 해제 기능 추가

### 5.1.10

-   POI 가공, 가시화 모듈 수정 ([issues73](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/73) 처리완료)
-   레이어 삭제 모듈 수정 ([issues72](https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/72) 처리완료)
-   선택된 객체 해제 기능 추가

### 5.1.9

-   3DS, OBJ 가공 수정
-   XND 파일 가공, 가시화 수정

### 5.1.8

-   POI 가공 기능 수정

### 5.1.6

-   배경 지도 기능 업데이트
    -   사용자 지정 Server 지도 설정 기능 추가
-   이슈 처리
-   https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/67 처리
-   https://github.com/EgisCorp/XDWORLD-Builder-Professional/issues/65 처리

### 5.1.5

-   VWorld API Key 업데이트

### 5.1.4

-   LOD1 지형결합, 층수 옵션 추가
-   XND 패킹 기능 잠금 해제

### 5.1.3

-   LOD1 가공결과 meta 추가
-   작은 객체 랜더링 옵션 추가 (WebGL에서 확인시 작은 객체 랜더링 옵션 확인)

### 5.1.2

-   LOD1 가공시 높이값 오류 수정

### 5.1.1

-   LOD1 가공 오류 수정 및 상대높이 UI 추가 (건물최저높이를 제외한 모든 값은 상대높이지만, DEM의 해상도가 5m 이하일 경우 절대높이로 구축)

### 5.1.0

-   Web 가시화 엔진 적용

### 5.0.6

-   3DS 가공 오류 수정

### 5.0.5

-   영상 병렬 처리
    -   기존 병렬처리 "사용" 기능의 경우 복수개 영상을 동시에 병렬로 가공
        -   개별 영상은 일반 속도로 가공
    -   새로 추가된 병렬처리 "사용(한장씩)" 기능의 경우 한장의 영상에서 여러 지역을 병렬로 가공
        -   입력된 영상이 한장, 복수장 관계없이 순서대로 한장씩 가공하며 한장을 병렬로 가공함.
    -   병렬 처리 진행 상태바 표시 방식 개선

### 5.0.4

-   UI 개선

### 5.0.4 (Vietnam)

-   UI 개선

### 5.0.3

-   가공 속도 개선

    -   Erdas img 포맷 (지형, 영상) 가공 속도 개선

-   영상 가시화

    -   영상 가시화 레벨 제한 해제 (기존 가공 후 영상 해상도 제대로 안보였던 오류 처리)

-   사용자 지도 예외처리
    -   영상, 지형 개별 처리 (ex. 영상만 입력할 경우 지형은 기본 지형으로 설정)

### 5.0.2 (Vietnam)

-   Version 5.0.2 사용
    -   베트남어 UI
    -   병렬처리 기능 제외

### 5.0.2

-   Shape 지원 가공 기능 중 하나인 POI 가공 기능 수정
    -   최소, 최대 레벨 UI 추가
    -   폰트 UI 추가
    -   지형 폴더 UI 추가
-   영상, 지형 가공 기능 보강
    -   영상 투명 색상 2 추가, 투명 색상 1은 우선 적용함.
    -   영상 병렬 처리 UI 추가
    -   영상 품질 조절 UI 추가
    -   영상 색상 품질 밝게 조절
    -   영상, 지형 작업 log 추가, 비정상적인 종료 후에도 이전과 같은 설정으로 재시작하면 비정상 종료 직전까지 했던 작업에 이어서 진행
    -   영상 생성 시작 레벨,종료 레벨 추가

### 5.0.1

-   영상병렬가공 PNG 기능 수정
-   LOD1 포맷 가공 오류 수정

### 5.0.0

-   LOD1 지형결합, 건물지반 방식 추가
-   라이센스 관련 기능 추가
-   타임락 기능 추가
-   다중영상 가공 기능
-   포인트 클라우드 색상 표현안되는 문제
-   포인트 클라우드 가시화 시 가시화 엔진과 빌더 화면 위치가 다른 문제
-   지하 오브젝트 가시화 기능
