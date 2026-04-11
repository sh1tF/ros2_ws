# My ROS2 Package

## Список узлов
1. **talker_node** — публикует сообщения в топик.
2. **listener_node** — подписывается на топик и выводит данные в консоль.

## Список топиков
- `/chatter` (String) — передача текстовых сообщений.

## Инструкция по запуску
1. Сборка: `colcon build`
2. Настройка окружения: `source install/setup.bash`
3. Запуск: `ros2 run <package_name> talker_node`
