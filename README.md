# Sales Summary c5696dcc8f202202f2b6509786c813157e1

## Summary
This static web app fetches data from a CSV file to calculate the total sales, assigns a custom title, and displays the total sales value on the webpage using Bootstrap 5 CDN.

## Setup
To deploy this app on GitHub Pages:
1. Fork this repository.
2. Upload your `data.csv` file to the 'attachments' folder.
3. Upload your `rates.json` file to the 'attachments' folder.
4. Go to the repository Settings.
5. Under the GitHub Pages section, set the Source branch to 'main' or 'master'.
6. Your web app will be live at: `https://<your-username>.github.io/<repository-name>`

## Usage
To access the page, visit the GitHub Pages URL. You can use query parameters to customize the data displayed on the page.

## Features
- Introduces a currency select `#currency-picker` that converts the computed total using `rates.json` from attachments and mirrors the active currency inside `#total-currency`.

## Code Explanation
The HTML/JS code parses the CSV data in a robust way, handling trailing newlines, empty rows, etc. The sales column is summed up, and the total value is displayed inside the `#total-sales` element.

## License
This project is licensed under the MIT License.

---
**Note:** Remember to replace `<your-username>` and `<repository-name>` with your actual GitHub username and repository name respectively.