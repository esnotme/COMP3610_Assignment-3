# COMP3610_Assignment-3
Project Setup
Follow these steps to run the notebook locally:

1. Clone the repository
bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
2. Open in VS Code
Launch VS Code.

Open the cloned folder (File → Open Folder).

3. Create a virtual environment
bash
python -m venv venv
Activate it:

Windows (PowerShell):

bash
venv\Scripts\activate
Mac/Linux:

bash
source venv/bin/activate
4. Install dependencies
Make sure you have a requirements.txt file in the repo. Then run:

bash
pip install -r requirements.txt
5. API Key setup
Before running the notebook:

Go to the third cell in the notebook.

Add your API key there (or set it as an environment variable).
Example:

python
import os
os.environ["LLM_API_KEY"] = "your_api_key_here"
6. Note on Colab users
The first cell in the notebook was used for installing pip packages to handle Colab’s updated environment errors.

If you’re running locally (VS Code, Jupyter), you may need to comment out or skip that cell since dependencies are already installed via requirements.txt.

7. Run the notebook
Open the .ipynb file in VS Code (with the Jupyter extension installed) and run the cells.
