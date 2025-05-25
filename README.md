# English  

# Personal-Homepage-zong  


## Description  
[Online Demo (Click to Visit)](https://www.rockaz.top/banburubi/)  
*Note: The demo server is located in China.*  

This project, named **Personal-Homepage-zong**, is a customized personal homepage built with HTML, CSS, and JavaScript for [Bumblebee - Android Zongzi (Network Name)]. It features a "Zongzi" theme with glassmorphism design and smooth animations, showcasing personal information, interest tags, timeline updates, an interactive "About" modal, and a **real-time birthday countdown** function.  


## Features  
- **Glassmorphism Interface**: Semi-transparent backgrounds, backdrop blur, and shadow effects create a modern visual style.  
- **Animated Interactions**: Fade-in, slide-in, and floating CSS animations enhance page loading and interaction experiences.  
- **Personal Info Display**: Includes avatar (with hover zoom), nickname, signature, and social media links (e.g., QQ Space).  
- **Interactive Tag Cloud**: Hover effects on tags (e.g., "Anime," "Minecraft") highlight hobbies with scaling and color changes.  
- **Timeline Updates**: Reverse-chronological display of recent activities with smooth slide-in animations.  
- **Modal "About" Popup**: Click the navigation link to trigger a personalized introduction modal, closable via button or outside click.  
- **Birthday Countdown**: Real-time countdown to [Bumblebee - Android Zongzi]’s birthday (set to May 6th by default), displaying days, hours, minutes, and seconds. Updates every second and includes hover animations.  
- **Responsive Design**: Automatic layout adjustment for mobile, tablet, and desktop devices.  


## File Structure  
All code is embedded in a single HTML file:  
```  
└── index.html       # Contains HTML structure, inline CSS, and JavaScript  
```  


## Usage  
1. **Direct Deployment**:  
   - Download `index.html`.  
   - Open in modern browsers (Chrome, Firefox, etc.) to view the homepage with real-time countdown.  

2. **Customization**:  
   - **Content Update**:  
     - Modify HTML text (nickname, signature, tags, timeline entries) to reflect real information.  
     - Replace tx.svg (avatar) and bg.svg (background) with custom images.  
   - **Birthday Date Adjustment**:  
     - In the JavaScript section, update the birthday date in getNextBirthday() (default: new Date(currentYear, 4, 6) = May 6th).  
     - Adjust the "formatTimeDifference" function to change the display format (e.g., hide months or seconds).  
   - **Style Tweaks**:  
     - Modify CSS variables (e.g., --primary-color, --glass-bg) to change theme colors.  
     - Adjust animation durations or easing in the @keyframes rules.  


## Compatibility  
Works on modern browsers (Chrome, Firefox, Edge, Safari). Older browsers may have limited support for CSS features like backdrop-filter or object-fit, affecting visual consistency.  


# 中文  

# 个人主页-粽  


## 描述  
[在线演示（点击访问）](https://www.rockaz.top/banburubi/)   

本项目名为 **Personal-Homepage-zong**，是为 [大黄蜂-安卓粽（网名）] 定制的个人主页，基于 HTML、CSS、JavaScript 构建，以“粽”为主题，融合玻璃拟态设计与流畅动画。页面包含个人信息展示、兴趣标签云、时间线动态、交互式“关于”弹窗及实时生日倒计时功能。  


## 功能特性  
- **玻璃拟态界面**：半透明背景、毛玻璃模糊与阴影效果，营造现代视觉风格。  
- **动画交互**：淡入、滑入、漂浮等 CSS 动画，提升页面加载与交互的灵动感。  
- **核心信息展示**：包含头像（悬停放大）、昵称、个性签名及社交链接（如QQ空间）。  
- **可交互标签云**：标签（如“二次元”“Minecraft”）支持悬停缩放与变色，直观呈现兴趣爱好。  
- **时间线动态**：按时间倒序列出近期活动，每条动态附带平滑滑入动画。  
- **模态“关于”弹窗**：点击导航栏“关于”触发个性化介绍弹窗，支持按钮关闭或点击外部区域关闭。  
- **生日倒计时**：实时显示距离 [大黄蜂-安卓粽] 生日（默认设定为5月6日）的剩余时间，精确到天、小时、分钟、秒，每秒自动更新并包含悬停动画。  
- **响应式布局**：自动适配手机、平板、桌面端，不同屏幕尺寸下布局智能调整。  


## 文件结构  
所有代码均内联于单个 HTML 文件：  
```  
└── index.html       # 包含 HTML 结构、内联 CSS 及 JavaScript
```  


## 使用方法  
1. **直接部署**：  
   - 下载 `index.html`。  
   - 使用 Chrome、Firefox 等现代浏览器打开，即可查看带实时倒计时的个人主页。  

2. **自定义修改**：  
   - **内容更新**：  
     - 编辑 HTML 中的昵称、签名、标签、时间动态等文本，替换为真实信息。  
     - 将 tx.svg（头像）和 bg.svg（背景图）替换为自定义图片。  
   - **生日日期调整**：  
     - 在 JavaScript 中修改 getNextBirthday() 函数中的生日日期（默认：new Date(currentYear, 4, 6)，即5月6日，注意月份从0开始计数）。  
     - 调整 "formatTimeDifference" 函数可改变显示格式（如隐藏月份或秒数）。  
   - **样式调整**：  
     - 通过 CSS 变量（如 --primary-color 主色、--glass-bg 玻璃背景）修改主题配色。  
     - 在 @keyframes 规则中调整动画时长或缓动效果。  


## 兼容性  
支持 Chrome、Firefox、Edge、Safari 等现代浏览器。旧版浏览器可能不支持 backdrop-filter、object-fit 等 CSS 特性，导致视觉效果略有差异。
