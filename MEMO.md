# メモ

物理的な準備: OAK-1をUSBでつなげる、以上

必要パッケージインストール（どちらの手順でも良さげ）

```text
git clone https://github.com/luxonis/depthai.git
cd depthai
```

https://github.com/luxonis/depthai#installation

---

デモプログラム1

```text
python3 depthai_demo.py -gt cv -cnn <学習済みモデル名>
```

例

```text
python3 depthai_demo.py -gt cv -cnn person-detection-retail-0013
```

---

デモプログラム2

```text
git clone https://github.com/ureuzy/depthai-experiments.git
cd depthai-experiments/gen2-people-counter
```

```text
python3 main.py -cam
```

(人検知数をprintし続けるだけの変更を加えました)
