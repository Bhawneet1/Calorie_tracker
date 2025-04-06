# Calorie Tracker

A calorie tracking application that allows users to upload images of their meals and calculates the calorie content using Grok and ImgBB.

## Features

- **Image Upload**: Upload images of your meals using ImgBB.
- **Calorie Calculation**: Automatically calculate the calorie content of the uploaded meals using Grok.

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)
- Grok API Key
- ImgBB API Key

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Bhawneet1/Calorie_tracker.git
    cd Calorie_tracker
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

### Configuration

1. Create a `.env` file in the root directory and add your API keys:
    ```env
    GROK_API_KEY=your_grok_api_key
    IMGBB_API_KEY=your_imgbb_api_key
    ```

### Usage

1. Start the application:
    ```sh
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000`.

3. Upload an image of your meal and get the calorie content!

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Grok](https://grok.com) for the calorie calculation API.
- [ImgBB](https://imgbb.com) for the image hosting service.
