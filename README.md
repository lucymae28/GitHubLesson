# Yippee Analysis - yippee

A reproducible analysis of yippee from the yippee dataset, examining variation in yippee dimensions across yippees in the yippee Archipelago, Yippeeland.

<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAN8AAADiCAMAAAD5w+JtAAAAflBMVEX///8AAADt7e3g4OC8vLz5+fn29vZERETV1dXa2trw8PCioqK/v78HBwfLy8s5OTlYWFglJSV7e3tSUlKGhoYdHR1ycnJNTU1paWk1NTWYmJivr69cXFzPz8/X19cQEBCMjIynp6csLCwXFxd2dnaTk5MjIyNiYmJFRUWJiYnbvKbwAAAKw0lEQVR4nO2daZuyOgyGDZssAqKyKCqK2/j//+BpCqhI66gDhfNevT/NKEsfS9M2SctoJJFIJBKJRCKRSCQSiUQikUgkEolEIpFIJBKJRCLpEFvlYfddtL+hUBHKAnicFFXpu5BfoRvI7JwjB4DMZQAQ5sHYNgy97+J+jDOO43h+rurJNb0mWvFdHI/Tvov7EVY8nwZF2S8TjTJhHafjNyc8LJ/OY9Gl/BLP2RfNLYyiKPm9YqxL4tLj944qoHh/wiAP3RzLOl+vp4u3z4rWax/P2nlWl6X7K7YyoTWR+b5pfGIzyLH7YImnJsqAremxtCVT/fNeTbeV8uxhCtRt/0Arb0Nq7rtL2PoUL3CAfbtFawNrvUZ1wcT7UlxxlQ21TMvBCZzEtPGk2l8vpO5TFHi8DqnD36/wwToeN61cbTEbk75lN5hmqHsBmsz8Lw9mnVWGveFmEL2hoVJ5UasjSCfMwYXFEOYWXoYDsajdp8lW6cj07QFCdzhYDs1qvbHoVk4uPG77sp+ywEGH1l7Le8Ac43PRyaXfxglJGdKOTPkEjXKfZtROSZeeXzu7Pu1Ur72NuI20axvg4Q1mfdUgNXFOp7dQ6aio01vwQX2TbrsofXIm46JOb8ElJabT6dq86ZMlhL10g6kPudP9AMMg8/pw1vltmsxI7ytg/KQ7RGB2Ej6b2F7IEF/I+DBFz4zwkegcYC7oVtgNmaIrcCpwcLghAj1RNyuZwlHYM+OJ1xedQZxRs8kTGjP9350BcBH4i+qrA/x0O1KqoZAfVGxAhAxjBIYnTGJcxD4vSQi+KepmOmnw7bjK3sZeA/ii5rq0QxJ0rxJj/m/rw/GgL6qPJ/oEjKyfWMBhIWam6yXtxngU5wGu2ZokEIpx+M4gjHnVZ2hP/FqkbRGfrognGucxnEAuRt8CpryvlP1z+sdvz5R1aWSMcNyNEzinIiyMfYQ55ye2d43CwuxlQFYJm2dwBE4EWTXyg8ccfTNGYQ/Bmm/37JxxBmTMKBu6e7atKHjNFBJeO2DpI7g8gV7GPgF2jIONNBOkjzNz0FdFbSzSNN3XKoZ3Ka+sYnJCGj2ewPQomRmI8PXy9dHoOVywEPbPY3H3bLuglllpIf6zfzxhyuomyDR3J8CCcvWZ6E53f2gRlHHteUtZNkYprdEhwefXqZ2wZBxvrV34c/z7d3j6DGoKyz7KrutjurmrbJLCj1PX57PuYAd96lNpkwuoPt36XV9SfnUq/q3rg5xR40qf+uycZr+cqb6Nn/2qrzIoZfzpSd94aPqMot0UffMGngiaGS2lvmqAsx+2vnKc9UO7uk38rI9h8Ut9cUQfUM0ftr6yK8uxK9MY/TxXH9Y5OWX9dPxA9XF5oY+J1NcVHPui/uP6bKmvzmt9/tD0KS+Ly9CXvDo8ZEW+++3fL7zJHLJsuvMd5ty2qj7WLXrVNxq9Ki8rIZfhzKhwmR6efvUZPr+8zPnDlX/4jDlh7Ln+tnNueTWWP1E58Q6/sl1SYvStefoMrj5OzvmeV9kcj5uA+Z8xm515CUX65odZ3JwXKlTZT+iK4zxWj1nn+kgvl+y4N9F2x2Zx8z3XP6g+LwtMTqfTjufExUmXAH0vA5vW+GniHviv4vS2X2P5MuZtZhB0HRS3fw8djQ/hnRZ/cEMT4B/EUdjq9SF6jfZujf75zv27b+jrCk9IfCVdQi4wU+PO3hcSH0PHZh/piiNiakXEN41VAHOxuSEUbw2ZmPg0ZtYJT+czYzgcxeRP0FGY6Jz2g7h0TGwJovXpAcCPqJth3GcutA3acxcW4lbLqTgzFZhfp0aCe13cLkNcfuQWPTVrsQmu0wzmglLsLJQXi16FtAjB/6hFGBuzxubNDC91DeCOhS+TM2bkR/3EijZCZu8ZKBroXvawxApnsocParCh762Zk4JOq3EfS+QUTFI+vy9Qf96Y6I1HzstR3qWnNZyYUNTSknc2G+riFmw572wxZHvROnOJeHj947GHwXyJOh67xLh10jr0jYneuLjf9cUjGnTw2p9N0LWvh7z3LYsM9EEHbQs0bLr29WT0v4GBjXkrWctWZhXgnginQeywQZ3Q86TF4W+ULDEAOJTNpuyVQ2afwa6Vi2mzBXXan/uzmgyuuD2d1sJaarNKg1l6kzq/J6p3SeLjPhR/c0+SAY7Cj7DBtd+NtWj+y9fLgG1CY4D6TNCrQJpfMPvQotsFqu9mWQYuJkvqTGjsOzftHndl8tDKzNef/MjbuKTYn49MCnlnm3QSH4/7GosimoZpgz/vCNxM18g9zfCkpelrj842Pb09aeyKPU5nTvsXUR7L2RPSKsHQvSSUyzvWUSVVOOt3f8IiizNBe/7YEO9m/iZsisyTj9qTkbiQCF5Y+YRJpxRI+jCVrZlBGqmdjr4KD+a9b8mkGGUaU3bfj7ae2GQqyHdXd4UuM2ZjK4o9eeq6PFu58ZdrG6QJBm0V9A8YpqlGEFuVM7C1bisivWBb1/obq3EXER/vMhR9OSxPHVx2BWHa/6yX4EMnG4etoIe12yz8bnYOczLI/mV9hvdv6xtZUp8QpL7vkPrEIPV9h9QnBqnvO6Q+MUh93/E/0HcMA76XyMpvMPdtHY4+7vz2wt4/Y0SdvY8LxXOGwOHoG/PewpFw9FWRMMe5QH5ylkxf2VD0LfkZxWx99h7WEdaggZtR/Bgjx2f5ktSB6IvO3G222PosgFsUwqHrpx2GPnU/EH2jGU+fsmbqU+G+vKjQt2LskrKCoeszcBujN/U1Y7bOUPxnRN+a+Tld5slYH93UdwI4POmbEaNqDePVOjM4sxeSo75D84UmTX3WDMKnwyKAc9sF/RIM9bE+L5fpNiKaTX2jCUNf0MvqLgYYzGV9TvT58+/19R4fu5GCqzKaCtF32nypT72IW8byK5jiyAjFE30770t9GWTcvSuF04G+nLf0vw9w23G+vjfsJy659WtXyPtaHMvEZNTSTV/0lOmBu94y9Lm1fIlh6WNviFjqe17/4EBj/Dkyp0+ps4PTx9gYBfVZcSMVCfXdIrOlPpwsPOjTrfOg9JnAWkZH9C2wsTH03eq00mfV9OFmtkPShzmFzdFGpe9JOdVXfba663vIXVeCgekjKg6NJINK36EuneorPtNP2U0fhPfD1KCzd519ByZmNb1M00IfMPQV1bMIqiVjRnq+H6aK2d/0A4zVsqHPmIXkM8M5g18TSPQ5SxgfkygizSwsd/lWc/BLE2WRQet1IDn1FUbc0KfkxQYPS4DL4+dE3+iWDxpWW+ioZ9JT4h+ehot+h/b2ZjtubCatLAsrkoS1F6cpZDqlR2U67/hWs8o6g8vG8zy6rcxnK0YFgK+luNQ/IvroA2dEtYV9O3CzkVHxYDOJsIymILq5L2L7689Qkmd9hl/2+WQ89uDAuMIPs3LuO5z7ytBqD4mIisdlEcptTGMcAe7vIbjyNn2/JckOZ+LwiBpB+NDOPPLArsqSLsiTdykFLnwYD6prexvMer9tbELfqFnl+BfrM3H8ZRDjuRb7wqHWwNcgQrkWbIOK4puV8PCr40TT0sPABl6fQHOVr7QFYXZ9+JC9aT5kZv9v9Y22ZDziZkWeuVt3XKvVPmJuF7mwgtC391p67u2tku0wreObeDeG2IVJJBKJRCKRSCQSiUQikUgkEolEIpFIJP8c/wFbYZWLBYISNAAAAABJRU5ErkJggg==" width=50%>


## About the Data

This project uses data collected by [Dr Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) at the [Palmer Station Long Term Ecological Research](https://pallter.marine.rutgers.edu/) site in Antarctica.

**Species studied:** Gentoo, Chinstrap, and Adelie penguins. 

**Research location:** [TODO: Which three islands were the penguins observed on? Hint: check the `island` column in `data/penguins_raw.csv`]

**Sample size:** [TODO: How many penguins are in the raw dataset? Hint: look at how the analysis script checks this]

**Years of data collection:** [TODO: What years were data collected? Hint: check the `year` column in the CSV]

## Variables Measured

The dataset includes the following morphological measurements:

| Variable | Range |
|----------|-------------|
| `bill_length_mm` | [TODO: Include range] |
| `bill_depth_mm` | [TODO: Include range] |
| `flipper_length_mm` | [TODO: Include range] |
| `body_mass_g` | [TODO: Include range] |

## What the Analysis Does

The R script `run_analysis_SOLUTIONS.R` performs the following steps:

1. **Data cleaning** -- [TODO: What does the cleaning step do to handle missing values? Hint: look at section 3 and 4 of the script]
2. **Exploratory boxplots** -- [TODO: Which variable is plotted against species in the first boxplot? Hint: look at section 5]
3. **Cluster analysis** -- [TODO: Which two measurements are used to show how species cluster? Hint: look at section 7]
4. **Regression analysis** -- [TODO: What relationship does the regression plot examine? Hint: look at section 7]

## Plots Produced

The analysis generates a multi-panel figure combining four plots:

- **Top left:** [TODO: What does this plot show?]
- **Top right:** [TODO: What does this plot show?]
- **Bottom left:** [TODO: What does this plot show?]
- **Bottom right:** [TODO: What does this plot show?]

## Project Structure

```
penguin-analysis/
├── README.md              ← You are here!
├── .gitignore             ← [TODO: What does a .gitignore file do?]
├── data/
│   └── penguins_raw.csv   ← [TODO: Describe this file in one sentence]
├── functions/
│   ├── plotting_functions.R  ← [TODO: Describe what this file contains]
│   └── saving_functions.R    ← [TODO: Describe what this file contains]
└── run_analysis_SOLUTIONS.R  ← [TODO: Describe what this file does]
```

## How to Run

1. Open `run_analysis_SOLUTIONS.R` in RStudio
2. Install required packages: `tidyverse`, `janitor`, `palmerpenguins`, `patchwork`
3. Run the script from top to bottom
4. Outputs are saved to the `figures/` folder

## Data Source

Horst AM, Hill AP, Gorman KB (2020). *palmerpenguins: Palmer Archipelago (Antarctica) penguin data.* R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/

## Authors

Lucy Bradbury :))


