# Divider 分隔符

## 基本使用
<f-divider margin="20px">我是分隔符</f-divider>
::: details 显示代码

```html
<f-divider>我是分隔符</f-divider>
```

:::

## 文字显示位置

`position` 属性可以配置文字显示的位置

<p/>
<f-divider position='left'>我是左边的文字</f-divider>
<p/>
<f-divider position='center'>我是居中的文字</f-divider>
<p/>
<f-divider position='right'>我是右边的文字</f-divider>
<p/>

::: details 显示代码

```html
<f-divider position='left'>我是左边的文字</f-divider>
<f-divider position='center'>我是居中的文字</f-divider>
<f-divider position='right'>我是右边的文字</f-divider>
```
:::

## 自定义颜色

`color` 属性可以配置不同的线条颜色

`fontColor` 属性配置不同文字颜色

`background` 属性配置文字背景颜色

<f-divider color='green' margin="30px" fontColor="green" background="yellow">我是绿色</f-divider>
<f-divider color='blue' margin="30px" fontColor="blue" background="yellow">我是蓝色</f-divider>
<f-divider color='#f40' margin="30px" fontColor="#f40" background="yellow">我是某宝色</f-divider>

::: details 显示代码

```html
<f-divider color='red' fontColor="red">我是红色</f-divider>
<f-divider color='blue' fontColor="blue">我是蓝色</f-divider>
<f-divider color='#f40' fontColor="#f40">我是某宝色</f-divider>
```
:::

## 上下距离

`margin` 可以配置距离上下的距离

<div>假装是内容</div>
<f-divider margin="60px" fontColor="blue">距离上下60px</f-divider>
<div>假装是内容</div>

::: details 显示代码

```html
<f-divider margin="60px" fontColor="green" >距离上下60px</f-divider>
```

:::

## 竖着显示

如果你不喜欢横着显示 `vertical` 属性可以竖着显示

如果使用 `vertical`属性，`color`&`background` 将会失效

<f-divider vertical color="red">竖着显示</f-divider>

::: details 显示代码

```html

<f-divider vertical color="red" >距离上下60px</f-divider>

```

:::



## Attributes

| 参数         | 说明                                                                                      | 类型    | 可选值                                        | 默认值  |
| ------------ | --------------------------------------------------------------------------------------- | ------- | --------------------------------------------- | ------- |
| `position`       | 文字显示位置                                                                               | string  | ` left` <br /> `center`<br /> `right` | center |
| `vertical`       | 显示风格                                                                           | boolean  | `true` <br /> `false` | false      |
| `color`       | 线条颜色                                                                        | string  | ——                                            | ——  |
| `fontColor`      | 文字颜色                                                                       | string  |——| ——      |
| `background`   | 背景颜色                                                                                  | boolean | ——                                            | ——   |
| `margin`  | 上下距离                                                                              | string  | ——                                            | ——      |
| `right-icon` | 右侧的 icon                                                                               | string  | ——                                            | ——      |