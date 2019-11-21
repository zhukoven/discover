## 👋 Hi there, welcome to Discover! 💡

Discover is an optimization tool built to work with Rhino Grasshopper. It is being developed by [Colidescope](https://colidescope.com) as free software with the goal of promoting performance-driven automated design workflows in the architecture, engineering, and construction industries.

## Working with Discover

To get started with Discover, please download the latest stable release and follow the instructions here: [https://colidescope.com/discover](https://colidescope.com/discover)

## Build instructions

If you'd like to tinker with the source code and test the latest build of Discover, you can compile it yourself from the source code hosted here. To start, clone, fork, or download a .zip file of the `master` branch of this repository. Discover is developed on Windows 10 using [Python 3.7.x](https://www.python.org/downloads/release/python-375/). It may work on other systems but has not been tested.

### Running the server

1. Open a command prompt and `cd` into the root folder of Discover.
2. Run `python -m venv env` to create a new virtual environment.
3. Run `.\env\Scripts\activate.bat` to activate the virtual environment.
4. Run `pip install -r requirements.txt` to install all Python dependencies.
5. Run `python server.py` to start the server.

### Compiling the front-end app

1. Instal Node JS (https://nodejs.org/dist/v10.16.0/node-v10.16.0-x64.msi).
2. Install angular CLI (Run `npm install -g @angular/cli` from command window).
3. Run `npm install` from command window, in the root folder of the angular app.
4. Run `ng serve` from command line, in the root folder of command window.
5. Open a web browser and go to http://localhost:4200
