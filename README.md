# Album Manager GUI

This is a graphical user interface (GUI) application for managing a list of music albums. The user can add, remove, and update albums, and view the list of all albums. The application is built using PyQt5 and stores the list of albums in a file called 'cdmethods.json'.

Fun fact: Majority of the code is written by chatGPT, including the readme.md.

## Prerequisites

- PyQt5
- json

## Installation

1. Clone the repository

git clone https://github.com/joeraven0/album-manager-gui.git


2. Install the dependencies

pip install pyqt5 json


3. Run the script

python musicGUI.py


## Usage

1. Enter the artist, title, year, and number of copies in stock for the album you want to add.
2. Click the "Add album" button to add the album to the list.
3. To remove an album, select the album in the table and click the "Remove album" button.
4. To update an album, select the album in the table, make the necessary changes in the input fields, and click the "Update album" button.
5. To view the list of all albums, click the "Print All Albums" button.

## License

This project is licensed under the [MIT License](LICENSE).
