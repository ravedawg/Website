---
layout: post
title:  "Referencing pics to save space"
date:   2021-08-21 00:01:00 -0400
categories: projects
tags: [code]
---
GitHub-pages limits users to 1GB of free hosting. My total storage for 12 posts with 3 images on average is about 250MB. Images run about 3MB each, and represent most of the growth of my site's baseline architecture. 

I'd like to avoid hitting the 1GB threshold, to keep my hosting free. One easy way to accomplish this is to start hosting my pictures somewhere else, and embedding references in my static site. Three lines of kramdown is much less expensive than uploading my pics. And it's apparently super easy. I'll demo with a flickr image from famous botanical water colorist, Evelyn Binns.

1. Navigate to the site, select the share icon (arrow). Copy and paste the code from the embed tab.
<p align="middle">
  <img src="/photos/20210904_flickr.png" title="click share, copy the code on the embed tab" width="400" />
</p>


2. Paste the code into your site's html. That's it.

```

<p align="middle">
    <a data-flickr-embed="true" href="https://www.flickr.com/photos/142654530@N06/43289561432/in/photolist-iWVZs2-aNb4BH-binNUT-8WkSRX-8WoTko-8WkRap-8WoZQh-8WkNwp-8WkNNc-8Wp1su-8WkUGt-8WoYih-8WkRrt-8WkSyz-8WkTat-8WoTQJ-8Wp3QN-8WoZ6j-8WkTNX-8VqzFH-8WoWfj-8WoXBG-8WkVst-8WoUBN-8WkXvx-8Wp36L-8Wp29W-8WoSdb-8WkWai-8WkYur-8WkZcr-8WkWZH-8Wp4wA-8WkRVH-8WkMik-8VtDaW-8WkXPk-8WkQb4-8VtC7J-9cVHcq-9cSBHT-9cSFfn-9cSE9k-9cSzdT-9cSGyB-9cVEn9-9cSHHz-9cSAv8-8WkMAe-28XmjqQ" title="Flowers Drawings : Evelyn Binns WATERCOLOR"><img src="https://live.staticflickr.com/1823/43289561432_3976a81ebc_w.jpg" width="270" height="400" alt="Flowers Drawings : Evelyn Binns WATERCOLOR">
    </a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script><p align="middle">Watercolor by Evelyn Binns. She's an amazing talent.
</p>

```

voila:

<p align="middle">
    <a data-flickr-embed="true" href="https://www.flickr.com/photos/142654530@N06/43289561432/in/photolist-iWVZs2-aNb4BH-binNUT-8WkSRX-8WoTko-8WkRap-8WoZQh-8WkNwp-8WkNNc-8Wp1su-8WkUGt-8WoYih-8WkRrt-8WkSyz-8WkTat-8WoTQJ-8Wp3QN-8WoZ6j-8WkTNX-8VqzFH-8WoWfj-8WoXBG-8WkVst-8WoUBN-8WkXvx-8Wp36L-8Wp29W-8WoSdb-8WkWai-8WkYur-8WkZcr-8WkWZH-8Wp4wA-8WkRVH-8WkMik-8VtDaW-8WkXPk-8WkQb4-8VtC7J-9cVHcq-9cSBHT-9cSFfn-9cSE9k-9cSzdT-9cSGyB-9cVEn9-9cSHHz-9cSAv8-8WkMAe-28XmjqQ" title="Flowers Drawings : Evelyn Binns WATERCOLOR"><img src="https://live.staticflickr.com/1823/43289561432_3976a81ebc_w.jpg" width="270" height="400" alt="Flowers Drawings : Evelyn Binns WATERCOLOR"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
    <p align="middle">Watercolor by Evelyn Binns. She's an amazing talent.</p>
</p>

Worked first try. Same thing for videos. Am I anywhere close to needing to upload all my images to flickr and embed references in my website? At 261MB, I got a ways to go before hitting github-page's 1GB threshold. But it's nice to know that I have the option for more space-efficiency if I need it.
