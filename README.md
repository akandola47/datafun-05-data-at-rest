Arshpreet Kandola Module 5 Project
domain: Buisness
September 24 2023

https://github.com/akandola47/datafun-05-data-at-rest

Focus of this project repository will be data at rest and looking at how to read and write from files and relational databases.


CREATING AND ACTIVATING A  VIRTUAL ENVIORNMENT

Step 4: Set up a Virtual Environment
Next, we'll create and activate a virtual environment specifically for this project. We'll also install additional packages required for this project.

Create a Virtual Environment
Open the terminal in VS Code. (View / Terminal)
Run the following command to create a virtual environment for this project.
python -m venv .venv
Verify that a new .venv folder was created. It may take a while for the command to complete.

🚀 Rocket Tip: When VS Code Python Extension offers to select the Environment, say Yes.

Activate the Virtual Environment
Wait for the creation to finish, then activate the virtual environment:

For PowerShell: .venv\Scripts\Activate
For macOS/Linux: source .venv/bin/
🚀 Rocket Tip: Notice the terminal changes to reflect the active virtual environment.

INSTALLING DEPENDENCIES

Install Dependencies to the Active Virtual Environment
Install additional project dependencies into the active virtual environment. The packages ipykernel and jupyterlab are required to run a notebook. The packages pandas, matplotlib, and seaborn are used to work with data and charts.

python -m pip install --upgrade pip ipykernel jupyterlab
python -m pip install --upgrade pandas matplotlib seaborn
python -m pip install --upgrade voila
Alternatively, you can install all the packages listed in the requirements.txt file.

python -m pip install --upgrade -r requirements.txt
Note: The --upgrade parameter gets the latest version of each package.

EXECUTING SCRIPTS IN PYTHON

With your repo folder open in VS Code, start exploring. Open, read, and run each project script (each file will have a .py extension) in order. You don't need to fully understand the code yet. Instead, try to figure out what each file is doing.

Open acquainted.py (or another .py file).
Read the comments and code carefully.
Execute each script - one at a time.
On macOS/Linux, change python to python3 in the commands below.
python acquainted.py
python basic_expressions.py
python basic_functions.py
python circle_calc.py
python data_io.py
python easy_stats.py
Helpful hint: Hit the up arrow in the terminal to get the last command. Edit as needed and hit return.

