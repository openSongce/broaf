# TEAM Broaf

### 📍 GPS 기반 SNS 앱 "Broaf"

> **내 주변**을 기록하고, 지도로 공유하는 **로컬 SNS**  
> 카카오맵 위에 타임라인과 경로를 얹었습니다

<br>

## 📑 목차
1. [프로젝트 소개](#-프로젝트-소개)
2. [주요 기능](#-주요-기능)
3. [주요 화면 및 기능 소개](#-주요-화면-및-기능-소개)
4. [주요 기술](#-주요-기술)
5. [기술 스택](#-기술-스택)
6. [시스템 아키텍처](#%EF%B8%8F-시스템-아키텍처)
7. [팀원 정보](#-팀원-정보)

<br>

## 📋 프로젝트 소개

<img src="assets/broaf_icon.png" height="160">

**Broaf**는 사용자의 위치·동선을 기반으로 **포스트를 작성**하고,  
**지도·리스트 UI**로 타임라인을 확인하는 **GPS 기반 SNS 앱**입니다.  
개발 당시 여러 작업(지도, 경로, 리스트, 학업) 병행으로 부담이 컸지만,  
우선순위 재정의·작업 분할·일정 관리로 프로젝트를 완수했습니다.

### 프로젝트 정보
| 항목 | 내용 |
| --- | --- |
| 서비스명 | Broaf |
| 사용 기술 | **Java**, Android Studio, **Firebase**, **Kakao Map API** |
| 역할 | **지도 경로 표시**, **리사이클러뷰 목록 UI**, 인증/데이터 연동 |

<br>

## ✨ 주요 기능

1. **지도 피드**: 내 주변 포스트 클러스터링, 상세 보기   
2. **게시글 작성**: 사진/텍스트/위치 태그, 공개 범위 설정  
3. **알림**: 댓글/좋아요/팔로우 알림

<br>

## 🚀 주요 화면 및 기능 소개

- **지도 화면**: 마커·클러스터 · 현재 위치 추적  
- **리스트**: RecyclerView + ViewHolder 패턴
- **작성/상세**: 위치 태그·이미지 첨부·댓글

<p align="left">
  <img src="asset/broaf_map.gif" height="480" style="margin-right: 14px;">
  <img src="asset/broaf_list.gif" height="480" style="margin-right: 14px;">
</p>

<br>

## 🔬 주요 기술

<details>
<summary><strong>지도 & 경로</strong></summary>

- **Kakao Map API** 마커/경로(Polyline)  
- 현재 위치 추적
- 경로 데이터 직렬화/복원
</detail능 | png33030@yu.ac.kr |
| 남은주 | 회원가입 및 로그 | yu21iarty@gmail.com |
| 최지원 | 지도 및 공통 UI | polonej@ynu.ac.kr |

### [🎨 Figma](https://www.figma.com/design/ojjw6nM2PrwB7v2TqnlNUr/SE---Broaf?node-id=0-1&t=xyoNiMJauPW6ysmE-1)
