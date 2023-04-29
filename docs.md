# 치환자 목록 #
https://tistory.github.io/document-tistory-skin/
<br>
<br>


## 공통 치환자 ##
---

### 블로그 정보 ###
|  |  |
| - | - |
[##_title_##] | 블로그 제목
[##_image_##] | 블로그 대표 이미지 url
[##_blog_image_##] | 블로그 대표 이미지를 포함한 IMG 태그
[##_desc_##] | 블로그 설명
[##_blogger_##] | 블로그 소유자의 필명
<br>

### 블로그 URL ###
|  |  |
| - | - |
[##_blog_link_##] | 블로그 url
[##_rss_url_##] | rss feed 주소
[##_taglog_link_##] | 태그로그 url
[##_guestbook_link_##] | 방명록 url
<br>

### 기타 ###
|  |  |
| - | - |
[##_page_title_##] | 페이지 제목
[##_blog_menu_##] | 블로그 메뉴 리스트
[##_body_id_##] | 페이지 타입에 따른 id
<br>

### 광고 치환자 ###
|  |  |
| - | - |
[##revenue_list_upper##] | 블로그 홈/목록 상단
[##revenue_list_lower##] | 블로그 홈/목록 하단
<br>


## 홈 커버 ##
|  |  |
| - | - |
<s_cover_group> | 커버 그룹 치환자
<s_cover_rep> | 개별 커버 표시
<s_cover> | 개별 커버. name 애트리뷰트로 이름을 지정한다. 정의되지 않은 이름의 커버는 사용되지 않는다.
[##_cover_title_##] | 개별 커버 타이틀
<s_cover_url> | 커버 url이 있는 경우에만 치환
[##_cover_url_##] | 개별 커버 url
<s_cover_item> | 개별 커버 컨텐츠
<s_cover_item_not_article_info> | 컨텐츠가 글이 아닌 경우에만 치환 (내부 치환자는 s_cover_item에 직접 사용 가능)
<s_cover_item_article_info> | 컨텐츠가 글인 경우에만 치환
[##_cover_item_title_##] | 컨텐츠 타이틀
[##_cover_item_summary_##] | 컨텐츠 요약/내용
[##_cover_item_url_##] | 컨텐츠 url
<s_cover_item_thumbnail> | 컨텐츠 이미지가 있는 경우에만 치환
[##_cover_item_thumbnail_##] | 컨텐츠 이미지
~ [##_cover_item_category_##] | 카테고리 명
~ [##_cover_item_category_url_##] | 카테고리 url
~ [##_cover_item_date_##] | 글 발행 날짜/시간 (yyyy.mm.dd HH:MM)
~ [##_cover_item_simple_date_##] | 글 발행 날짜 (yyyy.mm.dd)
~ [##_cover_item_comment_count_##] | 댓글 수
<br>

#### 홈 커버 치환자 구성
---
+ <s_cover_group>
  + <s_cover_rep>
    + <s_cover>
      + [##_cover_title_##]
      + <s_cover_url>
        + [##_cover_url_##]
      + <s_cover_item>
        + <s_cover_item_not_article_info>
          + [##_cover_item_title_##]
          + [##_cover_item_summary_##]
          + [##_cover_item_url_##]
          + <s_cover_item_thumbnail>
            + [##_cover_item_thumbnail_##]
        + <s_cover_item_article_info>
            + [##_cover_item_title_##]
            + [##_cover_item_summary_##]
            + [##_cover_item_url_##]
            + <s_cover_item_thumbnail>
              + [##_cover_item_thumbnail_##]
            + [##_cover_item_category_##]
            + [##_cover_item_category_url_##]
            + [##_cover_item_date_##]
            + [##_cover_item_simple_date_##]
            + [##_cover_item_comment_count_##]
---
<br>


## 스킨 옵션 ##
|  |  |
| - | - |
| <s_if_var_{VARIABLE_NAME}> | 옵션의 값이 있으면 (bool 타입인 경우 true이면) 치환
| <s_not_var_{VARIABLE_NAME}> | 옵션의 값이 없으면 (bool 타입인 경우 false이면) 치환
| [##_var_{VARIABLE_NAME}_##] | 옵션의 값
<br>

