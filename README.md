# Machine Translation with T5 Transformer Model

This project uses the T5 transformer model to perform machine translation from English to German. The code is provided as a Jupyter Notebook and can be run directly in a GitHub Notebook.

## Usage
To use this code, simply open the machine_translation_t5.ipynb notebook file in a GitHub repository and click on the "Open in Colab" button. This will open the notebook in a new Colab environment, where you can run the code and explore the results.

The notebook loads the Opus Europarl Corpus dataset, preprocesses the data, and trains a model to perform machine translation. The code also includes a translate() function that can be used to translate new sentences using the trained model.

## Installation
!pip install transformers \n
!pip install datasets \n
!pip install sacrebleu \n

## Results
The pretrained T5 models (t5-small and t5-base) show good performance on translating sentences from the "opus_euconst" dataset. As shown in the example translation, the translated sentences are almost identical to the true translations. However, the BLEU score can be improved with additional training, which may take a longer time depending on the resources available.

## Acknowledgments
This project was created with the help of the Hugging Face Transformers library and the Opus Europarl Corpus dataset. Thanks to the contributors of these resources for making this project possible.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.
