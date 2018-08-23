# Style Settings Optional

## Drop-Down setting:

### 隐藏内容（主页）[hide]

#### 不隐藏[none]

pass

#### 隐藏页脚（右下角的链接）[footer]

```css
.Footer {
    display: none!important;
}
```

#### 隐藏按钮（反馈与回到顶部）[button]

```css
a.btn-backtotop.btn-action, .CornerButtons, .FeedbackButton-button-3waL {
    display: none !important;
}
```

#### DEFAULT: 隐藏页脚、按钮[all]

```css
a.btn-backtotop.btn-action, .CornerButtons, .FeedbackButton-button-3waL {
    display: none !important;
}
.Footer {
    display: none!important;
}
```

### 隐藏内容（问题）[recommend]

#### DEFAULT: 隐藏相关推荐[recommends]

```css
/*相关推荐*/
div.Card-header.RelatedCommodities-title,
div.Card-section.RelatedCommodities-list {
    display: none !important;
}
```

#### 不隐藏[none]

pass

### 图片明暗变化[img]

#### DEFAULT: 开启[pics]

```css
/*图片明暗变化*/
img {
    opacity: .7 !important;
    transition: opacity .2s
}
img:hover,
a:hover img,
#mpiv-popup {
    opacity: 1 !important
}
```

#### 关闭[none]

pass

### 隐藏内容（搜索）[search]

#### DEFAULT: 显示[none]

pass

#### 隐藏搜索自动补全[autocomplete]

```css
/*搜索自动补全*/
div.Menu.AutoComplete-menu.SearchBar-menu.SearchBar-noValueMenu,
div.Menu.AutoComplete-menu.SearchBar-menu.SearchBar-hasValueMenu {
    display: none !important;
}
```
