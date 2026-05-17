# Corolas 地球档案馆

earth-online.corolas.top | Corolas子项目

## 简介
地球档案数据可视化平台，汇聚地理、环境、气候等多维度地球数据。

## 技术栈
- Frontend: React 19 + TypeScript + Vite
- Styling: Tailwind CSS + shadcn/ui
- Backend: Supabase (Auth + PostgreSQL + Edge Functions)
- Deploy: Vercel (GitHub Push → Auto Deploy)
- CI/CD: GitHub Actions

## 环境变量
| 变量 | 说明 |
|------|------|
| VITE_SUPABASE_URL | Supabase项目URL |
| VITE_SUPABASE_ANON_KEY | Supabase Anon Key |

## 数据库
Supabase项目: https://supabase.com/dashboard/project/corolas-ne

## 本地开发
```bash
git clone https://github.com/CA53411/ne.git
cd ne
npm install
npm run dev
```

## 部署
Push到main分支自动触发Vercel部署
