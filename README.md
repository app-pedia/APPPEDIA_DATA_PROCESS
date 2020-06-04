—안드로이드랭크—
1.developer(AR)-개발자의 id정보를 get(크롤링)
2.developer_data.xlsx-개발자의 id 엑셀
3.developer_info(AR)-개발자의 id를 통해 개발자의 정보를 get(2번 엑셀 데이터를 읽어와서 크롤링)
4.xl_to_data(AR)-개발자의 모든 앱 id들을 get(크롤링)
5.all_id(AR).xlsx-개발자의 모든 앱 id 엑셀
6.data_parser(AR)-4번에서 크롤링한 앱들의 정보를 get(크롤링)


--플레이스토어--
7.data_parser(PS)- 플레이스토어 앱들을 정보를 get(크롤링)
8.all_id(PS).xlsx-플레이스토어 앱들을 id 엑셀
9.text_rank-플레이스토어 앱들을 url(크롤링), 카테고리,(크롤링) 기능(크롤링하여 토큰화), 앱 설명(크롤링)
10.full_data.xlsx- 9번의 모든 data를 포함 
