
- # Introduction:
- **Fluffernut**: Ai companion, coding connoisseur

- **Description**: Fluffernut, The core idea here is to design a framework where users can easily add new features and functionality without altering the main structure. The code will be modular and encourage further development.

- We'll build it in Python, and use a command-based interface to allow users to interact with Fluffernut. Users will also be able to extend it with new commands or plugins.

- # Fluffernut - AI Companion for Automated Crypto Chart Reading

- Fluffernut is an AI companion designed to automate the process of reading cryptocurrency charts. With Fluffernut, you can easily fetch real-time market data, visualize crypto charts, and perform basic technical analysis (e.g., moving averages) to help you make informed decisions. Whether you're a crypto enthusiast or an experienced trader, Fluffernut can be customized to suit your needs for automation and analysis.

- ## Features

- **Real-time Crypto Data Fetching**: Automatically fetches real-time OHLCV (Open, High, Low, Close, Volume) data for cryptocurrencies from Binance (or other exchanges).
- **Charting**: Visualizes the closing prices of selected cryptocurrency pairs with easy-to-read plots using `matplotlib`.
- **Simple Technical Analysis**: Includes a basic Moving Average analysis with Golden Cross signals to help identify market trends.
- **Automated Monitoring**: Runs continuously and fetches data at regular intervals (customizable), providing up-to-date information for decision-making.

- ## Installation

- Follow these steps to get Fluffernut up and running:

- 1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/fluffernut.git
   cd fluffernut

- **Usage**: The Fluffernut class handles user interaction and execution of commands.
Commands are registered via register_command(), and executed with execute_command().
The run() method starts a simple text-based shell that listens for commands.
Plugin System:

- Plugins are functions that, when loaded, register additional commands.
In this example, we’ve loaded two plugins: math_plugin and greeting_plugin.
User Interaction:

- The user can enter commands (e.g., add 5 3, greet John, help).
Fluffernut responds with the appropriate output or error message.
The user can type exit to quit.

- **New/Future Functionality** To add new functionality, users can create their own plugins (functions) that register commands with register_command.
Each plugin can provide any type of functionality, from calculations to data manipulation, games, and more.


- [Fluffernut](https://x.com/Fluffernut13813) 

