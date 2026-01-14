# VillagerBall - 村人捕獲プラグイン

> ⚠️ **α版（アルファ版）** - このプラグインは現在開発中です。バグが存在する可能性があります。

村人をモンスターボール風に捕獲できるプラグインです。

## 概要

村人を特殊なボールで捕獲してアイテム化！どこでも解放可能。取引データや職業を保持したまま村人を安全に移動できます。

## ⚠️ α版について

- 機能が不完全な場合があります
- バグが存在する可能性があります
- 問題を発見した場合は [Discord](https://discord.gg/zYY55dzhjd) でご報告ください

## ダウンロード

[Releases](https://github.com/henntekosennsi1-rgb/VillagerBall/releases)

## 主な機能

- 村人をボールで捕獲
- どこでも解放可能
- 取引データ・職業・レベル等を保持
- 捕獲成功率の設定
- 職業別の捕獲率設定
- エフェクト・クールダウン設定

## 使い方

| アイテム | 説明 |
|---------|------|
| **空のボール** | エンダーパール（光彩付き） |
| **村人入りボール** | エンダーアイ（村人データ入り） |

- 空のボールで村人を右クリック → 捕獲
- 村人入りボールで地面を右クリック → 解放

## コマンド

| コマンド | 説明 |
|---------|------|
| `/villagerball give [player]` | ボールを付与 |
| `/villagerball reload` | 設定再読み込み |

エイリアス: `/vb`, `/vball`

## 権限

| 権限 | 説明 | デフォルト |
|-----|------|----------|
| `villagerball.admin` | 管理コマンド | op |
| `villagerball.use` | ボール使用 | true |
| `villagerball.capture` | 捕獲 | true |
| `villagerball.release` | 解放 | true |

## 動作環境

- Spigot/Paper 1.21.x
- Java 17以上

## コミュニティ

**Discord:** https://discord.gg/zYY55dzhjd

## ライセンス

All Rights Reserved
