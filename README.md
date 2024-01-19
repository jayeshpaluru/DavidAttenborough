Setup a virtual environment:

```bash
python3 -m pip install virtualenv
python3 -m virtualenv venv
source venv/bin/activate
```

Then, install the dependencies:
`pip install -r requirements.txt`

## Run it!

```bash
python capture.py
```
In one terminal. In the other, run the narrator, make sure your OpenAI API Key is included in your code:

```bash
python narrator.py
```

