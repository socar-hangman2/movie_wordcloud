# movie_wordcloud
네이버 영화 리뷰를 사용하여 wordcloud를 만들어보는 프로그램입니다. 구글 코랩과 구글 드라이브를 사용하였습니다.

### 데이터 수집 → 데이터 가공 → 데이터 시각화
- 데이터 수집: 네이버 영화 리뷰 데이터 스크랩을 통해서 데이터를 수집했습니다. [데이터 수집 코드](https://github.com/piaochung/naver_movie_scrap)
- 데이터 가공: Counter 라이브러리를 사용하여 빈도수를 체크하고 단어의 길이가 1이거나 빈도수가 1인 단어들을 제거했습니다.
- 데이터 시각화: WordCloud 라이브러리를 사용하여 데이터 시각화를 진행하였습니다.


![귀멸의 칼날 무한열차 리뷰 분석 이미지](https://github.com/piaochung/movie_wordcloud/blob/main/movie_review_wordcloud/output/%EA%B7%B9%EC%9E%A5%ED%8C%90%20%EA%B7%80%EB%A9%B8%EC%9D%98%20%EC%B9%BC%EB%82%A0_%20%EB%AC%B4%ED%95%9C%EC%97%B4%EC%B0%A8%ED%8E%B8.png)
