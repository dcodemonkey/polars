# Create a Virtual Environment using
python -m venv <env_name>
# activate the virtual environment
## For Windows
.\<env_name>\Scripts\activate
## For macOS/Linux
source <env_name>/bin/activate
# Install the required packages
pip install -r requirements.txt
# To run the application
Open any jupyter notebook and select the virtual environment as the kernel.
# To deactivate the virtual environment
deactivate
# To remove the virtual environment
## For Windows
rmdir /s /q <env_name>
## For macOS/Linux
rm -rf <env_name>