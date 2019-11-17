eecs731-final_dota
==============================

Investigating the International

Defense of the Ancients 2, or DotA2, is one of the most popular Electronic Sports (Esports) in recent years.  Every year, The International is held which serves as the NCAA Basketball tournament in the world of DotA2.  Similar to NCAA, DotA2 has a "season", but rather than traditional collegiate basketball where teams play a series of games against set opponents, DotA2 has a season of preliminary tournaments where teams are awarded prize pools based on placement, as well as invitation to The International.  The International has one of the largest prize pools in all of Esports, exceeding 20 million dollars each of the last 4 years.  Esports are growing in popularity and market value.  Similar to traditional sports betting, Esports betting has exploded.  


Our project aims to utilize open source data sources to collect seasonal tournament data, along with previous International data. By performing feature engineering of various data sources, we hope to provide a variety of techniques to estimate success of a team and to predict the outcome of future International's.  Specifically, we would like to perform Regression analysis on a given matchup to determine a victor with a percentage determination, and we would also like to frame the problem as a Classification problem and run simulation to determine our prediction.  Additionally, should time permit, we'd like to explore forecasting to see if we can make very early predictions of season outcomes.

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
