Here’s a README for your Flag Quiz Game project:

---

# Flag Quiz Game

A web-based quiz game that tests your knowledge of world flags. Guess the country based on the displayed flag and keep track of your score!

## Features

- **Random Flag Display**: Shows a random flag from a database of countries.
- **Answer Checking**: Accepts user input and checks if the answer is correct.
- **Score Tracking**: Keeps track of the number of correct answers.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) and npm installed on your machine.
- PostgreSQL database set up with a `flags` table.

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yohansbekele12/flag-quize.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd flag-quize
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

4. **Set up the `.env` file**:
   - In the root directory, create a `.env` file with the following environment variables:
     ```plaintext
     PORT=3000
     DB_USER=your_db_user
     DB_HOST=localhost
     DB_NAME=world
     DB_PASSWORD=your_db_password
     DB_PORT=5432
     ```
5. **Start the application**:

   ```bash
   npm start
   ```

6. **Access the game**:
   - Open your browser and go to `http://localhost:3000`.

## Usage

1. The app will display a random flag.
2. Enter the country name corresponding to the displayed flag.
3. Submit your answer to check if it's correct.
4. Your score will update based on correct answers.

## Database Setup

Make sure you have a PostgreSQL database named `world` with a `flags` table. The table should include columns for `country` and `capital` to store country names and their corresponding capitals.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This README gives a clear overview and instructions for users and contributors. Let me know if you'd like to customize it further!
