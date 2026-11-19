Fuji Sushi & Asian Bistro (fujimn.com) - static HTML version
===========================================================

Upload the CONTENTS of this folder (including the hidden .htaccess file) to the web root of
fujimn.com, or to any subfolder for a staging preview. All links are relative.
Works on Apache/LiteSpeed (.htaccess) and Cloudflare Pages (_headers).

Pages (all 45, same URLs as the live site)
  /  /about/  /menu/  /daily-specials/  /special-offers/  /contact/
  and the 39 menu category pages under /menu/... (sushi, rolls, ramen, Chinese food, hibachi,
  bento, lunch specials, kids menu, drinks, desserts, etc.)
Found from the sitemap, WordPress's own page list and a full crawl. The site has no blog posts,
no forms and no redirects.

Images
------
Every image and file referenced by every page was downloaded and checked; all references resolve.
The home page slider (Slider Revolution) and its add-on scripts are included and work offline.
One theme icon (owl.video.play.png) does not exist on the live server either.

Noindex (staging)
-----------------
Every page has <meta name="robots" content="noindex, nofollow" />; .htaccess and _headers send an
X-Robots-Tag: noindex, nofollow header.
BEFORE GOING LIVE: remove that meta line from each page, the noindex block from .htaccess and
the X-Robots-Tag line from _headers, or the site will drop out of Google.
