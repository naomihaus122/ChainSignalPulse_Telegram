# ChainSignalPulse

**ChainSignalPulse** — это инновационный мониторинг-сервис для выявления необычной активности в сети Ethereum в реальном времени.

В отличие от обычных анализаторов блокчейна, ChainSignalPulse **вычисляет аномальные сигналы** путём статистического анализа количества транзакций по блокам, выявляя резкие всплески активности, которые могут указывать на:

- Массовые переводы токенов
- Атаки на DeFi-протоколы
- Запуск крупных NFT-дропов
- Боты/флуд активности

## 🔧 Возможности

- Получение свежих блоков с Etherscan
- Расчёт статистических аномалий
- Уведомления в консоль и Telegram
- Простая настройка

## 🚀 Установка

1. Получите API ключ от [Etherscan.io](https://etherscan.io/myapikey)
2. Создайте Telegram-бота и получите его токен через [BotFather](https://t.me/BotFather)
3. Получите свой Telegram Chat ID
4. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```
5. Запустите:
   ```bash
   python chain_signal_pulse.py
   ```

## 🛠 Настройки

- `ETHERSCAN_API_KEY` — ваш API ключ
- `TELEGRAM_BOT_TOKEN` — токен Telegram-бота
- `TELEGRAM_CHAT_ID` — ваш Telegram chat ID
- `ANOMALY_THRESHOLD_MULTIPLIER` — чувствительность к аномалиям

## 📄 License

MIT
