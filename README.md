# Google Maps Search API and Ollama Integration

This repository demonstrates the integration of the Google Maps Search API and Ollama for location-based queries and processing results with AI models. The project retrieves places using the Google Maps API and processes the data using Ollama to refine the results based on custom prompts.

## Features

- **Google Maps API Integration**: Retrieve places within a specific radius based on location and query parameters.
- **Ollama AI Processing**: Use Ollama to process and filter the retrieved places, returning the most accurate results based on your specified criteria.

## Getting Started

### Prerequisites

- Python 3.8+
- Google Maps API key
- Ollama API access

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your API keys**:

   - Create a `config.json` file in the root directory:
     ```json
     {
         "api_key": "YOUR_GOOGLE_MAPS_API_KEY"
     }
     ```

   - Add the `config.json` file to your `.gitignore` to keep it secure:
     ```
     config.json
     ```

### Usage

1. **Run the main script**:
   ```bash
   python main.py
   ```

2. **Results**:
   - The script will retrieve locations based on the parameters set in the script and save the results to a JSON file.
   - Ollama will process the retrieved places and provide filtered results based on your custom prompts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Third-Party Services

This project uses the Google Maps Search API and Ollama. By using this project, you agree to comply with the respective terms of service:

- [Google Maps Platform Terms of Service](https://developers.google.com/maps/terms)
- [Ollama Terms of Service](https://ollama.com/terms)

Please note that the use of these services may be subject to additional fees, usage limits, and other restrictions imposed by the service providers.

## Acknowledgments

- [Google Maps API Documentation](https://developers.google.com/maps/documentation)
- [Ollama Documentation](https://ollama.com/docs)

### Key Points:

- **Configuration**: Ensure the `config.json` file containing your API keys is securely managed and not included in your version control by adding it to `.gitignore`.
- **Third-Party Compliance**: The README clearly states the need to comply with the terms of the third-party services used.
- **License**: The MIT License is a simple, permissive license suitable for most projects. It allows others to use, modify, and distribute your code. 

Make sure to customize the file according to your project's specific details, like the repository name and any additional instructions.
