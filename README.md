Lounch the server :
In order to lounch the server we recomand to use a http python one. Run the following command in the main directory :

```
git clone https://github.com/qdonnars/Sankey.git
mkdir data
cp path_to_data_to_display data/sankey.csv
python -m http.server 8000
```

You will then be able to acces the visalization on your browser http://localhost:8000/
