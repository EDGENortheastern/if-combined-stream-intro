# Introduction to Streamlit

[Streamlit](https://docs.streamlit.io/) is a Python framework designed to help you build interactive web applications using only Python. It removes the need for HTML, CSS, or JavaScript, allowing you to focus entirely on the logic of your data project while Streamlit takes care of the interface. When you run a Streamlit script, the framework automatically renders your text, widgets, charts, and dataframes as a functioning web application inside your browser.

The central idea behind Streamlit is that an app is simply a Python script that runs from the first line to the last every time the user interacts with it. This approach creates an interface that feels instant and responsive without requiring you to manage internal state or callbacks. 

To run the project locally you will need to:

1. Clone the repo to your local:

```bash
git clone https://github.com/EDGENortheastern/if-combined-stream-intro.git
```

2. Create a virtual environment on a Mac

```bash
python3 -m venv venv
```

or on Windows:

```bash
python -m venv venv
```

3. Activate the virtual environment on a Mac

```bash
source venv/bin/activate
```

or on Windows

```bash
venv\Scripts\activate
```

4. Install Streamlit

```bash
pip install streamlit
```

5. Run the app and see it in the browser

```bash
streamlit run app.py
```
