# solar-challenge-week1
First Week Challenge of KAIM

## Setup Instructions

1. **Clone the repository from Github**
```bash
git clone https://github.com/shalomkerry/solar-challenge-week1
cd solar-challenge-week1
```

2. **Create and activate virtual environment**
```bash
python3 -m venv venv
source venv/bin/activate
```
3. **Install dependencies**

```bash
pip install -r requirements.txt
```
### Project Structure
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── ci.yml
├── notebooks/
│   └── README.md
├── scripts/
│   └── README.md
├── src/
├── tests/
├── .gitignore
├── README.md
├── requirements.txt

### CI
This project uses Github Actions to verify setup with:
- Python installation check
- Requirements installation
CI runs on every push or pull request to the main branch main branch

---

### 4. Commit the README

```bash
git add README.md
git commit -m "docs: add setup instructions to README"
