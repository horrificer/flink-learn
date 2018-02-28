curl -XPUT "http://localhost:9200/twitter-stats/_mapping/stats" -d'
	 {
	 "stats" : {
	 "properties" : {
	 "count": {"type": "long"},
	 "lang": {"type": "string"},
	 "window-start": {"type": "date"}
	 },
	 "_timestamp" : {"enabled" : true, "path" : "window-start", "store": "yes" }
	 }
	 }'

	 Sample tweet:
	 {"created_at":"Wed Jun 01 13:35:32 +0000 2016","id":738001034451156992,"id_str":"738001034451156992","text":"@ceyekku mau eek ak","source":"\u003ca href=\"http:\/\/twitter.com\/download\/android\" rel=\"nofollow\"\u003eTwitter for Android\u003c\/a\u003e","truncated":false,"in_reply_to_status_id":737989421799067648,"in_reply_to_status_id_str":"737989421799067648","in_reply_to_user_id":4201628843,"in_reply_to_user_id_str":"4201628843","in_reply_to_screen_name":"ceyekku","user":{"id":4292546423,"id_str":"4292546423","name":"binnie","screen_name":"machiattous","location":"benten ;","url":"http:\/\/twitter.com\/kayirrie","description":"bakpjm","protected":false,"verified":false,"followers_count":152,"friends_count":145,"listed_count":5,"favourites_count":2815,"statuses_count":19744,"created_at":"Fri Nov 27 04:32:27 +0000 2015","utc_offset":-25200,"time_zone":"Pacific Time (US & Canada)","geo_enabled":false,"lang":"en","contributors_enabled":false,"is_translator":false,"profile_background_color":"C0DEED","profile_background_image_url":"http:\/\/abs.twimg.com\/images\/themes\/theme1\/bg.png","profile_background_image_url_https":"https:\/\/abs.twimg.com\/images\/themes\/theme1\/bg.png","profile_background_tile":false,"profile_link_color":"0084B4","profile_sidebar_border_color":"C0DEED","profile_sidebar_fill_color":"DDEEF6","profile_text_color":"333333","profile_use_background_image":true,"profile_image_url":"http:\/\/pbs.twimg.com\/profile_images\/736159560688226304\/Xchm2Pnq_normal.jpg","profile_image_url_https":"https:\/\/pbs.twimg.com\/profile_images\/736159560688226304\/Xchm2Pnq_normal.jpg","profile_banner_url":"https:\/\/pbs.twimg.com\/profile_banners\/4292546423\/1464349616","default_profile":true,"default_profile_image":false,"following":null,"follow_request_sent":null,"notifications":null},"geo":null,"coordinates":null,"place":null,"contributors":null,"is_quote_status":false,"retweet_count":0,"favorite_count":0,"entities":{"hashtags":[],"urls":[],"user_mentions":[{"screen_name":"ceyekku","name":"CEYEK.","id":4201628843,"id_str":"4201628843","indices":[0,8]}],"symbols":[]},"favorited":false,"retweeted":false,"filter_level":"low","lang":"in","timestamp_ms":"1464788132666"}
	 {
	 "created_at":"Wed Jun 01 13:35:32 +0000 2016",
	 "id":738001034451156992,
	 "id_str":"738001034451156992",
	 "text":"@ceyekku mau eek ak",
	 "source":"\u003ca href=\"http:\/\/twitter.com\/download\/android\" rel=\"nofollow\"\u003eTwitter for Android\u003c\/a\u003e",
	 "truncated":false,
	 "in_reply_to_status_id":737989421799067648,
	 "in_reply_to_status_id_str":"737989421799067648",
	 "in_reply_to_user_id":4201628843,
	 "in_reply_to_user_id_str":"4201628843",
	 "in_reply_to_screen_name":"ceyekku",
	 "user":{
	 "id":4292546423,
	 "id_str":"4292546423",
	 "name":"binnie",
	 "screen_name":"machiattous",
	 "location":"benten ;",
	 "url":"http:\/\/twitter.com\/kayirrie",
	 "description":"bakpjm",
	 "protected":false,
	 "verified":false,
	 "followers_count":152,
	 "friends_count":145,
	 "listed_count":5,
	 "favourites_count":2815,
	 "statuses_count":19744,
	 "created_at":"Fri Nov 27 04:32:27 +0000 2015",
	 "utc_offset":-25200,
	 "time_zone":"Pacific Time (US & Canada)",
	 "geo_enabled":false,
	 "lang":"en",
	 "contributors_enabled":false,
	 "is_translator":false,
	 "profile_background_color":"C0DEED",
	 "profile_background_image_url":"http:\/\/abs.twimg.com\/images\/themes\/theme1\/bg.png",
	 "profile_background_image_url_https":"https:\/\/abs.twimg.com\/images\/themes\/theme1\/bg.png",
	 "profile_background_tile":false,
	 "profile_link_color":"0084B4",
	 "profile_sidebar_border_color":"C0DEED",
	 "profile_sidebar_fill_color":"DDEEF6",
	 "profile_text_color":"333333",
	 "profile_use_background_image":true,
	 "profile_image_url":"http:\/\/pbs.twimg.com\/profile_images\/736159560688226304\/Xchm2Pnq_normal.jpg",
	 "profile_image_url_https":"https:\/\/pbs.twimg.com\/profile_images\/736159560688226304\/Xchm2Pnq_normal.jpg",
	 "profile_banner_url":"https:\/\/pbs.twimg.com\/profile_banners\/4292546423\/1464349616",
	 "default_profile":true,
	 "default_profile_image":false,
	 "following":null,
	 "follow_request_sent":null,
	 "notifications":null
	 },
	 "geo":null,
	 "coordinates":null,
	 "place":null,
	 "contributors":null,
	 "is_quote_status":false,
	 "retweet_count":0,
	 "favorite_count":0,
	 "entities":{
	 "hashtags":[
	 ],
	 "urls":[
	 ],
	 "user_mentions":[
	 {
	 "screen_name":"ceyekku",
	 "name":"CEYEK.",
	 "id":4201628843,
	 "id_str":"4201628843",
	 "indices":[
	 0,
	 8
	 ]
	 }
	 ],
	 "symbols":[
	 ]
	 },
	 "favorited":false,
	 "retweeted":false,
	 "filter_level":"low",
	 "lang":"in",
	 "timestamp_ms":"1464788132666"
	 }