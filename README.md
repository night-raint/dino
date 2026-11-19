# Dino 2D (Fantasy Forest Runner)

Проект 2D-игры в стиле Runner на Unity 2022.3.62f3 LTS.

## Структура визуальных ассетов (Assets/ArtAssets/)
Все элементы выполнены в пиксель-арт стилистике с именованием строго в стиле **PascalCase** и разбиты по тематическим подпапкам:

- `Characters/` — спрайты главного героя:
  - `KnightIdle.png` — рыцарь в состоянии покоя
  - `KnightRun1.png`, `KnightRun2.png` — покадровая анимация бега
  - `KnightJump.png` — прыжок
  - `KnightDuck.png` — приседание под препятствия
- `Backgrounds/` — меняющийся фон (день / ночь):
  - `Day/` — дневной сказочный лес:
    - `SkyForestDay.png` — дневное небо
    - `ForestTreesDay.png` — силуэты лесных деревьев
    - `GroundForestDay.png` — травяная тропа
  - `Night/` — ночной мистический лес:
    - `SkyForestNight.png` — ночное небо
    - `ForestTreesNight.png` — ночные деревья
    - `MoonForestNight.png` — луна
    - `FirefliesNight.png` — светящиеся светлячки
    - `GroundForestNight.png` — ночная тропа
- `Enemies/` — 2 вида противников:
  - `Flying/` — летающий враг:
    - `BatFly1.png`, `BatFly2.png` — пещерная летучая мышь с анимацией взмаха крыльев
  - `Ground/` — наземные препятствия на пути:
    - `MushroomMonster.png` — ядовитый гриб
    - `SpikeTrap.png` — шипы ловушки

## Конвенция коммитов
В проекте используется спецификация [Conventional Commits](https://www.conventionalcommits.org/):
- `feat`: добавление ассетов и игровых компонентов
- `chore`: настройка проекта и конфигурационных файлов
- `docs`: документация
