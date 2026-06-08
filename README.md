Smartphone as a Screen-Scanner: a Flat Matrix Capable of Reading Light

A smartphone screen can be understood not only as a device for displaying images, but also as a potential optical matrix capable of reading the light that falls onto it. If its pixels operate in a two-phase mode — first emitting light, then switching into a sensing phase — the display could receive a ready-made “image” of the light distributed across its surface.

The main limitation is that this image is tied to the plane of the screen.

In other words, the screen does not see the full volume of space at once like a camera with a lens. Instead, it reads the distribution of light across its own surface:

X coordinate on the screen
Y coordinate on the screen
brightness / color / frequency / phase of incoming light

However, depth and volume could still be reconstructed algorithmically if additional cues are available:

- how the glare changes when the phone moves
- the angle at which the light arrives
- how the brightness gradient is distributed
- whether several frequencies, colors, or pulses are used
- how the reflection shifts between frames
- whether the shape of the illumination is known

In this case, the screen becomes not just a flat scanner, but a flat input surface for reconstructing volume.

A good formulation for the document:

Such a screen is not a camera in the classical sense: it has no lens that immediately forms an image of space. It receives a map of light on its own plane. However, with the right sensing algorithm, temporal modulation, device motion, or gradient analysis, this flat map can be used to reconstruct volumetric information about the environment in front of the screen.

Even shorter:

The screen receives a two-dimensional light map, but the algorithm can extract three-dimensional features from it.

Core idea:

A smartphone screen is not an eye, but a retina without a lens.
With motion, modulation, and computation added, it begins to function as a spatial scanner.


sameshit
Смартфон как экран-сканер: плоская матрица, способная читать свет

Экран смартфона можно рассматривать как потенциальную оптическую матрицу, которая способна не только показывать изображение, но и считывать падающий на неё свет. Если пиксели работают в двухтактном режиме — фаза свечения, затем фаза приёма — дисплей может получать готовую “картинку” света, падающего на его поверхность.

Главное ограничение: это картинка, привязанная к плоскости экрана.

То есть экран видит не весь объём сразу, как камера с объективом, а распределение света по своей поверхности:

координата X на экране
координата Y на экране
яркость / цвет / частота / фаза падающего света

Но объём действительно можно восстанавливать алгоритмически, если есть дополнительные признаки:

- как меняется блик при движении телефона
- под каким углом приходит свет
- как распределяется градиент яркости
- есть ли несколько частот / цветов / импульсов
- как отражение сдвигается между кадрами
- известна ли форма подсветки

Тогда экран становится не просто плоским сканером, а плоским входом для реконструкции объёма.

Хорошая фраза для документа:

Такой экран не является камерой в классическом смысле: у него нет объектива, который сразу строит изображение пространства. Он получает карту света на собственной плоскости. Однако при правильном алгоритме считывания, временной модуляции, движении устройства или анализе градиентов эта плоская карта может использоваться для восстановления объёмной информации о среде перед экраном.

И короче:

Экран получает двумерную световую карту, но алгоритм может извлекать из неё трёхмерные признаки.

Смысл сильный:
смартфонный экран — это не глаз, а сетчатка без линзы.
Но если добавить движение, модуляцию и вычисление — он начинает работать как сканер пространства.
