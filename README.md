# modditys.com

The temporary under-construction page for Moddities, served by GitHub Pages from `main` at https://modditys.com.
(The repo is named moddities.com; the domain we hold is modditys.com.)

- `index.html` is the whole page: the MoDDITIES lockup inline (from `~/moddities/brand/svg/lockup-mo_ddities_full`), with the throw animation in CSS. Tap the mark to throw the M again.
- `404.html` is a copy of `index.html`, so every path lands on the page. After editing, run `cp index.html 404.html`.
- `og.png` is the link-preview image: `rsvg-convert -w 1200 -h 630 og.svg -o og.png`.
- `CNAME` holds the custom domain, modditys.com. Its GoDaddy DNS has four A records on @ (185.199.108-111.153) and `www` CNAME → mobarakltd.github.io.
