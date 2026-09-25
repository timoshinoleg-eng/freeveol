# freeveol

Разрабатываю прикладные **AI/MCP-инструменты, developer tooling, B2B-автоматизацию и Mini Apps**. Основной фокус — доведение прототипов до production-состояния: воспроизводимый CI/CD, security gates, тестируемые контракты, privacy/read-only defaults и облачные сценарии развертывания.

## Основные проекты

### 1C AI Workbench

Open-source AI/MCP workbench для безопасного read-only анализа конфигураций **1С:Предприятие 8.3**. Локально индексирует BSL-код и метаданные, предоставляет evidence-first MCP-инструменты и сохраняет исходные данные пользователя под его контролем.

- Python / Rust / FastMCP / SQLite
- BSL и метаданные 1С
- signed release process, Gitleaks, REUSE, CodeQL
- GitVerse CI/CD + Cloud.ru pilot
- MIT

[GitVerse](https://gitverse.ru/freeveol/1c-ai-workbench) · [GitHub](https://github.com/timoshinoleg-eng/1c-ai-workbench)

### Mini Apps & interactive products

- **Tower MAX** — mobile-first tower game для MAX Mini App с production-oriented CI и browser acceptance tests.
- **Световой Рубеж** — TypeScript game MVP для MAX Mini App.
- **OFELIYA: Strain Zero** — Phaser 3 / TypeScript action game с платформенным слоем MAX/Telegram, server-side social/competitive systems и production smoke tests.
- **coder_survival** — Telegram Mini App с игровым web-интерфейсом.

### MCP, integrations & automation

- **avito-mcp** — MCP server fork с 148 upstream tools, ads domain и lookup helper.
- **ChatBot24** — Telegram/MAX-боты, Mini Apps и B2B-интеграции.

## Технологии

**Python · TypeScript · JavaScript · Rust · MCP / FastMCP · Phaser 3 · Docker · PostgreSQL · GitHub Actions · GitVerse CI/CD · Cloud.ru · Telegram / MAX Mini Apps**

## Инженерный подход

- evidence-first вместо недоказанных выводов;
- read-only и fail-closed defaults для чувствительных сценариев;
- автоматические тесты и acceptance gates перед release;
- воспроизводимые зависимости и supply-chain hardening;
- mobile-first UX для Mini Apps;
- минимизация ручных операций через CI/CD и автоматизацию.

## Ссылки

- GitHub: https://github.com/timoshinoleg-eng
- GitVerse: https://gitverse.ru/freeveol
- ChatBot24: https://chatbot24.su/

Открыт к B2B-пилотам, интеграциям и совместной разработке прикладных AI/MCP-инструментов.
