## ✅ Project Name

**Clockwork** – clear, memorable, scalable for GitHub/Play Store.

---

## ✅ Tech Stack (finalized)

|**Area**|**Tech**|
|---|---|
|Framework|**React Native (Expo, TypeScript)**|
|State Mgmt|**Zustand**|
|Styling|**NativeWind (Tailwind for RN), Paper**|
|Local DB|**expo-sqlite** (scalable), fallback AsyncStorage for initial testing|
|Date Utils|**date-fns**|
|Charts|**react-native-svg**, **react-native-svg-charts**|
|Forms/Validation|**react-hook-form, zod**|
|Notifications|**expo-notifications** (optional Phase 2)|
|CI/CD|**Expo EAS**, GitHub Actions|
|Testing (Phase 2)|**Jest, React Native Testing Library**|

---

## ✅ File/Folder Structure

```
clockwork/
├── app/                   # screens and navigation
│   ├── index.tsx          # home, navigation setup
│   ├── timer/             # start/stop timer UI + logic
│   ├── logs/              # view tracked sessions
│   ├── stats/             # charts & summary
│   ├── settings/          # (optional Phase 2)
├── components/            # reusable UI components
│   ├── TimerButton.tsx
│   ├── SessionCard.tsx
│   ├── TagSelector.tsx
├── store/                 # zustand stores
│   ├── timerStore.ts
│   ├── sessionStore.ts
├── lib/                   # utilities
│   ├── date.ts            # date-fns helpers
│   ├── charts.ts          # chart utilities
├── database/              # SQLite setup and schema
│   ├── index.ts
│   ├── migrations.ts
├── hooks/                 # custom hooks
├── assets/                # icons, splash, fonts
├── App.tsx
├── app.json               # Expo config
├── tailwind.config.js
├── package.json
```

---

## ✅ Prototype Plan (3-day deadline)

### 🎯 **Goal: Functional MVP Prototype**

> Track time for tasks with **start/stop**, **label**, **tag**, **view log list**, **view total time per tag/project**, **basic pie chart visualization**.

---

### **Day 1: Setup & Timer Logic**

✅ Initialize **Expo project with TypeScript**.  
✅ Add **NativeWind, React Native Paper, Zustand**.  
✅ Setup **SQLite** schema:

- Tables: `sessions`, `tags`.
    

✅ Implement:

- Timer start/stop.
    
- Duration tracking (pause/resume optional).
    
- Temporary in-memory storage (move to SQLite later).
    

---

### **Day 2: Session Labeling & Logs UI**

✅ Add session labeling:

- Title
    
- Optional description
    
- Tag selection/creation (stored in SQLite).
    

✅ Build **Logs screen:**

- FlatList of sessions.
    
- Show title, duration, tag, start/end times.
    

✅ Create reusable **SessionCard** and **TagSelector** components.

---

### **Day 3: Stats & Charts**

✅ Add **total time per tag/project calculation**.  
✅ Add **basic pie/bar chart** using `react-native-svg-charts`.  
✅ Create Stats screen showing:

- Total time tracked today.
    
- Top 5 tags/projects with total durations.
    

✅ Polish UI with NativeWind:

- Responsive layouts.
    
- Consistent spacing, typography.
    

✅ Add dark/light mode toggle.

---

## ✅ After Prototype

- Test flows.
    
- Polish state management.
    
- Optional: Expo EAS build for testing on your phone.
    

---

## ✅ Next Steps

If ready, I can now generate:

✅ **SQLite database schema + initialization code.**  
✅ **Zustand store initial draft (`timerStore`, `sessionStore`).**  
✅ **Day 1 checklist with command snippets for setup.**  
✅ **Initial screen wireframe structure for `Timer`, `Logs`, `Stats`.**

to let you start immediately without confusion and hit your **3-day prototype goal systematically**. Let me know if you want these next.