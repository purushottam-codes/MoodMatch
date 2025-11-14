# MoodMatch – 15 Week Roadmap 🎭

A creative side project to build a **mood-based recommender system**.  
Each week has a clear **goal, tasks, and final output** so progress is visible and portfolio-ready.

---

## Month 1: Python Foundations
### Week 1
- **Goal:** Build console app for mood-based suggestions
- **Tasks:** Input mood → print 3 hardcoded recommendations
- **Outcome:** First working prototype that responds to user mood
- **Files:** `src/moodmatch.py`
- **Final Output:** Console app with hardcoded mood → suggestions mapping

### Week 2
- **Goal:** Add file I/O to save user mood + suggestions
- **Tasks:** Write to `data/user_history.txt`
- **Outcome:** Persistent storage of user history
- **Files:** `src/moodmatch.py`, `data/user_history.txt`
- **Final Output:** Console app that logs moods + suggestions to file

### Week 3
- **Goal:** Add regex search for moods or genres
- **Tasks:** Extract keywords from user input
- **Outcome:** Smarter input handling with keyword detection
- **Files:** `src/moodmatch.py`
- **Final Output:** Console app that parses free-text mood input

### Week 4
- **Goal:** Document logic + mood categories
- **Tasks:** Create Markdown doc with examples
- **Outcome:** Clear taxonomy of moods and categories
- **Files:** `docs/mood_logic.md`
- **Final Output:** Documentation of mood categories + examples

---

## Month 2: Flask + SQL
### Week 5
- **Goal:** Build Flask form for mood + medium input
- **Tasks:** Create `/recommend` route
- **Outcome:** Web interface for input
- **Files:** `src/flask_app/app.py`, `templates/form.html`
- **Final Output:** Flask app with working form

### Week 6
- **Goal:** Validate input + handle errors
- **Tasks:** Use Flask-WTF for form validation
- **Outcome:** Robust form UX
- **Files:** `src/flask_app/forms.py`
- **Final Output:** Flask app with validated form

### Week 7
- **Goal:** Store content in SQLAlchemy DB
- **Tasks:** Create models for shows/songs
- **Outcome:** Structured DB for recommendations
- **Files:** `src/flask_app/models.py`, `data/content.db`
- **Final Output:** Database-backed recommender system

### Week 8
- **Goal:** Track user sessions + history
- **Tasks:** Use Flask sessions to store recent moods
- **Outcome:** Personalized recommendations
- **Files:** `src/flask_app/app.py`
- **Final Output:** Flask app with session tracking

---

## Month 3: APIs + Automation
### Week 9
- **Goal:** Script to add new content entries
- **Tasks:** CLI tool to append to DB
- **Outcome:** Easy content management
- **Files:** `src/tools/add_entry.py`
- **Final Output:** CLI tool for DB updates

### Week 10
- **Goal:** Fetch ratings from IMDb/Spotify
- **Tasks:** Use `requests` to call APIs
- **Outcome:** External data integration
- **Files:** `src/api_fetcher.py`
- **Final Output:** API-powered recommender

### Week 11
- **Goal:** Deploy Flask app with Ansible
- **Tasks:** Write playbook for local server
- **Outcome:** Automated deployment
- **Files:** `deploy/ansible/flask.yml`
- **Final Output:** Ansible-deployed app

### Week 12
- **Goal:** Add GitHub Actions for auto-testing
- **Tasks:** Test recommender logic
- **Outcome:** CI/CD pipeline for quality assurance
- **Files:** `.github/workflows/test.yml`
- **Final Output:** Automated test pipeline

---

## Month 4: FastAPI + Cloud
### Week 13
- **Goal:** Build FastAPI `/recommend` endpoint
- **Tasks:** Use query params for mood + medium
- **Outcome:** Modern API interface
- **Files:** `src/fastapi_app/main.py`
- **Final Output:** FastAPI recommender endpoint

### Week 14
- **Goal:** Add JWT auth for user sessions
- **Tasks:** Secure endpoints
- **Outcome:** Secure user handling
- **Files:** `src/fastapi_app/auth.py`
- **Final Output:** Authenticated FastAPI app

### Week 15
- **Goal:** Portfolio polish + showcase
- **Tasks:** Document architecture, polish README, record demo
- **Outcome:** Portfolio-ready project
- **Files:** `README.md`, `docs/architecture.png`, `docs/demo.mp4`
- **Final Output:** Complete MoodMatch repo with demo + documentation
