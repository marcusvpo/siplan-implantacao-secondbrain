```
prd_content = """# PRODUCT REQUIREMENT DOCUMENT (PRD)
## PROJECT: MARCOLA PRIME v1.0
### [CONFIDENTIAL - COMMAND CENTER REPOSITORY]

---

## 1. VISION & EXECUTIVE SUMMARY

### 1.1 Project Conception
**Project: Marcola Prime** is a hyper-personalized, mobile-first web application designed for exclusive personal use as a workout and fitness routine orchestration engine. The application acts as a digital "Command Center" (Jarvis-inspired UI) that centralizes tracking, progress visualization, scheduling, and supplementation logistics into a single, high-fidelity, low-friction terminal.

### 1.2 Core Pillars
* **Zero-Friction Logging:** The primary objective during a live workout is reducing cognitive overhead. Data entry must require minimal taps, leveraging historical defaults and predictive state machine behaviors.
* **Jarvis / Tactical UI Aesthetic:** Moving away from standard commercial health apps. The theme utilizes high-contrast dark themes, technical data visualizations, telemetry elements, and glowing indicators reminiscent of a military tactical display or an AI operations center.
* **Deep Analytics Terminal:** Turning raw workout logs into advanced training metrics (Total Tonnage, Muscle Group Heatmaps, Volume Distribution, Fatigue Forecasting).
* **Static Supplement Lifecycle Management:** A visual, non-tracking-heavy timeline of daily intake with background-calculated inventory lifespans.

---

## 2. TECHNICAL ARCHITECTURE & STACK

Optimized for **AI-Assisted Development (Vibe Coding)** using platforms such as Cursor, Lovable, Trae, and Replit. The stack is selected for rapid generation, component modularity, and strict type safety.

| Layer | Technology | Justification |
| :--- | :--- | :--- |
| **Frontend Framework** | React 19 (TypeScript) + Vite | Ultra-fast build times, strict typing for AI parsing, clean component instantiation. |
| **Styling Engine** | Tailwind CSS | Utility-first, immediate UI building, seamless integration with custom animations/glow variables. |
| **Database & Auth** | Supabase (PostgreSQL) | Instant REST API generation, easy row-level security, simple schema migration tracking. |
| **State Management** | Zustand | Lightweight, hooks-based, decoupled from UI rendering, perfect for active workout session tracking. |
| **Data Visualization** | Recharts / Chart.js | Pure React SVG components, easily styled with custom CSS glow effects and gradients. |
| **Iconography** | Lucide React | Clean, minimalist, modern technical icons. |
| **Deployment Target**| Vercel | Instant continuous integration, easy DNS routing, optimized edge delivery. |

---

## 3. UI/UX & DESIGN SYSTEM (JARVIS / COMMAND CENTER)

### 3.1 Visual Language
The app must feel alive, scientific, and responsive. UI elements should resemble a data terminal with soft cybernetic glows, sharp borders, and monospaced diagnostic layouts.

* **Background:** True Deep Black (`#000000`) and Tactical Charcoal (`#0B0F19`).
* **Primary Accent (Telemetry Cyan):** `#00F0FF` (Used for active buttons, highlights, and primary metrics).
* **Secondary Accent (Matrix Green):** `#39FF14` (Used for successfully completed sets, PR achievements, and normal system states).
* **Alert Accent (Warning Amber):** `#FFB300` (Used for rest timers, heavy loading states, and fatigue thresholds).
* **Typography:** * Headers & Numbers: `JetBrains Mono` or `Share Tech Mono` (via Google Fonts) for that tactical read-out look.
    * Body Text: `Inter` or `SF Pro Display` for high readability under low-light gym conditions.
* **Effects:** Subtle text-shadow glows (`text-shadow: 0 0 8px rgba(0, 240, 255, 0.6)`) and ultra-thin borders (`1px solid rgba(0, 240, 255, 0.15)`).

### 3.2 Layout & Hierarchy
* **Mobile-First Constraint:** Fixed width viewport behavior on desktop to mimic an advanced mobile device. 
* **Bottom Navigation Dock:** High-tech dashboard switcher (Dashboard, Workout Shell, Routine Builder, Logistics Terminal).
* **Top Telemetry Bar:** Status updates displaying current training day type, systematic fatigue levels, and an active operation ticker.

---

## 4. FUNCTIONAL MODULES

### MODULE 1: SECURE ENTRY & ACCESS SHELL (AUTHENTICATION)
* **Requirement 1.1:** Secure single-user lock screen mimicking an encrypted terminal biometric bypass.
* **Requirement 1.2:** Persistent session handling (JWT via Supabase stored securely) to prevent the user from being logged out mid-workout.

### MODULE 2: TACTICAL WORKOUT BUILDER (CONFIGURATOR)
* **Requirement 2.1:** Micro-architecture configuration engine. Must support the following operational splits:
    * *Push / Pull / Legs (PPL)*
    * *Upper / Lower (U/L)*
    * *Full Body*
    * *Hybrid Engine:* PPL + Upper/Lower (5-Day Custom Configuration).
* **Requirement 2.2:** Strict Temporal Boundary: Hardcoded for a **5-day consecutive operational week (Monday through Friday)**, automatically resetting or transitioning phases during the weekend.
* **Requirement 2.3:** Drag-and-drop or ultra-fast click reordering of exercise execution paths within a selected split day.

### MODULE 3: ZERO-FRICTION WORKOUT CONSOLE (EXECUTION MODE)
* **Requirement 3.1 (Smart Defaults):** Opening an exercise automatically pulls historical data from the exact previous iteration of that specific workout split. Fields for `Weight (kg)`, `Reps`, and `Sets` are pre-filled as placeholder data.
* **Requirement 3.2 (The Single-Tap Confirmation):** If the user matches the historical parameters, a single tap on the row marks the set as verified (glowing green state change).
* **Requirement 3.3 (Plate Calculator Widget):** Next to the weight input field, an icon opens an inline modal showing an exact visual breakdown of a standard Olympic barbell setup based on target weight (e.g., Target: 90kg -> Display: 20kg Bar + 2x 20kg plates + 2x 15kg plates).
* **Requirement 3.4 (PR Target Engine):** If historical data indicates a threshold is about to be crossed (higher weight or higher rep volume), the row flashes in an Amber "Overload Detected" state. Succeeding triggers a localized system alert (Visual confirmation overlay).
* **Requirement 3.5 (Tactical Rest Interface):** Confirming a set initiates a counting down progress bar (radial or linear bar across the top of the viewport) configured to the exercise's specific rest interval. A gentle haptic vibration occurs on zero.

### MODULE 4: THE OPERATIONAL ANALYTICS TERMINAL (METRICS)
* **Requirement 4.1 (Anatomical Heatmap):** A 2D vector graphic representation of the human muscular system (Front/Back) displayed on the main dashboard. The opacity/saturation of color overlays (Telemetry Cyan/Green) scales dynamically based on the total sets performed per muscle group within the current rolling 7-day window.
* **Requirement 4.2 (Total Tonnage Over Time):** A multi-line graph calculating total weight shifted per session ($Tonnage = \\sum (Sets \\times Reps \\times Weight)$) allowing visual progress monitoring even when individual set weights remain plateaued.
* **Requirement 4.3 (Progress Tracking Matrices):** Individual historical line graphs for every single exercise accessible via a single tap from the exercise encyclopedia or execution screen.
* **Requirement 4.4 (Fatigue Degradation Index):** A logical metric indicating estimated systemic fatigue based on sequential training volume throughout the Mon-Fri operational block, showing peak capacity on Monday/Tuesday and degradation markers by Friday.

### MODULE 5: SUPPLEMENT LOGISTICS MATRIX (STATIC DISPLAY)
* **Requirement 5.1 (Timeline Chronology):** A visual, clean timeline widget on the core terminal dashboard displaying the user's daily supplement distribution, organized by hour blocks rather than interactive check-boxes.
    * *Example Baseline Array:*
        * `08:00` - Micronized Creatina Monohidratada (5g)
        * `18:30` - Olympus Whey 3W [Flavor Profile: Morango com Ninho] (30g) + Water Matrix
* **Requirement 5.2 (Supply Lifespan Engine):** A simple inventory metric where the user inputs the opening date of a supplement canister along with the total weight (e.g., 900g Whey / 250g Creatine). Based on daily baseline consumption models, a countdown widget displays "Days of Fuel Remaining" with alert triggers when supply reaches $\\le 5$ days.

### MODULE 6: COMPREHENSIVE EXERCISE ARCHIVE
* **Requirement 6.1:** A structured relational catalog containing standard free-weight, cable, and machine exercises categorized cleanly by primary and secondary muscle groups.
* **Requirement 6.2:** High-fidelity, low-bandwidth visual loop system (optimized technical SVG diagrams, line drawings, or high-contrast modern icons) representing the exact starting and terminal mechanics of each movement.

---

## 5. DATABASE SCHEMA & DATA MODELS (POSTGRESQL / SUPABASE)

### 5.1 `profiles`
```

Saída de código

````
PRD File generated successfully.

```sql
create table profiles (
  id uuid references auth.users on delete cascade primary key,
  updated_at timestamp with time zone,
  username text unique,
  full_name text,
  operational_split text check (operational_split in ('PPL', 'UL', 'FULLBODY', 'HYBRID')) default 'HYBRID'
);
````

### 5.2 `exercises`

SQL

```
create table exercises (
  id uuid default gen_random_uuid() primary key,
  name text not null,
  primary_muscle text not null,
  secondary_muscles text[],
  mechanics text check (mechanics in ('compound', 'isolation')),
  equipment text not null,
  icon_identifier text
);
```

### 5.3 `workout_plans`

SQL

```
create table workout_plans (
  id uuid default gen_random_uuid() primary key,
  user_id uuid references profiles(id) on delete cascade,
  name text not null, -- e.g., 'Day A - Push 1'
  day_of_week int check (day_of_week between 1 and 5), -- 1=Mon, 5=Fri
  created_at timestamp with time zone default now()
);
```

### 5.4 `plan_exercises`

SQL

```
create table plan_exercises (
  id uuid default gen_random_uuid() primary key,
  plan_id uuid references workout_plans(id) on delete cascade,
  exercise_id uuid references exercises(id),
  order_index int not null,
  target_sets int default 4,
  target_rest_seconds int default 90
);
```

### 5.5 `workout_logs`

SQL

```
create table workout_logs (
  id uuid default gen_random_uuid() primary key,
  user_id uuid references profiles(id) on delete cascade,
  exercise_id uuid references exercises(id),
  logged_at timestamp with time zone default now(),
  set_number int not null,
  weight numeric not null,
  reps int not null,
  is_pr boolean default false,
  completed_successfully boolean default true
);
```

### 5.6 `supplement_inventory`

SQL

```
create table supplement_inventory (
  id uuid default gen_random_uuid() primary key,
  user_id uuid references profiles(id) on delete cascade,
  name text not null,
  brand text,
  flavor text,
  container_size_grams numeric not null,
  daily_dosage_grams numeric not null,
  opened_at date not null,
  is_active boolean default true
);
```

## 6. VIBE CODING PROMPT BLUEPRINTS (DEVELOPMENT STRATEGY)

To ensure maximum generation accuracy when piping sections of this PRD into AI IDEs (Cursor, Lovable, Trae), follow this sequential prompt sequence:

### PHASE 1: UI Theme & Static Layout Prompt

> `"Build a mobile-first web app dashboard using Vite, React, TypeScript, and Tailwind CSS. The design system is a Jarvis Command Center/Tactical Cyberpunk terminal. Use absolute deep blacks (#000000), charcoal surfaces (#0B0F19), and glowing neon telemetry cyan (#00F0FF) text, icons, and borders. Generate a mock landing dashboard that displays a static top telemetry bar, a bottom dock navigator, and a middle canvas containing a placeholder data visualization grid using Recharts. Ensure JetBrains Mono font configuration is applied to all numerical data outputs for a precision scientific readout."`

### PHASE 2: Database Layer Instantiation Prompt

> `"Using the standard Supabase JavaScript SDK client and TypeScript, write the state management engine using Zustand to map to the following PostgreSQL schemas: [Insert Section 5 Database Schema tables here]. The store must handle fetching the current user profile, managing an active workout state array, caching historical defaults, and syncing confirmed logs instantly to the remote database."`

### PHASE 3: Friction-Free Logging Logic Prompt

> `"Build the core Live Workout Session component. It must map over an array of exercises scheduled for the current training split. For every exercise, fetch the immediate past log parameters from the database and populate the input fields as low-contrast placeholders. If the user taps a row without typing anything, trigger a state update that sets the row to 'completed_successfully' using the placeholder values, causing the row border to transition into a neon green glowing state. Append a 90-second countdown alert system to the completion trigger."`

## 7. NON-FUNCTIONAL REQUIREMENTS & PERFORMANCE ENVELOPE

- **PWA Packaging:** Must include a standard Web App Manifest and basic Service Worker caching strategy to allow adding "Project: Marcola Prime" directly to the mobile device home screen as a standalone application shell.
    
- **Latency Profile:** Interface component transitions must stay under 50ms. Local state mutations via Zustand must be instantaneous, with Supabase database sync handling operations in an asynchronous background thread.
    
- **Local Caching Fail-Safe:** If internet connectivity drops inside concrete-heavy gym structures, the active workout state must serialize instantly to `localStorage` or `IndexedDB`, auto-synchronizing back to Supabase upon link restoration.
    
    """
    

```

A LINGUAGEM PADRÃO SERÁ PT-BR, PORÉM TERMOS EM INGLES SOBRE TREINOS E EXERCICIOS SERÃO ACEITOS!