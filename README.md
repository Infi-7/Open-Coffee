# Open Coffee
  Open Coffee is a Flask-based web application designed to help users discover and manage cafes. The platform     supports user authentication, cafe addition, and integration with an external API for listing cafes.

## Features
  - User Accounts: Register, log in, and manage sessions.
  - Add Cafes: Authenticated users can submit details about cafes, including amenities and location.
  - API Integration: Communicates with a REST API for cafe data management.
  - Responsive Design: Clean and responsive UI using Bootstrap.

## Technologies Used
  - Backend: Flask, SQLAlchemy
  - Frontend: HTML, CSS, Bootstrap
  - Authentication: Flask-Login
  - API Integration: requests library

## Installation
  1. Clone the repository:
     ```
      git clone https://github.com/Infi-7/Open-Coffee.git
      cd Open-Coffee
     ```
  
  2. Install dependencies:
     ```
       pip install -r requirements.txt
     ```

  3. Set up the .env file:
     ```
      secret_key=your_secret_key
      db_path=sqlite:///cafes.db
      api_link=http://your-api-link/
     ```
  
  4. Initialize the database:
     ```
       flask db upgrade
     ```

  5. Run the app:
     ```
       flask run
     ```

## Screenshots
  ![image](https://github.com/user-attachments/assets/4fdab4ae-9793-4379-9940-2f46c8c5ac7b)
  ![image](https://github.com/user-attachments/assets/a9052833-fefe-4df6-82f1-6552a315565c)
  ![image](https://github.com/user-attachments/assets/a0a89de4-ac25-4957-8b22-4841221a486f)
  ![image](https://github.com/user-attachments/assets/7db2a1f8-c6e1-40d7-896f-07d1cff0eb07)
  ![image](https://github.com/user-attachments/assets/0efea196-73e3-4abc-b61e-609a51c4d2ae)

## License
  This project is licensed under the MIT License.
  Feel free to customize this further for your project! Let me know if you'd like help adding more details.
