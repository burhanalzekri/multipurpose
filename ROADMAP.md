# 🗺️ ROADMAP — Neon-Green 3D Redesign

## المرحلة 0: تحضير
- قراءة HANDOFF.md
- فحص app/landing.css
- نسخة احتياطية: cp app/landing.css app/landing.css.bak

## المرحلة 1: CSS Variables
إضافة في :root:
--neon: #00ff88; --neon-dim: #00cc6a;
--bg-0: #0a0a0a; --bg-1: #111; --bg-2: #1a1a1a;
--border: rgba(0,255,136,0.15);

## المرحلة 2: خلفية داكنة
body { background: var(--bg-0); color: #e5e5e5; }

## المرحلة 3: الأزرار
زر رئيسي: gradient نيون + box-shadow متوهج + hover رفع

## المرحلة 4: 3D
- البطاقات: perspective + rotateX + shadows متعددة
- hover: translateY(-4px) + glow أقوى

## المرحلة 5: Glassmorphism
Navbar: backdrop-filter blur(20px) + rgba(10,10,10,0.7)

## المرحلة 6: Animations
- @keyframes neonPulse
- @keyframes float

## المرحلة 7: Layout
Hero ضخم + gradient text + grid responsive

## المرحلة 8: analytics + signals components
تحديث ألوان + 3D bars

## المرحلة 9: صقل
scrollbar نيون + selection + focus states

## المرحلة 10: اختبار
جوال حقيقي + RTL + تفاعلية (mood/report buttons)

الوقت: ~3.5 ساعات | الأولوية: 1→2→3→4→7
