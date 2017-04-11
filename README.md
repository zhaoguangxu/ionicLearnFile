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

# ionic Toggle(切换开关)
1. 切换开关类似与 HTML 的 checkbox 标签，但它更易于在移动设备上使用。
2. 切换开关可以使用 toggle-assertive 来指定颜色。
3. 该实例有是多个切换开关列表。注意，每个选项的 item 类后需要添加 item-toggle 类。

# ionic checkbox（复选框）
1. ionic 里面的 Checkbox 和普通的 Checkbox 效果上其实相差不大，只是样式上有所不同。
2. 注意，每个选项的 item 类后需要添加 item-checkbox 类。

# ionic 单选框
1. ionic 单选按钮与标准 type="radio" 的 input元素类似。以下展示了现代app类型的单选按钮。
2. 每个 item-radio 中的 type="radio" 的 input 元素的 name 属性都相同。radio-icon 类用于是否显示图标。

# ionic Range
1. ionic Range 是一个滑块控件，ionic 为 Range 提供了很多种默认的样式。而且你可以在许多种元素里使用它比如列表或者 Card 。

# ionic select
1. ionic select 的 select 相比原生的要更加美观些。但是弹出的可选选项样式是浏览器默认的。
2. 每个平台上的可选项样式都是不一样的，在PC电脑的浏览器上，你会看到传统的下拉界面，Android 上会弹出单选按钮选项，iOS 有个滚轮操作界面。

# ionic tab(选项卡)
1. ionic tab(选项卡) 是水平排列的按钮或者链接，用以页面间导航的切换。它可以包含文字和图标的组合，是一种移动设备上流行的导航方法。
2. 以下选项卡容器使用了 tabs 类，每个选项卡使用 tab-item 类。默认情况下，选项卡是文本的，并没有图标。
3. 默认情况，选项卡颜色为默认，你可以设置以下不同颜色样式：tabs-default ，tabs-light ，tabs-stable ，tabs-positive ，tabs-calm ，tabs-balanced ，tabs-energized ，tabs-assertive ，tabs-royal ，tabs-dark。
4. 要隐藏选项卡栏，可使用 tabs-item-hide 类。

### 图标选项卡
1. 在 tabs 类后添加 tabs-icon-only 类可设置只显示图标选项卡。

### 顶部图标+文字选项卡
1. 在 tabs 类后添加 tabs-icon-top 类可设置顶部图标+文字选项卡。

### 左侧图标+文字选项卡
1. 在 tabs 类后添加 tabs-icon-left 类可设置左侧图标+文字选项卡。

### 条纹样式选项卡
1. 可以在带有 tabs 的样式名的元素上添加 tabs-striped 来实现像 Android 风格的 tabs。也可以添加 tabs-top 来实现选项卡在页面顶部。
2. 条纹选项卡颜色可通过 tabs-background-{color} 和 tabs-color-{color} 来控制， {color} 值可以是：default, light, stable, positive, calm, balanced, energized, assertive, royal, 或 dark。
3. 注意：如果要再选项卡上设置头部标题，需要使用 has-tabs-top 类。

# ionic 网格(Grid)
1. ionic 的网格(Grid)和其他大部分框架有所不同，它采用了弹性盒子模型(Flexible Box Model) 。而且在移动端，基本上的手机都支持。row 样式指定行，col 样式指定列。

### 同等大小网格
1. 在带有 row 的样式的元素里如果包含了 col 的样式，col 就会设置为同等大小。

### 指定列宽
1. 你可以设定一行中各个列的大小不一样。默认情况下，列都会被划分为同等大小。但你也可以按百分比来设置列的宽度（一行为 12 个网格）。
2. 注意：实例中，每个 col 样式会自动添加上边框和灰色背景。

### 有偏移量的网格
1. 列可以设置左侧偏移量，实例如下：

### 纵向对齐网格
1. 弹性盒子模型可以很容易设置列纵向对齐。纵向对齐包含顶部，中间部分，底部，可以应用到每一行的列，或者指定的某列。

### 响应式网格
1. 手持设备屏幕在切换时，例如横屏，竖屏等。就需要设置每行的网格可以实现根据不同宽度自适应大小。
2. 不同设备响应式类的样式如下:
    +.responsive-sm	小于手机横屏
    +.responsive-md	小于平板竖屏
    +.responsive-lg	小于平板横屏

# ionic 颜色
1. ionic 提供了很多颜色的配置，当然你可以根据自己的需要自定义颜色。

# ionic icon(图标)
1. ionic 也默认提供了许多的图标，大概有 700 多个，针对 Android 和 iOS 有不同的样式。
2. Ionic icons 官网: http://ionicons.com/
3. 国内图标样式 CDN 地址：https://cdn.bootcss.com/ionicons/2.0.1/css/ionicons.min.css。
4. 用法也非常的简单，由一个 icon 类及指定图标类组成

# ionic 上拉菜单(ActionSheet)
1. 上拉菜单(ActionSheet)通过往上弹出的框，来让用户选择选项。
2. 非常危险的选项会以高亮的红色来让人第一时间识别。你可以通过点击取消按钮或者点击空白的地方来让它消失。
3. 在代码中触发上拉菜单，需要在你的 angular 控制器中使用 $ionicActionSheet 服务：
4. $ ionPlatform 用于检测当前的平台，以及如何覆盖PhoneGap / Cordova中的Android后退按钮。

# ionic 背景层
1. 我们经常需要在 UI 上，例如在弹出框、加载框、其他弹出层中显示或隐藏背景层。
2. 在组件中可以使用$ionicBackdrop.retain()来显示背景层，使用$ionicBackdrop.release()隐藏背景层。
3. 每次调用retain后，背景会一直显示，直到调用release消除背景层。

# ionic 下拉刷新
1. 在加载新数据的时候，我们需要实现下拉刷新效果，

# ionic 复选框
1. ionic 复选框（checkbox）与普通的 HTML 复选框没什么区别，以下实例演示了 ionic 复选框 ion-checkbox 的应用。

# ionic 单选框操作
1. 实例中，根据选中的不同选项，显示不同的值。

# ionic 切换开关操作
1. 以下实例中，通过切换不同开关 checked 显示不同的值，true 为打开，false 为关闭。

# ionic 手势事件
1. on-hold: 长按的时间是500毫秒。
2. on-tap: 这个是手势轻击事件，如果长按时间超过250毫秒，那就不是轻击了。。
3. on-double-tap: 手双击屏幕事件
4. on-touch: 这个和 on-tap 还是有区别的，这个是立即执行，而且是用户点击立马执行。不用等待 touchend/mouseup 。
5. on-release: 当用户结束触摸事件时触发。
6. on-drag: 这个有点类似于PC端的拖拽。当你一直点击某个物体，并且手开始移动，都会触发 on-drag。
7. on-drag-up: 向上拖拽。
8. on-drag-right: 向右拖拽。
9. on-drag-down: 向下拖拽。
10. on-drag-left:向左边拖拽。
11. on-swipe: 指手指滑动效果，可以是任何方向上的。而且也和 on-drag 类似，都有四个方向上单独的事件。
12. on-swipe-up: 向上的手指滑动效果。
13. on-swipe-right: 向右的手指滑动效果。
14. on-swipe-down: 向下的手指滑动效果。
15. on-swipe-left: 向左的手指滑动效果。

### $ionicGesture
1. 一个angular服务展示ionicionic.EventController手势。
2. 在一个元素上添加一个事件监听器。on(eventType, callback, $element)
    + eventType	  string	       监听的手势事件。
    + callback    function(e)    当手势事件发生时触发的事件。
    + $element    element        angular元素监听的事件。
    + options     object         对象。
3. 在一个元素上移除一个手势事件监听器。 off(eventType, callback, $element)
    + eventType	  string	       移除监听的手势事件。
    + callback    function(e)    移除监听器。
    + $element    element        被监听事件的angular元素。

# ionic 头部和底部

### ion-header-bar
1. 这个是固定在屏幕顶部的一个头部标题栏。如果给它加上'bar-subheader' 这个样式，它就是副标题。

### API
1. align-title       string	      这个是对齐 title 的。如果没有设置，它将会按照手机的默认排版(Ios的默认是居中，Android默认是居左)。它的值可以是 'left','center','right'。
2. no-tap-scroll     boolean      默认情况下，头部标题栏在点击屏幕时内容会滚动到头部，可以将 no-tap-scroll 设置为 true 来禁止该动作。。它的值是布尔值（true/false）。

### ion-footer-bar
1.  ion-footer-bar 是在屏幕的底部。
### API
与 ion-header-bar 不同的是，ion-footer-bar 只有 align-title 这个 API。
align-title          string       这个是对齐 title 的。如果没有设置，它将会按照手机的默认排版(Ios的默认是居中，Android默认是居左)。它的值可以是 'left','center','right'。

# ionic 列表操作
1. 列表是一个应用广泛在几乎所有移动app中的界面元素。ionList 和 ionItem 这两个指令还支持多种多样的交互模式，比如移除其中的某一项，拖动重新排序，滑动编辑等等。

### API
1. delegate-handle    字符串       该句柄定义带有$ionicListDelegate的列表。  
2. show-delete        布尔值       列表项的删除按钮当前是显示还是隐藏。
3. show-reorder       布尔值       列表项的排序按钮当前是显示还是隐藏。
4. can-swipe          布尔值       列表项是否被允许滑动显示选项按钮。默认：true。
