# Profile Image Asset

Place your profile photograph in this directory:

- **Target File Path:** `images/profile.jpg`
- **Recommended Format:** JPEG or PNG
- **Recommended Dimensions:** Square aspect ratio (1:1), 400x400px to 800x800px
- **Display Treatment:**
  - Rendered at 90px x 90px (76px on mobile)
  - Circular crop (`border-radius: 50%`) with `object-fit: cover`
  - Subtle glowing border matching the portfolio's frosted glassmorphic theme
  - Active status pulse indicator

> Note: If `profile.jpg` is not present, the portfolio automatically displays an intentional dark glassmorphic monogram placeholder ("AY") so the layout remains polished without broken image icons or layout shifts.
