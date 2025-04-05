---
layout: page
title: "Как работает Ailingo?"
permalink: /how-it-works/
---

<div class="how-it-works-container">
  <div class="row mb-5">
    <div class="col-md-8 mx-auto">
      <div class="card feature-card">
        <div class="card-body">
          <h2 class="card-title text-center mb-4">
            <i class="fas fa-comments text-primary me-2"></i>
            Топики и диалоги
          </h2>
          <p class="lead text-center mb-4">Ailingo предлагает <strong>тематические диалоги</strong>, где бот играет определенную роль</p>
          
          <div class="examples-box p-4 mb-4">
            <h4 class="text-center mb-3">Примеры топиков:</h4>
            <div class="d-flex justify-content-center flex-wrap gap-3">
              <span class="badge bg-primary p-2">Такси</span>
              <span class="badge bg-primary p-2">Ресторан</span>
              <span class="badge bg-primary p-2">Случай на рынке</span>
            </div>
          </div>

          <div class="dialogue-description">
            <p class="text-center">Вы выбираете интересную вам тему, и начинается живой диалог с умным ботом. Он понимает контекст, отвечает естественно и помогает вам практиковать язык в реальных ситуациях. В процессе диалога вы получаете подсказки и обратную связь.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="row mb-5">
    <div class="col-md-6">
      <div class="card feature-card h-100">
        <div class="card-body">
          <h2 class="card-title text-center mb-4">
            <i class="fas fa-chart-bar text-success me-2"></i>
            Умная статистика
          </h2>
          <ul class="list-unstyled">
            <li class="mb-3">
              <i class="fas fa-check-circle text-success me-2"></i>
              Количество уникальных слов
            </li>
            <li class="mb-3">
              <i class="fas fa-check-circle text-success me-2"></i>
              Грамматика (правильность предложений)
            </li>
            <li class="mb-3">
              <i class="fas fa-check-circle text-success me-2"></i>
              Слова, добавленные в словарик
            </li>
            <li class="mb-3">
              <i class="fas fa-check-circle text-success me-2"></i>
              Процент корректных предложений
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card feature-card h-100">
        <div class="card-body">
          <h2 class="card-title text-center mb-4">
            <i class="fas fa-gamepad text-warning me-2"></i>
            Геймификация
          </h2>
          <ul class="list-unstyled">
            <li class="mb-3">
              <i class="fas fa-fire text-danger me-2"></i>
              Страйки — ежедневные серии выполнения топиков дают бонусы
            </li>
            <li class="mb-3">
              <i class="fas fa-coins text-warning me-2"></i>
              Монеты — зарабатывайте и открывайте новые темы
            </li>
            <li class="mb-3">
              <i class="fas fa-trophy text-info me-2"></i>
              Рейтинг — соревнуйтесь с друзьями!
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <div class="text-center mt-5">
    <a href="https://ailingo.artux.net" class="btn btn-success btn-lg">
      Начать учить язык с Ailingo
    </a>
  </div>
</div>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Roboto:wght@400;500;700&display=swap');

.how-it-works-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

.feature-card {
  border: none;
  border-radius: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
  height: 100%;
  padding: 2rem;
}

.feature-card h2 {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
  margin-bottom: 1.5rem;
  min-height: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.feature-card .lead {
  font-size: 1.1rem;
  line-height: 1.6;
  margin-bottom: 2rem;
}

.feature-card p {
  font-family: 'Inter', sans-serif;
  font-weight: 400;
  line-height: 1.6;
  margin-bottom: 0;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.examples-box {
  background: #f8f9fa;
  border-radius: 10px;
  padding: 2rem;
  margin: 2rem 0;
}

.examples-box h4 {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
  margin-bottom: 1.5rem;
}

.badge {
  font-size: 1rem;
  padding: 0.5rem 1.5rem;
  margin: 0.5rem;
  font-family: 'Inter', sans-serif;
}

.btn-lg {
  padding: 1rem 2rem;
  font-weight: 600;
  font-family: 'Inter', sans-serif;
  min-width: 200px;
}

.dialogue-description {
  padding: 0 1rem;
}

.dialogue-description p {
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.8;
}

.list-unstyled li {
  padding: 0.75rem 0;
  display: flex;
  align-items: center;
}

.list-unstyled i {
  flex-shrink: 0;
  margin-right: 1rem;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

@media (max-width: 768px) {
  .feature-card {
    margin-bottom: 1.5rem;
  }
  
  .feature-card h2 {
    min-height: auto;
  }
}
</style>
