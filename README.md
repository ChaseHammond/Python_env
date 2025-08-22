# Python Project Template

This is a **GitHub Template Repository** for starting new Python projects quickly.  
Click **"Use this template"** to create your own repo with this setup.

---

## Features

- Environment management with [uv](https://docs.astral.sh/uv/)
- Project automation with [Taskfile](https://taskfile.dev/)
- Testing with [pytest](https://docs.pytest.org/)
- Pre-commit hooks (ruff, black, trailing-whitespace, etc.)
- Automatic folder/file creation (README, `.env`, scratch dir, tests)

---

## Getting Started

1. **Create your new repo from this template**
   - On GitHub, click **Use this template**
   - Choose a name for your new project (e.g., `bell-gargoyle`)

2. **Clone your new repo locally**
   ```bash
   git clone https://github.com/<your-username>/<your-new-project>
   cd <your-new-project>
   ```
3. **Run setup Tasks**
   ```bash
   task setup     # create files (.env, README.md, scratch/)
   task init      # name your project, create venv
   task install   # install dependencies + pre-commit hooks
   ```
4. **Activate Your Environment**
   ```bash
   source activate.sh
   ```
