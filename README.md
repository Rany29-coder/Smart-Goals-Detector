# SMART Goals Analyzer using BERT

SMART Goals Analyzer is a machine learning tool that leverages the BERT model for multi-label classification. It assesses user-defined goals against the SMART (Specific, Measurable, Achievable, Relevant, Time-bound) criteria, providing instant feedback and recommendations.

## Features

- **BERT-based Classification**: Utilizes the state-of-the-art BERT model for accurate predictions.
- **Customizable Thresholds**: Allows users to set custom decision thresholds for each SMART criterion.
- **Optimized Training**: Supports experimentation with various learning rates to achieve the best model performance.

## Installation

\```bash
git clone https://github.com/your_username/smart-goals-analyzer.git
cd smart-goals-analyzer
pip install -r requirements.txt
\```

## Usage

1. Train the model (optional if using a pre-trained model):
\```bash
python train.py
\```

2. Evaluate a goal:
\```bash
python evaluate.py --goal "Your goal here"
\```

## Contribution

Contributions are welcome! Please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
