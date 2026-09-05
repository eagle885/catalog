# تعليمات المشروع - كتالوج حمايات الهواتف

## how to update the website
1. edit files (index.html, images in _compressed/)
2. run: git add . && git commit -m "update" && git push
3. website updates automatically in 30 seconds

## file structure
- index.html = main catalog page (Arabic RTL)
- _compressed/ = product images (400px, quality 70)
- _hd/ = enhanced images for web (500px, quality 92, white bg)
- print-final.html = PDF generation page
- catalog-v35.pdf = latest PDF output

## product codes
GP1-GP29, each code = one product group with multiple colors

## adding new product
1. put images in source folder
2. convert to jpg: use PowerShell with PresentationCore
3. compress to _compressed/ (400px, q70)
4. create HD version in _hd/ (500px, q92, white bg)
5. add HTML section to index.html
6. push to github

## important notes
- Arabic only (RTL layout)
- WhatsApp: +972598608000
- No prices, no videos
- Images must be lowercase .jpg extension (Vercel/Linux is case-sensitive)
- Hosted on Vercel via GitHub (free tier)
- Repo: github.com/eagle885/catalog
