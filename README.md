# awesome-mobile-shits

短时间内应该不会考虑静态页或者 wiki，请直接 ctrl + f 进行搜索。


- 移动端/三星 galaxy 轻奢版 SM-G8750/曲面屏/mobile/背景图/Banner
- - desc: banner 不要用 `background` 加 `background-size: container/cover` 来做，会出现奇葩的缩放（正常的都不会这样），且自带浏览器正常，所有其它 app 里的 webview 都不正常
- - workaround: 换成 `img` 标签，显式地设置 `width`（貌似显式的设置 `height` 不行）
