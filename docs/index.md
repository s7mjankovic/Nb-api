<!-- - Welcome to Nova Borba API -->



## API

- Frontpage layout.
- All categories
- Single category
- Single news
- Comments for single news
- All pages
- Single page



## Frontpage layout

    Link        :    http://www.novaborba.rs/api/v1/frontpages

    Description :	 Current mobile layout with 15 news in order.

   	Return      :    - news title
   					 - news slug
   					 - news summary
   					 - news images (full, thumb_mid and thumb)




## All categories

    Link        :    http://www.novaborba.rs/api/v1/categories

    Description :	 All news categories.

   	Return      :    - category title
   					 - category slug
   					 - category ordering
   					 - category color
   					 - category link



## Single category

    Link        :    http://www.novaborba.rs/api/v1/category/CATEGORY SLUG

    Pagination  : 	 http://www.novaborba.rs/api/v1/category/CATEGORY SLUG/?page=1

    Description :	 All news with details in this category with pagination ( 15 news per page ).

   	Return      :    - news title
   					 - news slug
   					 - news summary
   					 - news content
   					 - news views
   					 - created ( datetime obj )
   					 - last update ( datetime obj )
   					 - news images (full, thumb_mid and thumb)




## Single news

    Link        :    http://www.novaborba.rs/api/v1/post/NEWS SLUG

    Description :	 All details for single news.

   	Return      :    - news title
   					 - news slug
   					 - news summary
   					 - news content
   					 - news views
   					 - created ( datetime obj )
   					 - last update ( datetime obj )
   					 - news images (full, thumb_mid and thumb)






## Comments for single news

    Link        :    http://www.novaborba.rs/api/v1/comments/NEWS SLUG

    Pagination  : 	 http://www.novaborba.rs/api/v1/comments/NEWS SLUG/?page=1

    Description :	  Comments for single news with pagination ( 10 comments per page ).

   	Return      :    - comment author name
   					 - comment content
   					 - created ( datetime obj )
   					 - comment number of LIKES
   					 - comments number of DISLIKES
   					 



## All pages

    Link        :    http://www.novaborba.rs/api/v1/pages

    Description :	 All pages with details for every page.

   	Return      :    - page title
   					 - page slug
   					 - page summary
   					 - page content
   					 - page link
   					 - page views
   					 - created ( datetime obj )
   					 - last update ( datetime obj )
   					 - page images (full, thumb_mid and thumb)




## Single page

    Link        :    http://www.novaborba.rs/api/v1/page/PAGE SLUG

    Description :	 Single page with all details.

   	Return      :    - page title
   					 - page slug
   					 - page summary
   					 - page content
   					 - page link
   					 - page views
   					 - created ( datetime obj )
   					 - last update ( datetime obj )
   					 - page images (full, thumb_mid and thumb)

