# ESMFold Streamlit App

This is a Streamlit application for predicting protein structures using the ESMFold model. The app allows users to input a protein sequence and visualize the predicted structure.

## Features

- Input protein sequences
- Predict protein structures using the ESMFold model
- Visualize predicted protein structures in 3D
- Display plDDT values as a confidence measure
- Download predicted PDB files

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/saikiranvankudothu/3dprotein.git
    cd 3dprotein
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit app:
    ```sh
    streamlit run streamlit_app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Enter a protein sequence in the sidebar and click the "Predict" button to see the predicted structure and plDDT values.

## Configuration

You can customize the appearance of the app by modifying the [config.toml](http://_vscodecontentref_/1) file.

## Dependencies

- Streamlit
- stmol
- py3Dmol
- biotite
- ipywidgets
- ipython_genutils


## Acknowledgements

- ESMFold model by [Hugging Face](https://huggingface.co/spaces/osanseviero/esmfold)
- Streamlit for the web framework
- stmol and py3Dmol for molecular visualization
- biotite for structure handling

## Author

- Sai Kiran