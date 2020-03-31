# Sankey Server Generator

You have a dataset to display a sankey but python's sankey tool isn't helping... This repo might be for you :)

You will be able in two steps to generateyour interactive sankey : pull the repo, add your data and launch a server.

```
git clone https://github.com/qdonnars/Sankey.git
mkdir data
cp path_to_data_to_display data/sankey.csv
python -m http.server 8000
```

You will then be able to acces the visalization on your browser http://localhost:8000/
