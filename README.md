# QA Demo Project

This is a demonstration project for **QA Manual and Automation (Web + API)** testing.

## Tech stack
| Area | Tools |
|------|-------|
| Language | Python 3 |
| Test‑runner | Pytest |
| UI | Selenium WebDriver |
| API | requests |
| Reporting | Allure |
| CI | GitHub Actions |

## Local run
```bash
git clone https://github.com/<your-login>/qa_demo_project.git
cd qa_demo_project
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
pytest -v --alluredir=allure-results
```
