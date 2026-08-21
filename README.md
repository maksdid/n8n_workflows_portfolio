# n8n Automation Portfolio

Коллекция рабочих n8n-автоматизаций для реальных бизнес-задач: приём и обработка лидов, документооборот, HR, AI-агенты и коммуникации с клиентами.

Каждая папка — отдельный воркфлоу с готовым `workflow.json` для импорта в n8n (Workflows → Import from File) и скриншотом канваса.

## Воркфлоу

| Превью | Воркфлоу | Что делает | Стек / интеграции |
|---|---|---|---|
| <img src="./lead-intake-crm/screenshot.jpg" width="150"> | [Lead Intake CRM](./lead-intake-crm) | Приём заявок с формы напрямую в CRM | Tally Forms, Google Sheets |
| <img src="./stale-lead-nudges/screenshot.jpg" width="150"> | [Stale Lead Nudges](./stale-lead-nudges) | Напоминает менеджеру о лидах, которые давно молчат | Notion CRM, Telegram |
| <img src="./feedback-processing/screenshot.jpg" width="150"> | [Multi-Source Feedback Processing](./feedback-processing) | Сбор фидбека из разных источников, уведомления в Slack | OpenAI, Slack |
| <img src="./applicant-digest/screenshot.jpg" width="150"> | [Daily Applicant Digest](./applicant-digest) | Ежедневная сводка новых кандидатов по вакансиям | Gemini AI, Gmail |
| <img src="./screen-applicants/screenshot.jpg" width="150"> | [Screen Applicants with AI](./screen-applicants) | Скрининг кандидатов, уведомление HR, запись в таблицу | AI Agent, Google Sheets |
| <img src="./telegram-advisor-bot/screenshot.jpg" width="150"> | [Telegram Advisor Bot](./telegram-advisor-bot) | Чат-бот с памятью диалога для консультаций | Telegram, GPT-4o-mini, Postgres |
| <img src="./rag-chatbot/screenshot.jpg" width="150"> | [RAG Chatbot](./rag-chatbot) | Бот отвечает по базе знаний компании | Supabase, TogetherAI, OpenRouter |
| <img src="./document-summarizer/screenshot.jpg" width="150"> | [Document Summarizer](./document-summarizer) | Автоконспект новых документов | Google Drive |
| <img src="./invoice-processing/screenshot.jpg" width="150"> | [Invoice Processing](./invoice-processing) | Распознаёт и суммирует счета автоматически | AWS Textract, Gemini |
| <img src="./slides-generator/screenshot.jpg" width="150"> | [Slides Generator](./slides-generator) | Автогенерация презентаций из CSV-данных | Google Slides |
| <img src="./linkedin-auto-posting/screenshot.jpg" width="150"> | [LinkedIn Auto-Posting](./linkedin-auto-posting) | Контент + генерация картинок для LinkedIn | GPT-4o, Telegram |
| <img src="./whatsapp-assistant/screenshot.jpg" width="150"> | [WhatsApp AI Assistant](./whatsapp-assistant) | Консультационный бот, легко адаптируется под нишу | WhatsApp, Gemini AI |

## Галерея

<table>
<tr>
<td align="center"><img src="./lead-intake-crm/screenshot.jpg" width="250"><br><b>Lead Intake CRM</b></td>
<td align="center"><img src="./stale-lead-nudges/screenshot.jpg" width="250"><br><b>Stale Lead Nudges</b></td>
</tr>
<tr>
<td align="center"><img src="./feedback-processing/screenshot.jpg" width="250"><br><b>Feedback Processing</b></td>
<td align="center"><img src="./applicant-digest/screenshot.jpg" width="250"><br><b>Applicant Digest</b></td>
</tr>
<tr>
<td align="center"><img src="./screen-applicants/screenshot.jpg" width="250"><br><b>Screen Applicants</b></td>
<td align="center"><img src="./telegram-advisor-bot/screenshot.jpg" width="250"><br><b>Telegram Advisor Bot</b></td>
</tr>
<tr>
<td align="center"><img src="./rag-chatbot/screenshot.jpg" width="250"><br><b>RAG Chatbot</b></td>
<td align="center"><img src="./document-summarizer/screenshot.jpg" width="250"><br><b>Document Summarizer</b></td>
</tr>
<tr>
<td align="center"><img src="./invoice-processing/screenshot.jpg" width="250"><br><b>Invoice Processing</b></td>
<td align="center"><img src="./slides-generator/screenshot.jpg" width="250"><br><b>Slides Generator</b></td>
</tr>
<tr>
<td align="center"><img src="./linkedin-auto-posting/screenshot.jpg" width="250"><br><b>LinkedIn Auto-Posting</b></td>
<td align="center"><img src="./whatsapp-assistant/screenshot.jpg" width="250"><br><b>WhatsApp AI Assistant</b></td>
</tr>
</table>

## Как использовать

1. Открой папку нужного воркфлоу
2. Скачай `workflow.json`
3. В n8n: Workflows → Import from File
4. Подключи свои credentials под используемые сервисы
5. Активируй воркфлоу
