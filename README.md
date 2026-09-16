Морозов Роман Сергеевич, группа 221341, вариант 6, лабораторная №1
## Git Hook

Hook находится в файле:

.githooks/pre-commit

Он автоматически запускает flake8 перед каждым коммитом.

### Установка hook
bash
git config core.hooksPath .githooks
chmod +x .githooks/pre-commit
