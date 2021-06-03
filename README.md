<h1 align="center">
  <br>logseq-bonofix-theme<br>
</h1>

<p align="center">
  <a href="#install">📦 Install</a>
   | 
  <a href="#screenshots">🌠 Screenshots</a>
   | 
  <a href="#whats-improved">✨ What's improved</a>
   | 
  <a href="#how-to-build">🔨 How to build</a>
</p>

This is a theme for [Logseq](https://github.com/logseq/logseq), focusing on **UI bug fixes** with massive mobile experience improvements.

## Install

Check your Version

### If you are using Chrome(chromium) or desktop version:

- General installation

  Copy the whole content of [custom.css](https://raw.githubusercontent.com/Sansui233/logseq-bonofix-theme/master/custom.css) into your logseq/custom.css file.

- If you are always working online

  Copy this one-line-installation into your logseq/custom.css file
  
  ```css
  @import url('https://cdn.jsdelivr.net/gh/sansui233/logseq-bonofix-theme/custom.css')
  ```

### If you are using Safari(webkit):

Copy this one-line-installation into your logseq/custom.css file

```css
@import url('https://cdn.jsdelivr.net/gh/sansui233/logseq-bonofix-theme/custom-safari.css')
```

### If you use Chrome(chromium) on desktop and Safari(webkit) on mobile

Recommend to use `custom-safari.css`. Then install Chrome extension [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), and add this line to logseq.com:

```css
.CodeMirror-line {
    width: 0;
}
```

## Screenshots

The style is strongly inspired by [logseq-bujo-theme](https://github.com/PiotrSss/logseq-bujo-theme ) and [Notion](https://notion.so). The code is mainly based on bujo theme, and you may find the style really notion-like.

![Desktop](./media/Desktop.png)

![Mobile](./media/Mobile.png)

## What's improved

**Bug fix**

- Fix code block overflow bug, see 👉 [details](https://github.com/Sansui233/logseq-bonofix-theme/blob/master/docs/fix-codemirror.md)

**Improvements**

- Code block style for both dark theme and white theme

- Better spacing to show the heading's outline

- Make tippy window like responsive card instead of filling the screen and obscuring text

- Mobile: full width search lists

- Mobile: fixed top bar

- Mobile: larger sync dot to be pressed

- Mobile: More stable scrolling experience

- No online fonts to work perfectly offline (for Google fonts service is not available in some area such as China)

**Style**

- add calender emoji before journal title  
  <img src="./media/journal-title-emoji.png" alt="Journal Title Emoji" width="600px" />

- style tags as labels  
  <img src="./media/tag-label.png" alt="Tags" width="300px" />

## How to build

1. Install [node](https://nodejs.org/)
2. Install sass  
  ```shell
  npm install
  ```
3. Clone repo  
  ```shell
  git clone https://github.com/Sansui233/logseq-bonofix-theme.git && cd logseq-bonofix-theme
  ```
4. Run build  
  ```shell
  npm run build
  ```


## Thanks

- [Logseq](https://github.com/logseq/logseq)
- [logseq-bujo-theme](https://github.com/PiotrSss/logseq-bujo-theme) by PiotrSss
- Dark mode of [Notion](https://notion.so)
- All feedbacks from email and discord
