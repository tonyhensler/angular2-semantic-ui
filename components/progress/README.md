# Progress Usage
由于progress标签属于html自带标签，所以此控件加入了前缀 `<l-progress></l-progress>`
```html
  <l-progress [label]="'Uploading file'" [percent]="percent" [text]="''" [color]="'teal'" [size]="'standard'"></l-progress>
```

# Options
- percent: 必选，进度（0-100）
- text: 可选，progress显示文字（50%、70%......）
- label: 可选，标签（显示在porgress下方）
- color: 可选，背景色, 具体可参见<a href="http://semantic-ui.com/modules/progress.html#color">Semantic-Ui Progress Color</a>
- size: 可选，控件尺寸, 具体可参见<a href="http://semantic-ui.com/modules/progress.html#size">Semantic-Ui Progress Size</a>