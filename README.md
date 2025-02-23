# Data Sweeper

Data Sweeper is a Streamlit web application that allows you to:

* **Transform files:** Convert between CSV and Excel formats.
* **Clean data:** Remove duplicates and fill missing values.
* **Visualize data:** Generate bar charts.
* **Select columns:** Choose specific columns to work with.

## Features

* **File Upload:** Upload CSV and Excel files.
* **Data Preview:** View a preview of your data in a table.
* **Data Cleaning:**
    * Remove duplicate rows.
    * Fill missing numerical values with the mean.
* **Column Selection:** Choose specific columns for processing.
* **Data Visualization:** Generate bar charts of numerical columns.
* **File Conversion:** Convert files between CSV and Excel formats.
* **Easy Download:** Download the processed files.

## Usage

1.  **Upload Files:** Use the sidebar to upload your CSV or Excel files.
2.  **Data Preview:** View the data preview on the main page.
3.  **Data Cleaning:** Check the "Clean Data" box and use the buttons to remove duplicates or fill missing values.
4.  **Column Selection:** Select the columns you want to keep.
5.  **Data Visualization:** Check the "Show Bar Chart" box to generate a bar chart.
6.  **File Conversion:** Choose the desired output format (CSV or Excel) and click "Convert."
7.  **Download:** Click the "Download" button to save the converted file.

## Installation

1.  **Clone the Repository:**

    ```bash
    git clone [https://github.com/Abdurrehman2003/data-sweeper.git](https://github.com/Abdurrehman2003/data-sweeper.git)
    cd data-sweeper
    ```

2.  **Create a Virtual Environment (Recommended):**

    ```bash
    python -m venv venv
    ```

3.  **Activate the Virtual Environment:**

    * **Windows:**

        ```bash
        venv\Scripts\activate
        ```

    * **macOS/Linux:**

        ```bash
        source venv/bin/activate
        ```

4.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5.  **Run the App:**

    ```bash
    streamlit run app.py
    ```

## Deployment

This app can be deployed on Vercel:

1.  Push your code to a GitHub repository.
2.  Create a Vercel account.
3.  Import your GitHub repository into Vercel.
4.  Vercel will automatically build and deploy your app.

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues.

## License

This project is licensed under the [MIT License](LICENSE) 
