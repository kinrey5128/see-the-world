!注释

example.com 

!匹配	http://www.example.com/foo, http://www.google.com/search?q=www.example.com
!不匹配	https://www.example.com/

||example.com 

!匹配	http://example.com/foo, https://subdomain.example.com/bar
!不匹配	http://www.google.com/search?q=example.com



|http://example.com

!匹配 	所有开头为https://example.com网页
!不匹配 	短连接如http://t.co/dsadas
