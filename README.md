# Soundness-Testnet-Guide-Registration
Вот немного изменённый вариант текста:  

---

# 🛠 Soundness Testnet: Регистрация  

## 🔗 Ссылка:  
[Soundness Testnet](https://soundness.xyz/)  

### 🔹 Шаг 1: Подайте заявку  
🔹 Перейдите по ссылке выше и отправьте ваш email для регистрации.  

---

## 🔹 Шаг 2: Установка необходимых компонентов  

Обновите систему перед установкой:  
```bash
sudo apt update && sudo apt upgrade -y
```  

Загрузите и установите `soundnessup`:  
```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```  

Установите Rust:  
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```  

Примените изменения:  
```bash
source ~/.bashrc
```  

Установите и обновите `soundnessup`:  
```bash
soundnessup install  
soundnessup update  
```  

---

## 🔹 Шаг 3: Генерация ключа  

Создайте новый ключ:  
```bash
soundness-cli generate-key --name my-key
```  

Просмотрите seed-фразу (обязательно сохраните её в безопасном месте!):  
```bash
soundness-cli export-key --name my-key
```  

---

## 🔹 Шаг 4: Завершающие шаги  

✔ **Сохраните ваш seed и публичный ключ**  
✔ **Присоединитесь к [официальному Discord]((https://discord.gg/F4cGbdqgw8))**  
✔ **Перейдите в канал `#Testnet-access` и отправьте свой публичный ключ**  

🎉 **Готово! Вы зарегистрированы в Soundness Testnet.**  
