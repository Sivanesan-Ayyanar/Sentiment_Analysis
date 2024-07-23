
# Emotion Analysis Project

This project performs emotion analysis on text data using Natural Language Processing (NLP) techniques. It processes the text to remove unnecessary elements, identifies emotions from the text, and visualizes the results with bar and pie charts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Overview](#project-overview)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/yourusername/emotion-analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd emotion-analysis
   ```
## Usage

1. Place your text file (`read.txt`) in the project directory.
2. Ensure that your `emotions.txt` file, containing words and their corresponding emotions, is in the project directory.
3. Run the script:
   ```sh
   python main.py
   ```

## Project Overview

The Emotion Analysis project aims to identify and visualize emotions expressed in a text file. The project workflow includes:

1. **Text Processing:**
   - Reading the input text file.
   - Converting the text to lowercase and removing punctuation.
   - Tokenizing the text into individual words.
   - Removing common stop words from the tokenized words.

2. **Emotion Identification:**
   - Matching words from the processed text with a predefined list of words associated with specific emotions (stored in `emotions.txt`).
   - Creating a list of identified emotions based on the matches.

3. **Visualization:**
   - Counting the occurrences of each identified emotion.
   - Visualizing the emotion distribution using a bar graph and a pie chart.
   - The bar graph displays the frequency of each emotion, while the pie chart shows the proportion of each emotion.

This project provides a simple yet effective way to analyze and visualize the emotional content of a text, which can be useful for various applications like sentiment analysis, customer feedback analysis, and more.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


