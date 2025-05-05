# plan-sim
携帯プラン料金比較シミュレーター

# 📱 plan‑sim

携帯キャリアの **料金比較シミュレーター**  
必要なギガ数・通話分数・割引条件を入力すると、  
「現行プラン」と「比較プラン」の月額を計算します。

---

## ✅ ゴール

- **公開 URL** で誰でも試算できる Web アプリ
- プラン料金は毎日公式情報から自動更新
- API とフロントエンドを別レポに分けず、この repo で一括管理

## 🛠 スタック

| 層 | 技術 |
|----|------|
| API | FastAPI (Python 3.11) |
| DB | Supabase/PostgreSQL |
| フロント | Next.js + TypeScript + TailwindCSS |
| デプロイ | API: Fly.io ／ Front: Vercel |
| テスト | pytest + GitHub Actions |
| インフラ監視 | Upptime (Actions) |

## 📂 ディレクトリ構成（予定）


## 🚧 ロードマップ

- [ ] フェーズ0 README 作成（いまココ）
- [ ] フェーズ1 ローカル API MVP
- [ ] フェーズ2 自動テスト
- [ ] フェーズ3 Docker 化 …

