# DrugGenie 🔮

### Empowering AI-Based Drug Discovery

DrugGenie leverages state-of-the-art AI models, including RNN and Transformer architectures, to facilitate innovative drug discovery. It uses cutting-edge deep learning models from `DrugEx` to generate new chemical compounds based on user preferences and specifications. With DrugGenie, research teams can streamline the drug design pipeline, enhancing efficiency and discovery speed.

## Key Features

- **Dynamic Molecule Generation**: Generate molecules on-demand using RNN (LSTM) or Transformer models, eliminating the need for pre-generated datasets.
- **Detailed Evaluation**: Provides comprehensive evaluation results of generated molecules, considering Lipinski's Rule, ADME criteria, and toxicity/safety profiles.
- **Progressive Feedback**: Offers real-time feedback via progress bars and loading modals.
- **User-Friendly Interface**: An intuitive UI makes navigating and managing drug generation simple.

## Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **AI Models**: DrugEx

## Getting Started

### Prerequisites

1. **Python Environment**: Make sure Python 3.6+ is installed and set up.
2. **Required Packages**: Use the provided requirements file or install using the app later.

```bash
# Install dependencies
pip install -r requirements.txt
```
3. **Download and Prepare Models**: Ensure all relevant model files and datasets are available. Check the folder paths in the code.

## Installation

### Prerequisites

1. **Python Environment**: Ensure that Python 3.6+ is installed and available in your system's PATH.
2. **Model Files**: Prepare the required model files and datasets. The paths used in the code should align with your project's directory structure.

### Dependencies

- **Install Requirements**: To simplify the setup, the required dependencies are listed in a `requirements.txt` file.

```bash
# Clone the repository
git clone https://github.com/yourusername/druggenie.git
cd druggenie

# Install dependencies
pip install -r requirements.txt
```

## Configuration

1. **Check Model Paths**: Ensure the AI model files (RNN and Transformer models) and vocabulary files are available in the `models` directory. If you store them in a different location, update the paths in the code.

2. **Data Sources**: Verify that any testing datasets required for input are available and their paths are correctly referenced in the code. This will ensure accurate generation and evaluation.

3. **Environment Variables**: Set environment variables to point to the appropriate Flask application.

```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```

## Usage

### Generation

- **Select Model Type**: Choose between "RNN (LSTM)" or "Transformer" using the provided radio buttons.
- **Specify Quantity**: Input the desired number of molecules to generate.
- **Generate**: Click "Generate" and monitor the real-time progress bar for immediate feedback.

### Evaluation

The evaluation page provides a detailed assessment of the generated molecules based on key drug development criteria such as:

- **Lipinski's Rule**
- **ADME Properties**
- **Toxicity/Safety Profiles**

## Contributing

We welcome contributions to enhance the features, models, and evaluations of DrugGenie! Please follow these steps:

1. **Fork the repository.**
2. **Create a feature branch.**
3. **Commit your changes.**
4. **Submit a Pull Request.**

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- **DrugEx**: The AI models used in DrugGenie are powered by the DrugEx framework.

