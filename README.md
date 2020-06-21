# AndroidRank

: Developer
1. developer(AR) - 개발자의 id 정보를 Crawling하여 developer_data.xlsx에 insert
2. developer_info(AR) - 개발자의 id를 바탕으로 개발자의 정보를 Crawling

: Application
1. xl_to_data(AR) - 개발자의 모든 앱 id를 Crawling하여 all_id(AR).xlsx에 insert
2. data_parser(AR) - 앱의 id와 api_key를 바탕으로 앱의 정보를 Get



# PlayStore

: Application
1. data_parser(PS) - all_id(PS)를 바탕으로 앱의 정보를 Crawling
2. text_rank - 앱의 정보를 url(크롤링), 카테고리,(크롤링) 기능(크롤링하여 토큰화), 앱 설명(크롤링)으로 분류하여 full_data.xlsx에 insert
