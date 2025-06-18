# Inside Airbnb — Santiago Analysis

This project analyzes Airbnb listings data for Santiago using the public **Inside Airbnb** dataset. It explores price patterns, availability, and reviews to provide insights into the local short-term rental market.

---

## Tech Stack

- **Language**: Python 3.12
- **Data Analysis**: pandas, seaborn, matplotlib
- **Environment & Dependency Management**: 
This project uses [uv](https://astral.sh/docs/uv) as the package and environment manager + `pyproject.toml`
- **Notebook**: Jupyter via VSCode

---

## Project Structure

```bash 
inside_airbnb/
├─ santiago/            # Raw datasets 
├── notebooks/          # Jupyter notebooks for each dataset
│   ├── 01_exploratory_analysis.ipynb
│   ├── 02_analysis_calendar.ipynb
│   ├── 03_analysis_listings.ipynb
│   └── ...
├── pyproject.toml      # Project metadata and dependencies
├── README.md
└── .venv/              # Virtual environment
```

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/pmmaria/inside_airbnb.git
cd inside_airbnb
```
### 2. Add the datasets

This project uses datasets from [Inside Airbnb - Santiago](http://insideairbnb.com/get-the-data.html).

#### How to download data:

1. Go to the [Inside Airbnb Data page](http://insideairbnb.com/get-the-data.html).  
2. Download the relevant files for Santiago.  
3. Place the downloaded CSV files in a folder named `santiago/` in the root of this project.

The notebooks assume the data files are located in `./santiago/`.

### 3. Create the virtual environment

```bash
      uv sync
  ```
This reads from `pyproject.toml` and creates a `.venv/` folder with all required packages.


### 4. Activate the environment:

  ```bash
  source .venv/bin/activate   # On Linux/macOS
  ```
  
  ```bash
  .\.venv\Scripts\Activate.ps1 # For Windows PowerShell
  ```

### 5. Install the Jupyter kernel (if needed)
If running a notebook gives a kernel error, install it manually:

  ```bash
  uv add ipykernel
  ```

### 6. Notebooks

Run the notebooks in order:

- `01_exploratory_analysis.ipynb`: initial structure, preview of all datasets.

- `02_analysis_calendar.ipynb`: data cleaning and pricing trends (in progress).

- `03_analysis_listings.ipynb`: listings structure, features, and clustering (planned).

- `04_analysis_reviews.ipynb`: review patterns, sentiment, and activity (planned).



## Contact

Created by Maria Perez.

Feel free to reach out via GitHub or LinkedIn!

- mary.perez.m@gmail.com  
- [LinkedIn](https://www.linkedin.com/in/maria-perez1205) / - [GitHub](https://github.com/pmmaria) 

## Learn More About Me

I recently started a blog where I share my data projects, insights, and learning journey.  
Feel free to take a look and follow along:  
[https://pmmaria.github.io](https://pmmaria.github.io)

