### project structure

```
.
├── data/
│   ├── dataset.csv
├── data_pipeline/
│   ├── loader
│   ├── output
│   ├── processor
│   ├── validator
│   ├── utils
├── src/
│   ├── init
│   ├── cache
│   ├── database
│   ├── middleware
│   ├── models
│   ├── storage
│   ├── utils
├── tests/
├── main.py
├── streamlit_app.py
├── requirements.txt
├── README.md
```

### important notes
the file structure and functions should follow the mp3 file structure loosely but be modified to adapt to the new dataset. the dataset will be processed as a dataframe and stored in a sql database so any functions that expect a json should be modified. additionally, any api endpoints that aren't necessary can be removed.
