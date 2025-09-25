# YorkCollege Remake — Design README

This document focuses purely on the **design and user experience** of the new college app mock. The aim is to provide a clean, modern look and intuitive navigation while keeping the functionality minimal for now.

---

## 📱 Core Layout

The app is divided into **4 key navigation areas**, with buttons fixed at the bottom of the screen:

- **Home Button** → Opens the Announcements feed (college news, updates, events)
- **Timetable Button** → Displays a weekly timetable in a clean, scrollable format
- **Hamburger Menu Button** → Expands a side drawer or modal with additional options
  - Absence Logging
  - Student Personal Data
- **Logout Button** → Ends session and returns to login screen

---

## 🎨 Design Principles

1. **Minimalist UI**: Clean, distraction-free screens.
2. **Consistency**: Same button placement, color palette, and typography across the app.
3. **Responsive Layout**: Works on iPhones of all sizes.
4. **Accessibility**: High contrast text, readable font sizes, tap-friendly buttons.

---

## 🖼️ Suggested Visual Style

- **Color Scheme**:
  - Primary: Deep blue (trust, professionalism)
  - Secondary: Accent color (e.g., orange or green for highlights)
  - Background: Light/neutral grey or white
- **Typography**:
  - Headings: Bold, sans-serif (e.g., Inter, SF Pro)
  - Body: Regular sans-serif for readability
- **Buttons**:
  - Rounded corners, slightly elevated with shadows
  - Icons + text for clarity
- **Announcements List**:
  - Card layout (title, summary, timestamp)
  - Scrollable feed
- **Timetable View**:
  - Grid layout (days vs periods)
  - Highlight current day
- **Hamburger Menu**:
  - Slide-in panel with simple list items + icons

---

## 🛠️ Tech & Libraries (Frontend Design)

- **Framework**: React Native (Expo)
- **Navigation**: React Navigation (stack + bottom tab + drawer)
- **Icons**: Expo Vector Icons (Ionicons/Material)
- **UI Components**: Custom styled views with Tailwind RN or Styled Components
- **State**: React Context or Redux if needed

---

## 🧭 User Flow

1. **Login** → Token stored securely
2. **Home (Announcements)** → Default screen, quick updates
3. **Timetable** → Weekly schedule, student’s classes
4. **Hamburger Menu** → Extra options (Absence Logging + Student Data)
5. **Logout** → Clears session, returns to login

---

## ✅ Next Steps

- Create **mock components** (Announcements, Timetable, Hamburger Menu)
- Implement **bottom navigation bar** with icons + labels
- Style with consistent theme
- Add placeholder data for design testing

---

This README is purely for **design planning** — no backend wiring yet. Once design is approved, functionality can be integrated by connecting endpoints.