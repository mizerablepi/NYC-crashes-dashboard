# NYC-crashes-dashboard
A streamlit dashboard to visualise the vehicle crashes in New York City based on this [dataset]().

## How to run this app:

### Step 1: Install [conda](https://docs.conda.io/en/latest/miniconda.html) if not already installed

### Step 2: Create a new virtual enviroment using 
`conda create -n your-environment-name python=3.9 pandas jupyter streamlit plotly numpy pydeck`

### Step 3: Copy the [app.py](./app.py) to your workspace

### Step 4: Open terminal in your workspace and type the following command
`streamlit run app.py`

Your app will automatically start in your browser



## Screenshots
![Screenshot from 2022-10-02 20-57-41](https://user-images.githubusercontent.com/41267142/193462319-9d390ec1-7ed3-4542-ab42-55c2d4d07141.png)

A map with a slider indicating the number of people injured, user can change the slider to see where in new york how many people were injured. The map changes dynamically and as the data is stored in cache it wont take long to process

![Screenshot from 2022-10-02 20-58-23](https://user-images.githubusercontent.com/41267142/193462321-8c8b19c9-d766-4a34-9f31-3fa542dc0f85.png)

A 3D map showing the number of crashes occuring at the specified time. The height of the hexagons indicate how many accidents have happened at the spot at that time in the past years

![Screenshot from 2022-10-02 20-58-42](https://user-images.githubusercontent.com/41267142/193462325-227ff0e0-6fcd-4e38-9fb2-4ab117ed815e.png)

A simple histogram showing specifically at what minute the crashes happened in the above specified time. Followed by a table to show which street is the most dangerous for the selected entity('pedestrians', 'motorist', 'cyclists')

