---
layout: default
title: "Валентин — QA тестировщик"
theme: jekyll-theme-architect
markdown: kramdown
---

<style>
  /* Градиентный фон */
  body {
    background: linear-gradient(135deg, #000000ff, #af002d 70%);
    color: #fff !important;
    font-family: "Segoe UI", sans-serif;
  }

  h1, h2, h3 {
    text-shadow: 0 4px 10px rgba(0,0,0,0.3);
  }

  /* Центровка и стиль карточек */
  .card {
    background: rgba(255, 255, 255, 0.15);
    padding: 20px;
    border-radius: 14px;
    backdrop-filter: blur(8px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.25);
    margin: 20px 0;
  }

  img {
    border-radius: 14px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.4);
  }

  .skills-block {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }

  .skill {
    background: #b6b0b022;
    padding: 8px 14px;
    border-radius: 10px;
    font-weight: bold;
    backdrop-filter: blur(5px);
    box-shadow: 0 4px 10px rgba(109, 60, 60, 0.2);
  }
</style>

<!-- Заголовок -->
<h1 align="center">🔥 Привет! Я — Валентин</h1>
<h3 align="center">Начинающий QA-тестировщик</h3>

<!-- Фото -->
<p align="center">
  <img src="myfoto.jpg" alt="Моё фото" width="260" />
</p>

<div class="card">

## 🌈 Обо мне

- 🎓 Обучаюсь: **QAMID126 — Тестирование ПО**  
- 💻 Интересы: **Frontend, Backend, AI, Gamedev, DevOps и многое другое**  
- 🚀 Цель: **Стать сильным инженером и создавать качественные продукты**

</div>

<div class="card">

## ⚡ Навыки

### ⭐ Языки программирования
<div class="skills-block">
  <div class="skill">JavaScript</div>
  <div class="skill">Python</div>
</div>

### 🧰 Инструменты
<div class="skills-block">
  <div class="skill">Git</div>
  <div class="skill">GitHub</div>
  <div class="skill">Docker</div>
  <div class="skill">VS Code</div>
  <div class="skill">HTML / CSS</div>
  <div class="skill">Markdown</div>
  <div class="skill">VDS</div>
</div>

</div>

<div class="card">

## 💼 Пример кода

```python
def greet(name: str) -> str:
    return f"Привет, {name}!"

print(greet("мир"))
