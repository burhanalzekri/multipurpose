# 🎯 MULTISTORE-PROD — Handoff

## نظرة عامة
- Next.js 14+ (App Router) + TypeScript
- Tailwind CSS + custom CSS في app/landing.css
- RTL عربي كامل (dir="rtl", lang="ar")
- lucide-react للأيقونات

## البنية
- app/page.tsx → الصفحة الرئيسية
- app/layout.tsx → RTL + fonts + metadata
- app/landing.css → 🎨 90% من التنسيقات هنا
- components/marketing/landing-signals.tsx
- components/marketing/analytics-bento.tsx

## الهوية الحالية
- ألوان: بنفسجي (#7c3aed/#8b5cf6) + أبيض
- المشكلة: تصميم عام، غير 3D

## الهدف
تحويل إلى: داكن (#0a0a0a) + نيون أخضر (#00ff88) + 3D + glassmorphism

## قواعد
- لا تكسر RTL
- لا تغيّر بنية JSX
- احتفظ بـ data-* attributes
- استخدم CSS variables

## لا تفعل
- لا تعيد كتابة components من الصفر
- لا تحذف data-contextual-suggestion / data-mood-*
