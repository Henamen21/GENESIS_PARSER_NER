# NAMED ENTITY RECOMMENDATION (NER) FOR GENESIS BOOK

Extract Information from the book of genesis using Named Entity Recognition. The annotation is done by using [doccano](https://github.com/doccano/doccano) annotation.


## Installation


Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.
If you are using google colab, install the following packages directly to the notebook
```
!pip install spacy
!pip install spacy-transformers
```
For using in local computer, first download requirment.txt the run the following

```
pip install -r requirements.txt
```

## Usage
Annotate using Doccano Annotation

```bash
# download doccano file
git clone https://github.com/doccano/doccano.git
```
```bash
Initialize database.
doccano init
```
```bash
# Create a super user.
doccano createuser --username admin --password pass
```
```bash
# Start a web server.
doccano webserver --port 8000
```
```bash
# Start the task queue to handle file upload/download.
doccano task
```
```bash
# run the following address
http://127.0.0.1:8000/
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Connect With

[medium blog](https://medium.com/@heneyr24/named-entity-recognition-for-the-book-of-genesis-d08ae157a385)

[linkedin](www.linkedin.com/in/henok-solomon-a9070329a)

[EMAIL](mailto:hencoktok@gmail.com)
