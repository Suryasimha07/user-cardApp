# user-cardApp
User Card Grid Web Application
This is a simple web application built using create-react-app that displays a grid of user cards and allows fetching user data from an API. The application utilizes custom CSS to style the components.

Features
User card grid layout
Navbar displaying a brand name
"Get Users" button for fetching user data from the API
Loader while the API fetches data
Custom CSS styles using CSS modules
Technologies Used
React
create-react-app
HTML
CSS
Getting Started
To run the application locally, follow these steps:

Clone the repository:
bash
Copy code
git clone [repository_url]
Navigate to the project directory:
bash
Copy code
cd user-card-grid
Install the dependencies:
Copy code
npm install
Start the development server:
sql
Copy code
npm start
Open your browser and visit http://localhost:3000 to view the application.
Usage
The application displays a navbar at the top with a brand name.

Click on the "Get Users" button in the navbar to fetch user data from the API.

While the API fetches data, a loader will be displayed.

Once the data is fetched, a grid of user cards will be shown, each containing the user's image, name, and email.

API Used
The application makes an API call to https://reqres.in/api/users?page=1 to fetch the user data.

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.
