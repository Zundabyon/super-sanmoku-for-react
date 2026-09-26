# SUPER GOMOKU for React

> 三目並べを「Super 五目並べ」に育てながら学ぶ JavaScript / React / TypeScript

## About

**SUPER GOMOKU for React** は、React公式Tutorialのゲームを出発点に、React / TypeScript / JavaScriptをグループで学ぶためのプロジェクトです。

単にReactのAPIをできるだけ多く使うことは目的にしません。

React公式ドキュメントで学んだ概念について、

- Super Gomokuではどこに適用できるか
- その設計にする理由は何か
- あえて使わない方がよい場合はなぜか
- そのコードのどこがReact / TypeScript / JavaScriptなのか

をチームで考えながら、普通のゲームを少しずつ **SUPER GOMOKU** に進化させます。

## Goal

このプロジェクトのゴールは、React Tutorialを「完走する」ことではありません。

**Reactのコードについて、なぜそう書くのかをReact・TypeScript・JavaScriptの観点から説明し、その知識を使って自分たちで機能を設計・追加できるようになること**を目指します。

## How We Learn

1. React公式Tutorialをベースにゲームを実装する
2. 実装に登場したReact / JavaScript / TypeScriptの概念を整理する
3. React公式ドキュメントを読み、Tutorialだけでは登場しない概念も学ぶ
4. 各概念をSuper Gomokuへ適用すべきかチームで検討する
5. 必要な機能を設計・実装する
6. PRレビューで「何を使ったか」だけでなく「なぜそうしたか」を説明する

## React Coverage

React公式ドキュメントの内容について、Super Gomokuとの対応を整理していきます。

| Concept | Super Gomokuでの候補 | Decision | Why? |
| --- | --- | --- | --- |
| Components | Board / Cell / Game など | TBD | |
| Props | 盤面・イベントの受け渡し | TBD | |
| State | 盤面・手番・ゲーム状態 | TBD | |
| Conditional Rendering | 勝敗・ゲーム状態の表示 | TBD | |
| Rendering Lists / key | 手の履歴など | TBD | |
| Sharing State | Board / Game間の状態管理 | TBD | |
| Reducer | 複雑になったゲーム状態 | TBD | |
| Context | プレイヤー設定など | TBD | |
| Effects | 外部システムとの同期が必要なら検討 | TBD | |
| Refs | DOM操作等が本当に必要なら検討 | TBD | |
| Custom Hooks | ゲームロジック等の再利用 | TBD | |
| TypeScript | Props / State / Action等の型付け | TBD | |

`TBD` は「必ず使う」という意味ではありません。

**使わないと判断した理由も成果物の一部**とします。

## Development Principle

**Don't use React features just to check a box.**

Reactの機能を無理に五目並べへ詰め込むのではなく、まず問題を考え、その問題に対してReactの機能が適切かを判断します。

その結果、五目並べにランキング、設定、履歴、複数画面などが生えてきたら――それがSuperということで。

## Tech Stack

- React
- TypeScript
- Vite

詳細は学習・設計を進めながら決定します。

## References

- React Tutorial: `https://react.dev/learn/tutorial-tic-tac-toe`
- React Learn: `https://react.dev/learn`
- Using TypeScript: `https://react.dev/learn/typescript`
