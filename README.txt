DOIT Portfolio - Mobile Full Monitor FIXED

Fixes the real clipping cause:
- resets #mcard from absolute desktop positioning to relative mobile positioning
- removes top:50% and translateY(-50%) from the mobile monitor card
- preserves full 900x540 EQ-Alarmer screen
- keeps MA301+, intensity, S-wave arrival, alarm stage and sending status visible
- leaves current 3D camera/scenery framing unchanged
- desktop/laptop unchanged

GitHub update:
Replace D:\outputs\index.html
git add index.html
git commit -m "Fix full mobile monitor card"
git push
