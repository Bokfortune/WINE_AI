# 시스템 아키텍쳐
  - Frontend
      - streamlit 기반
      - 이미지 업로드, 설명입력, 결과표시(리뷰, 유사도, 상세추천)
  - Backend
      - sommelier.py , 이미지 분석, 벡터 DB검색, LLM 프롬프트 처리
  - 외부서비스
      - OPENAI API : GPT-4o mini (LLM) , exte-embedding-3-smaiil(임베딩)
  - 환경설정
      -  .env 파일로 처라

# 주요 사용 기술
  - 주요 라이브러리
     - openai, langchain_openai, ..
  - 모델
     - 토큰 임베딩 : exte-embedding-3-smaiil
     - LLM : GPT-4o - mini(LLM)
  - 벡터 DB
     - Pincone(us-east1-aws, cosine metric, dimension = 1536)
