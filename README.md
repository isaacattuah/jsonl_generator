# JSONL Generator

This Jupyter Notebook is designed to generate a JSONL file containing examples for fine-tuning language models. It uses the Vertex AI SDK from Google Cloud to interact with the Gemini Flash 1.5 language model and generate responses based on provided prompts.

## Features

- Authenticate with Google Cloud Platform
- Install required dependencies
- Generate random prompts similar to provided examples
- Call the Gemini Flash 1.5 language model to generate responses for the prompts
- Create JSON examples in the format required for fine-tuning the Gemini or PaLM language models
- Save the examples to a JSONL file for later use

## Usage

1. Set the desired number of examples and the model version (Gemini or PaLM).
2. Provide example prompts to use as a reference for generating new prompts.
3. Run the notebook cells to generate prompts, obtain model responses, and create the JSONL file.
4. The generated JSONL file will be saved in the specified output file path.

## Getting Started

Please note that this project requires a Google Cloud Platform (GCP) account to access and utilize the Gemini language model. This is because Gemini is currently offered as a managed service through Vertex AI, which is part of the Google Cloud platform.

Here's what you need to do:

1. Create a GCP Account: If you don't already have one, sign up for a free trial or create a new account on the [Google Cloud Platform website](https://cloud.google.com/?hl=en).
   
2. Enable Vertex AI API: Once you have a GCP account, you'll need to enable the Vertex AI API for your project. Instructions on how to do this can be found in the [Vertex AI documentation](https://cloud.google.com/vertex-ai/docs/start/cloud-environment).

3. Clone the repository:
```
git clone https://github.com/isaacattuah/jsonl_generator
```

4. Open the Jupyter Notebook:
Open `jsonl_generator.ipynb` in Jupyter Notebook or Google Colab.

5. Follow the instructions:
The notebook provides step-by-step code and comments for generating the JSONL file.

## Requirements

- Google Cloud Platform account
- Python 3
- Vertex AI SDK (installed automatically in the notebook)

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
