# flask-ner

Flask + spaCy simple API for Named Entity Recognition

The Python in this repo was developed using TDD and recorded for a video series on YouTube, which [can be found here](https://youtu.be/eAPmXQ0dC7Q).

Nicholas's edits:

1. Create a new virtual environment and activate it. You could do run something like this in your terminal:
    ```
    python -m venv ./flask-ner
    source flask-ner/bin/activate
    ```

    (Optional) Run this if you want to create a new virtual environment.


2. Run the requirement text file in your terminal.
    ```
    pip install -r requirements.txt
    ```
3. Run this in your terminal to install the `flaskner` module. (see the `setup.py` for details) 
    ```
    pip install .
    ```

4. Download the `spaCy` Named Entity Recognition model. Run this in your terminal: 
    ```
    python -m spacy download en_core_web_sm
    ```
