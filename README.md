# Loan_Qualifier_App
This is a simple command line loan qualifier app that streamlines and automates the process of finding loans for potential borrowers. This app collects borrower and loan attributes, pulls in data from a daily rate sheet and matches the user to loans that he/she would qualify for. If there are any matching loan programs, the user is also given the option to save the list of loans in a csv file after entering a path and name for the file.

---

## Technologies

This program was written in python 3.7. It uses the following libraries:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Use the following code to install the packages required for the app.

```python
  pip install fire
  pip install questionary
```
Then clone the repository and navigate to the directory where you cloned the repository to run the program.

---

## Usage

Run the **app.py** with:

```python
python app.py
```
The following prompts will display successivly to collect the user input.

![loan_qualifier_screenshot](https://user-images.githubusercontent.com/94941017/172275589-f2dbdbf5-ef18-4045-9d20-781e3bb1a11c.png)

Final results are output to a csv file.

---

## Contributors

Rachael Donham
rachaeldonham@gmail.com


---

## License

MIT
