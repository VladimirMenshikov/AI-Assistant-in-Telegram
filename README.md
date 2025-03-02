# ИИ-ассистент для компании по автоматизации бизнеса с помощью нейросетей

[Ссылка на проект](https://t.me/aibusinessautopilot_bot)  
[Скриншоты работы проекта](./screen#readme)

## Описание проекта
Этот проект представляет собой интеллектуального ассистента, созданного для упрощения работы компании, специализирующейся на автоматизации бизнес-процессов с использованием нейросетевых технологий. Ассистент разработан для взаимодействия с клиентами и предоставления им необходимой информации в режиме реального времени, что позволяет повысить эффективность обслуживания и оптимизировать рабочие процессы.

## Функционал
Ассистент обладает следующими ключевыми возможностями:

- Осмысленное ведение диалога
- Благодаря интеграции с передовыми нейросетевыми технологиями, ассистент способен поддерживать естественные и осмысленные диалоги с пользователями. Он понимает контекст беседы, адаптируется к запросам клиента и предоставляет релевантные ответы.
- Ответы на вопросы по базе знаний
- Ассистент имеет доступ к специально подготовленной базе знаний, содержащей информацию о продуктах, услугах, процессах и политике компании. Это позволяет ему быстро и точно отвечать на часто задаваемые вопросы клиентов.
- Запись клиента на консультацию
- Пользователи могут записаться на консультацию через ассистента. После подтверждения записи, событие автоматически добавляется в Google Календарь, что обеспечивает четкую координацию между клиентом и компанией.

### Используемые сервисы
Для реализации данного проекта были задействованы следующие сервисы:

**Qwen**
- Qwen был использован для создания системного промпта и формирования базы знаний. Этот мощный инструмент помог настроить ассистента таким образом, чтобы он мог эффективно взаимодействовать с пользователями и предоставлять точную информацию.

**[Savvy](https://suvvy.ai/)**
- Savvy — платформа для создания ИИ-ассистентов без необходимости глубоких технических знаний. Она была выбрана для быстрой и удобной разработки интерфейса ассистента, его настройки и интеграции с другими сервисами.

### Преимущества решения
- Автоматизация рутинных задач
- Ассистент берет на себя ответы на стандартные вопросы и организацию встреч, что значительно снижает нагрузку на сотрудников компании.
- Улучшение клиентского опыта
- Благодаря быстрому и качественному обслуживанию, клиенты получают более положительное впечатление от взаимодействия с компанией.
- Гибкость и масштабируемость
- Решение можно легко адаптировать под изменяющиеся потребности бизнеса и расширять функционал по мере необходимости.

## Технические детали
### Архитектура системы
#### Фронтенд
Интерфейс ассистента, созданный с помощью Savvy, обеспечивает простое и интуитивно понятное взаимодействие с пользователем.

#### Бэкенд
Интеграция с Qwen для обработки запросов и анализа контекста.
API-подключение к Google Календарю для управления записями и событиями.

#### База данных
Хранение и обновление базы знаний, которая используется для генерации ответов на вопросы пользователей.

## Процесс работы
Пользователь обращается к ассистенту через чат или другой интерфейс.
Ассистент анализирует запрос с помощью нейросети Qwen.
Если запрос требует записи на консультацию, ассистент запрашивает необходимые данные (например, дату и время) и добавляет событие в Google Календарь.
Ответы на информационные вопросы извлекаются из базы знаний и предоставляются пользователю.

## Заключение
Разработанный ИИ-ассистент является современным решением для автоматизации коммуникаций между компанией и её клиентами. Он не только повышает эффективность работы, но и улучшает качество обслуживания, делая взаимодействие с компанией более удобным и комфортным для пользователей.

_Если у вас есть дополнительные вопросы или вы хотите узнать больше о возможностях этого проекта, свяжитесь с нашей командой!_
