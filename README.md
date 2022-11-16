# youtube_scrapper
Little Youtube scrapper made in Python with BeautifulSoup

# RUNNING PIP
```pip install --upgrade pip```
```pip install -r requirements.txt```

# RUN THE SCRIPT
The script is made to run in the terminal, so you need to run it with the command:
```python3 scrapper.py --input input.json --output output.json```

# RUN THE TESTS
The tests are made with pytest, so you need to run it with the command:
```python -m pytest tests/```

# CODE COVERAGE
The code coverage is made with pytest-cov, so you need to run it with the command:
```pytest --cov=. tests/```