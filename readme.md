# Building  a portfolio
We will use mkdocs for building a portfolio.Mkdocs is  static  site generator that is geared towards projects documentation. It is written in python and uses that Jinja2 templateing engine. Mkdocs is easy to use and has a lot of features that make it w good choice for building a portfolio.

Link to the doumentation is [here]: https://www.mkdocs.org/


## 1. Install mkdocs 
``` bash
conda create -n mkdocs python=3.10.11 -y
conda activate  mkdocs
pip install mkdocs
```

## 2. Create a new mkdocs project 
```bash
mkdocs new My_Portfolio
cd  My_Portfolio
```

## 3. Run the development server
```bash
mkdocs serve
```
error:if found error in yml file then see that you are in your My_Portfolio folder.

> This is how you can specify the port and host 
```bash
mkdocs serve -a 127.0.0.1:8501
```

## 4. Build the project
```bash
mkdocs build
```
