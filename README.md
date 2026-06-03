# Red Team Python Journey

Documenting my path from Python fundamentals to penetration testing.

**Goal:** Red team penetration tester, entering through a SOC Analyst role.  
**Language:** Python — scripting, automation, and security tooling.  
**Background:** CS degree, alarm monitoring (SOC-adjacent), full-stack JS experience.

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

- [ ] How TCP/IP works at the code level
- [ ] Sockets — raw connections, client/server programs
- [ ] HTTP from scratch (before using libraries)
- [ ] Port scanning
- [ ] Reading and parsing network data
- [ ] DNS lookups
- [ ] Libraries: `socket`, `requests`, `scapy`

---

## Step 3 — CTF Challenges

- [ ] TryHackMe — complete beginner path
- [ ] Write Python scripts to automate challenge solutions
- [ ] HackTheBox — once comfortable with TryHackMe
- [ ] Build a portfolio of tools written during CTFs

---

## Step 4 — CompTIA Security+

- [ ] Study networking concepts (overlaps with Step 2)
- [ ] Study cryptography basics
- [ ] Study threat intelligence and attack types
- [ ] Study incident response procedures
- [ ] Pass the exam

---

## Step 5 — First Role

- [ ] SOC Analyst (entry point — alarm monitoring background is directly relevant)
- [ ] Build 2-3 portfolio projects (security tools written in Python)
- [ ] OSCP certification (gold standard for pen testers)
- [ ] Transition to junior penetration tester

---

## Security Tools (building along the way)

- [ ] Port scanner
- [ ] Network packet sniffer
- [ ] Password strength checker / cracker
- [ ] Directory/subdomain enumerator
- [ ] Basic keylogger (lab environment only)
- [ ] CLI tool that automates a CTF technique

---

## Resources

- [TryHackMe](https://tryhackme.com)
- [HackTheBox](https://hackthebox.com)
- Security+: Professor Messer (free), CompTIA CertMaster
- [OSCP](https://www.offensive-security.com/pwk-oscp/)
