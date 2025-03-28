# Soundness-Testnet-Guide-Registration
🛠 Soundness Testnet: Регистрация
🔗 Ссылка:
Soundness Testnet

🔹 Шаг 1: Подайте заявку
🔹 Перейдите по ссылке выше и отправьте ваш email для регистрации.

🔹 Шаг 2: Установка необходимых компонентов
Обновите систему перед установкой:

bash
Копировать
Редактировать
sudo apt update && sudo apt upgrade -y
Загрузите и установите soundnessup:

bash
Копировать
Редактировать
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
Установите Rust:

bash
Копировать
Редактировать
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
Примените изменения:

bash
Копировать
Редактировать
source ~/.bashrc
Установите и обновите soundnessup:

bash
Копировать
Редактировать
soundnessup install  
soundnessup update  
🔹 Шаг 3: Генерация ключа
Создайте новый ключ:

bash
Копировать
Редактировать
soundness-cli generate-key --name my-key
Просмотрите seed-фразу (обязательно сохраните её в безопасном месте!):

bash
Копировать
Редактировать
soundness-cli export-key --name my-key
🔹 Шаг 4: Завершающие шаги
✔ Сохраните ваш seed и публичный ключ
✔ Присоединитесь к официальному Discord
✔ Перейдите в канал #Testnet-access и отправьте свой публичный ключ

🎉 Готово! Вы зарегистрированы в Soundness Testnet.
