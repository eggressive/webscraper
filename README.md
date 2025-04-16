# webscraper

Webscraper agent

## Installation

## Virtual Environment

It is recommended to use a Python virtual environment to manage dependencies. To create and activate a virtual environment, follow these steps:

1. Create a virtual environment:

```bash
python -m venv venv
```

2. Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```

- On macOS/Linux:

```bash
source venv/bin/activate
```

To install the necessary dependencies, run the following command:

```bash
pip install -r requirements.txt
```

## Usage

To run the web scraper, follow these steps:

1. Configure your API keys in a `.env` file. The format for the `.env` file should be:

```bash
OPENAI_API_KEY=your_openai_api_key
MULTION_API_KEY=your_multion_api_key
```

2. Run the web scraper script:

```bash
python webscraper.py
```

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

## License

This project is licensed under the terms of the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.
