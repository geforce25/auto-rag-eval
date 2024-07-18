# TODO
* [x] the original file `pyproject.toml` doesn't follow any proper standard. Rewrite
it to properly use `poetry` for installing dependencies
* [ ] create a proper `requirements.txt` file

# Bugs
* [ ] the dependencies can't be installed correctly when running `poetry install`
* [ ] running the StackOverflow preprocessing script doesn't output the JSON file in the
 correct place
* [ ] the JSON file created by the StackOverflow preprocessing script is not 
proper JSON
* [ ] the shape of the JSON file created by the StackOverflow preprocessing 
script does not match what is expected by the exam generator