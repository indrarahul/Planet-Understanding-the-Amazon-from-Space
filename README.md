# Planet-Understanding-the-Amazon-from-Space

You can download dataset from Kaggle. Let's see how to do this by using the [Kaggle API](https://github.com/Kaggle/kaggle-api) as it's going to be pretty useful to you if you want to join a competition or use other Kaggle datasets later on.

First, install the Kaggle API by uncommenting the following line and executing it, or by executing it in your terminal.
```
pip install kaggle --upgrade
```

```
kaggle competitions download -c planet-understanding-the-amazon-from-space -f train-jpg.tar.7z -p {path}  
kaggle competitions download -c planet-understanding-the-amazon-from-space -f train_v2.csv -p {path}  
unzip -q -n {path}/train_v2.csv.zip -d {path}
```
