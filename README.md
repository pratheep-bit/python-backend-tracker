# Python Backend Engineering Roadmap & LeetCode 150 DSA Pattern Tracker

A production-grade, interactive learning and progress tracking platform for Python backend engineers and algorithmic problem solvers. Built with clean SaaS aesthetics, instant local persistence, Supabase cloud synchronization, and full mobile responsiveness.

🔗 **Live Production**: [https://pyback.vercel.app](https://pyback.vercel.app)

---

## ✨ Features

### 1. 🐍 Python Backend Engineering Roadmap (6 Phases • 24 Units)
- **Phase 1**: Python Core, OOP, Advanced Generators, Context Managers & Clean Design
- **Phase 2**: Networking, ASGI/WSGI, FastAPI & High-Performance Async Architecture
- **Phase 3**: PostgreSQL, SQL Optimization, Indexes & Redis Caching Patterns
- **Phase 4**: Celery, Redis Task Queues, Message Brokers & Event-Driven Systems
- **Phase 5**: Docker, Multi-stage Builds, Kubernetes & Production Observability
- **Phase 6**: High-Level System Design, Microservices, Sharding & Distributed Locks

### 2. ⚡ LeetCode 150 Patterns & Problem Tracker (192 Problems • 11 Patterns)
- Curated across 11 core algorithmic patterns:
  1. Two Pointers (Patterns 1, 4, 6, 7)
  2. Sliding Window (Pattern 9)
  3. Trees (Patterns 12, 13, 14, 15)
  4. Graphs (Patterns 19, 20)
  5. Dynamic Programming (Patterns 27, 28, 29, 34)
  6. Binary Search (Patterns 55, 56, 58)
  7. Stack & Monotonic Stack (Patterns 60, 61, 64)
  8. Linked List (Patterns 71, 72, 75)
  9. Array & String Fundamentals (Patterns 76–90)
  10. Heap / Priority Queue (Pattern 38)
  11. Backtracking (Pattern 42)
- Official LeetCode numbers, direct question links, revision tracking checkboxes, and batch revision reset.

### 3. 📝 Big-Screen Markdown Notes Modal
- Full markdown editor with heading tools, Python syntax blocks, and study checklists.
- 3 view modes: **Write**, **Split Screen**, and **Live Preview**.
- Big-screen fullscreen mode for uninterrupted note-taking.
- Auto-saves continuously to `localStorage` and syncs to Supabase cloud.

### 4. ☁️ Supabase Cloud Sync & Authentication
- Secure authentication with Supabase Auth (Sign In / Sign Up / Profile management).
- Real-time cloud sync of curriculum progress, LeetCode statuses, revision checkboxes, and study notes.
- Automatic offline-first fallback with `localStorage`.

### 5. 📱 Responsive SaaS Design
- Optimized for desktop, tablet, and mobile viewports.
- Adaptive controls: action buttons collapse to clean, uniform 28px square touch targets on small screens.
- Search filters and status counters (Completed, Work more, Not completed / Mastered, Learning, Not learned).

---

## 🛠️ Tech Stack

- **Frontend**: Vanilla HTML5, Modern CSS (TailwindCSS CDN), Vanilla JavaScript (ES6+)
- **Icons**: Lucide Icons
- **Backend / BaaS**: Supabase Auth & Realtime Database
- **Hosting & Edge Deployment**: Vercel

---

## 🚀 Running Locally

No dependencies required! Run using Python's built-in HTTP server:

```bash
# Clone the repository
git clone https://github.com/pratheep-bit/python-backend-tracker.git
cd python-backend-tracker

# Start local server
python3 -m http.server 8089 --bind 127.0.0.1
```

Open [http://127.0.0.1:8089](http://127.0.0.1:8089) in your browser.

---

## 📄 License

MIT License © 2026 Pratheep S
