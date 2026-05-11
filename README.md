# 한주헌 iOS Developer Portfolio

iOS 개발자 한주헌의 포트폴리오 페이지입니다.  
최종 프로젝트 `쟁여`를 중심으로 담당 역할, 기술적 개선 경험, 사용 기술, 배포 경험을 정리했습니다.

## 소개

`쟁여`는 식재료와 생활용품을 함께 관리할 수 있는 iOS 재고 관리 앱입니다.  
빠른 물품 등록, 재고 수량 관리, 유통기한 확인, 구매 예정 목록 관리까지 이어지는 생활 재고 관리 흐름을 제공합니다.

## 주요 내용

- 재고 조회, 검색, 카테고리 관리, 온보딩, 장바구니 화면 구현
- Coordinator와 DI 구조를 통한 화면 전환 및 의존성 흐름 정리
- NSFetchedResultsController + RxSwift 기반 CoreData 변경 감지 흐름 공통화
- StyledLabel, StyledButton, ProductCell 등 공통 UI 컴포넌트 제작
- 사용자 테스트 피드백 기반 검색어 강조 표시, 비활성 필터 UX 개선
- App Store 배포 과정 경험

## 기술 스택

- Swift, UIKit
- RxSwift
- CoreData
- MVVM, Coordinator
- Vision OCR, AI API
- Supabase, WidgetKit

## 로컬 실행

별도 빌드 과정 없이 `index.html` 파일을 브라우저에서 열어 확인할 수 있습니다.

```bash
open index.html
```

## 배포

GitHub Pages를 통해 정적 페이지로 배포합니다.

1. GitHub Repository의 `Settings`로 이동합니다.
2. `Pages` 메뉴를 선택합니다.
3. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
4. Branch는 `main`, folder는 `/ (root)`로 설정합니다.

## 연락처

- Email: skyofhan@naver.com
- GitHub: https://github.com/TyrHanz
