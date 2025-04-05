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
  margin-bottom: 3rem;
  padding: 4rem 1rem;
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

.hero-section h1 {
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  margin-bottom: 1.5rem;
  font-size: 3.2rem;
}

.hero-section p {
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  max-width: 800px;
  margin: 0 auto 2rem;
  line-height: 1.6;
  font-size: 1.25rem;
}

.features-section {
  padding: 4rem 0;
}

.features-section h2 {
  font-size: 2.5rem;
  margin-bottom: 3rem;
  font-weight: 600;
}

.feature-card {
  background: white;
  border-radius: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
  height: 100%;
  display: flex;
  flex-direction: column;
  padding: 2.5rem 2rem;
}

.feature-card i {
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
}

.feature-card h3 {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
  font-size: 1.75rem;
  margin-bottom: 1.25rem;
  color: #2d3748;
}

.feature-card p {
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  font-size: 1.1rem;
  line-height: 1.7;
  color: #4a5568;
  margin: 0;
  padding: 0 1rem;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.cta-buttons {
  margin-top: 2.5rem;
}

.btn-lg {
  padding: 1rem 2.5rem;
  font-weight: 600;
  font-family: 'Inter', sans-serif;
  min-width: 220px;
  font-size: 1.1rem;
  letter-spacing: 0.5px;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

.row {
  margin-bottom: 2.5rem;
}

@media (max-width: 768px) {
  .hero-section h1 {
    font-size: 2.5rem;
  }

  .hero-section p {
    font-size: 1.1rem;
  }

  .features-section h2 {
    font-size: 2rem;
  }

  .feature-card {
    margin-bottom: 1.5rem;
    padding: 2rem 1.5rem;
  }
  
  .feature-card h3 {
    font-size: 1.5rem;
  }

  .feature-card p {
    font-size: 1rem;
    padding: 0;
  }
}
</style>
