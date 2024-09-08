# Image Analyzer

This project is an interactive image analysis tool built with [Chainlit](https://github.com/chainlit/chainlit) and the [phi-3-vision-mlx](https://github.com/JosefAlbers/Phi-3-Vision-MLX) model. It allows users to upload images and ask questions about them, receiving AI-generated analyses in response. Its main purpose is to be a demo for the [phi-3-vision-mlx](https://github.com/JosefAlbers/Phi-3-Vision-MLX) model which is a vision model optimized for Apple Silicon chip that can analyze images and provide insights. Its basic app, nothing much more than a demo.

## Features

- User-friendly chat interface
- Image upload functionality
- Custom question input for each image
- AI-powered image analysis

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8+
- pip (Python package manager)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/gauravdhiman/image-analyzer.git
   cd image-analyzer
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv .venv
   source .venv/bin/activate
   
   # On Windows, use `.venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install chainlit phi-3-vision-mlx
   ```

## Usage

To run the Image Analyzer:

1. Start the Chainlit app:
   ```
   chainlit run app.py -w
   ```

2. Open your web browser and navigate to the URL provided in the terminal (usually `http://localhost:8000`).

3. In the chat interface:
   - Upload an image
   - Type a question about the image in the same message
   - Wait for the AI to analyze the image and provide a response

## Project Structure

- `app.py`: Main application file containing the Chainlit UI logic
- `image_analyzer.py`: Backend logic for image analysis using phi-3-vision-mlx
- `README.md`: This file, containing project documentation

## Contributing

Contributions to the Image Analyzer project are welcome. Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Chainlit](https://github.com/chainlit/chainlit) for the chat interface
- [phi-3-vision-mlx](https://github.com/JosefAlbers/Phi-3-Vision-MLX) for the image analysis capabilities
