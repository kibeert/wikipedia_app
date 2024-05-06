# wikipedia_app
# Wikipedia Search App

This is a simple web application built with Django that allows users to search for Wikipedia articles.

## Installation

1. Clone the repository:
git clone https://github.com/kibeert/wikipedia_app.git

2. Navigate to the project directory:
cd wikipedia-search-app

3. Install dependencies:
pip install -r requirements.txt

4. Apply database migrations:
python manage.py migrate


## Usage

1. Start the development server:
python manage.py runserver
2. Open your web browser and go to `http://127.0.0.1:8000/`.
3. Enter a search query in the search bar and press Enter.
4. Browse through the search results and click on an article to view its content.

## Features

- **Search:** Users can enter a search query to find relevant Wikipedia articles.
- **Results:** Display search results with article titles and summaries.
- **Detail:** Users can click on a search result to view the full article content.

## Technologies Used

- Django: A high-level Python web framework for rapid development.
- Wikipedia API: Used to fetch Wikipedia articles based on user queries.
- HTML/CSS: Frontend for displaying search results and article content.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a pull request.

## Credits

This project was created by kibeert and is licensed under the MIT License. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
