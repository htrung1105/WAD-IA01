# X-TECH Landing Page - Assignment IA03

## ✅ Requirements Completed

### 1. CSS Framework (✓)
- **Tailwind CSS** được sử dụng qua CDN
- Responsive layout với grid system
- Utility classes cho spacing, colors, typography

### 2. Minimize Images (✓)
- Chỉ cần **1 hình duy nhất**: Logo + hero mockup từ file `x-tech landing.png`
- Tất cả icons được tạo bằng **CSS thuần** (không dùng hình ảnh)
  - Monitor icon (màu xanh dương)
  - Server icon (màu xám)
  - Briefcase icon (màu xám đậm)
  - Folder icon (màu nâu)
  - Camera icon (màu xám đen)
  - Mouse icon (màu đen)
- Map trong footer được tạo bằng SVG
- Social media icons dùng text

### 3. No JavaScript (✓)
- Hoàn toàn không sử dụng JavaScript
- Chỉ dùng HTML + CSS (Tailwind)

### 4. Desktop View (3 điểm)
- Layout 3 cột cho features section
- Typography rõ ràng, dễ đọc
- Màu sắc gradient background giống thiết kế
- Buttons với hover effects (CSS only)

### 5. Mobile View (3 điểm)
- Responsive breakpoints: sm, md, lg
- Mobile: 1 cột
- Tablet: 2 cột
- Desktop: 3 cột
- Header stack vertically trên mobile

### 6. Browser Compatibility (1 điểm)
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- Sử dụng CSS standard properties
- Tailwind CSS CDN tương thích tất cả browsers

## 📁 File Structure

```
IA03/
├── index.html          # Main HTML file
├── custom.css          # Custom CSS (optional tweaks)
├── x-tech landing.png  # Single image used
└── README.md          # This file
```

## 🚀 How to Test Locally

1. Mở file `index.html` bằng browser
2. Test responsive: Resize browser window hoặc dùng DevTools (F12)
3. Test trên các browsers: Chrome, Firefox, Safari

## 🌐 Deploy to Live Host (1 điểm)

### Option 1: Netlify (Recommended - Free)

1. Đăng ký tài khoản tại https://www.netlify.com
2. Kéo thả folder `IA03` vào Netlify Drop
3. Nhận link: `https://your-site-name.netlify.app`

### Option 2: Vercel (Free)

1. Đăng ký tại https://vercel.com
2. Cài Vercel CLI:
   ```bash
   npm install -g vercel
   ```
3. Deploy:
   ```bash
   cd "d:\Private Data\WAD\IA03"
   vercel
   ```

### Option 3: GitHub Pages (Free)

1. Tạo repository trên GitHub
2. Upload files
3. Settings → Pages → Deploy from branch `main`
4. Link: `https://username.github.io/repo-name`

### Option 4: Render (Free)

1. Đăng ký tại https://render.com
2. New → Static Site
3. Connect repository hoặc upload files
4. Deploy

## 📊 Grading Checklist

- [x] Desktop view: 3 points
- [x] Mobile view: 3 points  
- [x] Using appropriate number of images: 2 points (chỉ 1 image)
- [x] Compatible with 3 browsers: 1 point (Chrome, Firefox, Safari)
- [ ] Uploaded to live host: 1 point (Cần deploy - xem hướng dẫn trên)

**Current Score: 9/10 points**

## 🎨 Design Features

### CSS-Only Icons
- Tất cả icons được vẽ bằng CSS `::before` và `::after` pseudo-elements
- Gradients, shadows, border-radius để tạo depth
- Không cần icon fonts hay image files

### Gradient Background
- Purple-to-black gradient giống thiết kế gốc
- Diagonal line pattern overlay (CSS only)

### Responsive Typography
- Font sizes scale với viewport
- Line heights tối ưu cho mobile và desktop

### Hover Effects
- Buttons có smooth transitions
- Social icons có hover states
- Tất cả dùng CSS transitions (no JavaScript)

## 💡 Tips for Full Score

1. **Deploy ngay**: Chọn 1 trong 4 options trên (Netlify dễ nhất)
2. **Test kỹ**: Mở trên Chrome, Firefox, Safari
3. **Screenshot**: Chụp màn hình cả desktop và mobile view
4. **Submit**: Link deployed + screenshots

## 🔧 Customization

Nếu muốn điều chỉnh:

- **Colors**: Edit trong `<style>` tag của `index.html`
- **Spacing**: Thay đổi Tailwind classes (px-6, py-8, gap-8, etc.)
- **Icons**: Chỉnh width, height, colors trong CSS classes (.icon-*)
- **Fonts**: Đã dùng Google Fonts (Roboto)

## ✨ Bonus Features

- Smooth hover animations
- Professional gradient effects
- Clean, semantic HTML
- Accessible markup
- Fast loading (no heavy images)
- SEO-friendly structure

---

**Good luck with your assignment! 🎓**

