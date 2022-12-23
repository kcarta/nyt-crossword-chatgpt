# GPT-3 Crossword Solver Experiment

*This README was generated by a language model trained by OpenAI and edited by a human.*

Welcome to the GPT-3 Crossword Solver Experiment! This repository contains a Python script, `app.py`, that was generated by [GitHub Copilot](https://github.com/openai/copilot) (powered by OpenAI's GPT-3) to see if GPT-3 could be used to solve the [New York Times Mini Crossword](https://www.nytimes.com/crosswords/).

This script is designed to generate crossword puzzle answers for clues from the New York Times. It does this by using the OpenAI API to generate answers based on a prompt for each clue.

## Requirements

- Python 3.6 or higher
- [OpenAI's GPT-3 API key](https://beta.openai.com/signup/show)
- Set your OpenAI API key as an environment variable named `OPENAI_API_KEY`

## Usage

To use this script, run the following command in your terminal:

`python app.py`

The script will first retrieve crossword data from the New York Times website, then generate prompts for each clue based on the clue text and the number of letters in the answer. It will then send these prompts to OpenAI and retrieve the generated answers. Finally, it will print out the clues along with the answers, grouped by direction (across or down).

## Modifying the script

You may wish to modify the script to customize its behavior. Here are some suggestions for ways you could do this:

- Change the temperature and frequency/presence penalties used when generating answers from OpenAI. These parameters control the creativity and uniqueness of the generated answers.
- Modify the formatting of the output. For example, you could print the clues and answers in a table, or add additional information such as the position of the clue in the crossword grid.
- Add additional functionality, such as saving the clues and answers to a file or integrating with a crossword puzzle solving tool.

## Dependencies

This script requires the following Python packages:

- requests: used to make HTTP requests to retrieve the crossword data from the New York Times website
- json: used to parse the JSON data retrieved from the New York Times website
- os: used to access environment variables
- openai: used to access the OpenAI API

## Example Output

Here is an example of what the output of the `app.py` script might look like:

```
Across:
1. Fast plane: JET
3. "___ on a Grecian Urn": ODE
4. Ointment ingredient: ALOE
5. Picket line crosser: SCAB
7. Exclamation of surprise: OHO

Down:
2. Actress ___ Pataky: ELSA
3. Certain test taker: EGG
6. "Jaws" actor: ROY
8. Classic arcade game: PACMAN
```

Please note that the answers shown above are just an example and may not necessarily be the correct answers for the actual crossword puzzle.

## Disclaimer

Please note that this experiment is for educational and entertainment purposes only. The New York Times Crossword is a copyrighted work and it is not permitted to distribute solutions or unauthorized copies of the puzzle.

## Credits

- The Python script, `app.py`, was generated by [GitHub Copilot](https://github.com/openai/copilot) (powered by OpenAI's GPT-3)
- This README was generated by a language model trained by OpenAI.

---

*This README was edited and merged by a human.*
