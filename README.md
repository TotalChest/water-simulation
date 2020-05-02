# Water-Simulation
Симуляция водной поверхности на OpenGL. Уравнение мелкой воды

### Сборка:
```bash
$ mkdir build
$ cd build
$ cmake -DCMAKE_BUILD_TYPE=Release ..
$ make -j 4
```

### Запуск:
```bash
$ ./main
```

### Управление:
- **Q** - вкл/выкл каркасную визуализацию поверхности воды
- **E** - поставить/убрать лодку
- **Стрелочки** - управление лодкой
- **WASD** - движение камеры
- **Мышь** - поворот камеры
- **R** - закрыть программу

### Дополнительные баллы:
- Текстуры
- Преломления
- Управление камерой
- Интерактивность
- Лодка

### Примеры: 
![Example](examples/Scene_1.gif)
![Example](examples/Scene_2.gif)
![Example](examples/Scene_3.gif)
