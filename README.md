## Resort Business Analysis

### Instruction to Run Program 

    ➢ Open CMD module
    ➢ First create a Virtual Environment in the working directory: python -m venv environment_name
    ➢ Active Virtual environment: evironmentname\Scripts\activate.bat
    ➢ Import and install requirement.txt file: pip install -r /path/to/requirements.txt

    Project Requirements: 

    ❖ Upload project to the GitHub (upload via Git) repository with minimum 5 separate commits 
    ❖ Files: Gitignore, readme, and requarment.txt 
    ❖ Paragraph on the project overview  
    ❖ Include relevant packages and special instructions to run the project. 
    ❖ Implement a data analysis program that uses: pandas, matplotlib, numpy, and data visualization tools

    Target Feature: 

    ❖ Read two data files (JSON, CSV, Excel, etc.)	 
    ❖ Clean data | Perform a pandas merge with your two data sets | Calculate new values based on the new data set
    ❖ Make at least 1 Pandas pivot table and 1 matplotlib/seaborn plot. 
    ❖ Clean your data and convert csv to database in SQL
    ❖ Set up a local database and read data in with SQLite
    ❖ Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data. 
    ❖ Utilize a virtual environment and include instructions in your README on how the user should set one up 
    ❖ Annotate your code with markdown cells in Jupiter Notebook




Business Overview:
     
    The Sunrise by the Shore is an oceanside resort rental found on the East Coast (state NC)
    ➢ In operation since January 2021
    ➢ Database 500 customers
    ➢ Package deals include: (room, parking, and indoor pool)
           Sale: shops/rental: golf, water sports, art/craft, souvenir, snack, dining room, 
              banquet room, lounge, fitness center, business center, conference room, and arcade
              
    Incentives: 
     Discounts: (15% off from weekly rate if renters rent for more than a week)

    Problem:
     Several different employees entered and uploaded the data in the format that was impossible to track
     
    Objectives:
    ➢ Conduct data cleaning, wrangling, and manipulating (missing, duplicated info, ...)
    ➢ Merge data into one data file
    ➢ Create a new system to better track existing data and new entries
    
    
    
    Future Goal Considerations:
    ➢ Check which facilities do not pull desired revenue
    ➢ Implement sales forecast: Projections are based on historical sales patterns
    ➢ Business expenditure/expansion
    ➢ Identify internal (any tax increase) and external (weather conditions) factors: effect and analysis
