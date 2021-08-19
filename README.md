<?xml version="1.0" encoding="UTF-8" standalone="yes"?>


</item>
<item>
<title>[COLOR white][B]LISTA 1[/B][/COLOR]</title>
<link>$doregex[makelist]</link>
<regex>
<name>makelist</name>
<listrepeat><![CDATA[
<title>[makelist.param1]</title>
<link>plugin://plugin.video.f4mTester/?streamtype=TSDOWNLOADER&amp;name=[makelist.param1]&amp;url=$doregex[encodedurl]</link>
<thumbnail>https://is3-ssl.mzstatic.com/image/thumb/Purple128/v4/79/7a/fa/797afae4-dd72-b2d8-3ac8-ad10ce3f2e5e/AppIcon-85-220-0-0-0-0-4-0-0-0-2x-sRGB-0-0-0.png/1200x630bb.png</thumbnail>
]]></listrepeat>
<expres>#EXTINF:.*,(.*?)\n.*(http.*tv)</expres>
<page>https://raw.githubusercontent.com/RAMALHOTV/VIP3/main/README.md</page>
<referer>google.com</referer>
<x-forward></x-forward>
<agent>VLC/3.0.0</agent>
<buffer>10</buffer>
</regex>
<regex>
<name>encodedurl</name>
<expres>$pyFunction:urllib.quote_plus('[makelist.param2]')<expres>
<page></page>
</regex>
</item>


</item>
<item>
<title>[COLOR white][B]LISTA 2[/B][/COLOR]</title>
<link>$doregex[makelist]</link>
<regex>
<name>makelist</name>
<listrepeat><![CDATA[
<title>[makelist.param1]</title>
<link>plugin://plugin.video.f4mTester/?streamtype=TSDOWNLOADER&amp;name=[makelist.param1]&amp;url=$doregex[encodedurl]</link>
<thumbnail>https://is3-ssl.mzstatic.com/image/thumb/Purple128/v4/79/7a/fa/797afae4-dd72-b2d8-3ac8-ad10ce3f2e5e/AppIcon-85-220-0-0-0-0-4-0-0-0-2x-sRGB-0-0-0.png/1200x630bb.png</thumbnail>
]]></listrepeat>
<expres>#EXTINF:.*,(.*?)\n.*(http.*tv)</expres>
<page>https://raw.githubusercontent.com/RAMALHOTV/VIP4/main/README.md</page>
<referer>google.com</referer>
<x-forward></x-forward>
<agent>VLC/3.0.0</agent>
<buffer>10</buffer>
</regex>
<regex>
<name>encodedurl</name>
<expres>$pyFunction:urllib.quote_plus('[makelist.param2]')<expres>
<page></page>
</regex>
</item>


<item>
<title>[COLOR white][B]LISTA 3[/B][/COLOR]</title>
<link>https://pastebr.xyz/raw/FBwVsVM9iz</link>
<externallink>https://pastebr.xyz/raw/FBwVsVM9iz</externallink>
</item>

<item>
<title>[COLOR white][B]LISTA 4[/B][/COLOR]</title>
<link>https://pastebr.xyz/raw/HRRRwXuTFo</link>
<externallink>https://pastebr.xyz/raw/HRRRwXuTFo</externallink>
</item>











