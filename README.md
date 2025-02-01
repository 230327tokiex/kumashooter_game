# Retro Bullet Hell Shooter - AI Generated Game

**Date: 2025/02/01**

This bullet hell shooter was generated in a single attempt using **o3-mini-high**. On its release day (2025/02/01), I tested it and was amazed by the result. (Take2 was just a simple button-link demo, but this final version – take3 – truly impresses!)  
In this version, the game balance has been adjusted so that, if left idle, the player will eventually lose. The player now has only 3 lives, making survival more challenging.

## Features

- **Complete bullet hell shooter in one HTML file**
- **Technical implementations:**
  - Object pooling for efficient bullet management
  - Collision detection system
  - Multiple bullet patterns for enemy attacks
  - Score and player lives system (player lives reduced from 10 to 3)
  - Visual effects (explosions, retro animations)
- **Retro-style design using emoji characters:**
  - **Player:** 🧸 (Teddy Bear)
  - **Enemy:** 🎃 (Evil Pumpkin)
  - **Player bullets:** 🍬 (Regular), 🍭 (Rare/Critical)
  - **Enemy bullets:** 💛, 💙, ❤️ (Various heart emojis)
- **Smooth animations** via requestAnimationFrame
- **No external dependencies** except Google Fonts (using the retro "Press Start 2P" font)
- **Balanced gameplay:**  
  If left idle, the barrage of enemy bullets will gradually reduce the player's lives, ensuring that victory requires active play.

## How to Play

1. Use the left and right arrow keys to move your teddy bear (🧸).
2. Avoid enemy bullets (hearts).
3. Your candies (🍬) are auto-fired.
4. Watch for rare lollipops (🍭) – these deal critical damage and can instantly defeat the enemy.
5. You have 3 lives to defeat the evil pumpkin (🎃). If you do nothing, the enemy's relentless attack will eventually lead to defeat.

## Technical Points of Interest

- Smooth animations with requestAnimationFrame.
- Efficient bullet management using an object pool.
- A robust collision detection system.
- Multiple enemy bullet patterns.
- Integrated visual effects and distinct game states (win/lose).

## Try It Out

Visit: [Deployment URL]

## About This Repository

This repository demonstrates advanced AI coding capabilities. The entire game was generated in a single attempt by GPT-4 Turbo (o3-mini-high) on 2025/02/01, showcasing the AI's ability to produce complex, functional code without iterative debugging. This final take (take3) now includes a balanced gameplay where, if left idle, the player will eventually lose due to a reduced life count (3 lives instead of 10).

## Notes

- The background music (BGM) uses a custom track created with SUNO.
- The game is contained entirely within a single HTML file for simplicity.
- No external dependencies are required except for Google Fonts.

## License

MIT License

Feel free to use this as a reference or starting point for your own projects!

---

# Retro Bullet Hell Shooter - AI生成ゲーム

**日付: 2025/02/01**

本ゲームは、**o3-mini-high** を用いて1回の生成試行で作成された弾幕シューティングゲームです。公開日である2025年2月1日に試作し、その出来栄えに感動しました。（Take2 はボタンリンクのみのデモでしたが、今回の最終版（Take3）は本当に素晴らしい仕上がりです！）  
今回のバージョンでは、ゲームバランスを調整し、放置状態ではプレイヤーが最終的に負けるようになっています。プレイヤーの残基は従来の10から3に変更され、より生存に工夫が必要となりました。

## 特徴

- **1つのHTMLファイルで完結する弾幕シューティングゲーム**
- **技術的な実装内容:**
  - 弾の管理にオブジェクトプールを採用
  - 当たり判定システム
  - 敵の攻撃パターン（複数の弾パターン）
  - スコアシステムおよびプレイヤーのライフ管理（残基を10→3に変更）
  - 爆発などのビジュアルエフェクトとレトロなアニメーション
- **レトロスタイルのデザイン（絵文字使用）:**
  - **プレイヤー:** 🧸（クマのぬいぐるみ）
  - **敵:** 🎃（悪のジャック・オ・ランタン）
  - **プレイヤー弾:** 🍬（通常）、🍭（レア/クリティカル）
  - **敵弾:** 💛、💙、❤️（ハート絵文字のバリエーション）
- **requestAnimationFrame によるスムーズなアニメーション**
- **外部依存は Google Fonts のみ**（レトロな "Press Start 2P" フォント使用）
- **ゲームバランス:**  
  放置状態では敵弾によりプレイヤーの残基が徐々に減少し、最終的に敗北します。プレイヤーは3回の被弾耐久しかないため、積極的な操作が求められます。

## 遊び方

1. 左右の矢印キーでクマのぬいぐるみ（🧸）を操作します。
2. 敵の弾（ハート）を避けてください。
3. プレイヤー弾（🍬）は自動で発射されます。
4. レアなロリポップ（🍭）に注目！ 命中すれば敵にクリティカルダメージを与え、即勝利となる場合もあります。
5. 悪のジャック・オ・ランタン（🎃）を倒すため、プレイヤーは3回の被弾耐久があります。何もしなければ、敵の激しい攻撃により敗北してしまいます。

## 技術的なポイント

- requestAnimationFrame によるスムーズなアニメーション
- オブジェクトプールを利用した効率的な弾管理
- 堅牢な当たり判定システム
- 複数の敵弾パターンの実装
- ビジュアルエフェクトとゲーム状態（勝利/敗北）の統合

## お試しください

公開URL: [Deployment URL]

## このリポジトリについて

本リポジトリは、高度なAIによるコーディング能力のデモンストレーションとして作成されました。2025年2月1日に o3-mini-high を用いて1回の試行で生成されたこのゲームは、反復的なデバッグなしに複雑かつ機能的なコードを生成できるAIの力を実証しています。今回の最終版（Take3）は、放置状態でもプレイヤーが負けるバランス調整（残基3に変更）を施し、より現実的なゲーム体験となっています。

## 注意事項

- BGMは SUNO で作成したカスタム音源（bgm.mp3）を使用しています。
- ゲームはシンプルさを重視し、1つのHTMLファイルで完結しています。
- 使用している外部依存は Google Fonts のみです。

## ライセンス

MIT License

このプロジェクトを参考に、ぜひご自身のプロジェクトにご活用ください！
