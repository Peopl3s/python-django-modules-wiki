# Django Modules Wiki

---
 
[Django](https://github.com/django/django) — веб-фреймворк Python высокого уровня, который способствует быстрой разработке и чистому, прагматичному дизайну.

## Содержание

---

- [Admin](#admin)
- [Auth](#auth)
- [Rest API](#rest-api)
- [Models](#models)
- [WYSIWYG](#wysiwyg)
- [Utils](#utils)
- [Другие библиотеки](#другие-библиотеки)

### Admin
- [django-admin-rangefilter](https://github.com/silentsokolov/django-admin-rangefilter/) - Фильтр по диапазону дат и числовому диапазону.
- [django-admin-sortable2](https://github.com/jrief/django-admin-sortable2/) - Drag-and-drop сортировка для `admin.ModelAdmin`, `admin.StackedInline` или `admin.TabularInline`.
- [django-image-cropping](https://github.com/jonasundderwolf/django-image-cropping/) - Кроппинг загруженных изображений через панель администратора.
- [django-nested-admin](https://github.com/theatlantic/django-nested-admin/) - Позволяет вложить `InlineModelAdmin` друг в друга. Drag-and-drop сортировка с помощью `django-admin-sortable2`.
- [django-admin-charts](https://pypi.org/project/django-admin-charts/) - Позволяет создавать графики статистики для `django-admin` и `django-admin-tools`.

### Auth
- [django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit/) - Набор утилит для интеграции OAuth2 в ваш проект.
- [django-two-factor-auth](https://github.com/jazzband/django-two-factor-auth/) - Двухфакторная аутентификация для Django.
- [django-rest-knox](https://github.com/James1345/django-rest-knox/) - Аутентификация основанная на `TokenAuthentication`, решающая некоторые проблемы стандратной реализации.

### Models
- [django-solo](https://github.com/lazybird/django-solo/) - Реализация `singleton` паттерна для моделей.
- [django-model-utils](https://github.com/jazzband/django-model-utils/) - Миксины и утилиты для работы с моделями (различные поля, модели, менеджеры).
- [django-autoslug](https://github.com/justinmayer/django-autoslug/) - Автоматически заполняет слаг.
- [django-phonenumber-field](https://github.com/stefanfoulis/django-phonenumber-field/) - Реализация интерфейса для конвертации, валидации и работы с телефонными номерами.
- [django-modeltranslation](https://django-modeltranslation.readthedocs.io/) - Перевод динамического контента на несколько языков.
- [django-simple-history](https://github.com/jazzband/django-simple-history/) - Автоматическое сохранение состояния модели при каждом создании/обновлении/удалении.
- [django-braces](https://django-braces.readthedocs.io/en/latest/) - Набор миксинов для Django-моделей.

### Rest API
- [django-rest-framework](https://github.com/encode/django-rest-framework/) - Мощный и гибкий набор инструментов для создания веб-API.
- [django-cors-headers](https://github.com/adamchainz/django-cors-headers) - Позволяет настраивать заголовки CORS для Django приложений.
- [django-channels](https://github.com/django/channels/) - Протокол WebSockets для Django, позволяющий в режиме реального времени взаимодействовать с клиентами.
- [django-ninja](https://github.com/vitalik/django-ninja/) - Быстрая и гибкая библиотека для создания API на основе функций в Django использующая `pydantic`.
- [drf-spectacular](https://github.com/tfranzel/drf-spectacular/) - Автоматический генерация `Swagger/OpenAPI 3` спецификации.
- [drf-yasg](https://github.com/axnsan12/drf-yasg) - Автоматический генерация `Swagger/OpenAPI 2` спецификации.

### WYSIWYG
- [django-ckeditor](https://github.com/django-ckeditor/django-ckeditor/) - CKEditor для Django с возможностью загрузки и предпросмотра изображений.
- [django-quill-editor](https://github.com/LeeHanYeong/django-quill-editor/) - Quill.js интеграция в Django Admin и Django Forms.
- [django-editorjs-fields](https://github.com/2ik/django-editorjs-fields/) - Editor.js интеграция в Django Admin и Django Forms.
- [django-tinymce](https://github.com/jazzband/django-tinymce/) - TinyMCE интеграция.

### Utils
- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar/) - Набор панелей, которые отображают различную отладочную информацию о текущем запросе/ответе.
- [django-silk](https://github.com/jazzband/django-silk/) - Профилировщик запросов.
- [django-extensions](https://github.com/django-extensions/django-extensions/) - Набор различных команд, утилит, валидаторов и расширений для Django.
- [django-cleanup](https://github.com/un1t/django-cleanup) - Автоматически удаляет файлы `FileField`, `ImageField` и подклассов.


### Другие библиотеки
> В процессе редактирования.
- [dramatiq](https://dramatiq.io/) - Аналог Celery.                                                                                                                      
- [graphene-django](https://github.com/graphql-python/graphene-django) - Интеграция GraphQL.
- [django-embed-video](https://django-embed-video.readthedocs.io/) - Django-приложение для удобного встраивания видео с YouTube и Vimeo и музыки из SoundCloud (можно писать свои бекенды, например, для ВК).
- [django-notifications](https://github.com/django-notifications/django-notifications) - Работа с уведомлениями.
- [django-select2](https://django-select2.readthedocs.io/) - Кастом autocomplete_fields для Django.
- [django-filter](https://django-filter.readthedocs.io/en/stable/) - Позволяет пользователям отфильтровать набор запросов на основе полей модели и отображает форму, позволяющую это сделать.
- [django-places](https://github.com/oscarmcm/django-places) - Django-приложение для хранения мест с функцией автозаполнения и связанной с выбранным местом картой.
- [pytils](https://github.com/last-partizan/pytils) - Pytils это инструменты для работы с русскими строками (транслитерация, числительные словами, русские даты и т.д.).
- [aldjemy](https://github.com/aldjemy/aldjemy) - Aldjemy интегрирует SQLAlchemy в существующий Django-проект, чтобы помочь вам создавать сложные запросы, которые не под силу Django ORM.
- [freezegun](https://github.com/spulec/freezegun) - Библиотека, которая позволяет вашим Python-тестам путешествовать во времени, подражая модулю datetime.
