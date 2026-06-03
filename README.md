# Red Team Python Journey

Documenting my path from Python fundamentals to penetration testing.

**Goal:** Red team penetration tester, entering through a SOC Analyst role.  
**Language:** Python — scripting, automation, and security tooling.  
**Background:** CS degree, alarm monitoring (SOC-adjacent), full-stack JS experience.

See [ROADMAP.md](ROADMAP.md) for the full plan.

---

## Step 1 — Python Fundamentals ✅

**Completed:** May 2026

Coming in with JavaScript experience and a CS degree, this step was about getting fluent in Python's idioms before moving into security-specific work.

### What I built

**Python Exercises** — four standalone scripts, each tested with pytest:

| File | Concepts covered |
|---|---|
| `grade_book.py` | Type hints, dataclasses, list comprehensions, JSON I/O |
| `student_report.py` | File I/O, context managers, data formatting |
| `pipeline.py` | Generators, chaining data transformations |
| `decorators.py` | Writing and applying decorators, `functools.wraps` |

**FastAPI CRUD App** — a fully functional REST API:

- `POST /items`, `GET /items`, `GET /items/{id}`, `PUT /items/{id}`, `DELETE /items/{id}`
- SQLAlchemy ORM with SQLite, Pydantic request/response models
- Dependency injection for DB sessions
- pytest integration tests with a real in-memory test database (not mocked)
- Async route handlers

### Key skills locked in

- Type hints, dataclasses, properties
- List comprehensions, generators
- File I/O, JSON, context managers
- Decorators
- pytest — unit and integration testing
- FastAPI, Pydantic, SQLAlchemy
- REST API design, dependency injection, async basics

---

## Step 2 — Networking with Python 🔄

*In progress*

- TCP/IP at the code level
- Raw sockets — client/server programs
- HTTP from scratch (before using libraries)
- Port scanning
- DNS lookups
- Libraries: `socket`, `requests`, `scapy`

---

## Steps 3–5

| Step | Topic | Status |
|---|---|---|
| 3 | CTF Challenges — TryHackMe → HackTheBox | Not started |
| 4 | CompTIA Security+ | Not started |
| 5 | SOC Analyst role → junior pen tester | Not started |

---

## Security Tools (building along the way)

- [ ] Port scanner
- [ ] Network packet sniffer
- [ ] Password strength checker / cracker
- [ ] Directory/subdomain enumerator
- [ ] Basic keylogger (lab environment only)
- [ ] CLI tool that automates a CTF technique
