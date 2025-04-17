+++
date = '2025-04-17T16:24:22+01:00'
title = 'Hello'
+++

Here I am using `.Site.getPage` in a shortcode:

{{% include "/some/page" %}}

---

Here I am using `.Site.getPage` to get the same page in a partial from a shortcode:

{{% include_indirect "/some/page" %}}
