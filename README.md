# Person tracking

![tracking](docs/01.gif)

## Задача

- Дан видеопоток с камеры с проходящими ней объектами.
- Решить задачу трекинга этих объектов.
- Реализовать UI демонстрирующий это.

## Стек технологий

- onnx\tf\pytorch для инференса моделей СНС
- FastAPI для Web API
- Html + css для web ui

## Интерфейс

- http://domain-name/api/v1/ping - проверка работоспособности сервиса
- ws://domain-name/api/v1/stream - web-socket для получения видеопотока
- http://domain-name/index.thml - страничка с web ui