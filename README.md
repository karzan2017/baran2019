<item>
<title>kurdsat</title>
<link>http://live1.karwan.tv/karwan.tv/kurdsat-tv/playlist.m3u8?wmsAuthSign=$doregex[get-auth]</link>
<regex>
 
 
<item>
<title>kurdsatnews </title>
<link>http://live1.karwan.tv/karwan.tv/kurdsat-news-tv/playlist.m3u8?wmsAuthSign=$doregex[get-auth]</link>
<thumbnail>https://nl.wikipedia.org/wiki/Bestand:NostalgieNet_logo.png</thumbnail>
</item>
 
 
 
<item>
<title>kurdsat</title>
<link>http://live1.karwan.tv/karwan.tv/kurdsat-tv/playlist.m3u8?wmsAuthSign=$doregex[get-auth]</link>
<regex>
<name>get-auth</name>
<expres>wmsAuthSign=(.*)</expres>
<page>http://www.livestreamcast.org/player/embed_t2.php?&c=twd</page>
<referer>http://www.tvonlinegratis.tv/parcerias/twd.php</referer>
</regex>
<thumbnail></thumbnail>
</item>
