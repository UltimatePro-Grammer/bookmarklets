# bookmarklets

All of my custom bookmarklets. Completely free &amp; MIT Licensed.

## Download

You can download the latest version of each bookmarklet by going to the links below.

-   [🔇 Adbloq: Instantly remove all ads on a page][adbloq]

## Contributing

This project accepts code contributions. To prepare the development environment, clone the repo and run `npm i`. You can then build all bookmarklets using `npm run build`.

[adbloq]: https://install-bookmarklet.pages.dev/?url=javascript%3A!function()%7Bconsole.log(%22Activated%20%F0%9F%94%87%20AdBloq%20bookmarklet.%22)%3Bconst%20rm%3Dfunction(e)%7Bfor(const%20o%20of%20e)o.remove()%7D%2CremoveAds%3De%3D%3E%7Brm(e.querySelectorAll(%5B%22*%5Bid*%3D-ad-%5D%22%2C%22*%5Bclass*%3D-ad-%5D%22%2C%22*%5Bid*%3D_ad_%5D%22%2C%22*%5Bclass*%3D_ad_%5D%22%2C%22*%5Bid*%3D-ads-%5D%22%2C%22*%5Bclass*%3D-ads-%5D%22%2C%22*%5Bid*%3D_ads_%5D%22%2C%22*%5Bclass*%3D_ads_%5D%22%2C%22*%5Bid%5E%3Dad_%5D%22%2C%22*%5Bid%5E%3Dad-%5D%22%2C%22*%5Bid%5E%3Dads_%5D%22%2C%22*%5Bid%5E%3Dads-%5D%22%2C%22*%5Bid*%3Dgoogle_ad%5D%22%2C%22*%5Bclass*%3Dgoogle_ad%5D%22%2C%22*%5Bdata-google-query-id%5D%22%2C%22*%5Bdata-google-av-adk%5D%22%2C%22*%5Baria-label*%3DAdvertisement%5D%22%2C%22.GoogleActiveViewElement%22%2C%22.GoogleActiveViewInnerContainer%22%2C%22iframe%5Bid%5E%3DadRoot%5D%22%2C%22video%5Bsrc*%3DAniview%5D%22%2C%22iframe%5BsrcDoc*%3Dceltra%5D%22%2C%22*%5Bclass*%3Dbx-campaign%5D%22%2C%22.ads-mode%22%2C%22*%5Bdata-text-ad%5D%22%2C%22*%5Bclass*%3Dprimisslate%5D%22%2C%22*%5Bid*%3Dprimis_%5D%22%2C%22*%5Btitle*%3DPrimis%5D%22%2C%22*%5Bdata-ad-unit-name%5D%22%2C%22*%5Bid*%3Dtaboola%5D%22%2C%22*%5Bclass*%3Dtaboola%5D%22%5D.join(%22%2C%22)))%3Be%3Dwindow.location.hostname%3Be.endsWith(%22wikipedia.org%22)%3Fdocument.querySelector(%22div%5Baria-label%5E%3Dfundraising%5D%22)%3F.querySelector(%22.frb-inline-close%22)%3F.click%3F.()%3Ae.endsWith(%22sporcle.com%22)%26%26document.querySelector(%22.avp-p-cn-close%22)%3F.click%3F.()%7D%2Cobserver%3Dnew%20MutationObserver(e%3D%3E%7Bfor(const%20o%20of%20e)o.addedNodes%26%26o.addedNodes.forEach(e%3D%3EremoveAds(e.parentElement))%7D)%3Bobserver.observe(document.body%2C%7BchildList%3A!0%2Csubtree%3A!0%7D)%2CremoveAds(document.body)%3B%7D()&name=%F0%9F%94%87%20AdBloq
