Bạn là một Senior Frontend Engineer + UI/UX Designer + Motion Designer chuyên xây dựng các website hiện đại, premium và có animation tinh tế.

Hãy xây dựng một website showcase hiện đại có tên:

**"MODERN UI STYLE LAB"**

Mục tiêu:
Tạo một website cho phép người dùng trải nghiệm **13 phong cách thiết kế web hiện đại** trong cùng một hệ thống. Người dùng có thể chuyển đổi giữa các style bằng Theme Switcher mà không làm thay đổi nội dung và cấu trúc UX chính của website.

Website phải có cảm giác như một **design laboratory / interactive design system**, cực kỳ polished, responsive và chuyên nghiệp.

━━━━━━━━━━━━━━━━━━━━

1. TECH STACK
   ━━━━━━━━━━━━━━━━━━━━

Sử dụng:

* React
* TypeScript
* Vite hoặc Next.js
* Tailwind CSS
* Framer Motion / Motion
* Lucide React Icons
* CSS Variables cho theme system
* CSS Grid + Flexbox
* Semantic HTML
* Responsive design
* Dark/light support khi phù hợp

Code phải sạch, modular và dễ mở rộng.

Không viết một file component khổng lồ.

Tách thành:

* components/
* sections/
* themes/
* hooks/
* data/
* utils/
* styles/

━━━━━━━━━━━━━━━━━━━━
2. CORE CONCEPT
━━━━━━━━━━━━━━━━━━━━

Xây dựng một **Universal Theme Engine**.

Tất cả UI component phải sử dụng design tokens thay vì hard-code style.

Ví dụ:

--background
--foreground
--surface
--surface-secondary
--primary
--secondary
--accent
--border
--shadow
--radius
--blur
--card-padding
--font-heading
--font-body
--animation-speed

Khi người dùng chọn một style:

* toàn bộ theme thay đổi
* màu sắc thay đổi
* typography thay đổi
* border thay đổi
* border-radius thay đổi
* shadow thay đổi
* background thay đổi
* card style thay đổi
* button style thay đổi
* animation thay đổi
* decorative effects thay đổi

Nhưng:

**Content, information architecture và UX flow phải giữ nguyên.**

Theme system cần có API:

setTheme(theme)
getTheme()
themeConfig

Cho phép dễ dàng thêm theme mới về sau.

━━━━━━━━━━━━━━━━━━━━
3. 13 DESIGN STYLES
━━━━━━━━━━━━━━━━━━━━

Triển khai đầy đủ 13 theme:

### 01 — GLASSMORPHISM

Phong cách kính mờ cao cấp.

Đặc điểm:

* backdrop blur
* translucent cards
* transparent layers
* soft borders
* floating elements
* glowing background
* subtle gradients

Card phải có cảm giác như kính thật.

Sử dụng blur vừa phải, tránh làm text khó đọc.

━━━━━━━━━━━━━━━━━━━━

### 02 — NEUMORPHISM / SOFT UI

Thiết kế nổi/chìm mềm.

Đặc điểm:

* soft shadows
* inner shadow
* outer shadow
* rounded surfaces
* tactile buttons
* subtle depth

Button khi hover/press phải tạo cảm giác vật lý.

━━━━━━━━━━━━━━━━━━━━

### 03 — CLAYMORPHISM

Phong cách 3D mềm, vui nhộn.

Đặc điểm:

* chunky rounded shapes
* thick soft shadows
* colorful surfaces
* playful typography
* soft 3D appearance

Animation vui vẻ nhưng không quá lố.

━━━━━━━━━━━━━━━━━━━━

### 04 — NEO-BRUTALISM

Phong cách mạnh, raw và high contrast.

Đặc điểm:

* black borders
* thick borders
* hard shadows
* high contrast colors
* large typography
* imperfect visual balance
* asymmetric layout

Hover button có thể:

* translate 4px
* shadow giảm
* border interaction

Tạo cảm giác “physical”.

━━━━━━━━━━━━━━━━━━━━

### 05 — MINIMALIST UI

Phong cách tối giản premium.

Đặc điểm:

* white space lớn
* typography rõ ràng
* neutral palette
* thin borders
* subtle shadows
* clean layout
* strong hierarchy

Animation cực kỳ nhẹ.

━━━━━━━━━━━━━━━━━━━━

### 06 — FROST UI

Phiên bản nhẹ hơn của Glassmorphism.

Đặc điểm:

* subtle transparency
* low blur
* neutral colors
* clean surfaces
* premium SaaS aesthetic

Không được sử dụng blur quá mạnh.

━━━━━━━━━━━━━━━━━━━━

### 07 — MESH GRADIENT

Phong cách abstract gradient.

Đặc điểm:

* multiple color gradients
* fluid gradients
* organic color transitions
* animated gradient background
* dreamy atmosphere

Background phải có cảm giác như liquid color.

Animation gradient rất chậm và smooth.

━━━━━━━━━━━━━━━━━━━━

### 08 — AURORA / BLURRED LIGHT

Phong cách ánh sáng cực quang.

Đặc điểm:

* glowing blobs
* blurred lights
* light streaks
* vibrant gradients
* atmospheric background

Tạo các floating light blobs chuyển động chậm phía background.

━━━━━━━━━━━━━━━━━━━━

### 09 — CYBER / FUTURISTIC UI

Phong cách sci-fi / AI / cyberpunk.

Đặc điểm:

* dark background
* neon accents
* HUD inspired UI
* grid overlays
* glowing borders
* futuristic typography
* geometric details

Thêm:

* scanline effect rất nhẹ
* grid background
* glowing cursor
* futuristic loading states

Không biến website thành một game UI quá mức.

━━━━━━━━━━━━━━━━━━━━

### 10 — OUTLINE / SKELETAL UI

Phong cách chỉ sử dụng đường nét.

Đặc điểm:

* outlined cards
* outlined buttons
* minimal fills
* thin borders
* wireframe aesthetic

Hover phải tạo animation:

border → glow
outline → filled state

━━━━━━━━━━━━━━━━━━━━

### 11 — RETRO-FUTURISM / SYNTHWAVE

Phong cách futuristic thập niên 80.

Đặc điểm:

* neon purple
* neon pink
* blue glow
* retro grid
* VHS-inspired texture
* pixel details
* nostalgic typography

Hero background có:

* perspective grid
* glowing horizon
* subtle noise

━━━━━━━━━━━━━━━━━━━━

### 12 — 3D / ISOMETRIC

Phong cách depth / perspective.

Đặc điểm:

* 3D floating cards
* isometric shapes
* perspective
* layered elements
* depth
* parallax

Tạo một số decorative 3D elements bằng CSS hoặc lightweight WebGL nếu cần.

Không sử dụng heavy 3D nếu không cần thiết.

━━━━━━━━━━━━━━━━━━━━

### 13 — ORGANIC

Phong cách tự nhiên, mềm mại.

Đặc điểm:

* blob shapes
* irregular borders
* pastel gradients
* curved layouts
* organic motion
* soft typography

Card có border-radius không đồng nhất để tạo cảm giác tự nhiên.

━━━━━━━━━━━━━━━━━━━━
4. WEBSITE STRUCTURE
━━━━━━━━━━━━━━━━━━━━

Tạo website gồm:

### NAVBAR

Logo:

MODERN UI LAB

Menu:

* Home
* Styles
* Components
* Playground
* About

Bên phải:

* Theme Switcher
* Dark/Light toggle nếu phù hợp
* GitHub icon

Navbar phải tự thay đổi theo theme.

━━━━━━━━━━━━━━━━━━━━

### HERO SECTION

Headline lớn:

"Explore the Visual Languages of the Modern Web"

Subtitle:

"One interface. Thirteen design systems. Infinite possibilities."

CTA:

"Explore Styles"

Secondary CTA:

"Open Playground"

Hero có visual decoration phụ thuộc theme.

Ví dụ:

Glassmorphism → floating glass panels

Cyber → HUD graphics

Synthwave → retro grid

Organic → blobs

Neo-Brutalism → offset shapes

3D → floating objects

━━━━━━━━━━━━━━━━━━━━

### STYLE SWITCHER

Đây là phần quan trọng nhất.

Hiển thị 13 theme trong một sidebar / floating panel.

Mỗi theme có:

* icon
* name
* short description
* miniature preview

Ví dụ:

Glassmorphism
"Frosted transparency"

Neumorphism
"Soft tactile depth"

Claymorphism
"Playful 3D surfaces"

Neo-Brutalism
"Bold raw interfaces"

...

Khi click:

Theme chuyển đổi ngay lập tức.

Transition khoảng 300–600ms.

Không reload trang.

━━━━━━━━━━━━━━━━━━━━
5. LIVE COMPONENT SHOWCASE
━━━━━━━━━━━━━━━━━━━━

Tạo section:

"Same Components. Different Worlds."

Hiển thị cùng một bộ component:

* Button
* Input
* Card
* Badge
* Toggle
* Checkbox
* Slider
* Avatar
* Modal
* Dropdown
* Tabs
* Tooltip
* Progress bar
* Notification
* Pricing card
* Stats card

Mỗi theme phải render chúng theo ngôn ngữ thiết kế tương ứng.

Ví dụ:

Neo-Brutalism:

BUTTON
████████
black border + hard shadow

Glass:

frosted translucent button

Cyber:

neon glowing button

Clay:

soft 3D button

Organic:

rounded organic button

━━━━━━━━━━━━━━━━━━━━
6. INTERACTIVE PLAYGROUND
━━━━━━━━━━━━━━━━━━━━

Tạo một Playground nơi người dùng có thể thử:

* border radius
* shadow intensity
* blur
* gradient
* animation speed
* spacing
* typography scale

Có live preview.

Hiển thị:

"Design Token Inspector"

Ví dụ:

Radius: 24px
Blur: 18px
Shadow: Medium
Animation: Smooth

Thay đổi slider → UI thay đổi realtime.

━━━━━━━━━━━━━━━━━━━━
7. STYLE COMPARISON
━━━━━━━━━━━━━━━━━━━━

Tạo section:

"One Component — 13 Styles"

Hiển thị cùng một card dưới dạng:

Glass
Neumorphism
Clay
Neo-Brutalism
Minimal
Frost
Mesh
Aurora
Cyber
Outline
Synthwave
3D
Organic

Người dùng có thể compare trực tiếp.

Có animation khi chuyển giữa các style.

━━━━━━━━━━━━━━━━━━━━
8. ANIMATION SYSTEM
━━━━━━━━━━━━━━━━━━━━

Animation phải cực kỳ polished.

Sử dụng:

* fade
* slide
* scale
* spring
* blur transition
* parallax
* magnetic buttons
* hover tilt
* floating animation
* scroll reveal
* staggered animation

Mỗi theme có motion language riêng.

Ví dụ:

Minimal:
→ slow fade

Cyber:
→ fast sharp transitions

Clay:
→ spring physics

Organic:
→ fluid motion

Neo-Brutalism:
→ instant snappy movement

Glass:
→ smooth floating motion

━━━━━━━━━━━━━━━━━━━━
9. MICRO INTERACTIONS
━━━━━━━━━━━━━━━━━━━━

Thêm:

* magnetic CTA
* hover glow
* button press
* card tilt
* cursor interaction
* animated underline
* theme transition
* scroll progress
* tooltips
* animated counters

Nhưng:

**Không được lạm dụng animation.**

UX phải luôn ưu tiên readability và usability.

━━━━━━━━━━━━━━━━━━━━
10. RESPONSIVE DESIGN
━━━━━━━━━━━━━━━━━━━━

Phải hoạt động tốt trên:

* Desktop
* Laptop
* Tablet
* Mobile

Desktop:

sidebar style selector.

Mobile:

bottom sheet / horizontal style selector.

Không để overflow ngang.

Typography phải tự scale.

━━━━━━━━━━━━━━━━━━━━
11. ACCESSIBILITY
━━━━━━━━━━━━━━━━━━━━

Bắt buộc:

* semantic HTML
* keyboard navigation
* visible focus states
* ARIA khi cần
* contrast tốt
* prefers-reduced-motion
* screen-reader friendly

Nếu người dùng bật:

prefers-reduced-motion

thì giảm toàn bộ animation mạnh.

━━━━━━━━━━━━━━━━━━━━
12. PERFORMANCE
━━━━━━━━━━━━━━━━━━━━

Đặc biệt tối ưu:

* backdrop-filter
* box-shadow
* blur
* gradient animation
* 3D effects

Không render animation nặng nếu không cần.

Lazy-load các visual effects nặng.

Ưu tiên CSS animation và GPU-friendly properties.

Tránh:

layout thrashing
continuous expensive JS calculations
heavy canvas rendering

Website phải vẫn mượt ở khoảng 60 FPS trong điều kiện bình thường.

━━━━━━━━━━━━━━━━━━━━
13. DESIGN SYSTEM ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━

Tạo:

ThemeConfig

Ví dụ:

type ThemeConfig = {
id: string
name: string
description: string
colors: ...
typography: ...
radius: ...
shadows: ...
effects: ...
motion: ...
}

Tạo riêng:

themes/glass.ts
themes/neumorphism.ts
themes/clay.ts
themes/brutalism.ts
themes/minimal.ts
themes/frost.ts
themes/mesh.ts
themes/aurora.ts
themes/cyber.ts
themes/outline.ts
themes/synthwave.ts
themes/isometric.ts
themes/organic.ts

Không hard-code 13 theme trong component.

━━━━━━━━━━━━━━━━━━━━
14. VISUAL QUALITY
━━━━━━━━━━━━━━━━━━━━

Website phải có cảm giác:

* premium
* modern
* experimental
* polished
* production-ready

Không làm theo kiểu:

"mỗi theme đổi background là xong."

Mỗi theme phải có:

* color language riêng
* typography riêng
* spacing behavior
* shadow system
* border system
* component language
* motion language
* decorative elements

Tức là mỗi theme phải thực sự giống một **design system độc lập**.

━━━━━━━━━━━━━━━━━━━━
15. FINAL EXPERIENCE
━━━━━━━━━━━━━━━━━━━━

Trang đầu tiên người dùng nhìn thấy phải cực kỳ ấn tượng.

Khi đổi theme:

TOÀN BỘ WEBSITE PHẢI CÓ CẢM GIÁC NHƯ ĐƯỢC THIẾT KẾ LẠI.

Ví dụ:

Glassmorphism
→ giống futuristic Apple/SaaS interface

Neo-Brutalism
→ giống experimental design studio

Cyber
→ giống AI command center

Synthwave
→ giống futuristic 80s dashboard

Organic
→ giống premium wellness startup

Clay
→ giống playful creative product

3D
→ giống high-end product landing page

━━━━━━━━━━━━━━━━━━━━
16. CODE QUALITY
━━━━━━━━━━━━━━━━━━━━

Code phải:

* TypeScript strict
* reusable
* modular
* scalable
* clean
* maintainable

Không dùng duplicated code.

Tạo reusable components như:

<Button /> <Card /> <Input /> <Modal /> <Navbar /> <ThemeSwitcher /> <ThemePreview />

Theme chỉ quyết định visual behavior.

━━━━━━━━━━━━━━━━━━━━
17. EXTRA FEATURES
━━━━━━━━━━━━━━━━━━━━

Thêm những tính năng giúp website cao cấp hơn:

* Share current theme
* Copy theme config
* Export CSS variables
* Random style button
* Favorite themes
* Theme search
* Theme preview cards
* "Surprise me" button
* keyboard shortcut để đổi theme
* persist theme bằng localStorage

Phím:

1 → Glass
2 → Neumorphism
3 → Clay
4 → Brutalism
5 → Minimal
6 → Frost
7 → Mesh
8 → Aurora
9 → Cyber
0 → Outline

Có thể dùng thêm modifier key cho các theme còn lại.

━━━━━━━━━━━━━━━━━━━━
18. IMPORTANT DESIGN RULE
━━━━━━━━━━━━━━━━━━━━

Không biến website thành một "gallery đơn giản".

Hãy xây dựng nó như một:

**interactive design operating system**

Nơi người dùng thực sự cảm nhận được sự khác biệt giữa từng design language.

Mọi chuyển đổi phải mượt.

Mọi component phải phản ứng theo theme.

Mọi theme phải có cá tính riêng.

Nhưng usability, readability, accessibility và performance luôn được ưu tiên hơn hiệu ứng.

━━━━━━━━━━━━━━━━━━━━
19. OUTPUT REQUIREMENT
━━━━━━━━━━━━━━━━━━━━

Hãy tạo toàn bộ source code hoàn chỉnh.

Bao gồm:

* folder structure
* components
* pages
* theme engine
* 13 themes
* responsive CSS
* animations
* theme switcher
* playground
* component showcase
* comparison section
* accessibility
* performance optimization

Website phải chạy được ngay sau:

npm install
npm run dev

Không để:

TODO
placeholder
broken component
empty section
fake interaction

Tất cả button và interaction quan trọng phải hoạt động thật.

Cuối cùng, hãy đảm bảo toàn bộ website có chất lượng như một **real premium frontend product**, không phải demo học tập đơn giản.
