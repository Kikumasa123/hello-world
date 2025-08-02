# GitHub Flow 実践リポジトリ

このリポジトリは GitHub Flow を実行するためのリポジトリです。

## 📋 概要

GitHub Flow は軽量でブランチベースのワークフローです。このリポジトリを使用して、GitHub Flow の実践方法を学習できます。

## 🔄 GitHub Flow とは

GitHub Flow は以下のステップで構成されています：

1. **ブランチの作成** - `main` ブランチから新しいブランチを作成
2. **変更の追加** - ファイルの追加、編集、削除を行う
3. **プルリクエストの作成** - 変更をレビューのために提出
4. **レビューと議論** - チームメンバーとの協議
5. **デプロイとテスト** - 変更をテスト環境で確認
6. **マージ** - `main` ブランチに変更を統合

## 🚀 使い方

```bash
# 1. リポジトリをクローン
git clone <repository-url>
cd <repository-name>

# 2. 新しいブランチを作成
git checkout -b feature/your-feature-name

# 3. 変更を加える
# ファイルを編集...

# 4. 変更をコミット
git add .
git commit -m "Add: 機能の説明"

# 5. ブランチをプッシュ
git push origin feature/your-feature-name

# 6. GitHub上でプルリクエストを作成
```

## 📚 参考リンク

- [GitHub Flow 公式ガイド](https://guides.github.com/introduction/flow/)
- [Git 基本コマンド](https://git-scm.com/docs)

## 🤝 コントリビューション

1. このリポジトリをフォーク
2. 機能ブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add: 素晴らしい機能'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

---

**Happy Coding! 🎉**
