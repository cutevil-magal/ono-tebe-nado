# ОноТебеНадо — Аукцион вещей, в которые никто не верил

**Адаптивный лендинг для аукциона с современной версткой**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/ru/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/ru/docs/Web/CSS)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://figma.com)

---

## 📖 О проекте

Я разработала современный лендинг для аукциона "Оно тебе надо", специализирующегося на продаже уникальных вещей с историей. Проект представляет собой адаптивную веб-страницу с акцентом на визуальную привлекательность и пользовательский опыт.

### 🎯 Ключевые особенности

- **Семантическая верстка** с использованием современных HTML5-тегов
- **Адаптивный дизайн**, корректно отображающийся на различных устройствах
- **Оптимизированная типографика** с кастомными шрифтами
- **Чистая CSS-архитектура** с методологией БЭМ
- **Интерактивные элементы** с плавными переходами

### 🛠 Технологический стек

**Frontend:**
- HTML5 (семантическая разметка)
- CSS3 (Flexbox, Grid, кастомные свойства)
- JavaScript (базовые взаимодействия)

**Инструменты:**
- Figma для работы с дизайн-макетом
- Git для контроля версий
- GitHub Pages для деплоя

---

## 🚀 Быстрый старт

### Посмотреть онлайн

🌐 **[Живая демо-версия](https://cutevil-magal.github.io/ono-tebe-nado/)**

### Запуск локально

1. **Клонирование репозитория**
   ```bash
   git clone https://github.com/cutevil-magal/ono-tebe-nado.git
   cd ono-tebe-nado
   ```

2. **Запуск проекта**
   - Откройте файл `index.html` в браузере
   - Или используйте Live Server в VS Code

### Системные требования
- Современный браузер с поддержкой HTML5 и CSS3
- Доступ к интернету для загрузки веб-шрифтов

---

## 📁 Структура проекта

```
ono-tebe-nado/
├── index.html          # Главная страница
├── styles/
│   ├── style.css       # Основные стили
│   └── fonts.css       # Подключение шрифтов
├── fonts/              # Локальные шрифты
├── images/             # Изображения и иконки
└── README.md           # Документация
```

---

## 🎨 Особенности реализации

### Семантическая разметка
```html
<header class="header">
  <nav class="nav">
  <main class="main">
  <section class="cover">
  <article class="lot">
```

### Современный CSS
```css
.cover {
  background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6));
  background-size: cover;
  background-position: center;
}
```

### Адаптивность
```css
@media (max-width: 768px) {
  .header__menu {
    flex-direction: column;
    gap: 1rem;
  }
}
```

### БЭМ-методология
```css
.lot {}
.lot__image {}
.lot__title {}
.lot__description {}
.lot__price {}
```

---

## 🎯 Результаты реализации

**Достигнутые цели:**
- ✅ Полное соответствие макету Figma
- ✅ Кроссбраузерная совместимость
- ✅ Оптимизированная производительность загрузки
- ✅ Чистый и поддерживаемый код
- ✅ Полная адаптивность под мобильные устройства

**Технические преимущества:**
- Семантическая разметка для улучшения SEO
- Оптимизированные изображения для быстрой загрузки
- Доступность для пользователей с ограниченными возможностями
- Современные CSS-техники для плавных анимаций

---

## 🔮 Планы по развитию

- [ ] Добавить интерактивные элементы аукциона
- [ ] Реализовать систему ставок в реальном времени
- [ ] Интегрировать систему оплаты
- [ ] Добавить личный кабинет пользователя
- [ ] Реализовать систему уведомлений
- [ ] Оптимизировать для PWA (Progressive Web App)

---

## 👩‍💻 Разработчик

**Анна Хвостикова** - Frontend Developer

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cutevil-magal)
[![Email](https://img.shields.io/badge/Email-ana.magal@yandex.by-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ana.magal@yandex.by)

---

## 📄 Лицензия

Проект создан на основе дизайн-макета из Figma. Исходный код доступен для ознакомления и обучения.

**Макет в Figma:** [Ссылка на дизайн](https://www.figma.com/design/9LedGHq8wV17oxL5gvcZTJ/%D0%9E%D0%BD%D0%BE-%D1%82%D0%B5%D0%B1%D0%B5-%D0%BD%D0%B0%D0%B4%D0%BE-(Copy)?node-id=0-1&node-type=canvas&t=lBf74eHPp0kCYBWP-0)

---
