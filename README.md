# Slim Chat Client

A lightweight and easy-to-use chat client developed with Laravel 11, designed for quick and seamless communication. It allows users to connect, chat, and share messages in real-time.

## Features

- **User-friendly Interface**: This chat client provides a clean and intuitive interface, making it easy for users to navigate and use the application.
  
- **Real-time Messaging**: Instantly send and receive messages, enabling real-time communication between users.
  
- **Multiple Chat Rooms**: Create and join multiple chat rooms based on interests, projects, or teams.
  
- **Customizable Username**: Users can set their own display name for each chat room.
  
- **Emoji Support**: Express yourself with a variety of emojis available for use in messages.
  
- **Cross-platform Compatibility**: A web-based application, accessible from any modern web browser.

## Installation

### Requirements

- [PHP](https://www.php.net/) (7.4 or higher)
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/) (for npm)
- [MySQL](https://www.mysql.com/)
- [Laravel 11](https://laravel.com/)

### Steps

1. Clone this repository:

    ```bash
    git clone https://github.com/arquizade/slim-chat-client.git
    ```

2. Navigate to the project directory:

    ```bash
    cd slim-chat-client
    ```

3. Install PHP dependencies using Composer:

    ```bash
    composer install
    ```

4. Install JavaScript dependencies using npm:

    ```bash
    npm install && npm run dev
    ```

5. Rename the `.env.example` file to `.env` and update the database configuration:

    ```bash
    cp .env.example .env
    ```

6. Generate application key:

    ```bash
    php artisan key:generate
    ```

7. Migrate and seed the database:

    ```bash
    php artisan migrate --seed
    ```

8. Start the Laravel development server:

    ```bash
    php artisan serve
    ```

9. Visit `http://localhost:8000` in your web browser to access the chat client.

## Usage

1. Upon accessing the application, you will be prompted to register or login.
  
2. After logging in, you can create a new chat room or join an existing one by selecting the appropriate option.
  
3. In the chat room, you can send messages by typing in the input box at the bottom and hitting enter or clicking the send button.
  
4. You can also use emojis by clicking on the emoji button and selecting the desired emoji from the list.

## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
*Screenshot of the main chat window.*

![Screenshot 2](screenshots/screenshot2.png)
*Screenshot of the emoji picker.*

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
