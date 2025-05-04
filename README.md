# Streamlit initial template

## This is inital template for streamlit project

1. Initialize uv project with utkarshpy package

   [utkarshpy github repo](https://github.com/utkarshg1/utkarshpy)

   ```bash
   utkarshpy
   ```

2. What does template.py do?

   template.py sets up the minimal required structure for a Streamlit project by:

   - Creating a `.streamlit` directory if it doesn't exist
   - Creating a `.streamlit/secrets.toml` file with an API_KEY placeholder
   - Adding `.streamlit/` to the `.gitignore` file to exclude secrets from version control
   - Adds `notebook` folder and and `api.ipynb` file inside the folder
   - Creating a basic `utils.py` file if it doesn't exist

   This ensures your Streamlit project has the necessary configuration for secrets management and follows best practices for project structure.
