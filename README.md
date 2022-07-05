# labelme_json_to_png
## Setup
```
pip install -r requirements.txt
```

## Usage
```
python labelme_json_to_png.py <Labelme JSON file directory.> -o=<output directory> -label_file=<label file>
```

### Label file format(Example)
Exclude background.
labelmeで割り当てた、ラベルを定義する。
```
aeroplane
bicycle
bird
...
```

## サンプルコマンド（自分用）
```
python labelme_json_to_png.py "json" -o="output" -label_file="label_names.txt"
```
