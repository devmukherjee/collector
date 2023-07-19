# Link Collector

Welcome to Link Collector! This application is designed to scrape a given user URL and display a list of links found on the particular webpage. Link Collector makes it easy to extract and organize relevant links from webpages for further analysis or reference. This README file provides an overview of the application and instructions on how to get started.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- URL Scraping: Link Collector allows users to provide a URL and scrape the webpage to extract all links present on that page.
- Link List: The application displays a list of links found on the webpage, making it convenient for users to review and access the extracted links.
- Webpage Preview: Users can click on each link in the list to preview the webpage's content directly within the application, providing a quick way to evaluate the relevance and credibility of the linked pages.
- Easy Organization: Link Collector organizes the extracted links in a user-friendly interface, making it simple to navigate through the list and manage the collected links efficiently.

## Installation

To run Link Collector locally on your machine, please follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/devmukherjee/collector.git
```

2. Navigate to the project root directory:

```bash
cd collector
```

3. Create a virtual environment:

```bash
python3 -m venv myenv
```

4. Activate the virtual environment:

On macOS and Linux:
```bash
source myenv/bin/activate
```

On Windows:
```bash
myenv\Scripts\activate
```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To use Link Collector, follow these steps:

1. Ensure you are in the project root directory: `collector`.

2. Start the development server:

```bash
python manage.py runserver
```

3. Open your web browser and visit `http://localhost:8000` to access Link Collector.

4. On the homepage, you will find a form where you can enter the URL you want to scrape.

5. Enter the URL and click the "Submit" button.

6. Link Collector will scrape the webpage and display a list of links found on the page.

7. Click on any link in the list to preview the content of the linked webpage.

8. Use the interface to navigate through the list, manage the collected links, and perform any necessary actions.

## Contributing

We welcome contributions to Link Collector! If you encounter any issues or have ideas for improvements, please open an issue on the GitHub repository. If you'd like to contribute code, please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make the necessary changes and commit your code.
4. Push the changes to your forked repository.
5. Open a pull request on the original repository, describing your changes in detail.

We appreciate your contributions!

## License

Link Collector is open-source software released under the [MIT License](LICENSE). You are free to use, modify, and distribute the codebase as per the terms of the license. Please refer to the [LICENSE](LICENSE) file for more information.

---

Thank you for choosing Link Collector! We hope you find this application useful in scraping and organizing links from webpages. Should you have any questions or require assistance, please feel free to reach out. Happy link collecting!
