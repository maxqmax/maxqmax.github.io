---
layout: page
title: "Ailingo"
permalink: /
---

<div class="hero-section text-center py-5">
  <h1 class="display-4 mb-4">Добро пожаловать в Ailingo!</h1>
  <p class="lead mb-4">Интеллектуальная платформа для изучения языков через интерактивные диалоги</p>
  <div class="cta-buttons">
    <a href="/how-it-works" class="btn btn-primary btn-lg mx-2">Как это работает?</a>
    <a href="https://ailingo.artux.net" class="btn btn-success btn-lg mx-2">Начать обучение</a>
  </div>
</div>

<div class="features-section py-5">
  <h2 class="text-center mb-5">Что делает Ailingo уникальным?</h2>
  
  <div class="row">
    <div class="col-md-4 mb-4">
      <div class="feature-card text-center p-4">
        <i class="fas fa-comments fa-3x mb-3 text-primary"></i>
        <h3>Диалоги</h3>
        <p>Практикуйте язык в реальных ситуациях с помощью тематических диалогов</p>
      </div>
    </div>
    
    <div class="col-md-4 mb-4">
      <div class="feature-card text-center p-4">
        <i class="fas fa-chart-line fa-3x mb-3 text-success"></i>
        <h3>Статистика</h3>
        <p>Отслеживайте прогресс в изучении слов, грамматики и стиля речи</p>
      </div>
    </div>
    
    <div class="col-md-4 mb-4">
      <div class="feature-card text-center p-4">
        <i class="fas fa-book fa-3x mb-3 text-info"></i>
        <h3>Словарик</h3>
        <p>Создавайте личный словарь на основе пройденных диалогов</p>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col-md-4 mb-4">
      <div class="feature-card text-center p-4">
        <i class="fas fa-graduation-cap fa-3x mb-3 text-warning"></i>
        <h3>Обучение</h3>
        <p>Проходите интерактивные мини-уроки с дружелюбным маскотом</p>
      </div>
    </div>
    
    <div class="col-md-4 mb-4">
      <div class="feature-card text-center p-4">
        <i class="fas fa-trophy fa-3x mb-3 text-danger"></i>
        <h3>Игровой формат</h3>
        <p>Получайте награды и бонусы за ежедневные занятия</p>
      </div>
    </div>

    <div class="col-md-4 mb-4">
      <div class="feature-card text-center p-4">
        <i class="fas fa-robot fa-3x mb-3 text-secondary"></i>
        <h3>AI-помощник</h3>
        <p>Общайтесь с ботом, который подстраивается под ваш уровень</p>
      </div>
    </div>
  </div>
</div>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Roboto:wght@400;500;700&display=swap');

.hero-section {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-radius: 10px;
  margin-bottom: 2rem;
  padding: 3rem 1rem;
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

.hero-section h1 {
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  margin-bottom: 1.5rem;
}

.hero-section p {
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  max-width: 800px;
  margin: 0 auto 2rem;
  line-height: 1.6;
}

.features-section {
  padding: 4rem 0;
}

.feature-card {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
  height: 100%;
  display: flex;
  flex-direction: column;
  padding: 2rem;
}

.feature-card .icon-wrapper {
  margin-bottom: 1.5rem;
}

.feature-card h3 {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
  font-size: 1.5rem;
  margin-bottom: 1rem;
  min-height: 2rem;
}

.feature-card p {
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  font-size: 1rem;
  line-height: 1.6;
  margin: 0;
  flex-grow: 1;
  display: flex;
  align-items: center;
  text-align: center;
  min-height: 4.8rem;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.cta-buttons {
  margin-top: 2.5rem;
}

.btn-lg {
  padding: 1rem 2rem;
  font-weight: 600;
  font-family: 'Inter', sans-serif;
  min-width: 200px;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

.row {
  margin-bottom: 2rem;
}

@media (max-width: 768px) {
  .feature-card {
    margin-bottom: 1.5rem;
  }
  
  .feature-card p {
    min-height: auto;
  }
}
</style>
