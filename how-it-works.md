---
layout: page
title: "Как работает Ailingo?"
permalink: /how-it-works/
---

<div class="how-it-works-container">
  <h1 class="text-center mb-5">Как работает Ailingo?</h1>

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

          <div class="dialogue-structure">
            <h4 class="text-center mb-3">Структура диалога:</h4>
            <div class="timeline">
              <div class="timeline-item">
                <div class="timeline-icon bg-primary">
                  <i class="fas fa-1"></i>
                </div>
                <div class="timeline-content">
                  <h5>Welcome-prompt</h5>
                  <p>Бот начинает разговор (например, "Привет! Куда едем?")</p>
                </div>
              </div>
              <div class="timeline-item">
                <div class="timeline-icon bg-success">
                  <i class="fas fa-2"></i>
                </div>
                <div class="timeline-content">
                  <h5>System-prompt</h5>
                  <p>Определяет тему и поведение бота</p>
                </div>
              </div>
              <div class="timeline-item">
                <div class="timeline-icon bg-info">
                  <i class="fas fa-3"></i>
                </div>
                <div class="timeline-content">
                  <h5>End-prompt</h5>
                  <p>Завершение диалога (например, "Вы приехали, с вас 300 рублей!")</p>
                </div>
              </div>
            </div>
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
.how-it-works-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
}

.feature-card {
  border: none;
  border-radius: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
}

.examples-box {
  background: #f8f9fa;
  border-radius: 10px;
}

.timeline {
  position: relative;
  padding: 2rem 0;
}

.timeline-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 2rem;
  position: relative;
}

.timeline-icon {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  margin-right: 1rem;
  flex-shrink: 0;
}

.timeline-content {
  flex-grow: 1;
}

.timeline-content h5 {
  margin-bottom: 0.5rem;
  color: #333;
}

.badge {
  font-size: 1rem;
  padding: 0.5rem 1rem;
}

.btn-lg {
  padding: 1rem 2rem;
  font-weight: 600;
}
</style>
