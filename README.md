# 🌿 Fructus Iter

> A mobile-first digital marketplace connecting local producers, farmers, and artisans from La Araucanía, Chile, with buyers at weekly fairs and local markets.

**Course:** Diseño de Experiencia de Usuario e Interacción Humano Computador — UXD-HCI 2026
**Department:** Departamento de Cs. Computación e Informática
**University:** Universidad de La Frontera (UFRO), Temuco, Chile

---

## Index

1. [**Introduction**](#1-introduction)
   - [1.1. The Problem](#11-the-problem)
   - [1.2. Our Solution](#12-our-solution)
2. [**Team & Roles**](#2-team--roles)
3. [**Strategy**](#3-strategy)
   - [3.1. Value Proposition Canvas](#31-value-proposition-canvas)
   - [3.2. UX Personas](#32-ux-personas)
   - [3.3. Benchmark Analysis](#33-benchmark-analysis)
4. [**Structure**](#4-structure)
   - [4.1. Navigation Flow](#41-navigation-flow)
5. [**Skeleton**](#5-skeleton)
   - [5.1. Low-Fi Wireframes](#51-low-fi-wireframes)
6. [**Surface**](#6-surface)
   - [6.1. Interface Evolution](#61-interface-evolution)
   - [6.2. Heuristic Evaluation](#62-heuristic-evaluation)
   - [6.3. Accessibility](#63-accessibility)
   - [6.4. High Definition Interfaces](#64-high-definition-interfaces)
7. [**Annex**](#7-annex)

---

## 1. Introduction

### 1.1. The Problem

Local producers from La Araucanía — horticulturists, Mapuche artisans, and beekeepers — lack digital channels to publish their weekly offerings, coordinate pre-orders, and build a loyal customer base. Existing e-commerce platforms do not adapt to the seasonal rhythm or local market logic, where **trust and proximity** are core values for buyers.

> *"As a beekeeper from Cunco who sells at the Temuco fair on Saturdays, I need to publish my weekly honey offer with my contact information, receive pre-orders through the app, and have my regular customers find me easily — so I can sell all my stock without bringing product back home."*

**Key pain points identified:**

- Producers have no digital channel to announce their weekly stock before fair day
- Buyers don't know what's available until they physically arrive at the market
- No mechanism for pre-orders or reservations between producers and regular customers
- Existing platforms don't reflect the seasonal, trust-based logic of local fairs

---

### 1.2. Our Solution

**Fructus Iter** is a mobile-first marketplace that bridges the gap between local fair producers and buyers. It enables producers to publish their weekly stock, receive pre-orders, and build a loyal digital customer base — while giving buyers transparent access to fresh, locally sourced products before fair day.

#### 🌱 Producer Features
- Publish weekly stock with photos, prices, and availability before fair day
- Receive and manage pre-orders from regular customers
- Build a loyal digital customer base with direct contact tools

#### 🛒 Buyer Features
- Browse local producers and their weekly offerings from the app
- Pre-order products and reserve stock before arriving at the fair
- Campus pick-up flow for UFRO staff and students
- Transparent pricing with no hidden fees or intermediaries

#### 🗺️ UX Elements Mapping (Jesse James Garrett)

| UX Plane | Deliverable |
|---|---|
| **Strategy** | Problem statement, Value Proposition Canvas, UX Personas |
| **Scope** | Benchmark analysis, Opportunity Matrix (ERIC) |
| **Structure** | Navigation flow diagram |
| **Skeleton** | Low-Fi wireframes |
| **Surface** | HD interfaces, Interface evolution, Heuristic evaluation |

---

## 2. Team & Roles

| Name | Role | Responsibilities |
|---|---|---|
| **Felipe Medina** | Project Lead & Designer | Coordination, presentation leadership, formal deliverable models and UI design |
| **Stephanie Mercado** | Analyst & Designer | User interviews, annotations, needs conceptualization, UI design |

---

## 3. Strategy

### 3.1. Value Proposition Canvas

The Value Proposition Canvas maps the alignment between producer and buyer pain points and the platform's gain creators and pain relievers.

**Key customer jobs identified:**
- Sell all weekly stock without returning unsold produce
- Publish product offerings digitally before fair day
- Access fresh, locally sourced produce without visiting the fair in person
- Plan weekly purchases in advance with transparent pricing

**Key pains addressed:**
- Unsold produce at the end of fair days
- No digital channel for producers to reach customers
- Buyers unaware of available stock until physical arrival
- Supermarket alternatives are more expensive and less fresh

📄 [Value Proposition Canvas — Fructus Iter (English)](Tareas/Value%20Proposition%20Canvas/Value%20Proposition%20Canvas%20(English%20Version).pdf)

📄 [Value Proposition Canvas — Fructus Iter (Spanish)](Tareas/Value%20Proposition%20Canvas/Value%20Proposition%20Canvas.pdf)

---

### 3.2. UX Personas

Three personas were identified based on field context and the user story provided for the project scenario. Each persona represents a distinct user type with unique needs, frustrations, and technology usage patterns.

#### 👤 Juan Catrileo — Fair Vendor (Producer)
> *"I leave at 4 in the morning and sometimes come back with half my stock. I don't have time to let all my customers know what I brought."*

- 52 years old · Cunco, La Araucanía · Primary education
- **Key need:** Publish weekly stock and receive pre-orders before Saturday
- **Main frustration:** Produce that rots unsold, no digital channel of his own

#### 👤 Marcela Vidal — UFRO Administrative Staff (Buyer)
> *"I want to eat healthy during the week, but I don't have time to go to the fair on Saturday. I need to know what's available and have someone reserve it for me."*

- 41 years old · Temuco · Technical university degree
- **Key need:** Pre-order fresh produce without going to the fair
- **Main frustration:** The fair closes before she finishes work, supermarket fruit is less fresh

#### 👤 Diego Painevil — University Student (Buyer)
> *"I buy at the supermarket because I don't know what's at the fair or how much it costs. If I could see the products with prices before going, I'd go often."*

- 21 years old · UFRO student · Fixed monthly budget
- **Key need:** Know what's available and compare prices before leaving campus
- **Main frustration:** Doesn't know what's being sold, arrives late and stock is gone

📄 [UX Personas — Fructus Iter (English)](Tareas/UX_personas/JuanCatrileo(EnglishVersion).png)

![Juan Catrileo](Tareas/UX_personas/JuanCatrileo(EnglishVersion).png)
![Marcela Vidal](Tareas/UX_personas/MarcelaVidal(EnglishVersion).png)
![Diego Painevil](Tareas/UX_personas/DiegoPainevil(EnglishVersion).png)

---

### 3.3. Benchmark Analysis

Competitive analysis conducted following the two-phase methodology: **Exploratory Phase** (mapping the ecosystem) and **Competitive Reference Phase** (in-depth analysis for design decisions).

#### Tool Selection & Justification

| # | Tool | Category | Justification |
|---|---|---|---|
| 1 | **Lomi** | Direct Competitor | Chilean marketplace connecting local producers with buyers directly. Same problem, same cultural and market context. |
| 2 | **GoodMeal** | Analogous Competitor | Chilean food rescue app with 1M+ users. Handles fresh food surplus but uses mystery bags — fundamentally different UX logic from Fructus Iter. |
| 3 | **Cheaf** | Analogous Competitor | Chilean surplus food app with 1.5M users. Works with fruits, vegetables, and dairy via a pick-up model. Similar domain, different problem framing. |
| 4 | **Uber Eats** | Design Reference | Sets the UX standard for food delivery catalogs, ordering flows, and order tracking at scale. Used as visual and interaction reference. |

#### Opportunity Matrix (ERIC Framework)

| Quadrant | Key Insights |
|---|---|
| ↑ **Increase** | Grower brand identity · P2P trust & human warmth · Real-time stock accuracy · Visual-first interface |
| + **Include** | Live market stand toggle · Campus pick-up flow · No-middleman transactions · Hyper-local price mapping |
| ↓ **Reduce** | Cognitive load for older users · Data & text input overhead · Financial friction & fees · Constant screen-time dependency |
| × **Remove** | Anonymity in supply chain · Restaurant-style dashboards · Blind buying / mystery bags · Heavy GPS tracking overhead |

**Key differentiator:** Fructus Iter is the only solution in this domain that combines visible producer identity, no-middleman transactions, and a campus-oriented pick-up flow tailored for the UFRO community.

![Benchmark Map](Tareas/Benchmark/Benchmark_Map.png)

---

## 4. Structure

### 4.1. Navigation Flow

The navigation diagram covers all app functionalities across both user roles (producer and buyer), from onboarding through to order tracking and profile management.

```
Landing Page
├── Sign In
└── Register
    └── Home
        ├── Profile
        │   ├── Edit Profile
        │   ├── Settings
        │   └── Sign Out
        ├── Favorites
        │   ├── Stores
        │   └── Products
        ├── Store
        │   ├── Products
        │   └── Purchase → Cart → Payment → Confirmation
        └── Search
            ├── Vegetables
            ├── Fruits
            └── Crafts
```

![Navigation Diagram](Tareas/Diagrama_navegacion/Diagrama_navegacion.png)

---

## 5. Skeleton

### 5.1. Low-Fi Wireframes

Initial paper wireframes covering all core user flows, digitized and organized by functional group. The wireframes represent the first iteration of the interface before any visual design decisions were made.

**Flows covered:**

| Flow | Screens |
|---|---|
| Onboarding | Sign In · Register |
| Home & Browse | Home · Search · Categories |
| Catalog & Product | Product list · Product detail |
| Cart & Checkout | Cart · Payment · Order confirmation |
| Pickup & Tracking | Order tracking · Delivery status |
| Favorites | Add to favorites · My favorites |
| Profile | My profile · Edit profile · Settings |

📄 [Low-Fi Wireframes — Fructus Iter (PDF)](Avance_1/Wireframes_Avance1/Wireframe_avance1.pdf)

---

## 6. Surface

### 6.1. Interface Evolution

The design evolved from paper wireframes to high-fidelity interfaces through multiple iterations guided by usability principles and feedback from Avance 1.

Key design decisions made during the evolution process:

- **Green color system** (`#2E7D32`, `#4CAF50`, `#F1F8F0`) chosen to reinforce the organic, local, and trustworthy nature of the platform
- **Visual-first product cards** with large images to reduce cognitive load for producers less familiar with digital interfaces
- **Bottom navigation bar** with 5 fixed sections (Home, Search, Orders, Favorites, Profile) following established mobile marketplace conventions identified in the benchmark
- **Producer identity visible on every listing** — name, location, and story — directly addressing the key differentiator identified in the ERIC matrix

*Interface evolution document with annotated before/after comparisons — coming in Avance 2.*

---

### 6.2. Heuristic Evaluation

A heuristic evaluation was conducted on the high-fidelity Fructus Iter prototype using Nielsen's 10 usability heuristics as the evaluation framework.

📄 [Heuristic Evaluation — Fructus Iter (PDF)](Avance_2/Heuristic%20Evaluation/Heuristic_Evaluation.pdf)

---

### 6.3. Accessibility

Accessibility analysis conducted as part of the Avance 2 requirements, reviewing the platform against established accessibility standards.

📄 [Accessibility Analysis — Fructus Iter (PDF)](Avance_2/Accessibility/Accessibility%20in%20Discord.pdf)

---

### 6.4. High Definition Interfaces

High-fidelity screens for all functionalities designed in Figma, following the app's green color system and accessible UI patterns informed by the benchmark and heuristic evaluation.

**Key screens:**
- Onboarding (Sign Up / Sign In)
- Home with category grid and featured products
- Product catalog and detail view
- Cart, checkout, and order confirmation
- Order tracking and campus pick-up flow
- Favorites (stores and products)
- Profile and settings

🔗 [Figma Prototype — Fructus Iter](https://www.figma.com/design/aAvGQ0lL6xu3XAz2v8vcvm/Fructus-Iter?node-id=329-3128&p=f&t=W8TL7ZePVDXgkSBs-0)

---

## 7. Annex

Central repository of all project deliverables, organized by UX design phase.

### Strategy Documents

- 📄 [Value Proposition Canvas (English)](Tareas/Value%20Proposition%20Canvas/Value%20Proposition%20Canvas%20(English%20Version).pdf)
  > Alignment between producer and buyer needs and the platform's proposed value.

- 📄 [Value Proposition Canvas (Spanish)](Tareas/Value%20Proposition%20Canvas/Value%20Proposition%20Canvas.pdf)

- 🖼️ [UX Persona — Juan Catrileo (English)](Tareas/UX_personas/JuanCatrileo(EnglishVersion).png)

- 🖼️ [UX Persona — Marcela Vidal (English)](Tareas/UX_personas/MarcelaVidal(EnglishVersion).png)

- 🖼️ [UX Persona — Diego Painevil (English)](Tareas/UX_personas/DiegoPainevil(EnglishVersion).png)

- 🖼️ [Benchmark Opportunity Matrix](Tareas/Benchmark/Benchmark_Map.png)
  > ERIC framework opportunity matrix comparing Lomi, GoodMeal, Cheaf, and Uber Eats.

### Structure Documents

- 🖼️ [Navigation Flow Diagram](Tareas/Diagrama_navegacion/Diagrama_navegacion.png)
  > Complete navigation architecture covering all app functionalities.

### Skeleton Documents

- 📄 [Low-Fi Wireframes — Avance 1](Avance_1/Wireframes_Avance1/Wireframe_avance1.pdf)
  > Full set of paper wireframes digitized and organized by user flow.

### Surface Documents

- 📄 [Heuristic Evaluation](Avance_2/Heuristic%20Evaluation/Heuristic_Evaluation.pdf)
  > Usability evaluation of the HD prototype using Nielsen's 10 heuristics.

- 📄 [Accessibility Analysis](Avance_2/Accessibility/Accessibility%20in%20Discord.pdf)
  > Accessibility review of the platform based on course workshop guidelines.

- 🔗 [Figma Prototype (HD)](https://www.figma.com/design/aAvGQ0lL6xu3XAz2v8vcvm/Fructus-Iter?node-id=329-3128&p=f&t=W8TL7ZePVDXgkSBs-0)

---

> **UXD-HCI 2026 · Universidad de La Frontera · Temuco, Chile**
> *All repository documentation is written in English as per course requirements.*
> *Application interfaces are in Spanish as per course requirements.*
