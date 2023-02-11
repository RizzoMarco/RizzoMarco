### Hi there 👋

var originalimg = largesrc.replace("sendimage?width=640&height=425&file=", "");
var fullsrc = 'http://' + window.location.host + originalimg;
var divopen = '<div class="itemShare">Share this image: '
var twitter = '<a target="_blank" href="http://twitter.com/home?status='+title+' '+ link +' "><img border="0" src="/assets/images/site-images/social-icons/twitter.gif"></a>'
var facebook = '<a target="_blank" href="http://www.facebook.com/sharer.php?u='+link+'&amp;t='+title+'" name="fb_share"><img border="0" src="/assets/images/site-images/social-icons/facebook.gif"></a>'
var linkedin = '<a target="_blank" href="http://www.linkedin.com/shareArticle?url='+link+'&amp;title='+title+'"><img border="0" src="/assets/images/site-images/social-icons/linkedin.gif"></a>'
var googleplus = '<a target="_blank" href="https://plus.google.com/share?url='+link+'"><img src="https://www.gstatic.com/images/icons/gplus-16.png" alt="Share on Google+"/></a>'
var pintrest = '<a target="_blank" href="//www.pinterest.com/pin/create/button/?url='+link+'&media='+fullsrc+'&description='+title+'" data-pin-do="buttonPin" data-pin-config="none"><img src="//assets.pinterest.com/images/pidgets/pinit_fg_en_rect_gray_20.png" /></a>'
var divclose = '</div>'
var linkStr = divopen + tw"+ facebook +" "+linkedin+" "+googleplus+" "+pintrest + divclose;
$rgGallery.find('div.rg-caption').find(".itemShare").remove();
$rgGallery.find('div.rg-caption').append(linkStr);
<!--

**RizzoMarco/RizzoMarco** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
