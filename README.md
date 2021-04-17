## movie_wordcloud
네이버 영화 리뷰를 사용하여 wordcloud를 만들어보는 프로그램입니다. 구글 코랩과 구글 드라이브를 사용하였습니다.

## 파일 목록
|이름|내용|
|-|-|
|review_scraper|리뷰를 가져와서 데이터 시각화를 하는 코드입니다.|
|output|결과 이미지를 저장하는 폴더입니다.|

## 데이터 수집 → 데이터 가공 → 데이터 시각화
- 데이터 수집: 네이버 영화 리뷰 데이터 스크랩을 통해서 데이터를 수집했습니다. [데이터 수집 코드](https://github.com/piaochung/naver_movie_scrap)
- 데이터 가공: Counter 라이브러리를 사용하여 빈도수를 체크하고 단어의 길이가 1이거나 빈도수가 1인 단어들을 제거했습니다.
- 데이터 시각화: WordCloud 라이브러리를 사용하여 데이터 시각화를 진행하였습니다.

## 결과 이미지
![미니언즈 리뷰 분석 이미지](https://github.com/piaochung/movie_wordcloud/blob/main/movie_review_wordcloud/output/%EB%AF%B8%EB%8B%88%EC%96%B8%EC%A6%88.png)

## Dependency
- python3
- konlpy
- wordcloud
- pandas
- matplotlib
