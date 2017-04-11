# ionicLearnFile
学习ionic文档

1. ion-side-menus： 是一个带有边栏菜单的容器，可以通过点击按钮或者滑动屏幕来展开菜单。
2. ion-side-menu-content：展示主要内容的容器，可以通过滑动屏幕来展开menu。
3. ion-side-menu：存放侧边栏的容器。


# ionic 头部与底部

### Header(头部)
1. Header是固定在屏幕顶部的组件,可以包如标题和左右的功能按钮。
2. ionic 默认提供了许多种颜色样式，你可以调用不同的样式名，当然也可以自定义一个。

### Sub Header（副标题）
1. Sub Header同样是固定在顶部，只是是在Header的下面，就算没有写Header这个，Sub Header这个样式也会距离顶部有一个Header的距离。颜色样式同 Header 。

### Footer(底部)
1. Footer 是在屏幕的最下方，可以包含多种内容类型。
2. 此外，如果底部没有标题，但是又需要右边的按钮，你需要在右侧按钮添加 pull-right如:

# ionic 按钮
1. 按钮是移动app不可或缺的一部分，不同风格的app，需要的不同按钮的样式。默认情况下，按钮显示样式为：display: inline-block。
2. button-block 样式按钮显示为：display: block，它将完全填充父元素的宽度，包含了内边距属性padding。
3. 使用 button-full 类，可以让按钮显示完全宽度，且不包含内边距padding。

### 不同大小的按钮
1. button-large 设置为大按钮，button-small 设置为小按钮。

### 无背景按钮
1. button-outline 设置背景为透明。

### 无背景与边框按钮
1. button-clear 设置按钮背景为透明，且无边框。

### 图标按钮
1. 我们可以在按钮上添加图标。

### 头部/底部添加按钮
1. 头部/底部可以添加按钮，按钮的样式根据头部/底部来设定，所以你不需要为按钮添加额外的样式。
2. button-clear 类可以设置无背景和边框的头部/底部按钮。

### 按钮栏
1. 我们可以使用 button-bar 类来设置按钮栏。以下实例中，我们在头部和内容中添加了按钮栏。

# ionic 列表
1. 列表是一个应用广泛的界面元素，在所有移动app中几乎都会使用到。
2. 列表可以是基本文字、按钮，开关，图标和缩略图等。
3. 列表项可以是任何的HTML元素。容器元素需要list类，每个列表项需要使用item类。
4. ionList和ionItem可以很容易的支持各种交互方式，比如，滑动编辑，拖动排序，以及删除项。

### 列表分隔符
1. 我们可以使用 item-divider 类来为列表创建分隔符，默认情况下，列表项以不同的背景颜色和字体加粗来区分，但你也可以很容易的定制他。

### 带图标列表
1. 我们可以在列表项的左侧或右侧指定图标。
2. 使用 item-icon-left 图标在左侧， item-icon-right 设置图标在右侧。如果你需要在两边都有图标，则两个类都添加上即可。

### 按钮列表
1. 使用 item-button-right 或 item-button-left 类将按钮放在列表项中。

### 带头像列表
1. 使用 item-avatar 来创建一个带头像的列表：

### 缩略图列表
1. item-thumbnail-left 类用于添加左侧对齐的缩略图， item-thumbnail-right 类用于添加右侧对齐的缩略图。

### 内嵌列表(inset list)
1. 我们可以在容器当中内嵌列表，列表不会显示完整的宽度。
2. 内嵌列表的样式为：list list-inset，与常规列表区别是，它设置了外边距（marign）,类似于选项卡。
3. 内嵌列表是没有阴影效果的，滚动时效果会更好。

# ionic 卡片
1. 近年来卡片(card)的应用越来越流行，卡片提供了一个更好组织信息展示的工具。
2. 针对移动端的应用，卡片会根据屏幕大小自适应大小。
3. 我们可以很灵活的控制卡片的显示效果，甚至实现动画效果。
4. 卡片一般放在页面顶部，当然也可以实现左右切换的功能。
5. 卡片(card)默认样式带有box-shadow(阴影)，由于性能的原因，和他类似的元素像 list list-inset 并没有阴影。
6. 如果你有很多的卡片，每个卡片都有很多子元素，建议使用内嵌列表（inset list）。

### 卡片的头部与底部
1. 我们可以通过添加 item-divider 类为卡片添加头部与底部：

### 卡片列表
1. 使用 list card 类来设置卡片列表：

### 带图片卡片
1. 卡片中使用图片，效果会更好

### 卡片展现


# ionic 表单和输入框
1. list 类同样可以用于 input 元素。item-input 和 item 类指定了文本框及其标签。

### 输入框属性：placeholder
1. 以下实例中，默认为100%宽度（左右两侧没有边框），并使用 placeholder 属性设置输入字段预期值的提示信息。

### 输入框属性：input-label
1. 使用 input-label 将标签放置于输入框 input 的左侧。

### 堆叠标签
1. 堆叠标签通常位于输入框的头部。每个选项使用 item-stacked-label 类指定。 每个输入框需要指定 input-label。以下实例也使用了 placeholder 属性来设置信息输入提示。

###  浮动标签
1. 浮动标签类似于堆叠标签，但浮动标签有一个动画的效果，每个选项需要指定 item-floating-label 类，输入标签需要指定 input-label。

### 内嵌表单
1. 默认情况下每个输入域宽度都是100%，但我们可以使用 list list-inset 或 card 类设置表单的内边距(padding)， card 类带有阴影。

### 内嵌输入域
1. 使用 list-inset 设置内嵌实体列表。 使用 item-input-inset 样式可以内嵌一个按钮。

### 带图标的输入框
1. item-input 输入框可以很简单的添加图标。 图标可以在 <input> 前添加。

### 头部输入框
1. 输入框可放置在头部，并可添加提交或取消按钮。
