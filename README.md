# TicTacToeWebSocketsAndKtor (Android Client) 🎮

A real-time, multiplayer Tic-Tac-Toe Android application built with **Jetpack Compose** and **Ktor WebSockets**. This client pairs with a Ktor backend to provide a synchronized, turn-based gaming experience across different devices.

---

## 🌟 Features

* **Real-time Synchronization:** Uses WebSockets to ensure board states and player turns are updated instantly across all clients.
* **MVI Architecture:** Implements a clean **Model-View-Intent** pattern for predictable state management and UI updates.
* **Modern UI:** Built entirely with **Jetpack Compose** and **Material 3** for a smooth, responsive user interface.
* **Turn-based Logic:** Authoritative game flow that handles player turns, win/draw animations, and game-over states.
* **Clean Architecture:** Separated into Data, Domain, and Presentation layers for better maintainability and testing.

---

## 🛠 Tech Stack

| Category | Technology |
| :--- | :--- |
| **Language** | Kotlin |
| **UI Framework** | Jetpack Compose |
| **Networking** | Ktor Client (WebSockets) |
| **Architecture** | Clean Architecture + MVI |
| **DI Framework** | Dagger Hilt |
| **Serialization** | Kotlinx Serialization |

---

## 🏗 Project Structure

* **`data`**: Contains the WebSocket implementation and DTO (Data Transfer Object) models for communicating with the Ktor server.
* **`domain`**: Defines the business logic, including game state models and the repository interface.
* **`presentation`**: Handles the UI state and Composables. The ViewModel processes "Intents" (e.g., clicking a cell) and updates the "State" (the board).

---

## 🚀 Getting Started

### Prerequisites
* **Android Studio** (Flamingo or later)
* **JDK 17+**
* **TicTacToe Backend:** You must have the [TicTacToeKtorWebSocketsBackend](https://github.com/shubham230523/TicTacToeKtorWebSocketsBackend) running locally or hosted.

### Installation & Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/shubham230523/TicTacToeWebSocketsAndKtor.git
