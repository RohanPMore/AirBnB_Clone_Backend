# AirBnB Clone Backend

This project is the backend component of an AirBnB clone application, developed using Django and Django Rest Framework. It provides APIs for managing property listings, user authentication, bookings, and more.

## Features

- **User Authentication**: Secure registration and login functionalities.
- **Property Management**: APIs to create, update, delete, and retrieve property listings.
- **Booking System**: Manage bookings, including creation, modification, and cancellation.
- **Search Functionality**: Search properties based on various criteria.

## Technologies Used

- **Backend**: Django, Django Rest Framework
- **Frontend**: Next.js (planned or in development)
- **Containerization**: Docker

## Getting Started

### Prerequisites

- **Python 3.x**: Ensure Python is installed on your system.
- **Docker**: For containerized deployment (optional but recommended).

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/RohanPMore/AirBnB_Clone_Backend.git
   cd AirBnB_Clone_Backend
   ```

2. **Set Up Virtual Environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**:

   ```bash
   python manage.py runserver
   ```

   The application will be accessible at `http://localhost:8000/`.

### Using Docker

For a containerized setup:

1. **Build and Start Containers**:

   ```bash
   docker-compose up --build
   ```

   This will set up the application along with any dependencies defined in the `docker-compose.yml` file.

## API Endpoints

The backend provides various API endpoints to interact with the system. Detailed API documentation can be found [here](link_to_api_documentation).

## Credit

This project was developed following step-by-step tutorials from [Code with Stein](https://codewithstein.com) and his YouTube channel [Code with Stein](https://www.youtube.com/@CodeWithStein).

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
