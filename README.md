# Inside Airbnb Analysis - Santiago

This project analyzes Airbnb listings and calendar data for Santiago, Chile.  
It includes data cleaning, exploratory analysis, and visualization using Jupyter notebooks.

## Project structure

- `01_exploratory_analysis.ipynb`: Initial data exploration and cleaning  
- `02_analysis_calendar.ipynb`: Calendar data analysis (in progress)  
- `03_analysis_listings.ipynb`: Listings data analysis (in progress)  
- `cleaned_data/`: Cleaned CSV files (not uploaded to GitHub)  
- `figures/`: Saved histograms and plots  
- `.venv/`: Python virtual environment (ignored)  

## Data

This project uses datasets from [Inside Airbnb - Santiago](http://insideairbnb.com/get-the-data.html).

### How to download data:

1. Go to the [Inside Airbnb Data page](http://insideairbnb.com/get-the-data.html).  
2. Download the relevant files for Santiago.  
3. Place the downloaded CSV files in a folder named `santiago/` in the root of this project.

The notebooks assume the data files are located in `./santiago/`.

## Setup

This project uses [uv](https://astral.sh/docs/uv) as the package and environment manager.

### To get started:

1. Clone the repository  
2. Initialize and sync the environment (only needed the first time):

    ```bash
    uv init       # Run once when starting the project
    uv sync       # Install dependencies from pyproject.toml
    ```

3. Activate the environment:

    - If using `uv`, run:
    
      ```bash
      uv shell
      ```

    - Or if you manually created a virtual environment named `.venv`:

      ```bash
      source .venv/bin/activate   # On Linux/macOS
      ```

      For Windows PowerShell:

      ```powershell
      .\.venv\Scripts\Activate.ps1
      ```

4. Run the notebooks in order starting with `01_exploratory_analysis.ipynb`.

---

## Contact

Maria Perez — mary.perez.m@gmail.com  
[LinkedIn](https://www.linkedin.com/in/maria-perez1205) / [GitHub](https://github.com/pmmaria/pmmaria.github.io) / [GitHub Blog](pmmaria.github.io)

