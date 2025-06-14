# 🛠️ WebDev UI & Responsive Guide

A quick reference for responsive UI design, device sizes, and Tailwind breakpoints—perfect for Penpot, Tailwind, or raw CSS!

---

## 🧭 Quick Nav

- [🚦 Recommended Starting Screen Size](#-mobile-devices)
- [📱 Mobile Devices](#-tablets)
- [📲 Tablets](#-laptops--desktops)
- [💻 Laptops & Desktops](#-tailwind-css-breakpoints)
- [🎯 Tailwind CSS Breakpoints](#-tailwind-css-breakpoints)
- [🧠 Tip](#-mobile-first-design-tip)

---

## 🚦 Recommended Starting Screen Size

| Device/Width    | Width (px) | Height (px) | Why Start Here?                                           |
| --------------- | ---------- | ----------- | --------------------------------------------------------- |
| iPhone 12/13/14 | 375        | 812         | Modern common phone, good balance for mobile-first design |
| iPhone 6/7/8    | 375        | 667         | Classic baseline, still widely used                       |

> Starting at **375px wide** covers most modern phones comfortably without cramped layouts, then scale up from there!

---

## 📱 Mobile Devices

| Device          | Width (px) | Height (px) | Notes             |
| --------------- | ---------- | ----------- | ----------------- |
| iPhone SE       | 320        | 568         | Small screen size |
| iPhone XR / 11  | 414        | 896         | Common resolution |
| iPhone 12/13/14 | 390        | 844         | Modern default    |
| Galaxy S10      | 360        | 760         | Android baseline  |
| Pixel 6         | 412        | 915         | High-res Android  |

---

## 📲 Tablets

| Device           | Width (px) | Height (px) | Notes                |
| ---------------- | ---------- | ----------- | -------------------- |
| iPad Mini        | 768        | 1024        | iPad portrait        |
| iPad Pro (11”)   | 834        | 1194        | Common tablet screen |
| iPad Pro (12.9”) | 1024       | 1366        | Largest iPad         |

---

## 💻 Laptops & Desktops

| Device          | Width (px) | Height (px) | Notes                   |
| --------------- | ---------- | ----------- | ----------------------- |
| MacBook Air     | 1280       | 800         | Default macOS laptop    |
| HD Laptop       | 1366       | 768         | Very common screen size |
| MacBook Pro 16” | 1536       | 960         | Retina Display          |
| Full HD Monitor | 1920       | 1080        | Standard desktop        |
| 2K Display      | 2560       | 1440        | High-res desktop        |
| 4K UHD Display  | 3840       | 2160        | Ultra high resolution   |

---

## 🎯 Tailwind CSS Breakpoints

| Breakpoint | Min Width (px) | Use Case           |
| ---------- | -------------- | ------------------ |
| `sm`       | 640            | Small tablets      |
| `md`       | 768            | Tablets            |
| `lg`       | 1024           | Small desktops     |
| `xl`       | 1280           | Large screens      |
| `2xl`      | 1536           | Very large screens |

---

## 🧠 Mobile-First Design Tip

Design for `mobile-first` and then use breakpoints to expand for bigger screens!
