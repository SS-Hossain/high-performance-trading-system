High-Performance Order Execution and Management System

A robust and low-latency trading system implemented in C++ for trading on Deribit Test. The project supports order management, real-time market data streaming, and efficient WebSocket communication, tailored for trading in Spot, Futures, and Options markets.

Features
Core Functionality
Order Management

Place Orders
Cancel Orders
Modify Orders
Retrieve Orderbook
View Current Positions
Real-Time Market Data Streaming

Implements a WebSocket server.
Allows clients to subscribe to specific symbols.
Streams continuous orderbook updates for subscribed symbols.


Market Coverage
Instruments: Spot, Futures, and Options.
Scope: All supported symbols on Deribit Test.

Technical Specifications
Language: C++
Performance: Low-latency implementation.
Error Handling and Logging: Comprehensive logging and error management.
WebSocket Server:
Connection Management
Subscription Handling
Efficient Message Broadcasting


Bonus Features (Optional)
Performance Analysis and Optimization
Latency Benchmarking

Order placement latency.
Market data processing latency.
WebSocket message propagation delay.
End-to-end trading loop latency.
Optimization Techniques

Memory management.
Network communication.
Data structure selection.
Thread management.
CPU optimization.
Documentation

Detailed bottleneck analysis.
Benchmarking methodology and results.
Justification for optimizations.


Installation
Prerequisites
Development Environment: Visual Studio 2022 or equivalent.

Dependencies:

cURL library.
WebSocket library (e.g., websocketpp).
vcpkg for dependency management.
API Setup:

Create an account on Deribit Test.
Generate API keys for authentication.


Steps
1. Clone this repository:
    git clone https://github.com/SS-Hossain/high-performance-trading-system.git

2. Install dependencies via vcpkg:
   ./vcpkg install curl websocketpp  

3. Build the project in Visual Studio.
4. Run the executable.


Usage
Place Orders:
Configure your API keys and use the CLI or integrated tools to place trades.

Stream Market Data:
Connect a client to the WebSocket server and subscribe to desired symbols to receive updates.


Contributing
Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.


License
This project is licensed under the MIT License.



Contact
SK Shaid Hossain

Email: skshaidhossain777@gmail.com
LinkedIn: skshaidhossain
GitHub: SS-Hossain
