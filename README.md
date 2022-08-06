# Kustomization

#### Задача:
1. Создать базовое kubernetes приложение состоящее из Deployment, Service и Secret, использующее образ wordpress. В Secret должны находиться реквизиты доступа к базе
1. С помощью kustomize создать два варианта приложения - staging и production
1. Staging вариант должен быть запущен в неймспейсе staging, иметь label variant: staging, не должен хранить данные
1. Production вариант должен запущен в неймспейсе production, иметь лейбл variant: production, дополнительно иметь PersistentVolume для хранения пользовательских файлов

Прислать получившееся kustomize приложение в архиве

Инструменты:
kustomize
kubectl
minikube
