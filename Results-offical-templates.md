# Methodology
1. I chaged the layout.tsx on all of the variants with a single letter.
2. I used a stop timer by hand to measure from when I clicked to when I saw the letter on the screen. Not comprehensive per say, but 1000x better than nothing. This is real life benchmark for developers
3. I haven't modified any code from `pnpx create-payload-app@latest` from 1 November 2025.
4. I used `pnpm dev` with Node.js 23 on Windows 10 Intel Core i7-7820HQ 32GB RAM & Kingston SSD

# Next.js 16 official
< 100 ms to see changes. Practically it was instant. Especially with the new fileSystemCache for dev turbo pack.

# Blank (simple) template
It took 1-1.5 sec to see changes reflected on the UI. It was a good experience overall. Definitely things to be improved.

# Website template
2,3-2,5 sec. I had to wait which loses my focus. People expect < 50ms for smth to happen. 2+ sec. and we get distracted. That's really bad.

# Ecommerce
- 5.41s; 4s; 3.4s; 4s; 3.50s; 4:49s (multiple chars). That's straight up slow. Really bad unusable experinece. The DX is out the window.