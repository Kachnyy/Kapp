<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Долговой помощник</title>
<style>
    body { font-family: Arial, sans-serif; background: #f5f5f5; margin: 0; padding: 0; }
    header { background: #2c3e50; color: white; padding: 20px; text-align: center; }
    .container { padding: 20px; }
    .card {
        background: white; padding: 15px; margin-bottom: 15px;
        border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .price { color: #e74c3c; font-weight: bold; }
    h2 { margin: 0 0 10px 0; }
    input, select, button {
        width: 100%; padding: 10px; margin-top: 10px;
        border-radius: 5px; border: 1px solid #ccc; font-size: 16px;
    }
    button {
        background: #2c3e50; color: white; border: none; cursor: pointer;
    }
</style>
</head>
<body>

<header>
    <h1>Долговой помощник</h1>
    <p>Помогу разобраться с долгами и вернуть контроль</p>
</header>

<div class="container">

    <div class="card">
        <h2>Разбор долговой ситуации — <span class="price">2 000 ₽</span></h2>
        <p>Анализ ситуации + чёткий план действий.</p>
    </div>

    <div class="card">
        <h2>Переговоры с кредиторами — <span class="price">4 500 ₽</span></h2>
        <p>Стратегия, линия поведения, готовые фразы.</p>
    </div>

    <div class="card">
        <h2>Переговоры “под ключ” — <span class="price">10 000 ₽</span></h2>
        <p>Полное ведение процесса. Ты просто пересылаешь текст.</p>
    </div>

    <div class="card">
        <h2>Подготовка к встречам — <span class="price">3 000 ₽</span></h2>
        <p>Держим уверенность и психологическое преимущество.</p>
    </div>

    <div class="card">
        <h2>Консультация по банкротству — <span class="price">5 000 ₽</span></h2>
        <p>Риски, документы, имущество, подходит ли тебе.</p>
    </div>

    <div class="card">
        <h2>Кураторство банкротства — <span class="price">от 20 000 ₽</span></h2>
        <p>Полное сопровождение каждого шага.</p>
    </div>

    <div class="card">
        <h2>Доступ к людям в ФССП — <span class="price">5 000 ₽</span></h2>
        <p>Как говорить с приставом, какие заявления подавать.</p>
    </div>

    <div class="card">
        <h2>Full Support — <span class="price">30 000 ₽ / месяц</span></h2>
        <p>Ведение всех процессов 24/7.</p>
    </div>

    <h2>Оставить заявку</h2>
    <input id="name" placeholder="Ваше имя">
    <input id="contact" placeholder="Телеграм или телефон">
    <select id="service">
        <option disabled selected>Выберите услугу</option>
        <option>Разбор долговой ситуации</option>
        <option>Переговоры с кредиторами</option>
        <option>Переговоры под ключ</option>
        <option>Подготовка к встречам</option>
        <option>Консультация по банкротству</option>
        <option>Кураторство банкротства</option>
        <option>Доступ к людям в ФССП</option>
        <option>Full Support</option>
    </select>
    <button onclick="send()">Отправить</button>
</div>

<script>
function send() {
    alert("Заявка отправлена (тестовый режим).");
}
</script>

</body>
</html>
