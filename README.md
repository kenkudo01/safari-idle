# 🐾 Safari Simulation Game
Java / LibGDX / Group Project

---

## 📌 Overview
本プロジェクトは、ELTE の *Software Technology* の課題として  
Java と LibGDX を用いて開発した **サファリ箱庭シミュレーションゲーム** です。

動物の行動シミュレーション、レンジャー・ポーチャーの移動、  
ランダム地形生成、UI 操作などを実装しています。

---

## 🎮 Features
- 🦁 **動物 AI シミュレーション**
- 👮 **レンジャーが選択された動物へ移動し削除**
- 🏹 **ポーチャーがランダム移動・特定動物を攻撃**
- 🎛 **UI メニューで動物選択・削除・速度変更**
- 📐 **MVC アーキテクチャ**
- 🧪 **JUnit テスト（HumanTest / RangerTest）**

---

## 🖥️ Technologies Used
- Java 17  
- LibGDX  
- Gradle  
- JUnit  
- SimplexNoise  
- MVC Design Pattern  

---
## 🛠️ Why Java & LibGDX?

アーキテクチャの学習（MVC・OOP・責務分離）を重視したため、Java と LibGDX を選択しました。

### ✔ Java を選んだ理由
- Java は強力な **オブジェクト指向（OOP）** 言語である  
- 「Animal」「Ranger」「Poacher」「Map」といった  
  **モデル層の構造化・抽象化に最適**
- チームメンバーが Java に慣れており、  
  **レビュー・コード共有がしやすい**

### ✔ LibGDX を選んだ理由
- View 層が明確に分離でき、  
  **MVC と相性が良い**
- Controller と Model を中心に  
  **クリーンなアーキテクチャを構築しやすい**
- ゲームエンジンとしての自由度が高く、  
  **フルスクラッチに近い形でゲームロジックを実装できる**

---

## 🧩 Architecture (MVC)
### ✔ Model
動物、レンジャー、ポーチャー、マップなどの状態とロジックを保持。

### ✔ View
GameView / MapView が担当。  
ゲーム画面・マップ描画・UIを担当。

### ✔ Controller
GameController がゲーム進行・操作系を管理。  
ユーザー操作とモデル／ビューの橋渡しを行う。

---

## 📘 UML Diagram
UML 図はこちら：
<img width="6113" height="3234" alt="bonsai-Class diagram drawio" src="https://github.com/user-attachments/assets/d145306c-84df-4de2-9e70-6b61b69340b4" />

## 👥 Team  
 3名でのグループ開発。  
担当部分（Ken Kudo）：

### ✨ My Contributions
- Human logic 生成 
- Human のテストコード作成  
- 脆弱性調査
- MVC 設計の整理  
- UML 図の設計 
- コードレビューと Git 運用

---

## 📝 Future Improvements
- 動物 AI を増強（捕食・縄張り行動など）
- 建物・オブジェクト設置機能
- セーブ／ロード機能
- マルチプレイ拡張
  
---
