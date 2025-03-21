# Animal Adoption App

This is a simple web application that allows users to add animals for adoption, track donations, and manage animal listings. The app interacts with a local JSON server to store and retrieve animal data.

## Features

- **Add Animals**: Users can submit a form to add a new animal for adoption, including its name, image URL, and description.
- **Track Donations**: Each animal has a donation counter that can be incremented by $10 with a "Donate" button.
- **Remove Animals**: Animals can be "set free" (removed) from the adoption list, which deletes them from the database.
- **Persistent Data**: Animal data is stored and retrieved using a local JSON server.

## Technologies Used

- **HTML/CSS**: For structuring and styling the application.
- **JavaScript**: For handling DOM manipulation and interactivity.
- **Fetch API**: For making HTTP requests to the JSON server.
- **JSON Server**: A local server used to simulate a RESTful API for storing animal data.

## Setup Instructions

### Prerequisites

- Node.js and npm installed on your machine.
- A modern web browser.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/animal-adoption-app.git
   cd animal-adoption-app

## Usage

### Add an Animal:
- Fill out the form with the animal's name, image URL, and description.
- Click **"Submit"** to add the animal to the adoption list.

### Donate to an Animal:
- Click the **"Donate $10"** button on an animal's card to increase its donation amount.

### Remove an Animal:
- Click the **"Set Free"** button on an animal's card to remove it from the adoption list.

## Project Structure


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
