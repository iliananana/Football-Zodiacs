# Football-Zodiacs
A program to get the zodiac sign of tier 1 &amp; 2 players, designed to help you draft a fantasy football team based on player's astrology charts.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install [kerykeion](https://pypi.org/project/kerykeion/) & [pandas](https://pandas.pydata.org/).

```bash
pip3 install kerykeion
pip3 install pandas
```

## Usage
Provide a csv file containg players and their birthdays with the following headers:

| name | year | month | day | position | tier |
|------|------|-------|-----|----------|------|


Program will return a csv with the player's sun, moon, and rising signs.

| name | position | tier | sun_sign | moon_sign | rising_sign |
|------|----------|------|----------|-----------|-------------|

When ranking players based on their zodiacs, use your own judgment and intuition, and be sure to research how their sun, moon, and rising signs may be influenced by the current season.
