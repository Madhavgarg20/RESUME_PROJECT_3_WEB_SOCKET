# Tic-Tac-Toe WebSocket Game

A real-time Tic-Tac-Toe game implemented using Node.js, Express, and Socket.IO. This project demonstrates how to create a multiplayer game with WebSocket support, allowing users to play against each other .

## Features

- **Real-Time Multiplayer:** Play Tic-Tac-Toe with another player over WebSocket.
- **Dynamic Game Updates:** Game board updates in real-time as players make moves.
- **Winner and Draw Detection:** Alerts players when the game ends with a win or a draw.

## Technologies Used

- **Node.js**: JavaScript runtime for building server-side applications.
- **Express**: Web framework for Node.js to handle HTTP requests.
- **Socket.IO**: Library for real-time, bidirectional event-based communication.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **HBS**: Handlebars templating engine for rendering views.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/Madhavgarg20/RESUME_PROJECT_3_WEB_SOCKET.git
    cd RESUME_PROJECT_3_WEB_SOCKET
    ```

2. **Install Dependencies**

    ```bash
    npm install
    ```

3. **Start the Server**

    ```bash
    npm start
    ```

    The server will start and listen for incoming WebSocket connections.

## Usage

1. Open your browser and navigate to `http://localhost:3000` to access the game.
2. Enter your name and click on Search for a player.
3. Enjoy the game with real-time updates!

## Deployment

To deploy this project, you can use platforms like [Render](https://render.com) . Follow the respective platform’s deployment instructions and ensure that your `package.json` and project files are correctly configured.

### Render Deployment

1. Create a new web service on Render.
2. Connect your GitHub repository.
3. Set the build and start commands. For example:

    - **Build Command**: `npm install`
    - **Start Command**: `npm start`

4. Deploy your project.

## Configuration

- **Port**: The server runs on port `3000` by default. You can change this in `app.js`.
- **Environment Variables**: Set up any necessary environment variables through your deployment platform's dashboard.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork the repository and submit pull requests. Any contributions to improve the game or fix bugs are welcome!

## Contact

For questions or support, please open an issue on the GitHub repository or contact me at [madhavgargjan20@example.com](mailto:your-email@example.com).
