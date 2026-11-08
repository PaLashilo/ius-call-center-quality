# Проектирование информационно-управляющих систем

Этап 1, вариант 18 — «Качество обработки обращений в call-центр».

| | |
|---|---|
| Автор | Пашинская Пелагея |
| Группа | МПМИИ251 |
| Статус | черновик v0.1, ожидает human-gate преподавателя (рецензия этапа 1) |
| Срок | 16.11.2026 (со слов студентки) |

Учебные тексты, диаграммы и матрица взяты из комплекта этапа 1 без изменения содержания. Каталоги `tools/` и `sources/`, упомянутые во внутреннем README комплекта, в архив не входили и в репозиторий не добавлены.

`specs/plan.md` и `specs/tasks.md` — **несогласованные черновики**. К исполнению они не принимаются, пока преподаватель не пройдёт human-gate по `specs/spec.md` и затем по плану и задачам.

## Состав репозитория

| Файл | Содержание |
|---|---|
| `docs/stage-1-variant-18.docx`, `docs/stage-1-variant-18.pdf` | Основной отчёт этапа 1: титул, границы, роли, AS-IS/TO-BE, обоснование UML и CASE, параметры P01–P06, FR, 15 EARS с приёмкой, NFR, KPI, требования к ИИ, данные, матрица, SDD/constitution/версионирование/журнал, план раздела об ошибках агента, проверка покрытия |
| `constitution.md` | 7 принципов в стиле Spec Kit (draft v0.1) |
| `specs/spec.md` | Specify v0.1 (draft), источник истины для plan/tasks |
| `specs/plan.md` | Черновик плана, **не согласован** (ждёт human-gate после Specify) |
| `specs/tasks.md` | Черновик задач, **не согласован** (ждёт human-gate по spec и plan) |
| `diagrams/01-use-case.puml`, `diagrams/01-use-case.png` | Варианты использования |
| `diagrams/02-activity-as-is.puml`, `diagrams/02-activity-as-is.png` | Activity AS-IS обработки обращения |
| `diagrams/03-activity-to-be.puml`, `diagrams/03-activity-to-be.png` | Activity TO-BE цикла оценки (с fallback) |
| `diagrams/04-sequence-audit.puml`, `diagrams/04-sequence-audit.png` | Sequence аудитор–система–агент |
| `diagrams/05-state-call-scenario.puml`, `diagrams/05-state-call-scenario.png` | Состояния оценки звонка и сценария |
| `traceability.xlsx` | EARS → элемент модели → будущая архитектура; листы параметров и FR |
| `.gitignore` | Служебные файлы ОС и редакторов |

`.puml` — текстовые исходники PlantUML; `.png` отрисованы Python/Pillow.
