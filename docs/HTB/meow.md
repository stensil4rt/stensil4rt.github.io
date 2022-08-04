---
template: overrides/blog.html
description: >
  Это описание коробки  ‘Meow’. 
search:
  exclude: true
hide:
  - feedback
---

# Описание

__Это описание коробки  ‘Meow’, входящей в состав лабораторий ‘Starting Point’,
и имеет оценку сложности  ‘Very Easy’.__

<aside class="mdx-author" markdown>
![@squidfunk][@squidfunk avatar]

<span>__Martin Donath__ · @squidfunk</span>
<span>
:octicons-calendar-24: September 26, 2021 ·
:octicons-clock-24: 5 min read ·
[:octicons-tag-24: 7.3.0+insiders-3.1.1][insiders-3.1.1]
</span>
</aside>

  [@squidfunk avatar]: https://avatars.githubusercontent.com/u/932156
  [insiders-3.1.1]: ../../insiders/changelog.md#3.1.1

---

## Подключение для взлома Коробки

![image](https://user-images.githubusercontent.com/62753044/182839883-3ec60216-1f2a-413c-8e14-758ec84ed2f9.png)
Проверяем, чтобы подключение было - зеленым!
![image](https://user-images.githubusercontent.com/62753044/182839918-0a972e95-2271-4e4a-9038-73206256ddff.png)
![image](https://user-images.githubusercontent.com/62753044/182840028-5d7d8bff-4dc1-4572-85c5-9e8f206593a9.png)
Получаем IP адрес
![image](https://user-images.githubusercontent.com/62753044/182840142-7c8ac0d9-e2c9-4ce4-b19e-ef252c460c73.png)

## Сканирование
Первый шаг любого теста на проникновение в цель известен как сканирование. Это документация о текущем состоянии цели, чтобы узнать о ней как можно больше.
Давайте воспользуемся командой ping для IP-адреса цели, чтобы узнать, достигают ли наши пакеты места назначения. Итак, набрав команду 
```
ping {target_IP}
```
![image](https://user-images.githubusercontent.com/62753044/182840469-8da8f2a3-f318-4aaa-b61b-85178af6c96e.png)



