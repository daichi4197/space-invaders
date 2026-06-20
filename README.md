# Space Invaders ゲーム（Python/Pygame）

Pythonの**Pygame**ライブラリを使用した、シンプルな**Space Invadersスタイルのシューティングゲーム**です。

YouTube動画【Pygame超入門】の学習成果として開発しました。

## ゲーム説明

自機を操作して、上から降りてくる敵を撃ち落とすゲーム。敵を撃ち落とすとスコアが加算されます。

## 遊び方

| キー | 動作 |
|------|------|
| **← 左矢印** | プレイヤーを左に移動 |
| **→ 右矢印** | プレイヤーを右に移動 |
| **スペースキー** | 弾を発射 |

## セットアップ

### 必要環境
- Python 3.7以上
- pygame

### インストール

1. リポジトリをクローン
```bash
git clone https://github.com/daichi4197/space-invaders.git
cd space-invaders
```

2. 依存パッケージをインストール
```bash
pip install -r requirements.txt
```

3. **画像・サウンドファイルを配置**（⚠️ 重要）
   - `assets/` フォルダに以下のファイルを配置してください
   - player.png（自機画像）
   - enemy.png（敵画像）
   - bullet.png（弾画像）
   - background.wav（BGM）
   - laser.wav（発射音）

### ゲームを実行

```bash
python main.py
```

または、カスタマイズ版を実行：
```bash
python custom_game.py
```

## ファイル構成

```
.
├── README.md           # このファイル
├── requirements.txt    # 依存パッケージ
├── main.py            # シンプル版ゲーム
├── custom_game.py     # カスタマイズ版ゲーム
└── assets/            # ゲーム素材（画像・音声）
    ├── player.png
    ├── enemy.png
    ├── bullet.png
    └── sounds/
        ├── background.wav
        └── laser.wav
```

## 参考

このプロジェクトは以下のYouTube動画を参考に学習・開発しました。

- **【Pygame超入門】50分でゲーム開発（Python）の基礎をマスター**
  https://www.youtube.com/watch?v=fAJ_BjLd3Ro

## ライセンス

MIT License

## 画像について

このプロジェクトのカスタマイズ版（custom_game.py）で使用している画像ファイルはプライベート素材のため、GitHubには含まれていません。

シンプル版（main.py）で遊ぶ場合は、フリー素材のゲームアセットをダウンロードして `assets/` フォルダに配置してください。
