# CarCheckUp Web Application

CarCheckUp is a web application for a UK based company  that provides comprehensive car information and vehicle history reports. This application allows users to check the details and history of a vehicle by providing its registration number.

## Features

- Vehicle Information: Get detailed information about a vehicle, including make, model, year, and fuel type.
- MOT History: View the complete MOT test history of a vehicle, including the test date, mileage, and results.
- Road Tax Details: Check the road tax status and expiration date of a vehicle.
- Vehicle Valuation: Get an estimated valuation of a vehicle based on its make, model, and year.
- Outstanding Finance Check: Determine if a vehicle has any outstanding finance or loans against it.

## Technologies Used

- Front-end: HTML, CSS, JavaScript
- Back-end: Python, Django
- Database: MySQL
- APIs: DVLA API, MOT API, Finance API, Valuation API

## Installation

1. Clone the repository: `git clone https://github.com/your-username/carcheckup-web.git`
2. Navigate to the project directory: `cd carcheckup-web`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up the database and configure the database settings in `settings.py`.
5. Run database migrations: `python manage.py migrate`
6. Start the development server: `python manage.py runserver`
7. Access the application locally: [http://localhost:8000](http://localhost:8000)

Note: Please ensure you have Python and Django installed on your system before proceeding with the installation.

## Usage

1. Open your web browser.
2. Visit the CarCheckUp website: [https://carcheckup.co.uk/](https://carcheckup.co.uk/).
3. Enter the vehicle registration number in the provided input field.
4. Click on the "Check" button to retrieve the information and reports related to the vehicle.
5. Explore the different sections to view the vehicle's details, MOT history, road tax status, valuation, and outstanding finance check.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or inquiries, please contact the CarCheckUp team at support@carcheckup.co.uk.