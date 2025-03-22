## 画像圧縮
ffmpeg を使い以下を実行
```
mkdir generated
for f in **/*.jpeg; do ffmpeg -i "$f"  -q:v 18  ./generated/"$f"; done
```
