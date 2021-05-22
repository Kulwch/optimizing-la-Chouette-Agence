#optimizing-la-Chouette-Agence

4th project in the OpenClassrooms webdeveloper course. Project consists in optimizing an existing website to improve its accessibility and SEO.

Starting from the v1.0.0 version of the site, i had to conduct an audit of the site, then formulate recommendations to optimize the site's accessibility and SEO. Among all observations i made, i had to determine 10 prorities, and then execute these corrections on the code source. The objective was essentially to improve the site's loading speed, the ressources weights, and the accessibility.

The 10 priorities i determined are:
    - optimizing images (resized, png compressed or converted to webp)
    - contrasts (changed font color so the contrast between background and foreplan always exceeds 4.5 : 1 as WCAG 2.0 advises; removed the paper texture that was problematic)
    - content's accessibility (some texts were in img; font-sizes were too small)
    - black hat SEO removal (div keywords of 1px font-size; links spammy in footer, also all irrelevant)
    - Internal navigation (bad hierarchical structure of the h tags; no robots.txt, no sitemap)
    - Visual content alternate text (no alternate content for backgrounds, the alt attribute was not correctly filled for each img; added aria-label when necessary)
    - head tag wrong parameters (lang set to default; meta name="keywords" deprecated; content empty in the meta description; title not filled; no meta robots)
    - site's structure (headers were not identicals; links name inappropriate; no semantic tag used, only div)
    - mobile display to improve (overflows; accessibility rules not all respected)
    - Optimization of all resources (scripts, css, images...; minification, compressing in GZIP, setting scripts in async or defer; lazy loading for pictures; setting cache)

This work done, the site is released in its v1.1.0 version.

Remaining work that can be done later to finalize the site's optimization: 

- search for quality links (parterships to establish)
- media social links must link towards the company's professionnal accounts
- pictures not very relevant; must search more accurate pictures based on the context
- withdraw useless resources
- the form can be improved (accessibility)

The result of optimization is here: https://kulwch.github.io/optimizing-la-Chouette-Agence/
