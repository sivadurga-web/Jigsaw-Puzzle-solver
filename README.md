# Digital Image Processing Course Project
## Paper Title: [A Genetic Algorithm-Based Solver for Small-Scale Jigsaw Puzzles](https://link.springer.com/content/pdf/10.1007%2F978-3-030-53956-6_32.pdf)

### Directories:
```
|_ Images: Contains supporting image files for the GUI and code to execute
|_ Code: Mainstream Genetic Algo code
|_ Test_Photos : Sample Images for testing 
|_ Old: Previous files. (Not required)
|-- GUI.py: Wrapper UI for Genetic Algo implementation
|-- guidelines.md: Guidelines for the project
```

### Setting up the environment:

```bash
$ cd Code
$ pip3 install -r requirements.txt
$ sudo apt-get install python-tk
```

Install project in editable mode:

```bash
$ pip3 install -e .
```

### Running the GUI:
- Firstly execute the GUI file with following command from head directory.
```
python3 GUI.py
```
- Select an input image by clicking on the ```Input Image``` option.
- Once the image is loaded, enter the Population, Generation and size of each piece in the puzzle creator in the respective entries and press ```<Return>``` (Enter) after each entry.
- Click on ```Puzzle``` to create a puzzle of given input image.
- Finally click on ```Solve``` to solve the puzzle using Genetic Algo.
- Formed image can be saved using ```Save Image``` option. 
