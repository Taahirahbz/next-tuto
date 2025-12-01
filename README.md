STEP 1 — Create .devcontainer/devcontainer.json
STEP 2 — Create .devcontainer/install-conda.sh    (Make it executable:        chmod +x .devcontainer/install-conda.sh)
STEP 3 — Open the repo in GitHub Codespaces
🧪 STEP 4 — Test everything

Open a new terminal and run:

✔ Check Conda
conda --version

✔ Activate env
conda activate nf

✔ Check Python
python --version

✔ Check Nextflow
nextflow -version
