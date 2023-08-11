# 🚢 항해 16기 3조 미니 프로젝트
</br>

# 플리플리
이 프로젝트는 사용자들이 좋아하는 가수의 이미지와 노래를 등록할 수 있는 웹 애플리케이션입니다.


## ✔️ 프로젝트 기능 소개
프로젝트의 주요 기능들은 다음과 같습니다.

### 사용자 관련 기능

- 회원 가입:
 
- 로그인:
  1. 일반 로그인
  </br>
  - 로그인 시 AccessToken발급
  - AccessToken만료시 RefreshToken을 통한 AccessToken발급 (개발 중)
  </br>
  2. 소셜 로그인
  </br>
  - 구글 로그인 기능
  - 카카오 로그인 기능

### 게시글 관련 기능

- 댓글 작성:

- 이미지 업로드: 이미지 파일 업로드시 AWS S3 bucket에 저장


## ✔️ 기술적 의사 결정

## ✔️ 설치 방법
### 필요한 의존성 패키지
```
pip install flask pymongo dnspython jwt certifi requests Flask-OAuthlib python-dotenv email_validator boto3
```

## ✔️ 구성원 및 맡은 기능
+ 김민경 / 게시글 작성 페이지
+ 김지나 / 상세 페이지
+ 이준영 / 회원가입
+ 지유진 / 메인 페이지 & 네비게이션 바 & 사이드바
+ 홍종훈 / 로그인
