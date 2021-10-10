<pre><font color="#8AE234"><b>sysadmin@UbuntuDesktop</b></font>:<font color="#729FCF"><b>~/Documents</b></font>$ curl --cookie ryancookies.txt http://localhost:8080/wp-admin/index.php
&lt;!DOCTYPE html&gt;
&lt;!--[if IE 8]&gt;
&lt;html xmlns=&quot;http://www.w3.org/1999/xhtml&quot; class=&quot;ie8 wp-toolbar&quot;  lang=&quot;en-US&quot;&gt;
&lt;![endif]--&gt;
&lt;!--[if !(IE 8) ]&gt;&lt;!--&gt;
&lt;html xmlns=&quot;http://www.w3.org/1999/xhtml&quot; class=&quot;wp-toolbar&quot;  lang=&quot;en-US&quot;&gt;
&lt;!--&lt;![endif]--&gt;
&lt;head&gt;
&lt;meta http-equiv=&quot;Content-Type&quot; content=&quot;text/html; charset=UTF-8&quot; /&gt;
&lt;title&gt;Dashboard &amp;lsaquo; wordpress &amp;#8212; WordPress&lt;/title&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
addLoadEvent = function(func){if(typeof jQuery!=&quot;undefined&quot;)jQuery(document).ready(func);else if(typeof wpOnload!=&apos;function&apos;){wpOnload=func;}else{var oldonload=wpOnload;wpOnload=function(){oldonload();func();}}};
var ajaxurl = &apos;/wp-admin/admin-ajax.php&apos;,
	pagenow = &apos;dashboard&apos;,
	typenow = &apos;&apos;,
	adminpage = &apos;index-php&apos;,
	thousandsSeparator = &apos;,&apos;,
	decimalPoint = &apos;.&apos;,
	isRtl = 0;
&lt;/script&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width,initial-scale=1.0&quot;&gt;
&lt;link rel=&apos;dns-prefetch&apos; href=&apos;//s.w.org&apos; /&gt;
&lt;style type=&quot;text/css&quot;&gt;
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
&lt;/style&gt;
&lt;link rel=&apos;stylesheet&apos; href=&apos;http://localhost:8080/wp-admin/load-styles.php?c=0&amp;amp;dir=ltr&amp;amp;load%5B%5D=dashicons,admin-bar,common,forms,admin-menu,dashboard,list-tables,edit,revisions,media,themes,about,nav-menus,widgets,site-icon,&amp;amp;load%5B%5D=l10n,buttons,wp-auth-check&amp;amp;ver=4.6.1&apos; type=&apos;text/css&apos; media=&apos;all&apos; /&gt;
&lt;link rel=&apos;stylesheet&apos; id=&apos;thickbox-css&apos;  href=&apos;http://localhost:8080/wp-includes/js/thickbox/thickbox.css?ver=4.6.1&apos; type=&apos;text/css&apos; media=&apos;all&apos; /&gt;
&lt;!--[if lte IE 7]&gt;
&lt;link rel=&apos;stylesheet&apos; id=&apos;ie-css&apos;  href=&apos;http://localhost:8080/wp-admin/css/ie.min.css?ver=4.6.1&apos; type=&apos;text/css&apos; media=&apos;all&apos; /&gt;
&lt;![endif]--&gt;
		&lt;script type=&quot;text/javascript&quot;&gt;
			window._wpemojiSettings = {&quot;baseUrl&quot;:&quot;https:\/\/s.w.org\/images\/core\/emoji\/2\/72x72\/&quot;,&quot;ext&quot;:&quot;.png&quot;,&quot;svgUrl&quot;:&quot;https:\/\/s.w.org\/images\/core\/emoji\/2\/svg\/&quot;,&quot;svgExt&quot;:&quot;.svg&quot;,&quot;source&quot;:{&quot;concatemoji&quot;:&quot;http:\/\/localhost:8080\/wp-includes\/js\/wp-emoji-release.min.js?ver=4.6.1&quot;}};
			!function(a,b,c){function d(a){var c,d,e,f,g,h=b.createElement(&quot;canvas&quot;),i=h.getContext&amp;&amp;h.getContext(&quot;2d&quot;),j=String.fromCharCode;if(!i||!i.fillText)return!1;switch(i.textBaseline=&quot;top&quot;,i.font=&quot;600 32px Arial&quot;,a){case&quot;flag&quot;:return i.fillText(j(55356,56806,55356,56826),0,0),!(h.toDataURL().length&lt;3e3)&amp;&amp;(i.clearRect(0,0,h.width,h.height),i.fillText(j(55356,57331,65039,8205,55356,57096),0,0),c=h.toDataURL(),i.clearRect(0,0,h.width,h.height),i.fillText(j(55356,57331,55356,57096),0,0),d=h.toDataURL(),c!==d);case&quot;diversity&quot;:return i.fillText(j(55356,57221),0,0),e=i.getImageData(16,16,1,1).data,f=e[0]+&quot;,&quot;+e[1]+&quot;,&quot;+e[2]+&quot;,&quot;+e[3],i.fillText(j(55356,57221,55356,57343),0,0),e=i.getImageData(16,16,1,1).data,g=e[0]+&quot;,&quot;+e[1]+&quot;,&quot;+e[2]+&quot;,&quot;+e[3],f!==g;case&quot;simple&quot;:return i.fillText(j(55357,56835),0,0),0!==i.getImageData(16,16,1,1).data[0];case&quot;unicode8&quot;:return i.fillText(j(55356,57135),0,0),0!==i.getImageData(16,16,1,1).data[0];case&quot;unicode9&quot;:return i.fillText(j(55358,56631),0,0),0!==i.getImageData(16,16,1,1).data[0]}return!1}function e(a){var c=b.createElement(&quot;script&quot;);c.src=a,c.type=&quot;text/javascript&quot;,b.getElementsByTagName(&quot;head&quot;)[0].appendChild(c)}var f,g,h,i;for(i=Array(&quot;simple&quot;,&quot;flag&quot;,&quot;unicode8&quot;,&quot;diversity&quot;,&quot;unicode9&quot;),c.supports={everything:!0,everythingExceptFlag:!0},h=0;h&lt;i.length;h++)c.supports[i[h]]=d(i[h]),c.supports.everything=c.supports.everything&amp;&amp;c.supports[i[h]],&quot;flag&quot;!==i[h]&amp;&amp;(c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&amp;&amp;c.supports[i[h]]);c.supports.everythingExceptFlag=c.supports.everythingExceptFlag&amp;&amp;!c.supports.flag,c.DOMReady=!1,c.readyCallback=function(){c.DOMReady=!0},c.supports.everything||(g=function(){c.readyCallback()},b.addEventListener?(b.addEventListener(&quot;DOMContentLoaded&quot;,g,!1),a.addEventListener(&quot;load&quot;,g,!1)):(a.attachEvent(&quot;onload&quot;,g),b.attachEvent(&quot;onreadystatechange&quot;,function(){&quot;complete&quot;===b.readyState&amp;&amp;c.readyCallback()})),f=c.source||{},f.concatemoji?e(f.concatemoji):f.wpemoji&amp;&amp;f.twemoji&amp;&amp;(e(f.twemoji),e(f.wpemoji)))}(window,document,window._wpemojiSettings);
		&lt;/script&gt;
		
&lt;script type=&apos;text/javascript&apos;&gt;
/* &lt;![CDATA[ */
var userSettings = {&quot;url&quot;:&quot;\/&quot;,&quot;uid&quot;:&quot;3&quot;,&quot;time&quot;:&quot;1633660947&quot;,&quot;secure&quot;:&quot;&quot;};/* ]]&gt; */
&lt;/script&gt;
&lt;script type=&apos;text/javascript&apos; src=&apos;http://localhost:8080/wp-admin/load-scripts.php?c=0&amp;amp;load%5B%5D=jquery-core,jquery-migrate,utils&amp;amp;ver=4.6.1&apos;&gt;&lt;/script&gt;
	&lt;link id=&quot;wp-admin-canonical&quot; rel=&quot;canonical&quot; href=&quot;http://localhost:8080/wp-admin/index.php&quot; /&gt;
	&lt;script&gt;
		if ( window.history.replaceState ) {
			window.history.replaceState( null, null, document.getElementById( &apos;wp-admin-canonical&apos; ).href + window.location.hash );
		}
	&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;var _wpColorScheme = {&quot;icons&quot;:{&quot;base&quot;:&quot;#82878c&quot;,&quot;focus&quot;:&quot;#00a0d2&quot;,&quot;current&quot;:&quot;#fff&quot;}};&lt;/script&gt;
&lt;style type=&quot;text/css&quot; media=&quot;print&quot;&gt;#wpadminbar { display:none; }&lt;/style&gt;
&lt;/head&gt;
&lt;body class=&quot;wp-admin wp-core-ui no-js  index-php auto-fold admin-bar branch-4-6 version-4-6-1 admin-color-fresh locale-en-us no-customize-support no-svg&quot;&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
	document.body.className = document.body.className.replace(&apos;no-js&apos;,&apos;js&apos;);
&lt;/script&gt;


&lt;div id=&quot;wpwrap&quot;&gt;

&lt;div id=&quot;adminmenumain&quot; role=&quot;navigation&quot; aria-label=&quot;Main menu&quot;&gt;
&lt;a href=&quot;#wpbody-content&quot; class=&quot;screen-reader-shortcut&quot;&gt;Skip to main content&lt;/a&gt;
&lt;a href=&quot;#wp-toolbar&quot; class=&quot;screen-reader-shortcut&quot;&gt;Skip to toolbar&lt;/a&gt;
&lt;div id=&quot;adminmenuback&quot;&gt;&lt;/div&gt;
&lt;div id=&quot;adminmenuwrap&quot;&gt;
&lt;ul id=&quot;adminmenu&quot;&gt;


	&lt;li class=&quot;wp-first-item current menu-top menu-top-first menu-icon-dashboard menu-top-last&quot; id=&quot;menu-dashboard&quot;&gt;
	&lt;a href=&apos;index.php&apos; class=&quot;wp-first-item current menu-top menu-top-first menu-icon-dashboard menu-top-last&quot; &gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-dashboard&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Dashboard&lt;/div&gt;&lt;/a&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-not-current-submenu wp-menu-separator&quot; aria-hidden=&quot;true&quot;&gt;&lt;div class=&quot;separator&quot;&gt;&lt;/div&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-has-submenu wp-not-current-submenu menu-top menu-icon-post open-if-no-js menu-top-first&quot; id=&quot;menu-posts&quot;&gt;
	&lt;a href=&apos;edit.php&apos; class=&quot;wp-has-submenu wp-not-current-submenu menu-top menu-icon-post open-if-no-js menu-top-first&quot; aria-haspopup=&quot;true&quot;&gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-admin-post&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Posts&lt;/div&gt;&lt;/a&gt;
	&lt;ul class=&apos;wp-submenu wp-submenu-wrap&apos;&gt;&lt;li class=&apos;wp-submenu-head&apos; aria-hidden=&apos;true&apos;&gt;Posts&lt;/li&gt;&lt;li class=&quot;wp-first-item&quot;&gt;&lt;a href=&apos;edit.php&apos; class=&quot;wp-first-item&quot;&gt;All Posts&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&apos;post-new.php&apos;&gt;Add New&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&apos;edit-tags.php?taxonomy=category&apos;&gt;Categories&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&apos;edit-tags.php?taxonomy=post_tag&apos;&gt;Tags&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-has-submenu wp-not-current-submenu menu-top menu-icon-media&quot; id=&quot;menu-media&quot;&gt;
	&lt;a href=&apos;upload.php&apos; class=&quot;wp-has-submenu wp-not-current-submenu menu-top menu-icon-media&quot; aria-haspopup=&quot;true&quot;&gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-admin-media&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Media&lt;/div&gt;&lt;/a&gt;
	&lt;ul class=&apos;wp-submenu wp-submenu-wrap&apos;&gt;&lt;li class=&apos;wp-submenu-head&apos; aria-hidden=&apos;true&apos;&gt;Media&lt;/li&gt;&lt;li class=&quot;wp-first-item&quot;&gt;&lt;a href=&apos;upload.php&apos; class=&quot;wp-first-item&quot;&gt;Library&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&apos;media-new.php&apos;&gt;Add New&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-has-submenu wp-not-current-submenu menu-top menu-icon-page&quot; id=&quot;menu-pages&quot;&gt;
	&lt;a href=&apos;edit.php?post_type=page&apos; class=&quot;wp-has-submenu wp-not-current-submenu menu-top menu-icon-page&quot; aria-haspopup=&quot;true&quot;&gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-admin-page&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Pages&lt;/div&gt;&lt;/a&gt;
	&lt;ul class=&apos;wp-submenu wp-submenu-wrap&apos;&gt;&lt;li class=&apos;wp-submenu-head&apos; aria-hidden=&apos;true&apos;&gt;Pages&lt;/li&gt;&lt;li class=&quot;wp-first-item&quot;&gt;&lt;a href=&apos;edit.php?post_type=page&apos; class=&quot;wp-first-item&quot;&gt;All Pages&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&apos;post-new.php?post_type=page&apos;&gt;Add New&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-not-current-submenu menu-top menu-icon-comments menu-top-last&quot; id=&quot;menu-comments&quot;&gt;
	&lt;a href=&apos;edit-comments.php&apos; class=&quot;wp-not-current-submenu menu-top menu-icon-comments menu-top-last&quot; &gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-admin-comments&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Comments &lt;span class=&quot;awaiting-mod count-0&quot;&gt;&lt;span class=&quot;pending-count&quot;&gt;0&lt;/span&gt;&lt;/span&gt;&lt;/div&gt;&lt;/a&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-not-current-submenu wp-menu-separator&quot; aria-hidden=&quot;true&quot;&gt;&lt;div class=&quot;separator&quot;&gt;&lt;/div&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-not-current-submenu menu-top menu-icon-users menu-top-first&quot; id=&quot;menu-users&quot;&gt;
	&lt;a href=&apos;profile.php&apos; class=&quot;wp-not-current-submenu menu-top menu-icon-users menu-top-first&quot; &gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-admin-users&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Profile&lt;/div&gt;&lt;/a&gt;&lt;/li&gt;
	&lt;li class=&quot;wp-not-current-submenu menu-top menu-icon-tools menu-top-last&quot; id=&quot;menu-tools&quot;&gt;
	&lt;a href=&apos;tools.php&apos; class=&quot;wp-not-current-submenu menu-top menu-icon-tools menu-top-last&quot; &gt;&lt;div class=&quot;wp-menu-arrow&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-image dashicons-before dashicons-admin-tools&apos;&gt;&lt;br /&gt;&lt;/div&gt;&lt;div class=&apos;wp-menu-name&apos;&gt;Tools&lt;/div&gt;&lt;/a&gt;&lt;/li&gt;&lt;li id=&quot;collapse-menu&quot; class=&quot;hide-if-no-js&quot;&gt;&lt;div id=&quot;collapse-button&quot;&gt;&lt;div&gt;&lt;/div&gt;&lt;/div&gt;&lt;span&gt;Collapse menu&lt;/span&gt;&lt;/li&gt;&lt;/ul&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;div id=&quot;wpcontent&quot;&gt;

		&lt;div id=&quot;wpadminbar&quot; class=&quot;nojq nojs&quot;&gt;
						&lt;div class=&quot;quicklinks&quot; id=&quot;wp-toolbar&quot; role=&quot;navigation&quot; aria-label=&quot;Toolbar&quot; tabindex=&quot;0&quot;&gt;
				&lt;ul id=&quot;wp-admin-bar-root-default&quot; class=&quot;ab-top-menu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-menu-toggle&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;#&quot;&gt;&lt;span class=&quot;ab-icon&quot;&gt;&lt;/span&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Menu&lt;/span&gt;&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-wp-logo&quot; class=&quot;menupop&quot;&gt;&lt;a class=&quot;ab-item&quot; aria-haspopup=&quot;true&quot; href=&quot;http://localhost:8080/wp-admin/about.php&quot;&gt;&lt;span class=&quot;ab-icon&quot;&gt;&lt;/span&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;About WordPress&lt;/span&gt;&lt;/a&gt;&lt;div class=&quot;ab-sub-wrapper&quot;&gt;&lt;ul id=&quot;wp-admin-bar-wp-logo-default&quot; class=&quot;ab-submenu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-about&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-admin/about.php&quot;&gt;About WordPress&lt;/a&gt;		&lt;/li&gt;&lt;/ul&gt;&lt;ul id=&quot;wp-admin-bar-wp-logo-external&quot; class=&quot;ab-sub-secondary ab-submenu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-wporg&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;https://wordpress.org/&quot;&gt;WordPress.org&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-documentation&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;https://codex.wordpress.org/&quot;&gt;Documentation&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-support-forums&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;https://wordpress.org/support/&quot;&gt;Support Forums&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-feedback&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;https://wordpress.org/support/forum/requests-and-feedback&quot;&gt;Feedback&lt;/a&gt;		&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-site-name&quot; class=&quot;menupop&quot;&gt;&lt;a class=&quot;ab-item&quot; aria-haspopup=&quot;true&quot; href=&quot;http://localhost:8080/&quot;&gt;wordpress&lt;/a&gt;&lt;div class=&quot;ab-sub-wrapper&quot;&gt;&lt;ul id=&quot;wp-admin-bar-site-name-default&quot; class=&quot;ab-submenu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-view-site&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/&quot;&gt;Visit Site&lt;/a&gt;		&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-comments&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-admin/edit-comments.php&quot;&gt;&lt;span class=&quot;ab-icon&quot;&gt;&lt;/span&gt;&lt;span id=&quot;ab-awaiting-mod&quot; class=&quot;ab-label awaiting-mod pending-count count-0&quot; aria-hidden=&quot;true&quot;&gt;0&lt;/span&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;0 comments awaiting moderation&lt;/span&gt;&lt;/a&gt;	&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-new-content&quot; class=&quot;menupop&quot;&gt;&lt;a class=&quot;ab-item&quot; aria-haspopup=&quot;true&quot; href=&quot;http://localhost:8080/wp-admin/post-new.php&quot;&gt;&lt;span class=&quot;ab-icon&quot;&gt;&lt;/span&gt;&lt;span class=&quot;ab-label&quot;&gt;New&lt;/span&gt;&lt;/a&gt;&lt;div class=&quot;ab-sub-wrapper&quot;&gt;&lt;ul id=&quot;wp-admin-bar-new-content-default&quot; class=&quot;ab-submenu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-new-post&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-admin/post-new.php&quot;&gt;Post&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-new-media&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-admin/media-new.php&quot;&gt;Media&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-new-page&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-admin/post-new.php?post_type=page&quot;&gt;Page&lt;/a&gt;		&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;&lt;/li&gt;&lt;/ul&gt;&lt;ul id=&quot;wp-admin-bar-top-secondary&quot; class=&quot;ab-top-secondary ab-top-menu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-my-account&quot; class=&quot;menupop with-avatar&quot;&gt;&lt;a class=&quot;ab-item&quot; aria-haspopup=&quot;true&quot; href=&quot;http://localhost:8080/wp-admin/profile.php&quot;&gt;Howdy, Ryan&lt;img alt=&apos;&apos; src=&apos;http://1.gravatar.com/avatar/af7fd20efa4486d92fb0a0fe0cab7843?s=26&amp;#038;d=mm&amp;#038;r=g&apos; srcset=&apos;http://1.gravatar.com/avatar/af7fd20efa4486d92fb0a0fe0cab7843?s=52&amp;amp;d=mm&amp;amp;r=g 2x&apos; class=&apos;avatar avatar-26 photo&apos; height=&apos;26&apos; width=&apos;26&apos; /&gt;&lt;/a&gt;&lt;div class=&quot;ab-sub-wrapper&quot;&gt;&lt;ul id=&quot;wp-admin-bar-user-actions&quot; class=&quot;ab-submenu&quot;&gt;
		&lt;li id=&quot;wp-admin-bar-user-info&quot;&gt;&lt;a class=&quot;ab-item&quot; tabindex=&quot;-1&quot; href=&quot;http://localhost:8080/wp-admin/profile.php&quot;&gt;&lt;img alt=&apos;&apos; src=&apos;http://1.gravatar.com/avatar/af7fd20efa4486d92fb0a0fe0cab7843?s=64&amp;#038;d=mm&amp;#038;r=g&apos; srcset=&apos;http://1.gravatar.com/avatar/af7fd20efa4486d92fb0a0fe0cab7843?s=128&amp;amp;d=mm&amp;amp;r=g 2x&apos; class=&apos;avatar avatar-64 photo&apos; height=&apos;64&apos; width=&apos;64&apos; /&gt;&lt;span class=&apos;display-name&apos;&gt;Ryan&lt;/span&gt;&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-edit-profile&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-admin/profile.php&quot;&gt;Edit My Profile&lt;/a&gt;		&lt;/li&gt;
		&lt;li id=&quot;wp-admin-bar-logout&quot;&gt;&lt;a class=&quot;ab-item&quot; href=&quot;http://localhost:8080/wp-login.php?action=logout&amp;#038;_wpnonce=7fe2cde29e&quot;&gt;Log Out&lt;/a&gt;		&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;		&lt;/li&gt;&lt;/ul&gt;			&lt;/div&gt;
						&lt;a class=&quot;screen-reader-shortcut&quot; href=&quot;http://localhost:8080/wp-login.php?action=logout&amp;#038;_wpnonce=7fe2cde29e&quot;&gt;Log Out&lt;/a&gt;
					&lt;/div&gt;

		
&lt;div id=&quot;wpbody&quot; role=&quot;main&quot;&gt;

&lt;div id=&quot;wpbody-content&quot; aria-label=&quot;Main content&quot; tabindex=&quot;0&quot;&gt;
		&lt;div id=&quot;screen-meta&quot; class=&quot;metabox-prefs&quot;&gt;

			&lt;div id=&quot;contextual-help-wrap&quot; class=&quot;hidden&quot; tabindex=&quot;-1&quot; aria-label=&quot;Contextual Help Tab&quot;&gt;
				&lt;div id=&quot;contextual-help-back&quot;&gt;&lt;/div&gt;
				&lt;div id=&quot;contextual-help-columns&quot;&gt;
					&lt;div class=&quot;contextual-help-tabs&quot;&gt;
						&lt;ul&gt;
						
							&lt;li id=&quot;tab-link-overview&quot; class=&quot;active&quot;&gt;
								&lt;a href=&quot;#tab-panel-overview&quot; aria-controls=&quot;tab-panel-overview&quot;&gt;
									Overview								&lt;/a&gt;
							&lt;/li&gt;
						
							&lt;li id=&quot;tab-link-help-navigation&quot;&gt;
								&lt;a href=&quot;#tab-panel-help-navigation&quot; aria-controls=&quot;tab-panel-help-navigation&quot;&gt;
									Navigation								&lt;/a&gt;
							&lt;/li&gt;
						
							&lt;li id=&quot;tab-link-help-layout&quot;&gt;
								&lt;a href=&quot;#tab-panel-help-layout&quot; aria-controls=&quot;tab-panel-help-layout&quot;&gt;
									Layout								&lt;/a&gt;
							&lt;/li&gt;
						
							&lt;li id=&quot;tab-link-help-content&quot;&gt;
								&lt;a href=&quot;#tab-panel-help-content&quot; aria-controls=&quot;tab-panel-help-content&quot;&gt;
									Content								&lt;/a&gt;
							&lt;/li&gt;
												&lt;/ul&gt;
					&lt;/div&gt;

										&lt;div class=&quot;contextual-help-sidebar&quot;&gt;
						&lt;p&gt;&lt;strong&gt;For more information:&lt;/strong&gt;&lt;/p&gt;&lt;p&gt;&lt;a href=&quot;https://codex.wordpress.org/Dashboard_Screen&quot; target=&quot;_blank&quot;&gt;Documentation on Dashboard&lt;/a&gt;&lt;/p&gt;&lt;p&gt;&lt;a href=&quot;https://wordpress.org/support/&quot; target=&quot;_blank&quot;&gt;Support Forums&lt;/a&gt;&lt;/p&gt;					&lt;/div&gt;
					
					&lt;div class=&quot;contextual-help-tabs-wrap&quot;&gt;
						
							&lt;div id=&quot;tab-panel-overview&quot; class=&quot;help-tab-content active&quot;&gt;
								&lt;p&gt;Welcome to your WordPress Dashboard! This is the screen you will see when you log in to your site, and gives you access to all the site management features of WordPress. You can get help for any screen by clicking the Help tab above the screen title.&lt;/p&gt;		&lt;/div&gt;
						
							&lt;div id=&quot;tab-panel-help-navigation&quot; class=&quot;help-tab-content&quot;&gt;
								&lt;p&gt;The left-hand navigation menu provides links to all of the WordPress administration screens, with submenu items displayed on hover. You can minimize this menu to a narrow icon strip by clicking on the Collapse Menu arrow at the bottom.&lt;/p&gt;&lt;p&gt;Links in the Toolbar at the top of the screen connect your dashboard and the front end of your site, and provide access to your profile and helpful WordPress information.&lt;/p&gt;			&lt;/div&gt;
						
							&lt;div id=&quot;tab-panel-help-layout&quot; class=&quot;help-tab-content&quot;&gt;
								&lt;p&gt;You can use the following controls to arrange your Dashboard screen to suit your workflow. This is true on most other administration screens as well.&lt;/p&gt;&lt;p&gt;&lt;strong&gt;Screen Options&lt;/strong&gt; &amp;mdash; Use the Screen Options tab to choose which Dashboard boxes to show.&lt;/p&gt;&lt;p&gt;&lt;strong&gt;Drag and Drop&lt;/strong&gt; &amp;mdash; To rearrange the boxes, drag and drop by clicking on the title bar of the selected box and releasing when you see a gray dotted-line rectangle appear in the location you want to place the box.&lt;/p&gt;&lt;p&gt;&lt;strong&gt;Box Controls&lt;/strong&gt; &amp;mdash; Click the title bar of the box to expand or collapse it. Some boxes added by plugins may have configurable content, and will show a &amp;#8220;Configure&amp;#8221; link in the title bar if you hover over it.&lt;/p&gt;			&lt;/div&gt;
						
							&lt;div id=&quot;tab-panel-help-content&quot; class=&quot;help-tab-content&quot;&gt;
								&lt;p&gt;The boxes on your Dashboard screen are:&lt;/p&gt;&lt;p&gt;&lt;strong&gt;At A Glance&lt;/strong&gt; &amp;mdash; Displays a summary of the content on your site and identifies which theme and version of WordPress you are using.&lt;/p&gt;&lt;p&gt;&lt;strong&gt;Activity&lt;/strong&gt; &amp;mdash; Shows the upcoming scheduled posts, recently published posts, and the most recent comments on your posts and allows you to moderate them.&lt;/p&gt;&lt;p&gt;&lt;strong&gt;Quick Draft&lt;/strong&gt; &amp;mdash; Allows you to create a new post and save it as a draft. Also displays links to the 5 most recent draft posts you&apos;ve started.&lt;/p&gt;&lt;p&gt;&lt;strong&gt;WordPress News&lt;/strong&gt; &amp;mdash; Latest news from the official WordPress project and the &lt;a href=&quot;https://planet.wordpress.org/&quot;&gt;WordPress Planet&lt;/a&gt;.&lt;/p&gt;							&lt;/div&gt;
											&lt;/div&gt;
				&lt;/div&gt;
			&lt;/div&gt;
		&lt;div id=&quot;screen-options-wrap&quot; class=&quot;hidden&quot; tabindex=&quot;-1&quot; aria-label=&quot;Screen Options Tab&quot;&gt;
&lt;form id=&apos;adv-settings&apos; method=&apos;post&apos;&gt;
		&lt;fieldset class=&quot;metabox-prefs&quot;&gt;
		&lt;legend&gt;Boxes&lt;/legend&gt;
		&lt;label for=&quot;dashboard_right_now-hide&quot;&gt;&lt;input class=&quot;hide-postbox-tog&quot; name=&quot;dashboard_right_now-hide&quot; type=&quot;checkbox&quot; id=&quot;dashboard_right_now-hide&quot; value=&quot;dashboard_right_now&quot;  checked=&apos;checked&apos; /&gt;At a Glance&lt;/label&gt;&lt;label for=&quot;dashboard_activity-hide&quot;&gt;&lt;input class=&quot;hide-postbox-tog&quot; name=&quot;dashboard_activity-hide&quot; type=&quot;checkbox&quot; id=&quot;dashboard_activity-hide&quot; value=&quot;dashboard_activity&quot;  checked=&apos;checked&apos; /&gt;Activity&lt;/label&gt;&lt;label for=&quot;dashboard_quick_press-hide&quot;&gt;&lt;input class=&quot;hide-postbox-tog&quot; name=&quot;dashboard_quick_press-hide&quot; type=&quot;checkbox&quot; id=&quot;dashboard_quick_press-hide&quot; value=&quot;dashboard_quick_press&quot;  checked=&apos;checked&apos; /&gt;&lt;span class=&quot;hide-if-no-js&quot;&gt;Quick Draft&lt;/span&gt; &lt;span class=&quot;hide-if-js&quot;&gt;Drafts&lt;/span&gt;&lt;/label&gt;&lt;label for=&quot;dashboard_primary-hide&quot;&gt;&lt;input class=&quot;hide-postbox-tog&quot; name=&quot;dashboard_primary-hide&quot; type=&quot;checkbox&quot; id=&quot;dashboard_primary-hide&quot; value=&quot;dashboard_primary&quot;  checked=&apos;checked&apos; /&gt;WordPress News&lt;/label&gt;		&lt;/fieldset&gt;
		
&lt;input type=&quot;hidden&quot; id=&quot;screenoptionnonce&quot; name=&quot;screenoptionnonce&quot; value=&quot;90f77bdaf5&quot; /&gt;
&lt;/form&gt;
&lt;/div&gt;		&lt;/div&gt;
				&lt;div id=&quot;screen-meta-links&quot;&gt;
					&lt;div id=&quot;contextual-help-link-wrap&quot; class=&quot;hide-if-no-js screen-meta-toggle&quot;&gt;
			&lt;button type=&quot;button&quot; id=&quot;contextual-help-link&quot; class=&quot;button show-settings&quot; aria-controls=&quot;contextual-help-wrap&quot; aria-expanded=&quot;false&quot;&gt;Help&lt;/button&gt;
			&lt;/div&gt;
					&lt;div id=&quot;screen-options-link-wrap&quot; class=&quot;hide-if-no-js screen-meta-toggle&quot;&gt;
			&lt;button type=&quot;button&quot; id=&quot;show-settings-link&quot; class=&quot;button show-settings&quot; aria-controls=&quot;screen-options-wrap&quot; aria-expanded=&quot;false&quot;&gt;Screen Options&lt;/button&gt;
			&lt;/div&gt;
				&lt;/div&gt;
		&lt;div class=&apos;update-nag&apos;&gt;&lt;a href=&quot;https://codex.wordpress.org/Version_5.8.1&quot;&gt;WordPress 5.8.1&lt;/a&gt; is available! Please notify the site administrator.&lt;/div&gt;
&lt;div class=&quot;wrap&quot;&gt;
	&lt;h1&gt;Dashboard&lt;/h1&gt;


	&lt;div id=&quot;dashboard-widgets-wrap&quot;&gt;
	&lt;div id=&quot;dashboard-widgets&quot; class=&quot;metabox-holder&quot;&gt;
	&lt;div id=&quot;postbox-container-1&quot; class=&quot;postbox-container&quot;&gt;
	&lt;div id=&quot;normal-sortables&quot; class=&quot;meta-box-sortables&quot;&gt;&lt;div id=&quot;dashboard_right_now&quot; class=&quot;postbox &quot; &gt;
&lt;button type=&quot;button&quot; class=&quot;handlediv button-link&quot; aria-expanded=&quot;true&quot;&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Toggle panel: At a Glance&lt;/span&gt;&lt;span class=&quot;toggle-indicator&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;&lt;/button&gt;&lt;h2 class=&apos;hndle&apos;&gt;&lt;span&gt;At a Glance&lt;/span&gt;&lt;/h2&gt;
&lt;div class=&quot;inside&quot;&gt;
	&lt;div class=&quot;main&quot;&gt;
	&lt;ul&gt;
	&lt;li class=&quot;post-count&quot;&gt;&lt;a href=&quot;edit.php?post_type=post&quot;&gt;1 Post&lt;/a&gt;&lt;/li&gt;&lt;li class=&quot;page-count&quot;&gt;&lt;a href=&quot;edit.php?post_type=page&quot;&gt;1 Page&lt;/a&gt;&lt;/li&gt;		&lt;li class=&quot;comment-count&quot;&gt;&lt;a href=&quot;edit-comments.php&quot;&gt;1 Comment&lt;/a&gt;&lt;/li&gt;
				&lt;li class=&quot;comment-mod-count hidden&quot;&gt;&lt;a href=&quot;edit-comments.php?comment_status=moderated&quot; aria-label=&quot;0 comments in moderation&quot;&gt;0 in moderation&lt;/a&gt;&lt;/li&gt;
			&lt;/ul&gt;
	&lt;p id=&apos;wp-version-message&apos;&gt;&lt;span id=&quot;wp-version&quot;&gt;WordPress 4.6.1 running Twenty Sixteen theme.&lt;/span&gt;&lt;/p&gt;	&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div id=&quot;dashboard_activity&quot; class=&quot;postbox &quot; &gt;
&lt;button type=&quot;button&quot; class=&quot;handlediv button-link&quot; aria-expanded=&quot;true&quot;&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Toggle panel: Activity&lt;/span&gt;&lt;span class=&quot;toggle-indicator&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;&lt;/button&gt;&lt;h2 class=&apos;hndle&apos;&gt;&lt;span&gt;Activity&lt;/span&gt;&lt;/h2&gt;
&lt;div class=&quot;inside&quot;&gt;
&lt;div id=&quot;activity-widget&quot;&gt;&lt;div id=&quot;published-posts&quot; class=&quot;activity-block&quot;&gt;&lt;h3&gt;Recently Published&lt;/h3&gt;&lt;ul&gt;&lt;li&gt;&lt;span&gt;Oct 7th, 10:01 pm&lt;/span&gt; &lt;a href=&quot;http://localhost:8080/wp-admin/post.php?post=1&amp;amp;action=edit&quot; aria-label=&quot;Edit &amp;#8220;Hello world!&amp;#8221;&quot;&gt;Hello world!&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;&lt;div id=&quot;latest-comments&quot; class=&quot;activity-block&quot;&gt;&lt;h3&gt;Recent Comments&lt;/h3&gt;&lt;ul id=&quot;the-comment-list&quot; data-wp-lists=&quot;list:comment&quot;&gt;
		&lt;li id=&quot;comment-1&quot; class=&quot;comment even thread-even depth-1 comment-item approved&quot;&gt;

			&lt;img alt=&apos;&apos; src=&apos;http://1.gravatar.com/avatar/d7a973c7dab26985da5f961be7b74480?s=50&amp;#038;d=mm&amp;#038;r=g&apos; srcset=&apos;http://1.gravatar.com/avatar/d7a973c7dab26985da5f961be7b74480?s=100&amp;amp;d=mm&amp;amp;r=g 2x&apos; class=&apos;avatar avatar-50 photo&apos; height=&apos;50&apos; width=&apos;50&apos; /&gt;
			
			&lt;div class=&quot;dashboard-comment-wrap has-row-actions&quot;&gt;
			&lt;p class=&quot;comment-meta&quot;&gt;
			From &lt;cite class=&quot;comment-author&quot;&gt;&lt;a href=&apos;https://wordpress.org/&apos; rel=&apos;external nofollow&apos; class=&apos;url&apos;&gt;A WordPress Commenter&lt;/a&gt;&lt;/cite&gt; on &lt;a href=&apos;http://localhost:8080/?p=1&apos;&gt;Hello world!&lt;/a&gt; &lt;span class=&quot;approve&quot;&gt;[Pending]&lt;/span&gt;			&lt;/p&gt;

						&lt;blockquote&gt;&lt;p&gt;Hi, this is a comment. To get started with moderating, editing, and deleting comments, please visit the Comments screen in&amp;hellip;&lt;/p&gt;&lt;/blockquote&gt;
						&lt;p class=&quot;row-actions&quot;&gt;&lt;span class=&apos;approve&apos;&gt;&lt;a href=&apos;comment.php?action=approvecomment&amp;#038;p=1&amp;#038;c=1&amp;#038;_wpnonce=3a29387429&apos; data-wp-lists=&apos;dim:the-comment-list:comment-1:unapproved:e7e7d3:e7e7d3:new=approved&apos; class=&apos;vim-a&apos; aria-label=&apos;Approve this comment&apos;&gt;Approve&lt;/a&gt;&lt;/span&gt;&lt;span class=&apos;unapprove&apos;&gt;&lt;a href=&apos;comment.php?action=unapprovecomment&amp;#038;p=1&amp;#038;c=1&amp;#038;_wpnonce=3a29387429&apos; data-wp-lists=&apos;dim:the-comment-list:comment-1:unapproved:e7e7d3:e7e7d3:new=unapproved&apos; class=&apos;vim-u&apos; aria-label=&apos;Unapprove this comment&apos;&gt;Unapprove&lt;/a&gt;&lt;/span&gt;&lt;span class=&apos;reply hide-if-no-js&apos;&gt; | &lt;a onclick=&quot;window.commentReply &amp;&amp; commentReply.open(&apos;1&apos;,&apos;1&apos;);return false;&quot; class=&quot;vim-r hide-if-no-js&quot; aria-label=&quot;Reply to this comment&quot; href=&quot;#&quot;&gt;Reply&lt;/a&gt;&lt;/span&gt;&lt;span class=&apos;edit&apos;&gt; | &lt;a href=&apos;comment.php?action=editcomment&amp;amp;c=1&apos; aria-label=&apos;Edit this comment&apos;&gt;Edit&lt;/a&gt;&lt;/span&gt;&lt;span class=&apos;spam&apos;&gt; | &lt;a href=&apos;comment.php?action=spamcomment&amp;#038;p=1&amp;#038;c=1&amp;#038;_wpnonce=695e98ffbb&apos; data-wp-lists=&apos;delete:the-comment-list:comment-1::spam=1&apos; class=&apos;vim-s vim-destructive&apos; aria-label=&apos;Mark this comment as spam&apos;&gt;Spam&lt;/a&gt;&lt;/span&gt;&lt;span class=&apos;trash&apos;&gt; | &lt;a href=&apos;comment.php?action=trashcomment&amp;#038;p=1&amp;#038;c=1&amp;#038;_wpnonce=695e98ffbb&apos; data-wp-lists=&apos;delete:the-comment-list:comment-1::trash=1&apos; class=&apos;delete vim-d vim-destructive&apos; aria-label=&apos;Move this comment to the Trash&apos;&gt;Trash&lt;/a&gt;&lt;/span&gt;&lt;span class=&apos;view&apos;&gt; | &lt;a class=&quot;comment-link&quot; href=&quot;http://localhost:8080/?p=1#comment-1&quot; aria-label=&quot;View this comment&quot;&gt;View&lt;/a&gt;&lt;/span&gt;&lt;/p&gt;
						&lt;/div&gt;
		&lt;/li&gt;
&lt;/ul&gt;&lt;h3 class=&quot;screen-reader-text&quot;&gt;View more comments&lt;/h3&gt;&lt;ul class=&apos;subsubsub&apos;&gt;
	&lt;li class=&apos;all&apos;&gt;&lt;a href=&apos;http://localhost:8080/wp-admin/edit-comments.php?comment_status=all&apos;&gt;All &lt;span class=&quot;count&quot;&gt;(&lt;span class=&quot;all-count&quot;&gt;1&lt;/span&gt;)&lt;/span&gt;&lt;/a&gt; |&lt;/li&gt;
	&lt;li class=&apos;moderated&apos;&gt;&lt;a href=&apos;http://localhost:8080/wp-admin/edit-comments.php?comment_status=moderated&apos;&gt;Pending &lt;span class=&quot;count&quot;&gt;(&lt;span class=&quot;pending-count&quot;&gt;0&lt;/span&gt;)&lt;/span&gt;&lt;/a&gt; |&lt;/li&gt;
	&lt;li class=&apos;approved&apos;&gt;&lt;a href=&apos;http://localhost:8080/wp-admin/edit-comments.php?comment_status=approved&apos;&gt;Approved &lt;span class=&quot;count&quot;&gt;(&lt;span class=&quot;approved-count&quot;&gt;1&lt;/span&gt;)&lt;/span&gt;&lt;/a&gt; |&lt;/li&gt;
	&lt;li class=&apos;spam&apos;&gt;&lt;a href=&apos;http://localhost:8080/wp-admin/edit-comments.php?comment_status=spam&apos;&gt;Spam &lt;span class=&quot;count&quot;&gt;(&lt;span class=&quot;spam-count&quot;&gt;0&lt;/span&gt;)&lt;/span&gt;&lt;/a&gt; |&lt;/li&gt;
	&lt;li class=&apos;trash&apos;&gt;&lt;a href=&apos;http://localhost:8080/wp-admin/edit-comments.php?comment_status=trash&apos;&gt;Trash &lt;span class=&quot;count&quot;&gt;(&lt;span class=&quot;trash-count&quot;&gt;0&lt;/span&gt;)&lt;/span&gt;&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;&lt;form method=&quot;get&quot;&gt;
&lt;div id=&quot;com-reply&quot; style=&quot;display:none;&quot;&gt;&lt;div id=&quot;replyrow&quot; style=&quot;display:none;&quot;&gt;
	&lt;fieldset class=&quot;comment-reply&quot;&gt;
	&lt;legend&gt;
		&lt;span class=&quot;hidden&quot; id=&quot;editlegend&quot;&gt;Edit Comment&lt;/span&gt;
		&lt;span class=&quot;hidden&quot; id=&quot;replyhead&quot;&gt;Reply to Comment&lt;/span&gt;
		&lt;span class=&quot;hidden&quot; id=&quot;addhead&quot;&gt;Add new Comment&lt;/span&gt;
	&lt;/legend&gt;

	&lt;div id=&quot;replycontainer&quot;&gt;
	&lt;label for=&quot;replycontent&quot; class=&quot;screen-reader-text&quot;&gt;Comment&lt;/label&gt;
	&lt;div id=&quot;wp-replycontent-wrap&quot; class=&quot;wp-core-ui wp-editor-wrap html-active&quot;&gt;&lt;link rel=&apos;stylesheet&apos; id=&apos;editor-buttons-css&apos;  href=&apos;http://localhost:8080/wp-includes/css/editor.min.css?ver=4.6.1&apos; type=&apos;text/css&apos; media=&apos;all&apos; /&gt;
&lt;div id=&quot;wp-replycontent-editor-container&quot; class=&quot;wp-editor-container&quot;&gt;&lt;div id=&quot;qt_replycontent_toolbar&quot; class=&quot;quicktags-toolbar&quot;&gt;&lt;/div&gt;&lt;textarea class=&quot;wp-editor-area&quot; rows=&quot;20&quot; cols=&quot;40&quot; name=&quot;replycontent&quot; id=&quot;replycontent&quot;&gt;&lt;/textarea&gt;&lt;/div&gt;
&lt;/div&gt;

	&lt;/div&gt;

	&lt;div id=&quot;edithead&quot; style=&quot;display:none;&quot;&gt;
		&lt;div class=&quot;inside&quot;&gt;
		&lt;label for=&quot;author-name&quot;&gt;Name&lt;/label&gt;
		&lt;input type=&quot;text&quot; name=&quot;newcomment_author&quot; size=&quot;50&quot; value=&quot;&quot; id=&quot;author-name&quot; /&gt;
		&lt;/div&gt;

		&lt;div class=&quot;inside&quot;&gt;
		&lt;label for=&quot;author-email&quot;&gt;Email&lt;/label&gt;
		&lt;input type=&quot;text&quot; name=&quot;newcomment_author_email&quot; size=&quot;50&quot; value=&quot;&quot; id=&quot;author-email&quot; /&gt;
		&lt;/div&gt;

		&lt;div class=&quot;inside&quot;&gt;
		&lt;label for=&quot;author-url&quot;&gt;URL&lt;/label&gt;
		&lt;input type=&quot;text&quot; id=&quot;author-url&quot; name=&quot;newcomment_author_url&quot; class=&quot;code&quot; size=&quot;103&quot; value=&quot;&quot; /&gt;
		&lt;/div&gt;
	&lt;/div&gt;

	&lt;p id=&quot;replysubmit&quot; class=&quot;submit&quot;&gt;
	&lt;a href=&quot;#comments-form&quot; class=&quot;save button-primary alignright&quot;&gt;
	&lt;span id=&quot;addbtn&quot; style=&quot;display:none;&quot;&gt;Add Comment&lt;/span&gt;
	&lt;span id=&quot;savebtn&quot; style=&quot;display:none;&quot;&gt;Update Comment&lt;/span&gt;
	&lt;span id=&quot;replybtn&quot; style=&quot;display:none;&quot;&gt;Submit Reply&lt;/span&gt;&lt;/a&gt;
	&lt;a href=&quot;#comments-form&quot; class=&quot;cancel button-secondary alignleft&quot;&gt;Cancel&lt;/a&gt;
	&lt;span class=&quot;waiting spinner&quot;&gt;&lt;/span&gt;
	&lt;span class=&quot;error&quot; style=&quot;display:none;&quot;&gt;&lt;/span&gt;
	&lt;/p&gt;

	&lt;input type=&quot;hidden&quot; name=&quot;action&quot; id=&quot;action&quot; value=&quot;&quot; /&gt;
	&lt;input type=&quot;hidden&quot; name=&quot;comment_ID&quot; id=&quot;comment_ID&quot; value=&quot;&quot; /&gt;
	&lt;input type=&quot;hidden&quot; name=&quot;comment_post_ID&quot; id=&quot;comment_post_ID&quot; value=&quot;&quot; /&gt;
	&lt;input type=&quot;hidden&quot; name=&quot;status&quot; id=&quot;status&quot; value=&quot;&quot; /&gt;
	&lt;input type=&quot;hidden&quot; name=&quot;position&quot; id=&quot;position&quot; value=&quot;-1&quot; /&gt;
	&lt;input type=&quot;hidden&quot; name=&quot;checkbox&quot; id=&quot;checkbox&quot; value=&quot;0&quot; /&gt;
	&lt;input type=&quot;hidden&quot; name=&quot;mode&quot; id=&quot;mode&quot; value=&quot;dashboard&quot; /&gt;
	&lt;input type=&quot;hidden&quot; id=&quot;_ajax_nonce-replyto-comment&quot; name=&quot;_ajax_nonce-replyto-comment&quot; value=&quot;cf36e3617e&quot; /&gt;&lt;input type=&quot;hidden&quot; id=&quot;_wp_unfiltered_html_comment&quot; name=&quot;_wp_unfiltered_html_comment&quot; value=&quot;a3bab887cc&quot; /&gt;	&lt;/fieldset&gt;
&lt;/div&gt;&lt;/div&gt;
&lt;/form&gt;
&lt;div class=&quot;hidden&quot; id=&quot;trash-undo-holder&quot;&gt;
	&lt;div class=&quot;trash-undo-inside&quot;&gt;Comment by &lt;strong&gt;&lt;/strong&gt; moved to the trash. &lt;span class=&quot;undo untrash&quot;&gt;&lt;a href=&quot;#&quot;&gt;Undo&lt;/a&gt;&lt;/span&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;hidden&quot; id=&quot;spam-undo-holder&quot;&gt;
	&lt;div class=&quot;spam-undo-inside&quot;&gt;Comment by &lt;strong&gt;&lt;/strong&gt; marked as spam. &lt;span class=&quot;undo unspam&quot;&gt;&lt;a href=&quot;#&quot;&gt;Undo&lt;/a&gt;&lt;/span&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;&lt;/div&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;	&lt;/div&gt;
	&lt;div id=&quot;postbox-container-2&quot; class=&quot;postbox-container&quot;&gt;
	&lt;div id=&quot;side-sortables&quot; class=&quot;meta-box-sortables&quot;&gt;&lt;div id=&quot;dashboard_quick_press&quot; class=&quot;postbox &quot; &gt;
&lt;button type=&quot;button&quot; class=&quot;handlediv button-link&quot; aria-expanded=&quot;true&quot;&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Toggle panel: &lt;span class=&quot;hide-if-no-js&quot;&gt;Quick Draft&lt;/span&gt; &lt;span class=&quot;hide-if-js&quot;&gt;Drafts&lt;/span&gt;&lt;/span&gt;&lt;span class=&quot;toggle-indicator&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;&lt;/button&gt;&lt;h2 class=&apos;hndle&apos;&gt;&lt;span&gt;&lt;span class=&quot;hide-if-no-js&quot;&gt;Quick Draft&lt;/span&gt; &lt;span class=&quot;hide-if-js&quot;&gt;Drafts&lt;/span&gt;&lt;/span&gt;&lt;/h2&gt;
&lt;div class=&quot;inside&quot;&gt;

	&lt;form name=&quot;post&quot; action=&quot;http://localhost:8080/wp-admin/post.php&quot; method=&quot;post&quot; id=&quot;quick-press&quot; class=&quot;initial-form hide-if-no-js&quot;&gt;

		
		&lt;div class=&quot;input-text-wrap&quot; id=&quot;title-wrap&quot;&gt;
			&lt;label class=&quot;screen-reader-text prompt&quot; for=&quot;title&quot; id=&quot;title-prompt-text&quot;&gt;

				Title			&lt;/label&gt;
			&lt;input type=&quot;text&quot; name=&quot;post_title&quot; id=&quot;title&quot; autocomplete=&quot;off&quot; /&gt;
		&lt;/div&gt;

		&lt;div class=&quot;textarea-wrap&quot; id=&quot;description-wrap&quot;&gt;
			&lt;label class=&quot;screen-reader-text prompt&quot; for=&quot;content&quot; id=&quot;content-prompt-text&quot;&gt;What&amp;#8217;s on your mind?&lt;/label&gt;
			&lt;textarea name=&quot;content&quot; id=&quot;content&quot; class=&quot;mceEditor&quot; rows=&quot;3&quot; cols=&quot;15&quot; autocomplete=&quot;off&quot;&gt;&lt;/textarea&gt;
		&lt;/div&gt;

		&lt;p class=&quot;submit&quot;&gt;
			&lt;input type=&quot;hidden&quot; name=&quot;action&quot; id=&quot;quickpost-action&quot; value=&quot;post-quickdraft-save&quot; /&gt;
			&lt;input type=&quot;hidden&quot; name=&quot;post_ID&quot; value=&quot;4&quot; /&gt;
			&lt;input type=&quot;hidden&quot; name=&quot;post_type&quot; value=&quot;post&quot; /&gt;
			&lt;input type=&quot;hidden&quot; id=&quot;_wpnonce&quot; name=&quot;_wpnonce&quot; value=&quot;cc3727b086&quot; /&gt;&lt;input type=&quot;hidden&quot; name=&quot;_wp_http_referer&quot; value=&quot;/wp-admin/index.php&quot; /&gt;			&lt;input type=&quot;submit&quot; name=&quot;save&quot; id=&quot;save-post&quot; class=&quot;button button-primary&quot; value=&quot;Save Draft&quot;  /&gt;			&lt;br class=&quot;clear&quot; /&gt;
		&lt;/p&gt;

	&lt;/form&gt;
	&lt;/div&gt;
&lt;/div&gt;
&lt;div id=&quot;dashboard_primary&quot; class=&quot;postbox &quot; &gt;
&lt;button type=&quot;button&quot; class=&quot;handlediv button-link&quot; aria-expanded=&quot;true&quot;&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Toggle panel: WordPress News&lt;/span&gt;&lt;span class=&quot;toggle-indicator&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;&lt;/button&gt;&lt;h2 class=&apos;hndle&apos;&gt;&lt;span&gt;WordPress News&lt;/span&gt;&lt;/h2&gt;
&lt;div class=&quot;inside&quot;&gt;
&lt;div class=&quot;rss-widget&quot;&gt;&lt;ul&gt;&lt;li&gt;&lt;a class=&apos;rsswidget&apos; href=&apos;https://wordpress.org/news/2021/10/the-month-in-wordpress-september-2021/&apos;&gt;The Month in WordPress: September 2021&lt;/a&gt; &lt;span class=&quot;rss-date&quot;&gt;October 5, 2021&lt;/span&gt;&lt;div class=&quot;rssSummary&quot;&gt;There’s a lot of tolerance in open source software for shipping slightly imperfect work. And that’s good. When we ship software that’s a little bit imperfect, it makes it clear how everyone can participate, how everyone could participate, if they could find this WordPress community that supports the CMS. That was Josepha Haden on the [&amp;hellip;]&lt;/div&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;&lt;div class=&quot;rss-widget&quot;&gt;&lt;ul&gt;&lt;li&gt;&lt;a class=&apos;rsswidget&apos; href=&apos;https://wptavern.com/default-theme-releases-may-become-more-frequent-following-wordpress-5-9?utm_source=rss&amp;#038;utm_medium=rss&amp;#038;utm_campaign=default-theme-releases-may-become-more-frequent-following-wordpress-5-9&apos;&gt;WPTavern: Default Theme Releases May Become More Frequent Following WordPress 5.9&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a class=&apos;rsswidget&apos; href=&apos;https://wptavern.com/the-heropress-network-launches-as-a-multi-project-portal?utm_source=rss&amp;#038;utm_medium=rss&amp;#038;utm_campaign=the-heropress-network-launches-as-a-multi-project-portal&apos;&gt;WPTavern: The HeroPress Network Launches as a Multi-Project Portal&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a class=&apos;rsswidget&apos; href=&apos;https://wptavern.com/first-look-at-wordpress-upcoming-twenty-twenty-two-default-theme-the-most-flexible-default-theme-ever-created-for-wordpress?utm_source=rss&amp;#038;utm_medium=rss&amp;#038;utm_campaign=first-look-at-wordpress-upcoming-twenty-twenty-two-default-theme-the-most-flexible-default-theme-ever-created-for-wordpress&apos;&gt;WPTavern: First Look at WordPress’ Upcoming Twenty Twenty-Two Default Theme: “The Most Flexible Default Theme Ever Created for WordPress”&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/div&gt;&lt;div class=&quot;rss-widget&quot;&gt;&lt;ul&gt;&lt;/ul&gt;&lt;/div&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;	&lt;/div&gt;
	&lt;div id=&quot;postbox-container-3&quot; class=&quot;postbox-container&quot;&gt;
	&lt;div id=&quot;column3-sortables&quot; class=&quot;meta-box-sortables&quot;&gt;&lt;/div&gt;	&lt;/div&gt;
	&lt;div id=&quot;postbox-container-4&quot; class=&quot;postbox-container&quot;&gt;
	&lt;div id=&quot;column4-sortables&quot; class=&quot;meta-box-sortables&quot;&gt;&lt;/div&gt;	&lt;/div&gt;
&lt;/div&gt;

&lt;input type=&quot;hidden&quot; id=&quot;closedpostboxesnonce&quot; name=&quot;closedpostboxesnonce&quot; value=&quot;e3593af4ea&quot; /&gt;&lt;input type=&quot;hidden&quot; id=&quot;meta-box-order-nonce&quot; name=&quot;meta-box-order-nonce&quot; value=&quot;275b140e2f&quot; /&gt;	&lt;/div&gt;&lt;!-- dashboard-widgets-wrap --&gt;

&lt;/div&gt;&lt;!-- wrap --&gt;


&lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;&lt;/div&gt;&lt;!-- wpbody-content --&gt;
&lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;&lt;/div&gt;&lt;!-- wpbody --&gt;
&lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;&lt;/div&gt;&lt;!-- wpcontent --&gt;

&lt;div id=&quot;wpfooter&quot; role=&quot;contentinfo&quot;&gt;
		&lt;p id=&quot;footer-left&quot; class=&quot;alignleft&quot;&gt;
		&lt;span id=&quot;footer-thankyou&quot;&gt;Thank you for creating with &lt;a href=&quot;https://wordpress.org/&quot;&gt;WordPress&lt;/a&gt;.&lt;/span&gt;	&lt;/p&gt;
	&lt;p id=&quot;footer-upgrade&quot; class=&quot;alignright&quot;&gt;
		Version 4.6.1	&lt;/p&gt;
	&lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;
&lt;/div&gt;
&lt;script type=&apos;text/javascript&apos;&gt;list_args = {&quot;class&quot;:&quot;WP_Comments_List_Table&quot;,&quot;screen&quot;:{&quot;id&quot;:&quot;dashboard&quot;,&quot;base&quot;:&quot;dashboard&quot;}};&lt;/script&gt;
&lt;script type=&apos;text/javascript&apos;&gt;list_args = {&quot;class&quot;:&quot;WP_Comments_List_Table&quot;,&quot;screen&quot;:{&quot;id&quot;:&quot;dashboard&quot;,&quot;base&quot;:&quot;dashboard&quot;}};&lt;/script&gt;
	&lt;div id=&quot;wp-auth-check-wrap&quot; class=&quot;hidden&quot;&gt;
	&lt;div id=&quot;wp-auth-check-bg&quot;&gt;&lt;/div&gt;
	&lt;div id=&quot;wp-auth-check&quot;&gt;
	&lt;button type=&quot;button&quot; class=&quot;wp-auth-check-close button-link&quot;&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Close dialog&lt;/span&gt;&lt;/button&gt;
			&lt;div id=&quot;wp-auth-check-form&quot; class=&quot;loading&quot; data-src=&quot;http://localhost:8080/wp-login.php?interim-login=1&quot;&gt;&lt;/div&gt;
			&lt;div class=&quot;wp-auth-fallback&quot;&gt;
		&lt;p&gt;&lt;b class=&quot;wp-auth-fallback-expired&quot; tabindex=&quot;0&quot;&gt;Session expired&lt;/b&gt;&lt;/p&gt;
		&lt;p&gt;&lt;a href=&quot;http://localhost:8080/wp-login.php&quot; target=&quot;_blank&quot;&gt;Please log in again.&lt;/a&gt;
		The login page will open in a new window. After logging in you can close it and return to this page.&lt;/p&gt;
	&lt;/div&gt;
	&lt;/div&gt;
	&lt;/div&gt;
	
&lt;script type=&apos;text/javascript&apos;&gt;
/* &lt;![CDATA[ */
var commonL10n = {&quot;warnDelete&quot;:&quot;You are about to permanently delete these items.\n  &apos;Cancel&apos; to stop, &apos;OK&apos; to delete.&quot;,&quot;dismiss&quot;:&quot;Dismiss this notice.&quot;};var wpAjax = {&quot;noPerm&quot;:&quot;Sorry, you are not allowed to do that.&quot;,&quot;broken&quot;:&quot;An unidentified error has occurred.&quot;};var quicktagsL10n = {&quot;closeAllOpenTags&quot;:&quot;Close all open tags&quot;,&quot;closeTags&quot;:&quot;close tags&quot;,&quot;enterURL&quot;:&quot;Enter the URL&quot;,&quot;enterImageURL&quot;:&quot;Enter the URL of the image&quot;,&quot;enterImageDescription&quot;:&quot;Enter a description of the image&quot;,&quot;textdirection&quot;:&quot;text direction&quot;,&quot;toggleTextdirection&quot;:&quot;Toggle Editor Text Direction&quot;,&quot;dfw&quot;:&quot;Distraction-free writing mode&quot;,&quot;strong&quot;:&quot;Bold&quot;,&quot;strongClose&quot;:&quot;Close bold tag&quot;,&quot;em&quot;:&quot;Italic&quot;,&quot;emClose&quot;:&quot;Close italic tag&quot;,&quot;link&quot;:&quot;Insert link&quot;,&quot;blockquote&quot;:&quot;Blockquote&quot;,&quot;blockquoteClose&quot;:&quot;Close blockquote tag&quot;,&quot;del&quot;:&quot;Deleted text (strikethrough)&quot;,&quot;delClose&quot;:&quot;Close deleted text tag&quot;,&quot;ins&quot;:&quot;Inserted text&quot;,&quot;insClose&quot;:&quot;Close inserted text tag&quot;,&quot;image&quot;:&quot;Insert image&quot;,&quot;ul&quot;:&quot;Bulleted list&quot;,&quot;ulClose&quot;:&quot;Close bulleted list tag&quot;,&quot;ol&quot;:&quot;Numbered list&quot;,&quot;olClose&quot;:&quot;Close numbered list tag&quot;,&quot;li&quot;:&quot;List item&quot;,&quot;liClose&quot;:&quot;Close list item tag&quot;,&quot;code&quot;:&quot;Code&quot;,&quot;codeClose&quot;:&quot;Close code tag&quot;,&quot;more&quot;:&quot;Insert Read More tag&quot;};var adminCommentsL10n = {&quot;hotkeys_highlight_first&quot;:&quot;&quot;,&quot;hotkeys_highlight_last&quot;:&quot;&quot;,&quot;replyApprove&quot;:&quot;Approve and Reply&quot;,&quot;reply&quot;:&quot;Reply&quot;,&quot;warnQuickEdit&quot;:&quot;Are you sure you want to edit this comment?\nThe changes you made will be lost.&quot;,&quot;warnCommentChanges&quot;:&quot;Are you sure you want to do this?\nThe comment changes you made will be lost.&quot;,&quot;docTitleComments&quot;:&quot;Comments&quot;,&quot;docTitleCommentsCount&quot;:&quot;Comments (%s)&quot;};var postBoxL10n = {&quot;postBoxEmptyString&quot;:&quot;Drag boxes here&quot;};var thickboxL10n = {&quot;next&quot;:&quot;Next &gt;&quot;,&quot;prev&quot;:&quot;&lt; Prev&quot;,&quot;image&quot;:&quot;Image&quot;,&quot;of&quot;:&quot;of&quot;,&quot;close&quot;:&quot;Close&quot;,&quot;noiframes&quot;:&quot;This feature requires inline frames. You have iframes disabled or your browser does not support them.&quot;,&quot;loadingAnimation&quot;:&quot;http:\/\/localhost:8080\/wp-includes\/js\/thickbox\/loadingAnimation.gif&quot;};var heartbeatSettings = {&quot;nonce&quot;:&quot;e11bb1fa04&quot;};var authcheckL10n = {&quot;beforeunload&quot;:&quot;Your session has expired. You can log in again from this page or go to the login page.&quot;,&quot;interval&quot;:&quot;180&quot;};var wpLinkL10n = {&quot;title&quot;:&quot;Insert\/edit link&quot;,&quot;update&quot;:&quot;Update&quot;,&quot;save&quot;:&quot;Add Link&quot;,&quot;noTitle&quot;:&quot;(no title)&quot;,&quot;noMatchesFound&quot;:&quot;No results found.&quot;,&quot;linkSelected&quot;:&quot;Link selected.&quot;,&quot;linkInserted&quot;:&quot;Link inserted.&quot;};var uiAutocompleteL10n = {&quot;noResults&quot;:&quot;No search results.&quot;,&quot;oneResult&quot;:&quot;1 result found. Use up and down arrow keys to navigate.&quot;,&quot;manyResults&quot;:&quot;%d results found. Use up and down arrow keys to navigate.&quot;};/* ]]&gt; */
&lt;/script&gt;
&lt;script type=&apos;text/javascript&apos; src=&apos;http://localhost:8080/wp-admin/load-scripts.php?c=0&amp;amp;load%5B%5D=hoverIntent,common,admin-bar,wp-ajax-response,jquery-color,wp-lists,quicktags,jquery-query,admin-comments,jquery-ui-core,jquery-&amp;amp;load%5B%5D=ui-widget,jquery-ui-mouse,jquery-ui-sortable,postbox,dashboard,thickbox,underscore,shortcode,media-upload,svg-painter,heartbeat,&amp;amp;load%5B%5D=wp-auth-check,wp-a11y,wplink,jquery-ui-position,jquery-ui-menu,jquery-ui-autocomplete&amp;amp;ver=4.6.1&apos;&gt;&lt;/script&gt;

		&lt;script type=&quot;text/javascript&quot;&gt;
		tinyMCEPreInit = {
			baseURL: &quot;&quot;,
			suffix: &quot;.min&quot;,
						mceInit: {},
			qtInit: {&apos;replycontent&apos;:{id:&quot;replycontent&quot;,buttons:&quot;strong,em,link,block,del,ins,img,ul,ol,li,code,close&quot;}},
			ref: {plugins:&quot;&quot;,theme:&quot;modern&quot;,language:&quot;&quot;},
			load_ext: function(url,lang){var sl=tinymce.ScriptLoader;sl.markDone(url+&apos;/langs/&apos;+lang+&apos;.js&apos;);sl.markDone(url+&apos;/langs/&apos;+lang+&apos;_dlg.js&apos;);}
		};
		&lt;/script&gt;
				&lt;script type=&quot;text/javascript&quot;&gt;
		
		( function() {
			var init, id, $wrap;

			if ( typeof tinymce !== &apos;undefined&apos; ) {
				// Fix RTL
				tinymce.on( &apos;addeditor&apos;, function( event ) {
					event.editor.rtl = event.editor.settings.rtl_ui ||
						( event.editor.editorManager &amp;&amp;
						event.editor.editorManager.i18n &amp;&amp;
						event.editor.editorManager.i18n.rtl );
				}, true );

				for ( id in tinyMCEPreInit.mceInit ) {
					init = tinyMCEPreInit.mceInit[id];
					$wrap = tinymce.$( &apos;#wp-&apos; + id + &apos;-wrap&apos; );

					if ( ( $wrap.hasClass( &apos;tmce-active&apos; ) || ! tinyMCEPreInit.qtInit.hasOwnProperty( id ) ) &amp;&amp; ! init.wp_skip_init ) {
						tinymce.init( init );

						if ( ! window.wpActiveEditor ) {
							window.wpActiveEditor = id;
						}
					}
				}
			}

			if ( typeof quicktags !== &apos;undefined&apos; ) {
				for ( id in tinyMCEPreInit.qtInit ) {
					quicktags( tinyMCEPreInit.qtInit[id] );

					if ( ! window.wpActiveEditor ) {
						window.wpActiveEditor = id;
					}
				}
			}
		}());
		&lt;/script&gt;
				&lt;div id=&quot;wp-link-backdrop&quot; style=&quot;display: none&quot;&gt;&lt;/div&gt;
		&lt;div id=&quot;wp-link-wrap&quot; class=&quot;wp-core-ui&quot; style=&quot;display: none&quot; role=&quot;dialog&quot; aria-labelledby=&quot;link-modal-title&quot;&gt;
		&lt;form id=&quot;wp-link&quot; tabindex=&quot;-1&quot;&gt;
		&lt;input type=&quot;hidden&quot; id=&quot;_ajax_linking_nonce&quot; name=&quot;_ajax_linking_nonce&quot; value=&quot;1c164f1801&quot; /&gt;		&lt;h1 id=&quot;link-modal-title&quot;&gt;Insert/edit link&lt;/h1&gt;
		&lt;button type=&quot;button&quot; id=&quot;wp-link-close&quot;&gt;&lt;span class=&quot;screen-reader-text&quot;&gt;Close&lt;/span&gt;&lt;/button&gt;
		&lt;div id=&quot;link-selector&quot;&gt;
			&lt;div id=&quot;link-options&quot;&gt;
				&lt;p class=&quot;howto&quot; id=&quot;wplink-enter-url&quot;&gt;Enter the destination URL&lt;/p&gt;
				&lt;div&gt;
					&lt;label&gt;&lt;span&gt;URL&lt;/span&gt;
					&lt;input id=&quot;wp-link-url&quot; type=&quot;text&quot; aria-describedby=&quot;wplink-enter-url&quot; /&gt;&lt;/label&gt;
				&lt;/div&gt;
				&lt;div class=&quot;wp-link-text-field&quot;&gt;
					&lt;label&gt;&lt;span&gt;Link Text&lt;/span&gt;
					&lt;input id=&quot;wp-link-text&quot; type=&quot;text&quot; /&gt;&lt;/label&gt;
				&lt;/div&gt;
				&lt;div class=&quot;link-target&quot;&gt;
					&lt;label&gt;&lt;span&gt;&lt;/span&gt;
					&lt;input type=&quot;checkbox&quot; id=&quot;wp-link-target&quot; /&gt; Open link in a new tab&lt;/label&gt;
				&lt;/div&gt;
			&lt;/div&gt;
			&lt;p class=&quot;howto&quot; id=&quot;wplink-link-existing-content&quot;&gt;Or link to existing content&lt;/p&gt;
			&lt;div id=&quot;search-panel&quot;&gt;
				&lt;div class=&quot;link-search-wrapper&quot;&gt;
					&lt;label&gt;
						&lt;span class=&quot;search-label&quot;&gt;Search&lt;/span&gt;
						&lt;input type=&quot;search&quot; id=&quot;wp-link-search&quot; class=&quot;link-search-field&quot; autocomplete=&quot;off&quot; aria-describedby=&quot;wplink-link-existing-content&quot; /&gt;
						&lt;span class=&quot;spinner&quot;&gt;&lt;/span&gt;
					&lt;/label&gt;
				&lt;/div&gt;
				&lt;div id=&quot;search-results&quot; class=&quot;query-results&quot; tabindex=&quot;0&quot;&gt;
					&lt;ul&gt;&lt;/ul&gt;
					&lt;div class=&quot;river-waiting&quot;&gt;
						&lt;span class=&quot;spinner&quot;&gt;&lt;/span&gt;
					&lt;/div&gt;
				&lt;/div&gt;
				&lt;div id=&quot;most-recent-results&quot; class=&quot;query-results&quot; tabindex=&quot;0&quot;&gt;
					&lt;div class=&quot;query-notice&quot; id=&quot;query-notice-message&quot;&gt;
						&lt;em class=&quot;query-notice-default&quot;&gt;No search term specified. Showing recent items.&lt;/em&gt;
						&lt;em class=&quot;query-notice-hint screen-reader-text&quot;&gt;Search or use up and down arrow keys to select an item.&lt;/em&gt;
					&lt;/div&gt;
					&lt;ul&gt;&lt;/ul&gt;
					&lt;div class=&quot;river-waiting&quot;&gt;
						&lt;span class=&quot;spinner&quot;&gt;&lt;/span&gt;
					&lt;/div&gt;
 				&lt;/div&gt;
 			&lt;/div&gt;
		&lt;/div&gt;
		&lt;div class=&quot;submitbox&quot;&gt;
			&lt;div id=&quot;wp-link-cancel&quot;&gt;
				&lt;button type=&quot;button&quot; class=&quot;button&quot;&gt;Cancel&lt;/button&gt;
			&lt;/div&gt;
			&lt;div id=&quot;wp-link-update&quot;&gt;
				&lt;input type=&quot;submit&quot; value=&quot;Add Link&quot; class=&quot;button button-primary&quot; id=&quot;wp-link-submit&quot; name=&quot;wp-link-submit&quot;&gt;
			&lt;/div&gt;
		&lt;/div&gt;
		&lt;/form&gt;
		&lt;/div&gt;
		
&lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;&lt;/div&gt;&lt;!-- wpwrap --&gt;
&lt;script type=&quot;text/javascript&quot;&gt;if(typeof wpOnload==&apos;function&apos;)wpOnload();&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
</pre>