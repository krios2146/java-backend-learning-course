+++
title = 'Облачное хранилище файлов'
weight = 6
bookTOC = false
+++

# Облачное хранилище файлов

[ТЗ проекта](../projects/cloud-file-storage.md)

{{ projects | project_count }} реализаций на {{ projects | unique_languages }}. {{ projects | review_count }} ревью.

Присылайте ваши реализации в чат сообщества - [@zhukovsd_it_chat](https://t.me/zhukovsd_it_chat).

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{%+ for p in projects +%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{%+ endfor +%}
