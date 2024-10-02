# Random Fact Generator

This project is a simple web application that generates random facts from Wikipedia based on selected categories. It's a fun and educational tool that can provide interesting information on various topics with just a click of a button.

## Features

- Generate random facts from Wikipedia
- Filter facts by categories:
  - Cars
  - Indian History
  - Food
  - Movies
  - Music
- Option to get facts from all categories
- Clean and simple user interface

## How It Works

The Random Fact Generator uses the Wikipedia API to fetch articles from specific categories or random articles from the entire Wikipedia database. When a user selects a category and clicks the "Generate New Fact" button, the application does the following:

1. If a category is selected, it fetches up to 500 pages from that category and then randomly selects one.
2. If no category is selected (All Categories), it fetches a completely random page from Wikipedia.
3. Once a page is selected, it fetches the summary for that page and displays it to the user.

## Usage

To use the Random Fact Generator:

1. Open the `index.html` file in a web browser.
2. Select a category from the dropdown menu (or leave it as "All Categories").
3. Click the "Generate New Fact" button.
4. Read the interesting fact that appears!

## Installation

No installation is required. Simply clone this repository or download the `index.html` file and open it in a web browser.

```bash
git clone https://github.com/yourusername/random-fact-generator.git
cd random-fact-generator
```

Then open `index.html` in your preferred web browser.

## Technologies Used

- HTML
- CSS
- JavaScript
- Axios (for making API requests)
- Wikipedia API

## Limitations

- The category pages are limited to 500 results to avoid overloading the API. For very large categories, this means you might not see all possible pages.
- Some categories might have subcategories or might not contain many pages, which could affect the variety of results.
- The "All Categories" option will fetch a completely random page from Wikipedia, which might not always be interesting or fact-like.

## Contributing

Contributions to improve the Random Fact Generator are welcome! Here are some ways you can contribute:

- Report bugs
- Suggest new features
- Add new categories
- Improve the user interface

Please feel free to submit a pull request or create an issue to discuss potential changes/additions.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

If you have any questions, feel free to reach out to [Your Name] at [your.email@example.com] or create an issue in this repository.

Enjoy learning random facts!
