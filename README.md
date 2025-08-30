# Top Python Projects on GitHub

A script that pulls data on the most-starred Python repositories from the GitHub API and generates an interactive SVG chart with the results.

This was originally a project from the book "Python Crash Course," which I've updated to work with the current GitHub API and added a proper README for.



---

## Setup

To get this running locally:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/turganaliev/API.git
    cd API
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    # On Windows, use: .\venv\Scripts\activate
    pip install -r requirements.txt
    ```

---

## Usage

Once the environment is set up, just run the main script:
```bash
python python_repos.py
```
This will create a `python_repos.svg` file in the project's root directory. You can open this file in any web browser to see the chart. The bars in the chart are clickable and link directly to the corresponding GitHub repositories.
