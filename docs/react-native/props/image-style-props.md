# Image Style Props

## Свойства / Props

### `borderTopRightRadius`

Радиус верхнего правого угла.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`border-top-right-radius`](../../css/border-top-right-radius.md) - аналог в CSS

### `backfaceVisibility`

Показывать обратную сторону элемента или нет.

| Тип                         | Обязательный |
| --------------------------- | ------------ |
| `enum('visible', 'hidden')` | Нет          |

[`backface-visibility`](../../css/backface-visibility.md) - аналог в CSS

### `borderBottomLeftRadius`

Радиус нижнего левого угла.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`border-bottom-left-radius`](../../css/border-bottom-left-radius.md) - аналог в CSS

### `borderBottomRightRadius`

Радиус нижнего правого угла.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`border-bottom-right-radius`](../../css/border-bottom-right-radius.md) - аналог в CSS

### `borderColor`

Цвет рамки.

| Тип     | Обязательный |
| ------- | ------------ |
| `color` | Нет          |

[`border-color`](../../css/border-color.md) - аналог в CSS

### `borderRadius`

Радиус углов рамки.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`border-radius`](../../css/border-radius.md) - аналог в CSS

### `borderTopLeftRadius`

Радиус верхнего левого угла.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`border-top-left-radius`](../../css/border-top-left-radius.md) - аналог в CSS

### `backgroundColor`

Цвет фона.

| Тип     | Обязательный |
| ------- | ------------ |
| `color` | Нет          |

[`background-color`](../../css/background-color.md) - аналог в CSS

### `borderWidth`

Ширина рамки.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`border-width`](../../css/border-width.md) - аналог в CSS

### `opacity`

Прозрачность элемента.

| Тип      | Обязательный |
| -------- | ------------ |
| `number` | Нет          |

[`opacity`](../../css/opacity.md) - аналог в CSS

### `overflow`

| Тип                         | Обязательный |
| --------------------------- | ------------ |
| `enum('visible', 'hidden')` | Нет          |

[`overflow`](../../css/overflow.md) - аналог в CSS

### `resizeMode`

| Тип                                                       | Обязательный |
| --------------------------------------------------------- | ------------ |
| `enum('cover', 'contain', 'stretch', 'repeat', 'center')` | Нет          |

### `tintColor`

| Тип     | Обязательный |
| ------- | ------------ |
| `color` | Нет          |

### `overlayColor`

| Тип      | Обязательный | Платформа |
| -------- | ------------ | --------- |
| `string` | Нет          | Android   |

Если изображение имеет закругленные углы, указание `overlayColor` приведет к тому, что оставшееся пространство в углах будет заполнено сплошным цветом. Это полезно в случаях, которые не поддерживаются реализацией Android закругленных углов:

- Некоторые режимы изменения размера, такие как `contain`
- Анимированные GIF

Типичный способ использования этого `prop` - изображения, отображаемые на сплошном фоне, и установка `overlayColor` на тот же цвет, что и на фоне.

Подробнее о том, как это работает под капотом, смотрите [https://frescolib.org/docs/rounded-corners-and-circles.html](https://frescolib.org/docs/rounded-corners-and-circles.html)

## Ссылки

- [Image Style Props](https://facebook.github.io/react-native/docs/image-style-props)