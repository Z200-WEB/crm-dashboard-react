# Salesforce-Inspired CRM Dashboard

EN: A business CRM dashboard built with React + Tailwind CSS, modeled after Salesforce workflows.
JP: ReactとTailwind CSSで構築した、Salesforce風のビジネス向けCRMダッシュボードです。

---

## 🎯 Why I Built This

I wanted to understand how enterprise tools like Salesforce support real business operations — customer management, sales pipeline tracking, and task coordination. Rather than building something flashy, I focused on **clarity of data, intuitive UX, and component architecture that reflects real-world business logic**.

このプロジェクトは、SalesforceのようなCRMがビジネスをどう支えているかを理解するために制作しました。派手な機能よりも、業務の流れが分かりやすい設計・使いやすさ・Reactコンポーネント設計を重視しました。

---

## ✨ Features / 機能

- **Customer / Lead Management** — Track leads with status (New, Contacted, Qualified, Closed)
- - **Opportunity Pipeline** — Manage deals across sales stages with estimated value
  - - **Task Management** — Assign follow-up tasks tied to customer records
    - - **Dashboard Overview** — Key business metrics visible at a glance
      - - **Responsive Design** — Usable on both desktop and tablet
        - - **Bilingual UI** — Japanese and English labels throughout
          -
          - ---
          -
          - ## 🛠 Tech Stack
          -
          - | Category | Technology |
          - |---|---|
          - | Frontend Framework | React 18 (Functional Components + Hooks) |
          - | Styling | Tailwind CSS 3 |
          - | Build Tool | Vite |
          - | Language | JavaScript (ES6+) |
          - | Icons | Lucide React |
          -
          - ---
          -
          - ## 🏗 Architecture & Design Decisions
          -
          - **Component Structure:** Each business domain (Customers, Opportunities, Tasks) is separated into its own component with clear props and local state. This mirrors how real enterprise apps are built — domain-driven UI components.
          -
          - **State Management:** Managed entirely with React hooks (useState, useMemo). No external state library needed for this scope, keeping the architecture simple and readable.
          -
          - **Data Flow:** All data flows top-down from a central App component. Filtering and sorting logic uses useMemo to avoid unnecessary re-renders.
          -
          - **Accessibility:** Semantic HTML elements, ARIA labels on interactive controls, keyboard-navigable UI, and clear visual focus indicators throughout.
          -
          - ---
          -
          - ## 📁 Project Structure
          -
          - ```
            crm-dashboard-react/
            ├── src/
            │   ├── components/
            │   │   ├── Dashboard.jsx      # Main metrics overview
            │   │   ├── CustomerList.jsx   # Customer/Lead management
            │   │   ├── OpportunityList.jsx # Sales pipeline view
            │   │   └── TaskList.jsx       # Follow-up task management
            │   ├── App.jsx                # Root component + data
            │   └── main.jsx               # Entry point
            ├── index.html
            ├── package.json
            ├── vite.config.js
            └── tailwind.config.js
            ```

            ---

            ## 🚀 Getting Started

            ```bash
            # Clone the repository
            git clone https://github.com/Z200-WEB/crm-dashboard-react.git

            # Install dependencies
            npm install

            # Start development server
            npm run dev
            ```

            The app runs at `http://localhost:5173`

            ---

            ## 📚 What I Learned

            Building this project taught me how **business requirements directly shape UI and data design**. The key insight: enterprise users need information density and speed, not visual flair. Every design decision — from table layouts to status color coding — was driven by usability for non-technical users.

            ---

            ## 🔮 Future Improvements

            - [ ] Migrate to TypeScript for type-safe component props
            - [ ] - [ ] Add unit tests with Vitest + React Testing Library
            - [ ] - [ ] Connect to real backend API (Node.js / Express)
            - [ ] - [ ] Implement user authentication
            - [ ] - [ ] Add Japanese language toggle
            - [ ]
            - [ ] ---
            - [ ]
            - [ ] ## 📄 License
            - [ ]
            - [ ] MIT License
            - [ ]
            - [ ] ---
            - [ ]
            - [ ] *Created by [Zawe Zaw Htet](https://z200-web.github.io/my-portofilo/) — Frontend Engineer, IT Student in Japan*# Salesforce-Inspired CRM Dashboard

## Overview
This project is a Salesforce-inspired CRM dashboard .
The purpose of this project is to understand how CRM systems support business operations,
such as customer management, sales progress tracking, and task organization.

Rather than focusing on complex or flashy features, I prioritized clarity, usability,
and understanding real business workflows.

## Background
I am an international student studying IT in Japan and aiming to work in a company
that supports business improvement using technology.
Through this project, I wanted to learn how systems like Salesforce are structured
and how they are used in real business environments.

## Features
- Customer / Lead management with status tracking
- Opportunity management with sales stages
- Task management for follow-ups
- Simple dashboard overview for business visibility

## What I Focused On
- Designing screens that are easy to understand for non-technical users
- Keeping the data structure simple and realistic
- Understanding the flow of sales and customer management
- Writing readable and maintainable React components

## Technologies Used
- React (Functional Components)
- Tailwind CSS
- JavaScript
- Dummy data (no backend)

## Use of AI Tools
Some parts of the initial implementation were generated with the help of AI tools.
After that, I reviewed, modified, and organized the code by myself to better understand
the structure and logic of the application.

## What I Learned
- Basic structure of CRM systems like Salesforce
- How business requirements affect UI and data design
- The importance of usability and clarity in business applications

## Future Improvements
- More detailed dashboard analytics
- Improved component separation
- Integration with real backend services

# Salesforce風 CRMダッシュボード

## 概要
本プロジェクトは、Salesforceを参考にして制作したCRMダッシュボードです。
顧客管理、案件管理、タスク管理など、CRMシステムがどのように
業務を支えているかを理解することを目的としています。

機能の多さや派手なデザインよりも、
業務の流れが分かりやすいこと、使いやすさを重視して制作しました。

## 制作背景
私は日本でITを学んでいる留学生で、
ITを通じて業務改善を支援する企業に興味があります。
本プロジェクトでは、SalesforceのようなCRMの構造や考え方を
実装を通して学びたいと考えました。

## 主な機能
- 顧客・リード管理（ステータス管理）
- 案件管理（営業ステージ）
- フォローアップ用タスク管理
- 業務状況を把握するための簡易ダッシュボード

## 工夫した点
- 非ITユーザーでも理解しやすい画面構成
- シンプルで現実的なデータ構造
- 営業・顧客管理の業務フローを意識した設計
- Reactコンポーネントの可読性を意識した実装

## 使用技術
- React（関数コンポーネント）
- Tailwind CSS
- JavaScript
- ダミーデータ（バックエンドなし）

## AIツールの利用について
初期実装の一部ではAIツールを活用しましたが、
その後コードを自分で確認・修正し、
構成やロジックを理解した上で整理しています。

## 学んだこと
- Salesforceに代表されるCRMシステムの基本構造
- 業務要件をUIやデータ設計に落とし込む考え方
- ビジネス向けアプリケーションにおける使いやすさの重要性

## 今後の改善点
- ダッシュボード機能の拡張
- コンポーネント構成の改善
- バックエンドとの連携
