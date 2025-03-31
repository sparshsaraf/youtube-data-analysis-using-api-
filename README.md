# YouTube Data Analysis using Python

This project performs data extraction, analysis, and visualization using the YouTube Data API. It retrieves channel statistics, video details, and playlist data to generate insights. The results are presented using Seaborn visualizations and exported to CSV for further analysis.

---

## Features

- Extract YouTube channel statistics (subscribers, views, total videos).
- Retrieve video details (views, likes, comments, published date).
- Perform data cleaning and conversion.
- Visualize insights using Seaborn.
- Export processed data to CSV.

---

## Prerequisites

Ensure you have Python installed. Install the required libraries using the following command:

```bash
pip install google-api-python-client pandas seaborn
```

You will also need a YouTube API key. Follow these steps to get one:
1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project.
3. Enable the YouTube Data API v3.
4. Generate an API key.

---

## Project Structure

```bash
.
├── main.py
├── README.md
└── requirements.txt
```

- `main.py` contains the code for extracting data, analyzing it, and visualizing results.
- `README.md` provides project documentation.
- `requirements.txt` lists the required dependencies.

---

## Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/youtube-data-analysis.git
```

2. Navigate to the project folder:
```bash
cd youtube-data-analysis
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Replace `Your_API_Key_Here` with your actual API key in `main.py`.

5. Run the script:
```bash
python main.py
```

---

## Visualizations
The project uses Seaborn for visualizing data. Examples include:
- Subscriber count comparisons
- Total views per channel
- Top 10 videos by views

You can customize the visualizations in `main.py`.

---

## Exporting Data
The processed data is exported as a CSV file named `Video_Details(author).csv`. You can use it for further analysis using Excel, Google Sheets, or any data analysis tool.

---

## Troubleshooting
- **API Quota Exceeded**: Ensure your API key has sufficient quota.
- **Invalid API Key**: Double-check your API key and project permissions.
- **Module Not Found**: Run `pip install -r requirements.txt` again.

---

## Contributing
Feel free to submit issues or pull requests to improve the project. Contributions are welcome!

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
- [YouTube Data API](https://developers.google.com/youtube/v3) for data extraction.
- [Seaborn](https://seaborn.pydata.org/) for visualizations.
- [Pandas](https://pandas.pydata.org/) for data manipulation.

