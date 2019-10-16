# Spotify's Music Analysis
This project aims at finding the similar music taste among different countries. This is quite similar to the function of "Your discover weekly" which compares the user's similar music taste in order to predict a list of songs that the user probably likes. The other two questions were also answered in this analysis:
- Which country has the most similar taste with the global music?
- Does HK anti-extradition protest affect the users from HK listening to more upset songs?

# Installation
```
Install jupyter notebook (please see https://jupyter.org/install for the details)
```

# Required libraries
```
pip install pandas
pip install spotipy
pip install fycharts (https://github.com/kelvingakuo/fycharts)
pip install matplotlib
pip install seaborn
```
# Run
```
git clone https://github.com/miki-lwy/notebooks
cd notebooks
jupyter notebook
```

# Limitation of this project
- Spotify Web API does not provide top songs for each region/ country
- Spotify chart is the only alternative
- Spotify chart only provides information:
    1. Top 200 daily/ weekly
    2. Top 50 viral daily/ weekly
- Dataset is small 

