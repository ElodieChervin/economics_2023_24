<!DOCTYPE html>
<html lang="en-US">
<head>
    <meta charset="UTF-8">
    <title>prelims_macro_lecture_1-fb318117-f5d4-4b1d-ab93-593d4db3a373</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.mathpix.com/fonts/cmu.css"/>
    <style>
  html,body {
    width: 100%;
    height: 100%;
  }
  *, *::before,*::after {
    box-sizing: border-box;
  }
  @-ms-viewport {
    width: device-width;
  }
  body {
    margin: 0;
    color: #1E2029;
    font-size: 14px;
    line-height: normal;
  }
  hr {
    box-sizing: content-box;
    height: 0;
    overflow: visible;
  }
  h1, h2, h3, h4, h5, h6 {
    margin-top: 0;
    margin-bottom: 0.5em;
    color: rgba(0, 0, 0, 0.85);
    font-weight: 500;
  }
  p {
    margin-top: 0;
    margin-bottom: 1em;
  }
  ol, ul, dl {
    margin-top: 0;
    margin-bottom: 1em;
  }
  ol ol, ul ul, ol ul, ul ol {
    margin-bottom: 0;
  }
  dt {
    font-weight: 500;
  }
  dd {
    margin-bottom: 0.5em;
    margin-left: 0;
  }
  blockquote {
    margin: 0 0 1em;
  }
  dfn {
    font-style: italic;
  }
  b, strong {
    font-weight: bolder;
  }
  small {
    font-size: 80%;
  }
  sub, sup {
    position: relative;
    font-size: 75%;
    line-height: 0;
    vertical-align: baseline;
  }
  sub {
    bottom: -0.25em;
  }
  sup {
    top: -0.5em;
  }
  a {
    color: #0B93ff;
    text-decoration: none;
    background-color: transparent;
    outline: none;
    cursor: pointer;
    transition: color 0.3s;
  }
  a:hover {
    color: #33aaff;
  }
  a:active {
    color: #0070d9;
  }
  a:active, a:hover {
    text-decoration: none;
    outline: 0;
  }
  a[disabled] {
    color: rgba(0, 0, 0, 0.25)
    cursor: not-allowed;
    pointer-events: none;
  }
  pre, code, kbd, samp {
    font-size: 1em;
  }
  pre {
    margin-top: 0;
    margin-bottom: 1em;
    overflow: auto;
  }
  figure {
    margin: 0 0 1em;
  }
  img {
    vertical-align: middle;
    border-style: none;
  }
  svg:not(:root) {
    overflow: hidden;
  }
  table {
    border-collapse: collapse;
  }
  caption {
    padding-top: 0.75em;
    padding-bottom: 0.3em;
    color: rgba(0, 0, 0, 0.45)
    text-align: left;
    caption-side: bottom;
  }
  th {
    text-align: inherit;
  }

mjx-container[jax="SVG"] {
  direction: ltr;
}

mjx-container[jax="SVG"] > svg {
  overflow: visible;
}

mjx-container[jax="SVG"] > svg a {
  fill: blue;
  stroke: blue;
}

mjx-assistive-mml {
  position: absolute !important;
  top: 0px;
  left: 0px;
  clip: rect(1px, 1px, 1px, 1px);
  padding: 1px 0px 0px 0px !important;
  border: 0px !important;
  display: block !important;
  width: auto !important;
  overflow: hidden !important;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

mjx-assistive-mml[display="block"] {
  width: 100% !important;
}

mjx-container[jax="SVG"][display="true"] {
  display: block;
  text-align: center;
  margin: 1em 0;
}

mjx-container[jax="SVG"][justify="left"] {
  text-align: left;
}

mjx-container[jax="SVG"][justify="right"] {
  text-align: right;
}

g[data-mml-node="merror"] > g {
  fill: red;
  stroke: red;
}

g[data-mml-node="merror"] > rect[data-background] {
  fill: yellow;
  stroke: none;
}

g[data-mml-node="mtable"] > line[data-line] {
  stroke-width: 70px;
  fill: none;
}

g[data-mml-node="mtable"] > rect[data-frame] {
  stroke-width: 70px;
  fill: none;
}

g[data-mml-node="mtable"] > .mjx-dashed {
  stroke-dasharray: 140;
}

g[data-mml-node="mtable"] > .mjx-dotted {
  stroke-linecap: round;
  stroke-dasharray: 0,140;
}

g[data-mml-node="mtable"] > svg {
  overflow: visible;
}

[jax="SVG"] mjx-tool {
  display: inline-block;
  position: relative;
  width: 0;
  height: 0;
}

[jax="SVG"] mjx-tool > mjx-tip {
  position: absolute;
  top: 0;
  left: 0;
}

mjx-tool > mjx-tip {
  display: inline-block;
  padding: .2em;
  border: 1px solid #888;
  font-size: 70%;
  background-color: #F8F8F8;
  color: black;
  box-shadow: 2px 2px 5px #AAAAAA;
}

g[data-mml-node="maction"][data-toggle] {
  cursor: pointer;
}

mjx-status {
  display: block;
  position: fixed;
  left: 1em;
  bottom: 1em;
  min-width: 25%;
  padding: .2em .4em;
  border: 1px solid #888;
  font-size: 90%;
  background-color: #F8F8F8;
  color: black;
}

foreignObject[data-mjx-xml] {
  font-family: initial;
  line-height: normal;
  overflow: visible;
}

.MathJax path {
  stroke-width: 3;
}

    #setText > div {
        justify-content: inherit;
        margin-top: 0;
        margin-bottom: 1em;
        
        
    }
    
    
    
    #setText div:last-child {
        margin-bottom: 0 !important;
    }

    #setText > br, #preview-content br {
        line-height: 1.2;
    }

    #preview-content > div {
        margin-top: 0;
        margin-bottom: 1em;
        
    }    
    
    .proof > div, .theorem > div {
        margin-top: 1rem;
    }

    #preview-content table {
      margin-bottom: 1em;
    }

    #setText table {
      margin-bottom: 1em;
    }
    
    #preview-content .sub-table table, #setText .sub-table table {
      margin-bottom: 0;
    }

    mjx-container {
      text-indent: 0;
      overflow-y: visible !important;
      padding-top: 1px;
      padding-bottom: 1px;
      
      
    }
    
    
    
    .math-inline mjx-container {
        display: inline-block !important;
        page-break-inside: avoid;
    }
    .math-block {
        align-items: center;
        min-width: min-content;
        page-break-after: auto;
        page-break-inside: avoid;
        margin-top: 1em;
        margin-bottom: 1em;
    }
    
    .math-block[data-highlight-color] mjx-container[jax="SVG"] > svg {
      background-color: var(--mmd-highlight-color);
    }    
    
    .math-block[data-highlight-text-color] mjx-container[jax="SVG"] > svg {
      color: var(--mmd-highlight-text-color);
    }    
    .math-inline[data-highlight-color] mjx-container[jax="SVG"] {
      background-color: var(--mmd-highlight-color);
    }    
    
    .math-inline[data-highlight-text-color] mjx-container[jax="SVG"] {
      color: var(--mmd-highlight-text-color);
    }
    
    .math-block p {
        flex-shrink: 1;
    }
    .math-block mjx-container {
        margin: 0 !important;
    }
    .math-error {
        background-color: yellow;
        color: red;
    }

    #preview-content svg, #setText svg { min-width: initial !important;}

    #preview-content img, #setText img {
        max-width: 100%;
    }
    
    #preview-content blockquote,  #setText blockquote {
        page-break-inside: avoid;
        color: #666;
        margin: 0 0 1em 0;
        padding-left: 3em;
        border-left: .5em solid #eee;
    }

    #preview-content pre, #setText pre {
        border: none;
        padding: 0;
        overflow: auto;
        font-size: 85%;
        line-height: 1.45;
        border-radius: 6px;
        box-sizing: border-box;
        background: #f8f8fa;
    }
    #preview-content pre code, #setText pre code{
        padding: 1rem;
        display: block;
        overflow-x: auto;
        line-height: 24px;
    }
    .empty {
        text-align: center;
        font-size: 18px;
        padding: 50px 0 !important;
    }

    #setText table, #preview-content table {
        display: table; 
        overflow: auto;
        max-width: 100%;
        border-collapse: collapse;
        page-break-inside: avoid;
    }
      
    #setText table th, #preview-content table th {
        text-align: center;
        font-weight: bold;
    }
    
    #setText table td, #preview-content table td,
    #setText table th, #preview-content table th {
        border: 1px solid #dfe2e5;
        padding: 6px 13px;
    }
      
    #setText table tr, #preview-content table tr {
        background-color: #fff;
        border-top: 1px solid #c6cbd1;
    }
    
    #setText table tr:nth-child(2n), #preview-content table tr:nth-child(2n) {
        background-color: #f6f8fa;
    }

    
    #setText .main-title, #setText .author, #preview-content .main-title, #preview-content .author  {
        text-align: center;
        margin: 0 auto;
    }
    
    #preview-content .main-title, #setText .main-title {
        line-height: 1.2;
        margin-bottom: 1em;
    }

    #preview-content .author, #setText .author  {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
    }

    #preview-content .author p, #setText .author p {
        min-width: 30%;
        max-width: 50%;
        padding: 0 7px;
    }

    #preview-content .author > p > span, #setText .author > p > span {
        display: block;
        text-align: center;
    }

    #preview-content .section-title, #setText .section-title {
        margin-top: 1.5em;
    }

    #preview-content .abstract, #setText .abstract {
        text-align: justify;
        margin-bottom: 1em;
    }

    #preview-content .abstract p, #setText .abstract p {
        margin-bottom: 0;
    }

    @media print {

      #preview {
        font-size: 10pt!important;
      }

      svg {
        shape-rendering: crispEdges;
      }

      .math-block svg, math-inline svg {
        margin-top: 1px;
      }

      #preview-content img, #setText img {
        display: block;
      }
      
      #preview-content .figure_img img, #setText .figure_img img {
        display: inline;
      }

      .preview-right {
        word-break: break-word;
      }

      #preview-content h1, #setText h1 {
        page-break-inside: avoid;
        position: relative;
        border: 2px solid transparent;
      }
  
      #preview-content h1::after, #setText h1::after {
        content: "";
        display: block;
        height: 100px;
        margin-bottom: -100px;
        position: relative;
      }
  
      #preview-content h2, #setText h2 {
        page-break-inside: avoid;
        position: relative;
        border: 2px solid transparent;
      }
  
      #preview-content h2::after, #setText h2::after {
        content: "";
        display: block;
        height: 100px;
        margin-bottom: -100px;
        position: relative;
      }
  
      #preview-content h3, #setText h3 {
        page-break-inside: avoid;
        position: relative;
        border: 2px solid transparent;
      }
  
      #preview-content h3::after, #setText h3::after {
        content: "";
        display: block;
        height: 100px;
        margin-bottom: -100px;
        position: relative;
      }
  
      #preview-content h4, #setText h4 {
        page-break-inside: avoid;
        position: relative;
        border: 2px solid transparent;
      }
  
      #preview-content h4::after, #setText h4::after {
        content: "";
        display: block;
        height: 100px;
        margin-bottom: -100px;
        position: relative;
      }
  
      #preview-content h5, #setText h5 {
        page-break-inside: avoid;
        position: relative;
        border: 2px solid transparent;
      }
  
      #preview-content h5::after, #setText h5::after {
        content: "";
        display: block;
        height: 100px;
        margin-bottom: -100px;
        position: relative;
      }
  
      #preview-content h6, #setText h6 {
        page-break-inside: avoid;
        position: relative;
        border: 2px solid transparent;
      }
  
      #preview-content h6::after, #setText h6::after {
        content: "";
        display: block;
        height: 100px;
        margin-bottom: -100px;
        position: relative;
      }
    }
    #preview-content sup, #setText sup {
      top: -.5em;
      position: relative;
      font-size: 75%;
      line-height: 0;
      vertical-align: baseline;
    }
    
    #preview-content .text-url, #setText .text-url {
      color: #0B93ff;
      cursor: text;
      pointer-events: none;
    }
    
    #preview-content .text-url a:hover, #setText .text-url a:hover {
      color: #0B93ff;
    }
    
    mark {
      background-color: #feffe6;
    }
    
    span[data-underline-type] mark {
      background: inherit;
      background-color: #feffe6;
      padding-top: 0;
      padding-bottom: 0;
    }
    
    *[data-has-dotfill] {
      position: relative;
      overflow: hidden;
    }
    
    *[data-has-dotfill] .dotfill::after {
      position: absolute;
      padding-left: .25ch;
      content: " . . . . . . . . . . . . . . . . . . . "
          ". . . . . . . . . . . . . . . . . . . . . . . "
          ". . . . . . . . . . . . . . . . . . . . . . . "
          ". . . . . . . . . . . . . . . . . . . . . . . "
          ". . . . . . . . . . . . . . . . . . . . . . . "
          ". . . . . . . . . . . . . . . . . . . . . . . "
          ". . . . . . . . . . . . . . . . . . . . . . . ";
      text-align: right;
    }
    
   .smiles {
     text-align: center;
   }

    #preview-content code, #setText code {
      font-family: Inconsolata;
      font-size: inherit;
      display: initial;
      background: #f8f8fa;
    }
    #preview-content .mmd-highlight code, #setText .mmd-highlight code, 
    #preview-content pre.mmd-highlight code, #setText pre.mmd-highlight code {
      background-color: transparent;
    }
    #preview-content pre code, #setText pre code {
      font-family: 'DM Mono', Inconsolata, monospace;
      color: #333;
      font-size: 15px;
    }

    .hljs-comment,
    .hljs-quote {
      color: #998;
      font-style: italic;
    }

    .hljs-command {
      color: #005cc5;
    }

    .hljs-keyword,
    .hljs-selector-tag,
    .hljs-subst {
      color: #d73a49;
      font-weight: bold;
    }

    .hljs-number,
    .hljs-literal,
    .hljs-variable,
    .hljs-template-variable,
    .hljs-tag .hljs-attr {
      color: #005cc5;
    }

    .hljs-string,
    .hljs-doctag {
      color: #24292e;
    }

    .hljs-title,
    .hljs-section,
    .hljs-selector-id {
      color: #6f42c1;
      font-weight: bold;
    }

    .hljs-subst {
      font-weight: normal;
    }

    .hljs-type,
    .hljs-class .hljs-title {
      color: #458;
      font-weight: bold;
    }

    .hljs-tag,
    .hljs-name,
    .hljs-attribute {
      color: #000080;
      font-weight: normal;
    }

    .hljs-regexp,
    .hljs-link {
      color: #009926;
    }

    .hljs-symbol,
    .hljs-bullet {
      color: #990073;
    }

    .hljs-built_in,
    .hljs-builtin-name {
      color: #24292e;
    }

    .hljs-meta {
      color: #999;
      font-weight: bold;
    }

    .hljs-meta-keyword {
      color: #d73a49;
    }

    .hljs-meta-string {
      color: #032f62;
    }

    .hljs-deletion {
      background: #fdd;
    }

    .hljs-addition {
      background: #dfd;
    }

    .hljs-emphasis {
      font-style: italic;
    }

    .hljs-strong {
      font-weight: bold;
    }

    .table_tabular table th,  .table_tabular table th {
        border: none !important;
        padding: 6px 13px;
    }
      
    #tabular tr, #tabular tr {
        border-top: none !important;
        border-bottom: none !important;
    }
    #tabular td, #tabular td {
        border-style: none !important;
        background-color: #fff;
        border-color: #000 !important;
        word-break: keep-all;
        padding: 0.1em 0.5em !important;
    }
    #tabular {
        display: inline-block !important;
    }
    #tabular td > p {
        margin-bottom: 0;
        margin-top: 0;
    }
    #tabular td._empty {
      height: 1.3em;
    }
    #tabular td .f {
      opacity: 0;
    }
    
    html[data-theme="dark"] #tabular tr, html[data-theme="dark"] #tabular td {
      background-color: #202226;
      border-color: #fff !important;
    }  
    .table_tabular {
        overflow-x: auto;
        padding: 0 2px 0.5em 2px;
    }
    .figure_img {
       margin-bottom: 0.5em;
       overflow-x: auto;
    }

  ol.enumerate, ul.itemize {
    padding-inline-start: 40px;
  }
/* It's commented because counter not supporting to change value 
  ol.enumerate.lower-alpha {
    counter-reset: item ;
    list-style-type: none !important;
  }
  .enumerate.lower-alpha > li {
    position: relative;
  }
  .enumerate.lower-alpha > li:before { 
    content: "("counter(item, lower-alpha)")"; 
    counter-increment: item; 
    position: absolute;
    left: -47px;
    width: 47px;
    display: flex;
    justify-content: flex-end;
    padding-right: 7px;
    flex-wrap: nowrap;
    word-break: keep-all;
  }
  */
  
  .itemize > li {
    position: relative;
  }
  .itemize > li > span.li_level, .li_enumerate.not_number > span.li_level { 
    position: absolute;
    right: 100%;
    white-space: nowrap;
    width: max-content;;
    display: flex;
    justify-content: flex-end;
    padding-right: 10px;
    box-sizing: border-box;
  }
  .li_enumerate.not_number {
    position: relative;
    display: inline-block;
    list-style-type: none;
  }

  #preview {
    font-family: 'CMU Serif', 'Georgia', Helvetica, Arial, sans-serif;
    font-size: 17px;
    visibility: visible;
    word-break: break-word;
    padding: 2.5em;
    max-width: 800px;
    margin: auto;
    box-sizing: content-box;
  }

  #preview h1, #preview h2, #preview h3, #preview h4, #preview h5, #preview strong {
    font-family: 'CMU Serif Bold', 'Georgia', Helvetica, Arial, sans-serif;
  }

  #preview  i, #preview  em {
    font-family: 'CMU Serif Italic', 'Georgia', Helvetica, Arial, sans-serif;
  }

  .mmd-menu {
    max-width: 320px;
    position: absolute;
    background-color: white;
    color: black;
    width: auto;
    padding: 5px 0px;
    border: 1px solid #E5E6EB;
    margin: 0;
    cursor: default;
    font: menu;
    text-align: left;
    text-indent: 0;
    text-transform: none;
    line-height: normal;
    letter-spacing: normal;
    word-spacing: normal;
    word-wrap: normal;
    white-space: nowrap;
    float: none;
    z-index: 201;
    border-radius: 5px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    -khtml-border-radius: 5px;
    box-shadow: 0px 10px 20px #808080;
    -webkit-box-shadow: 0px 10px 20px #808080;
    -moz-box-shadow: 0px 10px 20px #808080;
    -khtml-box-shadow: 0px 10px 20px #808080; 
  }
  
  .mmd-menu:focus { outline: none; }
  
  .mmd-menu.mmd-menu-sm {
    max-width: 100vw;
    padding-bottom: 34px;
    border-radius: 0;
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    -khtml-border-radius: 0;
  }

  .mmd-menu-item-icon {
    color: #1e2029;
    margin-left: auto;
    align-items: center;
    display: flex;
    flex-shrink: 0;
    display: none; 
  }

  .mmd-menu-item {
    padding-bottom: 8px;
    padding-top: 8px;
    padding-left: 1.25rem;
    padding-right: 1.25rem;
    display: flex;
    background: transparent; 
    height: 52px;
    max-height: 52px;
  }
  .mmd-menu-item:focus { outline: none; }

  .mmd-menu-item.active {
    background-color: #e1e0e5; 
  }

  .mmd-menu-item.active .mmd-menu-item-icon {
    display: flex; 
  }

  .mmd-menu-item-container {
    overflow: hidden; 
  }

  .mmd-menu-item-title {
    color: #1e2029;
    white-space: nowrap;
    text-overflow: ellipsis;
    overflow: hidden;
    font-size: 14px;
    line-height: 20px; 
  }

  .mmd-menu-item-value {
    color: #7d829c;
    white-space: nowrap;
    text-overflow: ellipsis;
    overflow: hidden;
    font-size: 12px;
    line-height: 16px; 
  }
  
  html[data-theme="dark"] .mmd-menu-item-title {
    color: #ebefe7;
  } 
  html[data-theme="dark"] .mmd-menu-item.active .mmd-menu-item-title {
    color: #1e2029;
  }
  html[data-theme="dark"] .mmd-menu {
    background-color: #33363a;
  }
  
  .mmd-context-menu-overlay{
    background: rgba(0, 0, 0, 0.56);
  }
  
.ClipboardButton {
  padding: 0;
  margin: 0.5rem;
  display: inline-block;
  cursor: pointer;
  color: rgb(36, 41, 47);
  background: rgb(246, 248, 250);
  border-radius: 6px;
  border: 1px solid rgba(31, 35, 40, 0.15);
  box-shadow: rgba(31, 35, 40, 0.04) 0 1px 0 0, rgba(255, 255, 255, 0.25) 0 1 0 0 inset;
  position: relative;
}

.ClipboardButton:hover {
  background-color: rgb(243, 244, 246);
  border-color rgba(31, 35, 40, 0.15);
  transition-duration: .1s;
}

.mmd-clipboard-icon {
  fill: currentColor;
  vertical-align: text-bottom;
}

.mmd-clipboard-copy-icon {
  color: rgb(101, 109, 118);
}
.mmd-clipboard-check-icon {
  color: rgb(26, 127, 55);
}

.mmd-tooltipped-no-delay:hover::before,
.mmd-tooltipped-no-delay:hover::after {
  animation-delay: 0s;
}

.mmd-tooltipped:hover::before,
.mmd-tooltipped:hover::after {
  display: inline-block;
  text-decoration: none;
  animation-name: tooltip-appear;
  animation-duration: .1s;
  animation-fill-mode: forwards;
  animation-timing-function: ease-in;
  animation-delay: .4s;
}

.mmd-tooltipped-w::before {
  top: 50%;
  bottom: 50%;
  left: -7px;
  margin-top: -6px;
  border-left-color: rgb(36, 41, 47)
}

.mmd-tooltipped::before {
  position: absolute;
  z-index: 1000001;
  display: none;
  width: 0;
  height: 0;
  color: rgb(36, 41, 47)
  pointer-events: none;
  content: "";
  border: 6px solid transparent;
  opacity: 0;
}

.mmd-tooltipped-w::after {
  right: 100%;
  bottom: 50%;
  margin-right: 6px;
  transform: translateY(50%);
}


.mmd-tooltipped::after {
    position: absolute;
    z-index: 1000000;
    display: none;
    padding: 0.5em 0.75em;
    font: normal normal 11px/1.5 'CMU Serif', 'Georgia', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: subpixel-antialiased;
    color: rgb(255, 255, 255);
    text-align: center;
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-wrap: break-word;
    white-space: pre;
    pointer-events: none;
    content: attr(aria-label);
    background: rgb(36, 41, 47);
    border-radius: 6px;
    opacity: 0;
}
</style>
</head>
<body>
  <div id="preview" class="preview scrollEditor">
    <div id="container-ruller" />
    <div id="preview-content">
      <h1 type="title" class="main-title" id="prelims_macro_lecture_1-fb318117-f5d4-4b1d-ab93-593d4db3a373">
prelims_macro_lecture_1-fb318117-f5d4-4b1d-ab93-593d4db3a373</h1>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-0 preview-line 0" id="introduction-to-macroeconomics" data_line_start="0" data_line_end="0" data_line="0,1" count_line="1">
Introduction to Macroeconomics</h2>
<div class="preview-paragraph-2 preview-line 2" data_line_start="2" data_line_end="2" data_line="2,3" count_line="1">Artur Doshchyn</div>
<div class="preview-paragraph-4 preview-line 4" data_line_start="4" data_line_end="4" data_line="4,5" count_line="1">Department of Economics and Linacre College</div>
<div class="preview-paragraph-6 preview-line 6" data_line_start="6" data_line_end="6" data_line="6,7" count_line="1">Introductory Economics</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-8 preview-line 8" id="outline" data_line_start="8" data_line_end="8" data_line="8,9" count_line="1">
Outline</h2>
<ol class="preview-paragraph-10 preview-line 10 11 12 13 14 15 16" data_line_start="10" data_line_end="16" data_line="10,17" count_line="7">
<li>Introducing the course</li>
<li>Stock vs Flow</li>
<li>GDP</li>
<li>Unemployment</li>
<li>Inflation</li>
<li>Monetary and Fiscal Policy</li>
</ol>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-17 preview-line 17" id="section-1%3A-course-introduction" data_line_start="17" data_line_end="17" data_line="17,18" count_line="1">
Section 1: Course Introduction</h2>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-18 preview-line 18" id="course-lectures" data_line_start="18" data_line_end="18" data_line="18,19" count_line="1">
Course Lectures</h2>
<div class="preview-paragraph-19 preview-line 19 20" data_line_start="19" data_line_end="20" data_line="19,21" count_line="2">Dr. Artur Doshchyn (AD)<br>
Professor Alexandre Kohlhas (AK)</div>
<div class="preview-paragraph-22 preview-line 22" data_line_start="22" data_line_end="22" data_line="22,23" count_line="1">My lecture slides are a guide to what I will cover in lectures - I will inevitably skip some slides in the interests of time.</div>
<div class="preview-paragraph-24 preview-line 24 25 26 27 28 29 30 31 32 33 34 35 36 37 38 39 40 41" data_line_start="24" data_line_end="41" data_line="24,42" count_line="18">Week 1 Lecture 1: Course Introduction Key Macroeconomic Concepts (AD) Monday<br>
Week 1 Lecture 2: The Long Run (AD) Tuesday<br>
Week 1 Lecture 3: The Solow Model (AD) Wednesday<br>
Week 2 Lecture 4: Persistent Growth (AD) Monday<br>
Week 2 Lecture 5: The Romer Model (AD) Tuesday<br>
Week 2 Lecture 6: The Labour Market (AD) Wednesday<br>
Week 3 Lecture 7: Inflation (AD) Monday<br>
Week 3 Lecture 8: Consumption (AD) Tuesday<br>
Week 4 Lecture 9: Investment (AD) Monday<br>
Week 4 Lecture 10: The Short Run (AK) Wednesday<br>
Week 5 Lecture 11: The IS Curve (AK) Monday<br>
Week 5 Lecture 12: MP Curve and Phillips' Curve (AK) Tuesday<br>
Week 5 Lecture 13: Applications of SR Model (AK) Wednesday<br>
Week 6 Lecture 14: AS/AD Framework (AK) Monday<br>
Week 6 Lecture 15: Shocks &amp; Stabilisation in AS/AD (AK) Tuesday<br>
Week 6 Lecture 16: AS/AD Applications (AK) Wednesday<br>
Week 7 Lecture 17: Exchange Rates &amp; Open Economy (AK) Monday<br>
Week 7 Lecture 18: Open Economy Applications (AK) Tuesday</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-44 preview-line 44" id="tutorials" data_line_start="44" data_line_end="44" data_line="44,45" count_line="1">
Tutorials</h2>
<div class="preview-paragraph-45 preview-line 45" data_line_start="45" data_line_end="45" data_line="45,46" count_line="1">Tutorials will test concepts and techniques. There are 6 associated Tutorial Sheets</div>
<div class="preview-paragraph-47 preview-line 47 48 49 50 51 52" data_line_start="47" data_line_end="52" data_line="47,53" count_line="6">Week 3: Tutorial 1, GDP Accounting and productivity<br>
Week 4: Tutorial 2, Growth<br>
Week 5: Tutorial 3, Unemployment, Inflation, Consumption, Investment<br>
Week 6: Tutorial 4, Recessions and the short-run<br>
Week 7: Tutorial 5, AS/AD Model and Monetary Policy<br>
Week 8: Tutorial 6, Open Economy</div>
<div class="preview-paragraph-54 preview-line 54" data_line_start="54" data_line_end="54" data_line="54,55" count_line="1">College Tutors may alter the timing or nature of the tutorials as they see fit</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-56 preview-line 56" id="macroeconomics-vs.-microeconomics" data_line_start="56" data_line_end="56" data_line="56,57" count_line="1">
Macroeconomics vs. microeconomics</h2>
<div class="preview-paragraph-57 preview-line 57" data_line_start="57" data_line_end="57" data_line="57,58" count_line="1">Microeconomics: Focuses on the study of individual people, firms, or markets.</div>
<div class="preview-paragraph-59 preview-line 59" data_line_start="59" data_line_end="59" data_line="59,60" count_line="1">Macroeconomics: Studies collections of people and firms, and how their interactions through markets determine the overall economic activity in a country or region, the &quot;big picture&quot;.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-61 preview-line 61" id="some-questions-in-macroeconomics" data_line_start="61" data_line_end="61" data_line="61,62" count_line="1">
Some questions in macroeconomics</h2>
<div class="preview-paragraph-63 preview-line 63 64" data_line_start="63" data_line_end="64" data_line="63,65" count_line="2">Big questions:<br>
` What causes economic output to grow?</div>
<ul class="preview-paragraph-65 preview-line 65 66 67 68 69 70" data_line_start="65" data_line_end="70" data_line="65,71" count_line="6">
<li>What causes economic output to fluctuate?</li>
<li>What causes unemployment?</li>
<li>What causes inflation? (or deflation?)</li>
<li>How are exchange rates determined?</li>
<li>What causes financial crises?</li>
</ul>
<div class="preview-paragraph-71 preview-line 71" data_line_start="71" data_line_end="71" data_line="71,72" count_line="1">Current policy questions</div>
<ul class="preview-paragraph-72 preview-line 72 73 74 75 76 77" data_line_start="72" data_line_end="77" data_line="72,78" count_line="6">
<li>How can the Federal Reserve stop inflation without causing a recession?</li>
<li>Fiscal stimulus versus austerity</li>
<li>How to address long-run government debt problems?</li>
<li>How to make the Eurozone more stable? Should some members exit?</li>
<li>How to repair the financial system?</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-78 preview-line 78" id="section-2%3A-stock-vs-flow" data_line_start="78" data_line_end="78" data_line="78,79" count_line="1">
Section 2: Stock vs Flow</h2>
<div class="preview-paragraph-79 preview-line 79" data_line_start="79" data_line_end="79" data_line="79,80" count_line="1">no other text contained on this slide.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-81 preview-line 81" id="flows-%24%5Crightarrow%24-stocks-1" data_line_start="81" data_line_end="81" data_line="81,82" count_line="1">
Flows <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">&#x2192;</mo>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">→</mo>
</math></mathmlword><asciimath style="display: none;">rarr</asciimath><latex style="display: none">\rightarrow</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="2.262ex" height="1.181ex" role="img" focusable="false" viewBox="0 -511 1000 522" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="2192" d="M56 237T56 250T70 270H835Q719 357 692 493Q692 494 692 496T691 499Q691 511 708 511H711Q720 511 723 510T729 506T732 497T735 481T743 456Q765 389 816 336T935 261Q944 258 944 250Q944 244 939 241T915 231T877 212Q836 186 806 152T761 85T740 35T732 4Q730 -6 727 -8T711 -11Q691 -11 691 0Q691 7 696 25Q728 151 835 230H70Q56 237 56 250Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">→</mo></math></mjx-assistive-mml></mjx-container></span> Stocks 1</h2>
<div class="preview-paragraph-82 preview-line 82 83" data_line_start="82" data_line_end="83" data_line="82,84" count_line="2"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-09.jpg?height=961&amp;width=1940&amp;top_left_y=510&amp;top_left_x=578" alt="" data-align="center"></figure><br>
The slide contains a drawing of a bathtub. The flow is the water coming from the tap, while the stock is the water that is contained in the tub.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-85 preview-line 85" id="flows-%24%5Crightarrow%24-stocks-2" data_line_start="85" data_line_end="85" data_line="85,86" count_line="1">
Flows <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">&#x2192;</mo>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">→</mo>
</math></mathmlword><asciimath style="display: none;">rarr</asciimath><latex style="display: none">\rightarrow</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="2.262ex" height="1.181ex" role="img" focusable="false" viewBox="0 -511 1000 522" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="2192" d="M56 237T56 250T70 270H835Q719 357 692 493Q692 494 692 496T691 499Q691 511 708 511H711Q720 511 723 510T729 506T732 497T735 481T743 456Q765 389 816 336T935 261Q944 258 944 250Q944 244 939 241T915 231T877 212Q836 186 806 152T761 85T740 35T732 4Q730 -6 727 -8T711 -11Q691 -11 691 0Q691 7 696 25Q728 151 835 230H70Q56 237 56 250Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">→</mo></math></mjx-assistive-mml></mjx-container></span> Stocks 2</h2>
<div class="preview-paragraph-86 preview-line 86" data_line_start="86" data_line_end="86" data_line="86,87" count_line="1">Stocks are measured at a specific point in time:</div>
<ul class="preview-paragraph-87 preview-line 87 88" data_line_start="87" data_line_end="88" data_line="87,89" count_line="2">
<li>Existing quantity accumulated in the past, e.g. I have <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
  <mn>1000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
  <mn>1000</mn>
</math></mathmlword><asciimath style="display: none;">£1000</asciimath><latex style="display: none">£ 1000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.05ex" xmlns="http://www.w3.org/2000/svg" width="6.265ex" height="1.665ex" role="img" focusable="false" viewBox="0 -714 2769 736" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g><g data-mml-node="mn" transform="translate(769, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow><mn>1000</mn></math></mjx-assistive-mml></mjx-container></span> of wealth</li>
</ul>
<div class="preview-paragraph-89 preview-line 89" data_line_start="89" data_line_end="89" data_line="89,90" count_line="1">Flows are measured over a period of time</div>
<ul class="preview-paragraph-90 preview-line 90 91" data_line_start="90" data_line_end="91" data_line="90,92" count_line="2">
<li>Analogous to rate or speed, e.g. I earn <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
  <mn>300</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
  <mn>300</mn>
</math></mathmlword><asciimath style="display: none;">£300</asciimath><latex style="display: none">£ 300</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.05ex" xmlns="http://www.w3.org/2000/svg" width="5.133ex" height="1.665ex" role="img" focusable="false" viewBox="0 -714 2269 736" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g><g data-mml-node="mn" transform="translate(769, 0)"><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow><mn>300</mn></math></mjx-assistive-mml></mjx-container></span> income per week</li>
</ul>
<div class="preview-paragraph-92 preview-line 92" data_line_start="92" data_line_end="92" data_line="92,93" count_line="1">Stocks are accumulated or depleted over time by flows.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-94 preview-line 94" id="gross-and-net-flows" data_line_start="94" data_line_end="94" data_line="94,95" count_line="1">
Gross and Net Flows</h2>
<div class="preview-paragraph-96 preview-line 96 97 98" data_line_start="96" data_line_end="98" data_line="96,99" count_line="3">Gross Inflow = 1 litre<br>
Gross Outflow = 2 litres<br>
What is Net flow (Change in Stock)?</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-100 preview-line 100" id="flows-%24%5Crightarrow%24-stocks-3" data_line_start="100" data_line_end="100" data_line="100,101" count_line="1">
Flows <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">&#x2192;</mo>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">→</mo>
</math></mathmlword><asciimath style="display: none;">rarr</asciimath><latex style="display: none">\rightarrow</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="2.262ex" height="1.181ex" role="img" focusable="false" viewBox="0 -511 1000 522" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="2192" d="M56 237T56 250T70 270H835Q719 357 692 493Q692 494 692 496T691 499Q691 511 708 511H711Q720 511 723 510T729 506T732 497T735 481T743 456Q765 389 816 336T935 261Q944 258 944 250Q944 244 939 241T915 231T877 212Q836 186 806 152T761 85T740 35T732 4Q730 -6 727 -8T711 -11Q691 -11 691 0Q691 7 696 25Q728 151 835 230H70Q56 237 56 250Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">→</mo></math></mjx-assistive-mml></mjx-container></span> Stocks 3</h2>
<div class="preview-paragraph-102 preview-line 102 103 104" data_line_start="102" data_line_end="104" data_line="102,105" count_line="3">stock = A person's wealth. What is the flow?<br>
flow = number of graduating Oxford Economists. What is the stock?<br>
stock = Government debt. What is the flow?</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-106 preview-line 106" id="section-3%3A-gdp" data_line_start="106" data_line_end="106" data_line="106,107" count_line="1">
Section 3: GDP</h2>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-108 preview-line 108" id="total-output-of-the-economy" data_line_start="108" data_line_end="108" data_line="108,109" count_line="1">
Total output of the economy</h2>
<div class="preview-paragraph-110 preview-line 110" data_line_start="110" data_line_end="110" data_line="110,111" count_line="1">Simple circular flow of income</div>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-111 preview-line 111" id="graph%3A-simple-circular-flow-of-income" data_line_start="111" data_line_end="111" data_line="111,112" count_line="1">
Graph: Simple circular flow of income</h3>
<div class="preview-paragraph-112 preview-line 112 113 114" data_line_start="112" data_line_end="114" data_line="112,115" count_line="3">A diagram showing  flows of income and goods from firms to household, and flows of labor and expenditure from households to firms is shown.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-14.jpg?height=1093&amp;width=1956&amp;top_left_y=466&amp;top_left_x=706" alt="" data-align="center"></figure><br>
output = income = expenditure</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-116 preview-line 116" id="national-accounts" data_line_start="116" data_line_end="116" data_line="116,117" count_line="1">
National Accounts</h2>
<div class="preview-paragraph-118 preview-line 118" data_line_start="118" data_line_end="118" data_line="118,119" count_line="1">Three ways to measure GDP</div>
<ol class="preview-paragraph-120 preview-line 120 121" data_line_start="120" data_line_end="121" data_line="120,122" count_line="2">
<li>GDP(E): the sum of all expenditure in the economy on finished goods and services - consumption, investment, government purchases, net exports</li>
</ol>
<div class="preview-paragraph-122 preview-line 122" data_line_start="122" data_line_end="122" data_line="122,123" count_line="1">This yields the national income identity: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi>Y</mi>
  <mo>=</mo>
  <mi>C</mi>
  <mo>+</mo>
  <mi>I</mi>
  <mo>+</mo>
  <mi>G</mi>
  <mo>+</mo>
  <mi>N</mi>
  <mi>X</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi>Y</mi>
  <mo>=</mo>
  <mi>C</mi>
  <mo>+</mo>
  <mi>I</mi>
  <mo>+</mo>
  <mi>G</mi>
  <mo>+</mo>
  <mi>N</mi>
  <mi>X</mi>
</math></mathmlword><asciimath style="display: none;">Y=C+I+G+NX</asciimath><latex style="display: none">Y=C+I+G+N X</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.186ex" xmlns="http://www.w3.org/2000/svg" width="21.615ex" height="1.781ex" role="img" focusable="false" viewBox="0 -705 9553.9 787" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="59" d="M66 637Q54 637 49 637T39 638T32 641T30 647T33 664T42 682Q44 683 56 683Q104 680 165 680Q288 680 306 683H316Q322 677 322 674T320 656Q316 643 310 637H298Q242 637 242 624Q242 619 292 477T343 333L346 336Q350 340 358 349T379 373T411 410T454 461Q546 568 561 587T577 618Q577 634 545 637Q528 637 528 647Q528 649 530 661Q533 676 535 679T549 683Q551 683 578 682T657 680Q684 680 713 681T746 682Q763 682 763 673Q763 669 760 657T755 643Q753 637 734 637Q662 632 617 587Q608 578 477 424L348 273L322 169Q295 62 295 57Q295 46 363 46Q379 46 384 45T390 35Q390 33 388 23Q384 6 382 4T366 1Q361 1 324 1T232 2Q170 2 138 2T102 1Q84 1 84 9Q84 14 87 24Q88 27 89 30T90 35T91 39T93 42T96 44T101 45T107 45T116 46T129 46Q168 47 180 50T198 63Q201 68 227 171L252 274L129 623Q128 624 127 625T125 627T122 629T118 631T113 633T105 634T96 635T83 636T66 637Z"></path></g><g data-mml-node="mo" transform="translate(1040.8, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(2096.6, 0)"><path data-c="43" d="M50 252Q50 367 117 473T286 641T490 704Q580 704 633 653Q642 643 648 636T656 626L657 623Q660 623 684 649Q691 655 699 663T715 679T725 690L740 705H746Q760 705 760 698Q760 694 728 561Q692 422 692 421Q690 416 687 415T669 413H653Q647 419 647 422Q647 423 648 429T650 449T651 481Q651 552 619 605T510 659Q484 659 454 652T382 628T299 572T226 479Q194 422 175 346T156 222Q156 108 232 58Q280 24 350 24Q441 24 512 92T606 240Q610 253 612 255T628 257Q648 257 648 248Q648 243 647 239Q618 132 523 55T319 -22Q206 -22 128 53T50 252Z"></path></g><g data-mml-node="mo" transform="translate(3078.8, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mi" transform="translate(4079, 0)"><path data-c="49" d="M43 1Q26 1 26 10Q26 12 29 24Q34 43 39 45Q42 46 54 46H60Q120 46 136 53Q137 53 138 54Q143 56 149 77T198 273Q210 318 216 344Q286 624 286 626Q284 630 284 631Q274 637 213 637H193Q184 643 189 662Q193 677 195 680T209 683H213Q285 681 359 681Q481 681 487 683H497Q504 676 504 672T501 655T494 639Q491 637 471 637Q440 637 407 634Q393 631 388 623Q381 609 337 432Q326 385 315 341Q245 65 245 59Q245 52 255 50T307 46H339Q345 38 345 37T342 19Q338 6 332 0H316Q279 2 179 2Q143 2 113 2T65 2T43 1Z"></path></g><g data-mml-node="mo" transform="translate(4805.2, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mi" transform="translate(5805.4, 0)"><path data-c="47" d="M50 252Q50 367 117 473T286 641T490 704Q580 704 633 653Q642 643 648 636T656 626L657 623Q660 623 684 649Q691 655 699 663T715 679T725 690L740 705H746Q760 705 760 698Q760 694 728 561Q692 422 692 421Q690 416 687 415T669 413H653Q647 419 647 422Q647 423 648 429T650 449T651 481Q651 552 619 605T510 659Q492 659 471 656T418 643T357 615T294 567T236 496T189 394T158 260Q156 242 156 221Q156 173 170 136T206 79T256 45T308 28T353 24Q407 24 452 47T514 106Q517 114 529 161T541 214Q541 222 528 224T468 227H431Q425 233 425 235T427 254Q431 267 437 273H454Q494 271 594 271Q634 271 659 271T695 272T707 272Q721 272 721 263Q721 261 719 249Q714 230 709 228Q706 227 694 227Q674 227 653 224Q646 221 643 215T629 164Q620 131 614 108Q589 6 586 3Q584 1 581 1Q571 1 553 21T530 52Q530 53 528 52T522 47Q448 -22 322 -22Q201 -22 126 55T50 252Z"></path></g><g data-mml-node="mo" transform="translate(6813.7, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mi" transform="translate(7813.9, 0)"><path data-c="4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path></g><g data-mml-node="mi" transform="translate(8701.9, 0)"><path data-c="58" d="M42 0H40Q26 0 26 11Q26 15 29 27Q33 41 36 43T55 46Q141 49 190 98Q200 108 306 224T411 342Q302 620 297 625Q288 636 234 637H206Q200 643 200 645T202 664Q206 677 212 683H226Q260 681 347 681Q380 681 408 681T453 682T473 682Q490 682 490 671Q490 670 488 658Q484 643 481 640T465 637Q434 634 411 620L488 426L541 485Q646 598 646 610Q646 628 622 635Q617 635 609 637Q594 637 594 648Q594 650 596 664Q600 677 606 683H618Q619 683 643 683T697 681T738 680Q828 680 837 683H845Q852 676 852 672Q850 647 840 637H824Q790 636 763 628T722 611T698 593L687 584Q687 585 592 480L505 384Q505 383 536 304T601 142T638 56Q648 47 699 46Q734 46 734 37Q734 35 732 23Q728 7 725 4T711 1Q708 1 678 1T589 2Q528 2 496 2T461 1Q444 1 444 10Q444 11 446 25Q448 35 450 39T455 44T464 46T480 47T506 54Q523 62 523 64Q522 64 476 181L429 299Q241 95 236 84Q232 76 232 72Q232 53 261 47Q262 47 267 47T273 46Q276 46 277 46T280 45T283 42T284 35Q284 26 282 19Q279 6 276 4T261 1Q258 1 243 1T201 2T142 2Q64 2 42 0Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>Y</mi><mo>=</mo><mi>C</mi><mo>+</mo><mi>I</mi><mo>+</mo><mi>G</mi><mo>+</mo><mi>N</mi><mi>X</mi></math></mjx-assistive-mml></mjx-container></span></div>
<ol start="2" class="preview-paragraph-124 preview-line 124 125 126 127" data_line_start="124" data_line_end="127" data_line="124,128" count_line="4">
<li>
<div>GDP(I): the sum of all income earned in the economy - wages and salaries, profits, rents, net interest, production taxes less subsidies</div>
</li>
<li>
<div>GDP(O): the sum of all production (output) in the economy - the &quot;value added&quot; at each stage of production</div>
</li>
</ol>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-128 preview-line 128" id="an-example" data_line_start="128" data_line_end="128" data_line="128,129" count_line="1">
An Example</h2>
<ul class="preview-paragraph-129 preview-line 129 130 131 132" data_line_start="129" data_line_end="132" data_line="129,133" count_line="4">
<li>Row 1. Level: Forester &amp; Product: Wood &amp; Price: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
</math></mathmlword><asciimath style="display: none;">$1000</asciimath><latex style="display: none">\$ 1000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.656ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2500 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(500, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">$</mi><mn>1000</mn></math></mjx-assistive-mml></mjx-container></span> &amp; Labour: 900 &amp; Capital: 100</li>
<li>Row 2: Level: Manufacturer &amp; Product: 10 tables &amp; Price: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
</math></mathmlword><asciimath style="display: none;">$200</asciimath><latex style="display: none">\$ 200</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.525ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2000 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(500, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">$</mi><mn>200</mn></math></mjx-assistive-mml></mjx-container></span> each &amp; Labour: 700 &amp; Capital: 300</li>
<li>Row: Level: Retailer &amp; Product: 10 tables &amp; Price: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
</math></mathmlword><asciimath style="display: none;">$400</asciimath><latex style="display: none">\$ 400</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.525ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2000 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(500, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">$</mi><mn>400</mn></math></mjx-assistive-mml></mjx-container></span> each &amp; Labour: 1200 &amp; Capital: 800</li>
</ul>
<div class="preview-paragraph-133 preview-line 133 134" data_line_start="133" data_line_end="134" data_line="133,135" count_line="2">Pictures representing the 3 stages (wood, a factory, and shop) are shown.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-16.jpg?height=506&amp;width=2462&amp;top_left_y=1174&amp;top_left_x=438" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-136 preview-line 136" id="an-example-2" data_line_start="136" data_line_end="136" data_line="136,137" count_line="1">
An Example</h2>
<div class="preview-paragraph-138 preview-line 138 139 140" data_line_start="138" data_line_end="140" data_line="138,141" count_line="3">Method 1: GDP(E) = <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>10</mn>
  <mo>&#x2217;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>4000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>10</mn>
  <mo>∗</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>4000</mn>
</math></mathmlword><asciimath style="display: none;">10**$400=$4000</asciimath><latex style="display: none">10 * \$ 400=\$ 4000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.186ex" xmlns="http://www.w3.org/2000/svg" width="17.597ex" height="1.882ex" role="img" focusable="false" viewBox="0 -750 7778 832" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mo" transform="translate(1222.2, 0)"><path data-c="2217" d="M229 286Q216 420 216 436Q216 454 240 464Q241 464 245 464T251 465Q263 464 273 456T283 436Q283 419 277 356T270 286L328 328Q384 369 389 372T399 375Q412 375 423 365T435 338Q435 325 425 315Q420 312 357 282T289 250L355 219L425 184Q434 175 434 161Q434 146 425 136T401 125Q393 125 383 131T328 171L270 213Q283 79 283 63Q283 53 276 44T250 35Q231 35 224 44T216 63Q216 80 222 143T229 213L171 171Q115 130 110 127Q106 124 100 124Q87 124 76 134T64 161Q64 166 64 169T67 175T72 181T81 188T94 195T113 204T138 215T170 230T210 250L74 315Q65 324 65 338Q65 353 74 363T98 374Q106 374 116 368T171 328L229 286Z"></path></g><g data-mml-node="mi" transform="translate(1944.4, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(2444.4, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(4222.2, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(5278, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(5778, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>10</mn><mo>∗</mo><mi mathvariant="normal">$</mi><mn>400</mn><mo>=</mo><mi mathvariant="normal">$</mi><mn>4000</mn></math></mjx-assistive-mml></mjx-container></span><br>
Method 2: GDP(I) = $900 +$100 +$700 +$300 +$1200 +$800 = $4000$<br>
Method 3: GDP(O) <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mo stretchy="false">[</mo>
  <mn>10</mn>
  <mo>&#x2217;</mo>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>&#x2212;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo stretchy="false">)</mo>
  <mo stretchy="false">]</mo>
  <mo>+</mo>
  <mo stretchy="false">[</mo>
  <mn>10</mn>
  <mo>&#x2217;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo>&#x2212;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
  <mo stretchy="false">]</mo>
  <mo>+</mo>
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>4000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mo stretchy="false">[</mo>
  <mn>10</mn>
  <mo>∗</mo>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>−</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo stretchy="false">)</mo>
  <mo stretchy="false">]</mo>
  <mo>+</mo>
  <mo stretchy="false">[</mo>
  <mn>10</mn>
  <mo>∗</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo>−</mo>
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
  <mo stretchy="false">]</mo>
  <mo>+</mo>
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>4000</mn>
</math></mathmlword><asciimath style="display: none;">=[10**($400-$200)]+[10**$200-$1000]+$1000=$4000</asciimath><latex style="display: none">=[10 *(\$ 400-\$ 200)]+[10 * \$ 200-\$ 1000]+\$ 1000=\$ 4000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.566ex" xmlns="http://www.w3.org/2000/svg" width="60.086ex" height="2.262ex" role="img" focusable="false" viewBox="0 -750 26558 1000" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mo" transform="translate(1055.8, 0)"><path data-c="5B" d="M118 -250V750H255V710H158V-210H255V-250H118Z"></path></g><g data-mml-node="mn" transform="translate(1333.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mo" transform="translate(2556, 0)"><path data-c="2217" d="M229 286Q216 420 216 436Q216 454 240 464Q241 464 245 464T251 465Q263 464 273 456T283 436Q283 419 277 356T270 286L328 328Q384 369 389 372T399 375Q412 375 423 365T435 338Q435 325 425 315Q420 312 357 282T289 250L355 219L425 184Q434 175 434 161Q434 146 425 136T401 125Q393 125 383 131T328 171L270 213Q283 79 283 63Q283 53 276 44T250 35Q231 35 224 44T216 63Q216 80 222 143T229 213L171 171Q115 130 110 127Q106 124 100 124Q87 124 76 134T64 161Q64 166 64 169T67 175T72 181T81 188T94 195T113 204T138 215T170 230T210 250L74 315Q65 324 65 338Q65 353 74 363T98 374Q106 374 116 368T171 328L229 286Z"></path></g><g data-mml-node="mo" transform="translate(3278.2, 0)"><path data-c="28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path></g><g data-mml-node="mi" transform="translate(3667.2, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(4167.2, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(5889.4, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mi" transform="translate(6889.7, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(7389.7, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(8889.7, 0)"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g><g data-mml-node="mo" transform="translate(9278.7, 0)"><path data-c="5D" d="M22 710V750H159V-250H22V-210H119V710H22Z"></path></g><g data-mml-node="mo" transform="translate(9778.9, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mo" transform="translate(10779.1, 0)"><path data-c="5B" d="M118 -250V750H255V710H158V-210H255V-250H118Z"></path></g><g data-mml-node="mn" transform="translate(11057.1, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mo" transform="translate(12279.3, 0)"><path data-c="2217" d="M229 286Q216 420 216 436Q216 454 240 464Q241 464 245 464T251 465Q263 464 273 456T283 436Q283 419 277 356T270 286L328 328Q384 369 389 372T399 375Q412 375 423 365T435 338Q435 325 425 315Q420 312 357 282T289 250L355 219L425 184Q434 175 434 161Q434 146 425 136T401 125Q393 125 383 131T328 171L270 213Q283 79 283 63Q283 53 276 44T250 35Q231 35 224 44T216 63Q216 80 222 143T229 213L171 171Q115 130 110 127Q106 124 100 124Q87 124 76 134T64 161Q64 166 64 169T67 175T72 181T81 188T94 195T113 204T138 215T170 230T210 250L74 315Q65 324 65 338Q65 353 74 363T98 374Q106 374 116 368T171 328L229 286Z"></path></g><g data-mml-node="mi" transform="translate(13001.6, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(13501.6, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(15223.8, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mi" transform="translate(16224, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(16724, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g><g data-mml-node="mo" transform="translate(18724, 0)"><path data-c="5D" d="M22 710V750H159V-250H22V-210H119V710H22Z"></path></g><g data-mml-node="mo" transform="translate(19224.2, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mi" transform="translate(20224.4, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(20724.4, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g><g data-mml-node="mo" transform="translate(23002.2, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(24058, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(24558, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mo stretchy="false">[</mo><mn>10</mn><mo>∗</mo><mo stretchy="false">(</mo><mi mathvariant="normal">$</mi><mn>400</mn><mo>−</mo><mi mathvariant="normal">$</mi><mn>200</mn><mo stretchy="false">)</mo><mo stretchy="false">]</mo><mo>+</mo><mo stretchy="false">[</mo><mn>10</mn><mo>∗</mo><mi mathvariant="normal">$</mi><mn>200</mn><mo>−</mo><mi mathvariant="normal">$</mi><mn>1000</mn><mo stretchy="false">]</mo><mo>+</mo><mi mathvariant="normal">$</mi><mn>1000</mn><mo>=</mo><mi mathvariant="normal">$</mi><mn>4000</mn></math></mjx-assistive-mml></mjx-container></span></div>
<div class="preview-paragraph-142 preview-line 142" data_line_start="142" data_line_end="142" data_line="142,143" count_line="1">Very important to notice that we measure value added. Adding value of output at each stage instead of value added would lead to double or triple counting</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-144 preview-line 144" id="an-international-example" data_line_start="144" data_line_end="144" data_line="144,145" count_line="1">
An International Example</h2>
<ul class="preview-paragraph-146 preview-line 146 147 148 149" data_line_start="146" data_line_end="149" data_line="146,150" count_line="4">
<li>Row 1. Level: Forester (Canada) &amp; Product: Wood &amp; Price: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>1000</mn>
</math></mathmlword><asciimath style="display: none;">$1000</asciimath><latex style="display: none">\$ 1000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.656ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2500 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(500, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">$</mi><mn>1000</mn></math></mjx-assistive-mml></mjx-container></span> &amp; Labour: 900 &amp; Capital: 100</li>
<li>Row 2: Level: Manufacturer (Mexico) &amp; Product: 10 tables &amp; Price: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
</math></mathmlword><asciimath style="display: none;">$200</asciimath><latex style="display: none">\$ 200</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.525ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2000 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(500, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">$</mi><mn>200</mn></math></mjx-assistive-mml></mjx-container></span> each &amp; Labour: 700 &amp; Capital: 300</li>
<li>Row: Level: Retailer (U.S.) &amp; Product: 10 tables &amp; Price: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
</math></mathmlword><asciimath style="display: none;">$400</asciimath><latex style="display: none">\$ 400</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.525ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2000 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mi"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(500, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="normal">$</mi><mn>400</mn></math></mjx-assistive-mml></mjx-container></span> each &amp; Labour: 1200 &amp; Capital: 800</li>
</ul>
<div class="preview-paragraph-150 preview-line 150" data_line_start="150" data_line_end="150" data_line="150,151" count_line="1">Method 1: US GDP(E) <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>10</mn>
  <mo>&#x2217;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>&#x2212;</mo>
  <mn>10</mn>
  <mo>&#x2217;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>2000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>10</mn>
  <mo>∗</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>−</mo>
  <mn>10</mn>
  <mo>∗</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>2000</mn>
</math></mathmlword><asciimath style="display: none;">=10**$400-10**$200=$2000</asciimath><latex style="display: none">=10 * \$ 400-10 * \$ 200=\$ 2000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.186ex" xmlns="http://www.w3.org/2000/svg" width="31.676ex" height="1.882ex" role="img" focusable="false" viewBox="0 -750 14000.7 832" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1055.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mo" transform="translate(2278, 0)"><path data-c="2217" d="M229 286Q216 420 216 436Q216 454 240 464Q241 464 245 464T251 465Q263 464 273 456T283 436Q283 419 277 356T270 286L328 328Q384 369 389 372T399 375Q412 375 423 365T435 338Q435 325 425 315Q420 312 357 282T289 250L355 219L425 184Q434 175 434 161Q434 146 425 136T401 125Q393 125 383 131T328 171L270 213Q283 79 283 63Q283 53 276 44T250 35Q231 35 224 44T216 63Q216 80 222 143T229 213L171 171Q115 130 110 127Q106 124 100 124Q87 124 76 134T64 161Q64 166 64 169T67 175T72 181T81 188T94 195T113 204T138 215T170 230T210 250L74 315Q65 324 65 338Q65 353 74 363T98 374Q106 374 116 368T171 328L229 286Z"></path></g><g data-mml-node="mi" transform="translate(3000.2, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(3500.2, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(5222.4, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mn" transform="translate(6222.7, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mo" transform="translate(7444.9, 0)"><path data-c="2217" d="M229 286Q216 420 216 436Q216 454 240 464Q241 464 245 464T251 465Q263 464 273 456T283 436Q283 419 277 356T270 286L328 328Q384 369 389 372T399 375Q412 375 423 365T435 338Q435 325 425 315Q420 312 357 282T289 250L355 219L425 184Q434 175 434 161Q434 146 425 136T401 125Q393 125 383 131T328 171L270 213Q283 79 283 63Q283 53 276 44T250 35Q231 35 224 44T216 63Q216 80 222 143T229 213L171 171Q115 130 110 127Q106 124 100 124Q87 124 76 134T64 161Q64 166 64 169T67 175T72 181T81 188T94 195T113 204T138 215T170 230T210 250L74 315Q65 324 65 338Q65 353 74 363T98 374Q106 374 116 368T171 328L229 286Z"></path></g><g data-mml-node="mi" transform="translate(8167.1, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(8667.1, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(10444.9, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(11500.7, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(12000.7, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mn>10</mn><mo>∗</mo><mi mathvariant="normal">$</mi><mn>400</mn><mo>−</mo><mn>10</mn><mo>∗</mo><mi mathvariant="normal">$</mi><mn>200</mn><mo>=</mo><mi mathvariant="normal">$</mi><mn>2000</mn></math></mjx-assistive-mml></mjx-container></span></div>
<div class="preview-paragraph-152 preview-line 152" data_line_start="152" data_line_end="152" data_line="152,153" count_line="1">Method 2: US GDP <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">(</mo>
  <mi>I</mi>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>1200</mn>
  <mo>+</mo>
  <mi mathvariant="normal">$</mi>
  <mn>800</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>2000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">(</mo>
  <mi>I</mi>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>1200</mn>
  <mo>+</mo>
  <mi mathvariant="normal">$</mi>
  <mn>800</mn>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>2000</mn>
</math></mathmlword><asciimath style="display: none;">(I)=$1200+$800=$2000</asciimath><latex style="display: none">(I)=\$ 1200+\$ 800=\$ 2000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.566ex" xmlns="http://www.w3.org/2000/svg" width="27.537ex" height="2.262ex" role="img" focusable="false" viewBox="0 -750 12171.6 1000" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path></g><g data-mml-node="mi" transform="translate(389, 0)"><path data-c="49" d="M43 1Q26 1 26 10Q26 12 29 24Q34 43 39 45Q42 46 54 46H60Q120 46 136 53Q137 53 138 54Q143 56 149 77T198 273Q210 318 216 344Q286 624 286 626Q284 630 284 631Q274 637 213 637H193Q184 643 189 662Q193 677 195 680T209 683H213Q285 681 359 681Q481 681 487 683H497Q504 676 504 672T501 655T494 639Q491 637 471 637Q440 637 407 634Q393 631 388 623Q381 609 337 432Q326 385 315 341Q245 65 245 59Q245 52 255 50T307 46H339Q345 38 345 37T342 19Q338 6 332 0H316Q279 2 179 2Q143 2 113 2T65 2T43 1Z"></path></g><g data-mml-node="mo" transform="translate(893, 0)"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g><g data-mml-node="mo" transform="translate(1559.8, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(2615.6, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(3115.6, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g><g data-mml-node="mo" transform="translate(5337.8, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mi" transform="translate(6338, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(6838, 0)"><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(8615.8, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(9671.6, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(10171.6, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">(</mo><mi>I</mi><mo stretchy="false">)</mo><mo>=</mo><mi mathvariant="normal">$</mi><mn>1200</mn><mo>+</mo><mi mathvariant="normal">$</mi><mn>800</mn><mo>=</mo><mi mathvariant="normal">$</mi><mn>2000</mn></math></mjx-assistive-mml></mjx-container></span></div>
<div class="preview-paragraph-154 preview-line 154" data_line_start="154" data_line_end="154" data_line="154,155" count_line="1">Method 3: US GDP(O) <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>10</mn>
  <mo>&#x2217;</mo>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>&#x2212;</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>2000</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>10</mn>
  <mo>∗</mo>
  <mo stretchy="false">(</mo>
  <mi mathvariant="normal">$</mi>
  <mn>400</mn>
  <mo>−</mo>
  <mi mathvariant="normal">$</mi>
  <mn>200</mn>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mi mathvariant="normal">$</mi>
  <mn>2000</mn>
</math></mathmlword><asciimath style="display: none;">=10**($400-$200)=$2000</asciimath><latex style="display: none">=10 *(\$ 400-\$ 200)=\$ 2000</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.566ex" xmlns="http://www.w3.org/2000/svg" width="29.037ex" height="2.262ex" role="img" focusable="false" viewBox="0 -750 12834.2 1000" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1055.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mo" transform="translate(2278, 0)"><path data-c="2217" d="M229 286Q216 420 216 436Q216 454 240 464Q241 464 245 464T251 465Q263 464 273 456T283 436Q283 419 277 356T270 286L328 328Q384 369 389 372T399 375Q412 375 423 365T435 338Q435 325 425 315Q420 312 357 282T289 250L355 219L425 184Q434 175 434 161Q434 146 425 136T401 125Q393 125 383 131T328 171L270 213Q283 79 283 63Q283 53 276 44T250 35Q231 35 224 44T216 63Q216 80 222 143T229 213L171 171Q115 130 110 127Q106 124 100 124Q87 124 76 134T64 161Q64 166 64 169T67 175T72 181T81 188T94 195T113 204T138 215T170 230T210 250L74 315Q65 324 65 338Q65 353 74 363T98 374Q106 374 116 368T171 328L229 286Z"></path></g><g data-mml-node="mo" transform="translate(3000.2, 0)"><path data-c="28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path></g><g data-mml-node="mi" transform="translate(3389.2, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(3889.2, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(5611.4, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mi" transform="translate(6611.7, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(7111.7, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g><g data-mml-node="mo" transform="translate(8611.7, 0)"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g><g data-mml-node="mo" transform="translate(9278.4, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(10334.2, 0)"><path data-c="24" d="M162 187Q162 164 146 149T109 133H103V130Q108 115 115 105Q122 92 131 82T150 64T170 52T190 44T206 40T220 37L227 36V313Q190 320 162 335Q116 358 86 404T55 508Q55 567 85 614T165 685Q186 696 225 704H227V750H273V704L286 703Q369 690 413 631Q441 588 444 531Q444 514 443 509Q439 490 425 479T391 468Q368 468 353 483T337 522Q337 546 353 560T390 575L394 576V578Q386 599 372 614T342 637T314 649T288 656L273 658V408L288 405Q329 394 355 376Q396 348 420 300T444 199Q444 130 408 76T313 1Q286 -9 276 -9H273V-56H227V-10H221Q202 -6 193 -4T155 11T108 41T74 94T55 176V182Q55 227 95 238Q103 240 108 240Q129 240 145 226T162 187ZM225 657Q219 657 204 651T169 632T135 594T121 538Q121 512 131 491T156 457T187 435T213 423T227 420V539Q227 657 225 657ZM378 169Q378 230 339 265T274 301Q273 301 273 169V37Q324 50 351 87T378 169Z"></path></g><g data-mml-node="mn" transform="translate(10834.2, 0)"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1500, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mn>10</mn><mo>∗</mo><mo stretchy="false">(</mo><mi mathvariant="normal">$</mi><mn>400</mn><mo>−</mo><mi mathvariant="normal">$</mi><mn>200</mn><mo stretchy="false">)</mo><mo>=</mo><mi mathvariant="normal">$</mi><mn>2000</mn></math></mjx-assistive-mml></mjx-container></span></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-156 preview-line 156" id="uk-real-gdp-over-the-last-two-centuries" data_line_start="156" data_line_end="156" data_line="156,157" count_line="1">
UK Real GDP over the last two centuries</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-157 preview-line 157" id="graph%3A-uk-real-gdp-in-2006-prices" data_line_start="157" data_line_end="157" data_line="157,158" count_line="1">
Graph: UK Real GDP in 2006 prices</h3>
<div class="preview-paragraph-158 preview-line 158 159" data_line_start="158" data_line_end="159" data_line="158,160" count_line="2">A line graph showing UK real GDP from 1830 to 2010 (in 2006 prices) is shown. GDP dropped after the world wars, the first and second oil shocks in early and late 1970s, and the 2008 financial crisis. The curve resembles an exponential curve with the fastest rate of growth being observed in the last two decades.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-19.jpg?height=1353&amp;width=2934&amp;top_left_y=340&amp;top_left_x=234" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-161 preview-line 161" id="recent-uk-real-gdp-growth" data_line_start="161" data_line_end="161" data_line="161,162" count_line="1">
Recent UK real GDP growth</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-162 preview-line 162" id="graph%3A-change-in-real-uk-gdp" data_line_start="162" data_line_end="162" data_line="162,163" count_line="1">
Graph: Change in real UK GDP</h3>
<div class="preview-paragraph-163 preview-line 163" data_line_start="163" data_line_end="163" data_line="163,164" count_line="1">A line graph showing the change in UK Real GDP in percentage from the previous year from 2000 to 2022 is shown. GDP grew between 2 to 3 percent a year during the period, but dropped by close to 7 percent in Q1 of 2009 and by 22 percent in Q2 of 2020, and then recovered in Q4 of 2021 (20 percent increase). In Q3 2022, the increase in real GDP compared to the previous year was back to about 2%.</div>
<div class="preview-paragraph-165 preview-line 165" data_line_start="165" data_line_end="165" data_line="165,166" count_line="1"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-20.jpg?height=1259&amp;width=2114&amp;top_left_y=421&amp;top_left_x=606" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-167 preview-line 167" id="recent-uk-real-gdp-level" data_line_start="167" data_line_end="167" data_line="167,168" count_line="1">
Recent UK real GDP level</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-168 preview-line 168" id="graph%3A-real-uk-gdp-in-levels" data_line_start="168" data_line_end="168" data_line="168,169" count_line="1">
Graph: Real UK GDP in levels</h3>
<div class="preview-paragraph-169 preview-line 169 170" data_line_start="169" data_line_end="170" data_line="169,171" count_line="2">A line graph showing the UK Real GDP from 2000 to 2022 is shown. GDP grew steadily during the period, except from a drop in 2009 and 2020. While it took about 4 years for real GDP to reach its Q1 2009 level after the drop in Q4 2009, real GDP recovered in about 1.5 years after the 2021 drop.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-21.jpg?height=1364&amp;width=2122&amp;top_left_y=326&amp;top_left_x=602" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-172 preview-line 172" id="gdp(e)%3A-c%2Bi%2Bg%2Bnx" data_line_start="172" data_line_end="172" data_line="172,173" count_line="1">
GDP(E): C+I+G+NX</h2>
<div class="preview-paragraph-174 preview-line 174" data_line_start="174" data_line_end="174" data_line="174,175" count_line="1">Consumption (C): about <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>66</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>66</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">66%</asciimath><latex style="display: none">66 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.147ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1833 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="36" d="M42 313Q42 476 123 571T303 666Q372 666 402 630T432 550Q432 525 418 510T379 495Q356 495 341 509T326 548Q326 592 373 601Q351 623 311 626Q240 626 194 566Q147 500 147 364L148 360Q153 366 156 373Q197 433 263 433H267Q313 433 348 414Q372 400 396 374T435 317Q456 268 456 210V192Q456 169 451 149Q440 90 387 34T253 -22Q225 -22 199 -14T143 16T92 75T56 172T42 313ZM257 397Q227 397 205 380T171 335T154 278T148 216Q148 133 160 97T198 39Q222 21 251 21Q302 21 329 59Q342 77 347 104T352 209Q352 289 347 316T329 361Q302 397 257 397Z"></path><path data-c="36" d="M42 313Q42 476 123 571T303 666Q372 666 402 630T432 550Q432 525 418 510T379 495Q356 495 341 509T326 548Q326 592 373 601Q351 623 311 626Q240 626 194 566Q147 500 147 364L148 360Q153 366 156 373Q197 433 263 433H267Q313 433 348 414Q372 400 396 374T435 317Q456 268 456 210V192Q456 169 451 149Q440 90 387 34T253 -22Q225 -22 199 -14T143 16T92 75T56 172T42 313ZM257 397Q227 397 205 380T171 335T154 278T148 216Q148 133 160 97T198 39Q222 21 251 21Q302 21 329 59Q342 77 347 104T352 209Q352 289 347 316T329 361Q302 397 257 397Z" transform="translate(500, 0)"></path></g><g data-mml-node="mi" transform="translate(1000, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>66</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> of UK GDP</div>
<ul class="preview-paragraph-175 preview-line 175 176" data_line_start="175" data_line_end="176" data_line="175,177" count_line="2">
<li>Durable goods, non-durable goods and services purchased by households</li>
</ul>
<div class="preview-paragraph-177 preview-line 177" data_line_start="177" data_line_end="177" data_line="177,178" count_line="1">Investment (I): about <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>17</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>17</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">17%</asciimath><latex style="display: none">17 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.147ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1833 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z" transform="translate(500, 0)"></path></g><g data-mml-node="mi" transform="translate(1000, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>17</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> of UK GDP (including government investment)</div>
<ul class="preview-paragraph-178 preview-line 178 179 180 181" data_line_start="178" data_line_end="181" data_line="178,182" count_line="4">
<li>Non-residential investment (machinery, buildings etc) by firms</li>
<li>Residential investment (new homes/renovations) by firms and households</li>
<li>Changes in firms' inventories</li>
</ul>
<div class="preview-paragraph-182 preview-line 182" data_line_start="182" data_line_end="182" data_line="182,183" count_line="1">Government (G): about <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>20</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>20</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">20%</asciimath><latex style="display: none">20 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.147ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1833 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path></g><g data-mml-node="mi" transform="translate(1000, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>20</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> of UK GDP (excluding government investment)</div>
<ul class="preview-paragraph-183 preview-line 183 184 185" data_line_start="183" data_line_end="185" data_line="183,186" count_line="3">
<li>Goods and services purchased by all layers of government</li>
<li>Excludes social security transfers, which are not exchanged for new goods and services produced</li>
</ul>
<div class="preview-paragraph-186 preview-line 186" data_line_start="186" data_line_end="186" data_line="186,187" count_line="1">Net exports <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">(</mo>
  <mi>N</mi>
  <mi>X</mi>
  <mo>=</mo>
  <mi>X</mi>
  <mo>&#x2212;</mo>
  <mi>M</mi>
  <mo stretchy="false">)</mo>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">(</mo>
  <mi>N</mi>
  <mi>X</mi>
  <mo>=</mo>
  <mi>X</mi>
  <mo>−</mo>
  <mi>M</mi>
  <mo stretchy="false">)</mo>
</math></mathmlword><asciimath style="display: none;">(NX=X-M)</asciimath><latex style="display: none">(N X=X-M)</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.566ex" xmlns="http://www.w3.org/2000/svg" width="15.785ex" height="2.262ex" role="img" focusable="false" viewBox="0 -750 6977 1000" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path></g><g data-mml-node="mi" transform="translate(389, 0)"><path data-c="4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path></g><g data-mml-node="mi" transform="translate(1277, 0)"><path data-c="58" d="M42 0H40Q26 0 26 11Q26 15 29 27Q33 41 36 43T55 46Q141 49 190 98Q200 108 306 224T411 342Q302 620 297 625Q288 636 234 637H206Q200 643 200 645T202 664Q206 677 212 683H226Q260 681 347 681Q380 681 408 681T453 682T473 682Q490 682 490 671Q490 670 488 658Q484 643 481 640T465 637Q434 634 411 620L488 426L541 485Q646 598 646 610Q646 628 622 635Q617 635 609 637Q594 637 594 648Q594 650 596 664Q600 677 606 683H618Q619 683 643 683T697 681T738 680Q828 680 837 683H845Q852 676 852 672Q850 647 840 637H824Q790 636 763 628T722 611T698 593L687 584Q687 585 592 480L505 384Q505 383 536 304T601 142T638 56Q648 47 699 46Q734 46 734 37Q734 35 732 23Q728 7 725 4T711 1Q708 1 678 1T589 2Q528 2 496 2T461 1Q444 1 444 10Q444 11 446 25Q448 35 450 39T455 44T464 46T480 47T506 54Q523 62 523 64Q522 64 476 181L429 299Q241 95 236 84Q232 76 232 72Q232 53 261 47Q262 47 267 47T273 46Q276 46 277 46T280 45T283 42T284 35Q284 26 282 19Q279 6 276 4T261 1Q258 1 243 1T201 2T142 2Q64 2 42 0Z"></path></g><g data-mml-node="mo" transform="translate(2406.8, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mi" transform="translate(3462.6, 0)"><path data-c="58" d="M42 0H40Q26 0 26 11Q26 15 29 27Q33 41 36 43T55 46Q141 49 190 98Q200 108 306 224T411 342Q302 620 297 625Q288 636 234 637H206Q200 643 200 645T202 664Q206 677 212 683H226Q260 681 347 681Q380 681 408 681T453 682T473 682Q490 682 490 671Q490 670 488 658Q484 643 481 640T465 637Q434 634 411 620L488 426L541 485Q646 598 646 610Q646 628 622 635Q617 635 609 637Q594 637 594 648Q594 650 596 664Q600 677 606 683H618Q619 683 643 683T697 681T738 680Q828 680 837 683H845Q852 676 852 672Q850 647 840 637H824Q790 636 763 628T722 611T698 593L687 584Q687 585 592 480L505 384Q505 383 536 304T601 142T638 56Q648 47 699 46Q734 46 734 37Q734 35 732 23Q728 7 725 4T711 1Q708 1 678 1T589 2Q528 2 496 2T461 1Q444 1 444 10Q444 11 446 25Q448 35 450 39T455 44T464 46T480 47T506 54Q523 62 523 64Q522 64 476 181L429 299Q241 95 236 84Q232 76 232 72Q232 53 261 47Q262 47 267 47T273 46Q276 46 277 46T280 45T283 42T284 35Q284 26 282 19Q279 6 276 4T261 1Q258 1 243 1T201 2T142 2Q64 2 42 0Z"></path></g><g data-mml-node="mo" transform="translate(4536.8, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mi" transform="translate(5537, 0)"><path data-c="4D" d="M289 629Q289 635 232 637Q208 637 201 638T194 648Q194 649 196 659Q197 662 198 666T199 671T201 676T203 679T207 681T212 683T220 683T232 684Q238 684 262 684T307 683Q386 683 398 683T414 678Q415 674 451 396L487 117L510 154Q534 190 574 254T662 394Q837 673 839 675Q840 676 842 678T846 681L852 683H948Q965 683 988 683T1017 684Q1051 684 1051 673Q1051 668 1048 656T1045 643Q1041 637 1008 637Q968 636 957 634T939 623Q936 618 867 340T797 59Q797 55 798 54T805 50T822 48T855 46H886Q892 37 892 35Q892 19 885 5Q880 0 869 0Q864 0 828 1T736 2Q675 2 644 2T609 1Q592 1 592 11Q592 13 594 25Q598 41 602 43T625 46Q652 46 685 49Q699 52 704 61Q706 65 742 207T813 490T848 631L654 322Q458 10 453 5Q451 4 449 3Q444 0 433 0Q418 0 415 7Q413 11 374 317L335 624L267 354Q200 88 200 79Q206 46 272 46H282Q288 41 289 37T286 19Q282 3 278 1Q274 0 267 0Q265 0 255 0T221 1T157 2Q127 2 95 1T58 0Q43 0 39 2T35 11Q35 13 38 25T43 40Q45 46 65 46Q135 46 154 86Q158 92 223 354T289 629Z"></path></g><g data-mml-node="mo" transform="translate(6588, 0)"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">(</mo><mi>N</mi><mi>X</mi><mo>=</mo><mi>X</mi><mo>−</mo><mi>M</mi><mo stretchy="false">)</mo></math></mjx-assistive-mml></mjx-container></span> : about <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>&#x2212;</mo>
  <mn>3</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>−</mo>
  <mn>3</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">-3%</asciimath><latex style="display: none">-3 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.186ex" xmlns="http://www.w3.org/2000/svg" width="4.776ex" height="1.882ex" role="img" focusable="false" viewBox="0 -750 2111 832" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path></g><g data-mml-node="mi" transform="translate(1278, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>−</mo><mn>3</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> of UK GDP</div>
<ul class="preview-paragraph-187 preview-line 187 188" data_line_start="187" data_line_end="188" data_line="187,189" count_line="2">
<li>Expenditure by foreigners on domestically produced goods and services (exports), minus expenditure by UK residents on foreign goods and services (imports)</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-189 preview-line 189" id="composition-of-uk-gdp-by-expenditure" data_line_start="189" data_line_end="189" data_line="189,190" count_line="1">
Composition of UK GDP by expenditure</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-190 preview-line 190" id="graph%3A-composition-of-uk-gdp" data_line_start="190" data_line_end="190" data_line="190,191" count_line="1">
Graph: Composition of UK GDP</h3>
<div class="preview-paragraph-191 preview-line 191 192" data_line_start="191" data_line_end="192" data_line="191,193" count_line="2">A bar plot shows the composition of UK GDP between net exports X-M, consumption, investment, and government spending between 1838 and 2008. The largest share, about 75% (until 1940) and 60% (after 1040) is consumptions. Net exports was very close to 0 until 1900, and then became slightly negative, and remained mostly negative for the rest of the period. Government spending increased from about 6% until 1940 to about 20 percent thereafter. A notable exception corresponds to the first and second world war, when it was about 40% of GDP. Investment went from about 8 percent of GDP prior to 1940 to about 8 percent after 1940.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-23.jpg?height=987&amp;width=1936&amp;top_left_y=476&amp;top_left_x=631" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-194 preview-line 194" id="gdp(i)" data_line_start="194" data_line_end="194" data_line="194,195" count_line="1">
GDP(I)</h2>
<ul class="preview-paragraph-196 preview-line 196 197 198 199 200 201 202" data_line_start="196" data_line_end="202" data_line="196,203" count_line="7">
<li>GDP at market prices: 1933.3 <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
</math></mathmlword><asciimath style="display: none;">£</asciimath><latex style="display: none">£</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="1.74ex" height="1.64ex" role="img" focusable="false" viewBox="0 -714 769 725" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow></math></mjx-assistive-mml></mjx-container></span> billions, Share of GDP: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>100.0</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>100.0</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">100.0%</asciimath><latex style="display: none">100.0 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="7.038ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 3111 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1778, 0)"></path></g><g data-mml-node="mi" transform="translate(2278, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>100.0</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>, Per person: £ 29599</li>
<li>Total compensation of employees: 958.5 <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
</math></mathmlword><asciimath style="display: none;">£</asciimath><latex style="display: none">£</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="1.74ex" height="1.64ex" role="img" focusable="false" viewBox="0 -714 769 725" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow></math></mjx-assistive-mml></mjx-container></span> billions, Share of GDP: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>49.6</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>49.6</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">49.6%</asciimath><latex style="display: none">49.6 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="39" d="M352 287Q304 211 232 211Q154 211 104 270T44 396Q42 412 42 436V444Q42 537 111 606Q171 666 243 666Q245 666 249 666T257 665H261Q273 665 286 663T323 651T370 619T413 560Q456 472 456 334Q456 194 396 97Q361 41 312 10T208 -22Q147 -22 108 7T68 93T121 149Q143 149 158 135T173 96Q173 78 164 65T148 49T135 44L131 43Q131 41 138 37T164 27T206 22H212Q272 22 313 86Q352 142 352 280V287ZM244 248Q292 248 321 297T351 430Q351 508 343 542Q341 552 337 562T323 588T293 615T246 625Q208 625 181 598Q160 576 154 546T147 441Q147 358 152 329T172 282Q197 248 244 248Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="36" d="M42 313Q42 476 123 571T303 666Q372 666 402 630T432 550Q432 525 418 510T379 495Q356 495 341 509T326 548Q326 592 373 601Q351 623 311 626Q240 626 194 566Q147 500 147 364L148 360Q153 366 156 373Q197 433 263 433H267Q313 433 348 414Q372 400 396 374T435 317Q456 268 456 210V192Q456 169 451 149Q440 90 387 34T253 -22Q225 -22 199 -14T143 16T92 75T56 172T42 313ZM257 397Q227 397 205 380T171 335T154 278T148 216Q148 133 160 97T198 39Q222 21 251 21Q302 21 329 59Q342 77 347 104T352 209Q352 289 347 316T329 361Q302 397 257 397Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>49.6</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>, Per person: £14674</li>
<li>Gross operating surplus of private corporations: 392.6 <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
</math></mathmlword><asciimath style="display: none;">£</asciimath><latex style="display: none">£</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="1.74ex" height="1.64ex" role="img" focusable="false" viewBox="0 -714 769 725" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow></math></mjx-assistive-mml></mjx-container></span> billions, Share of GDP: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>20.3</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>20.3</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">20.3%</asciimath><latex style="display: none">20.3 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>20.3</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>, Per person: £6011</li>
<li>Other income: 354.0 <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
</math></mathmlword><asciimath style="display: none;">£</asciimath><latex style="display: none">£</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="1.74ex" height="1.64ex" role="img" focusable="false" viewBox="0 -714 769 725" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow></math></mjx-assistive-mml></mjx-container></span> billions, Share of GDP: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>18.3</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>18.3</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">18.3%</asciimath><latex style="display: none">18.3 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>18.3</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>, Per person: £5419</li>
<li>Gross value added at factor cost: 1700.9 <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
</math></mathmlword><asciimath style="display: none;">£</asciimath><latex style="display: none">£</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="1.74ex" height="1.64ex" role="img" focusable="false" viewBox="0 -714 769 725" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow></math></mjx-assistive-mml></mjx-container></span> billions, Share of GDP: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>88.0</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>88.0</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">88.0%</asciimath><latex style="display: none">88.0 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z"></path><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>88.0</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>, Per person: £26041</li>
<li>Taxes on products and production less subsidies: 232.4 <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
</math></mathmlword><asciimath style="display: none;">£</asciimath><latex style="display: none">£</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.025ex" xmlns="http://www.w3.org/2000/svg" width="1.74ex" height="1.64ex" role="img" focusable="false" viewBox="0 -714 769 725" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow></math></mjx-assistive-mml></mjx-container></span> billions, Share of GDP: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>12.0</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>12.0</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">12.0%</asciimath><latex style="display: none">12.0 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>12.0</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>, Per person: £ 3558</li>
</ul>
<div class="preview-paragraph-203 preview-line 203" data_line_start="203" data_line_end="203" data_line="203,204" count_line="1">Share of income to labour is between half and two thirds.</div>
<div class="preview-paragraph-205 preview-line 205" data_line_start="205" data_line_end="205" data_line="205,206" count_line="1">GDP income components 2016, current prices, seasonally adjusted, Other income = operating surplus of households + operating surplus of general government + operating surplus of public corporations + mixed income</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-207 preview-line 207" id="labour-share-of-uk-income" data_line_start="207" data_line_end="207" data_line="207,208" count_line="1">
Labour share of UK income</h2>
<h3 type="subsection" class="sub_section-title preview-paragraph-208 preview-line 208" id="graph%3A-labor-share-of-uk-income" data_line_start="208" data_line_end="208" data_line="208,209" count_line="1">
<span class="section-number">0.</span><span class="sub_section-number">1.</span> Graph: labor share of UK income</h3>
<div class="preview-paragraph-209 preview-line 209 210 211" data_line_start="209" data_line_end="211" data_line="209,212" count_line="3"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-25.jpg?height=353&amp;width=2802&amp;top_left_y=359&amp;top_left_x=232" alt="" data-align="center"></figure><br>
A line graph showing the labour share in the UK between 1948 and 2014 shows that Labour share of GDP has drifted down a little over time, from about 66 percent in the beginning of the period to about 50% in 1998, before it recovered to about 55 percent in 2014.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-25.jpg?height=477&amp;width=2793&amp;top_left_y=982&amp;top_left_x=262" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-213 preview-line 213" id="gdp-vs-gni" data_line_start="213" data_line_end="213" data_line="213,214" count_line="1">
GDP vs GNI</h2>
<div class="preview-paragraph-214 preview-line 214 215" data_line_start="214" data_line_end="215" data_line="214,216" count_line="2">Gross Domestic Product (GDP) denotes value of output of goods and services produced within a country (including nationals and resident foreigners). Measures value added in the<br>
country.</div>
<div class="preview-paragraph-218 preview-line 218" data_line_start="218" data_line_end="218" data_line="218,219" count_line="1">Gross National Income (GNI) denotes value of output of goods and services produced by the nationals of a country (excluding foreign residents remittances but including remittances from nationals resident abroad). Measures income of country's citizens</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-220 preview-line 220" id="from-gdp-to-gni" data_line_start="220" data_line_end="220" data_line="220,221" count_line="1">
From GDP to GNI</h2>
<div class="preview-paragraph-221 preview-line 221" data_line_start="221" data_line_end="221" data_line="221,222" count_line="1">Add transfers from overseas:</div>
<ul class="preview-paragraph-222 preview-line 222 223 224 225 226" data_line_start="222" data_line_end="226" data_line="222,227" count_line="5">
<li>remitted profits from UK firms' foreign operations</li>
<li>interest payments and dividends received from overseas investments</li>
<li>remittances from UK residents based overseas</li>
<li>grants received from foreign governments</li>
</ul>
<div class="preview-paragraph-227 preview-line 227" data_line_start="227" data_line_end="227" data_line="227,228" count_line="1">Deduct transfers to overseas countries:</div>
<ul class="preview-paragraph-228 preview-line 228 229 230 231 232" data_line_start="228" data_line_end="232" data_line="228,233" count_line="5">
<li>remitted profits by foreign firms operating in the UK</li>
<li>interest payments and dividends received by foreign investments in the UK</li>
<li>remittances by overseas residents based in the UK</li>
<li>grants paid by UK government</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-233 preview-line 233" id="some-issues-with-gdp" data_line_start="233" data_line_end="233" data_line="233,234" count_line="1">
Some Issues with GDP</h2>
<ul class="preview-paragraph-234 preview-line 234 235 236 237 238 239 240 241 242 243" data_line_start="234" data_line_end="243" data_line="234,244" count_line="10">
<li>Not all market activity is recorded in official statistics</li>
<li>Market prices may not reflect social values so may not be measure of welfare</li>
<li>GDP is a &quot;Gross&quot; concept - no allowance for depreciation and no concept of sustainability</li>
<li>GDP may not relate to consumption which is surely closer measure to welfare</li>
<li>GDP makes no allowance for inequality</li>
<li>Second hand good sales are not included - change of ownership but not production</li>
<li>Capital gains on houses do not enter GDP</li>
<li>Inventories count as a firm buying its own production</li>
<li>Even though most government services are not sold they are included in GDP. But price is measured by cost, e.g. public education as sum of teachers' salaries, cost of equipment etc.</li>
</ul>
<div class="preview-paragraph-244 preview-line 244" data_line_start="244" data_line_end="244" data_line="244,245" count_line="1">Check out &quot;Beyond GDP&quot; case study in the Jones' textbook.</div>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-247 preview-line 247" id="graph%3A-gdp-per-capita-in-different-countries-and-and-life-satisfaction" data_line_start="247" data_line_end="247" data_line="247,248" count_line="1">
Graph: GDP per capita in different countries and and life satisfaction</h3>
<div class="preview-paragraph-248 preview-line 248" data_line_start="248" data_line_end="248" data_line="248,249" count_line="1">A scatter plot showing GDP per capita and life satisfaction is shown. There is a positive, linear relationship between GDP per capital in UK dollars and average life satisfaction. The graph also shows that countries with higher GDP per capita, such as Norway, Ireland, and the US, have more inequality in life satisfaction between low and high earniers, with high earners being more satisfied than low earners.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-250 preview-line 250" id="section-4%3A-unemployment" data_line_start="250" data_line_end="250" data_line="250,251" count_line="1">
Section 4: Unemployment</h2>
<div class="preview-paragraph-251 preview-line 251" data_line_start="251" data_line_end="251" data_line="251,252" count_line="1">No other text is shown on this slide.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-253 preview-line 253" id="measuring-unemployment" data_line_start="253" data_line_end="253" data_line="253,254" count_line="1">
Measuring unemployment</h2>
<div class="preview-paragraph-254 preview-line 254" data_line_start="254" data_line_end="254" data_line="254,255" count_line="1">Labour force survey</div>
<ul class="preview-paragraph-255 preview-line 255 256 257" data_line_start="255" data_line_end="257" data_line="255,258" count_line="3">
<li>Employed: those 16+ who did paid work in the survey week or were temporarily away from paid work</li>
<li>Unemployed: those without a job who want a job, have been seeking work and can start in the next two weeks; or have found a job and will start in the next two weeks</li>
</ul>
<div class="preview-paragraph-258 preview-line 258" data_line_start="258" data_line_end="258" data_line="258,259" count_line="1">Economically inactive: the rest</div>
<div class="preview-paragraph-260 preview-line 260" data_line_start="260" data_line_end="260" data_line="260,261" count_line="1">Claimant count measure</div>
<ul class="preview-paragraph-261 preview-line 261 262" data_line_start="261" data_line_end="262" data_line="261,263" count_line="2">
<li>Those claiming unemployment-related benefits (JSA etc)</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-263 preview-line 263" id="current-uk-labour-force-survey-(october-2023)" data_line_start="263" data_line_end="263" data_line="263,264" count_line="1">
Current UK Labour Force Survey (October 2023)</h2>
<div class="preview-paragraph-265 preview-line 265" data_line_start="265" data_line_end="265" data_line="265,266" count_line="1">Employment =33.01 million people</div>
<div class="preview-paragraph-267 preview-line 267" data_line_start="267" data_line_end="267" data_line="267,268" count_line="1">Employment rate <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>75.7</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>75.7</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">=75.7%</asciimath><latex style="display: none">=75.7 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.186ex" xmlns="http://www.w3.org/2000/svg" width="8.296ex" height="1.882ex" role="img" focusable="false" viewBox="0 -750 3666.8 832" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1055.8, 0)"><path data-c="37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(2833.8, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mn>75.7</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></div>
<ul class="preview-paragraph-268 preview-line 268 269" data_line_start="268" data_line_end="269" data_line="268,270" count_line="2">
<li>proportion of people aged from 16 to 64 who were in work</li>
</ul>
<div class="preview-paragraph-270 preview-line 270" data_line_start="270" data_line_end="270" data_line="270,271" count_line="1">1.45 million unemployed people</div>
<ul class="preview-paragraph-271 preview-line 271 272" data_line_start="271" data_line_end="272" data_line="271,273" count_line="2">
<li>People not in work but seeking and available to work</li>
</ul>
<div class="preview-paragraph-273 preview-line 273" data_line_start="273" data_line_end="273" data_line="273,274" count_line="1">Unemployment rate <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>1.45</mn>
  <mrow>
    <mo>/</mo>
  </mrow>
  <mo stretchy="false">(</mo>
  <mn>1.45</mn>
  <mo>+</mo>
  <mn>33.01</mn>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mn>4.2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>1.45</mn>
  <mrow>
    <mo>/</mo>
  </mrow>
  <mo stretchy="false">(</mo>
  <mn>1.45</mn>
  <mo>+</mo>
  <mn>33.01</mn>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
  <mn>4.2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">=1.45//(1.45+33.01)=4.2%</asciimath><latex style="display: none">=1.45 /(1.45+33.01)=4.2 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.566ex" xmlns="http://www.w3.org/2000/svg" width="29.038ex" height="2.262ex" role="img" focusable="false" viewBox="0 -750 12834.8 1000" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1055.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z" transform="translate(778, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(1278, 0)"></path></g><g data-mml-node="TeXAtom" data-mjx-texclass="ORD" transform="translate(2833.8, 0)"><g data-mml-node="mo"><path data-c="2F" d="M423 750Q432 750 438 744T444 730Q444 725 271 248T92 -240Q85 -250 75 -250Q68 -250 62 -245T56 -231Q56 -221 230 257T407 740Q411 750 423 750Z"></path></g></g><g data-mml-node="mo" transform="translate(3333.8, 0)"><path data-c="28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path></g><g data-mml-node="mn" transform="translate(3722.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z" transform="translate(778, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mo" transform="translate(5723, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mn" transform="translate(6723.2, 0)"><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z" transform="translate(500, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1000, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1278, 0)"></path><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z" transform="translate(1778, 0)"></path></g><g data-mml-node="mo" transform="translate(9001.2, 0)"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g><g data-mml-node="mo" transform="translate(9668, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(10723.8, 0)"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z" transform="translate(778, 0)"></path></g><g data-mml-node="mi" transform="translate(12001.8, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mn>1.45</mn><mrow><mo>/</mo></mrow><mo stretchy="false">(</mo><mn>1.45</mn><mo>+</mo><mn>33.01</mn><mo stretchy="false">)</mo><mo>=</mo><mn>4.2</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span>.</div>
<ul class="preview-paragraph-274 preview-line 274 275" data_line_start="274" data_line_end="275" data_line="274,276" count_line="2">
<li>Number of unemployed divided by the total number of economically active people</li>
</ul>
<div class="preview-paragraph-276 preview-line 276" data_line_start="276" data_line_end="276" data_line="276,277" count_line="1">Inactive <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>8.7</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>8.7</mn>
</math></mathmlword><asciimath style="display: none;">=8.7</asciimath><latex style="display: none">=8.7</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.186ex" xmlns="http://www.w3.org/2000/svg" width="5.28ex" height="1.715ex" role="img" focusable="false" viewBox="0 -676 2333.8 758" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1055.8, 0)"><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z" transform="translate(778, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mn>8.7</mn></math></mjx-assistive-mml></mjx-container></span> million people</div>
<ul class="preview-paragraph-277 preview-line 277 278" data_line_start="277" data_line_end="278" data_line="277,279" count_line="2">
<li>Aged from 16 to 64 who were not working and not seeking or available to work</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-279 preview-line 279" id="unemployment-in-british-history" data_line_start="279" data_line_end="279" data_line="279,280" count_line="1">
Unemployment in British history</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-280 preview-line 280" id="graph%3A-unemployment-in-british-history" data_line_start="280" data_line_end="280" data_line="280,281" count_line="1">
Graph: Unemployment in British history</h3>
<div class="preview-paragraph-281 preview-line 281 282" data_line_start="281" data_line_end="282" data_line="281,283" count_line="2">The line graph shows unemployment between 1870 and 2000. It is highly volatile. The lowest point was in the 1950s (about 2% unemployment) and the highest point the 1930s (about 17 percent). Unemployment dropped during the first and second world wars, and increased after the oil shocks in the 1970s.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-33.jpg?height=1216&amp;width=2165&amp;top_left_y=332&amp;top_left_x=491" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-284 preview-line 284" id="recent-uk-unemployment-rate" data_line_start="284" data_line_end="284" data_line="284,285" count_line="1">
Recent UK unemployment rate</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-285 preview-line 285" id="graph%3A-unemployment-in-more-recent-british-history" data_line_start="285" data_line_end="285" data_line="285,286" count_line="1">
Graph: Unemployment in more recent British history</h3>
<div class="preview-paragraph-286 preview-line 286 287" data_line_start="286" data_line_end="287" data_line="286,288" count_line="2">The line graph shows unemployment between 1970 and 2022. It is ranged between 4 percent (in the early 1970s, and in 2018-2020) and 12 percent in 1983.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-34.jpg?height=745&amp;width=2086&amp;top_left_y=478&amp;top_left_x=607" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-289 preview-line 289" id="section-5%3A-inflation" data_line_start="289" data_line_end="289" data_line="289,290" count_line="1">
Section 5: Inflation</h2>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-291 preview-line 291" id="inflation-and-its-measurement" data_line_start="291" data_line_end="291" data_line="291,292" count_line="1">
Inflation and its measurement</h2>
<ul class="preview-paragraph-293 preview-line 293 294 295 296 297" data_line_start="293" data_line_end="297" data_line="293,298" count_line="5">
<li>Inflation is a general increase in prices of goods and services in an economy.</li>
<li>Note: relative price changes of particular goods are not inflation!</li>
<li>Inflation rate is the (annual) percentage change in a general price index, based on a basket of goods and services.</li>
<li>Equivalently the rate of decay in the value of money.</li>
</ul>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-298 preview-line 298" id="graph%3A-uk-inflation-rate" data_line_start="298" data_line_end="298" data_line="298,299" count_line="1">
Graph: UK inflation rate</h3>
<div class="preview-paragraph-299 preview-line 299 300" data_line_start="299" data_line_end="300" data_line="299,301" count_line="2">The line graph shows CPI inflation in percentage increase on year earlier from 1900 to 2008.<br>
Inflation was the highest during World war 1 (20 percent), world war 2 (15 percent) and the first oil shock (15 percent). A period of deflation occurred from 1924 (minus 16 percent) to 1933 (minus 4 percent).</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-302 preview-line 302" id="recent-uk-inflation-up-to-2020" data_line_start="302" data_line_end="302" data_line="302,303" count_line="1">
Recent UK inflation up to 2020</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-303 preview-line 303" id="graph%3A-uk-inflation-rate-in-recent-years" data_line_start="303" data_line_end="303" data_line="303,304" count_line="1">
Graph: UK inflation rate in recent years</h3>
<div class="preview-paragraph-304 preview-line 304 305 306" data_line_start="304" data_line_end="306" data_line="304,307" count_line="3">The line graph shows inflation from 1995 to 2020.<br>
Inflation was the highest in 2008 and 2012 (5 percent) and the lowest in 2015 (around 0 percent)<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-38.jpg?height=1144&amp;width=2084&amp;top_left_y=398&amp;top_left_x=536" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-308 preview-line 308" id="recent-uk-inflation-up-to-nov-2023" data_line_start="308" data_line_end="308" data_line="308,309" count_line="1">
Recent UK inflation up to Nov 2023</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-309 preview-line 309" id="graph%3A-uk-inflation-rate-in-recent-years-2" data_line_start="309" data_line_end="309" data_line="309,310" count_line="1">
Graph: UK inflation rate in recent years</h3>
<div class="preview-paragraph-310 preview-line 310 311 312" data_line_start="310" data_line_end="312" data_line="310,313" count_line="3">The line graph shows inflation from 2013 to 2023.<br>
Inflation attained about 11 percent in 2022, after being close to 0 in 2021.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-39.jpg?height=1271&amp;width=2296&amp;top_left_y=368&amp;top_left_x=502" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-314 preview-line 314" id="indices%3A-a-primer" data_line_start="314" data_line_end="314" data_line="314,315" count_line="1">
Indices: a primer</h2>
<div class="preview-paragraph-316 preview-line 316 317 318" data_line_start="316" data_line_end="318" data_line="316,319" count_line="3"><span class="math-block "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mtext> Index </mtext>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mfrac>
    <msub>
      <mtext> Variable </mtext>
      <mrow>
        <mi>t</mi>
      </mrow>
    </msub>
    <msub>
      <mtext> Variable </mtext>
      <mrow>
        <mtext>Base </mtext>
      </mrow>
    </msub>
  </mfrac>
  <mo>&#xD7;</mo>
  <mn>100</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mtext> Index </mtext>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mfrac>
    <msub>
      <mtext> Variable </mtext>
      <mrow>
        <mi>t</mi>
      </mrow>
    </msub>
    <msub>
      <mtext> Variable </mtext>
      <mrow>
        <mtext>Base </mtext>
      </mrow>
    </msub>
  </mfrac>
  <mo>×</mo>
  <mn>100</mn>
</math></mathmlword><asciimath style="display: none;">" Index "_(t)=(" Variable "_(t))/(" Variable "_("Base "))xx100</asciimath><latex style="display: none">\text { Index }_{t}=\frac{\text { Variable }_{t}}{\text { Variable }_{\text {Base }}} \times 100</latex><mjx-container class="MathJax" jax="SVG" display="true" role="presentation" style="position: relative"><svg style="vertical-align: -1.909ex" xmlns="http://www.w3.org/2000/svg" width="30.809ex" height="5.009ex" role="img" focusable="false" viewBox="0 -1370 13617.8 2213.8" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="msub"><g data-mml-node="mtext"><path data-c="A0" d=""></path><path data-c="49" d="M328 0Q307 3 180 3T32 0H21V46H43Q92 46 106 49T126 60Q128 63 128 342Q128 620 126 623Q122 628 118 630T96 635T43 637H21V683H32Q53 680 180 680T328 683H339V637H317Q268 637 254 634T234 623Q232 620 232 342Q232 63 234 60Q238 55 242 53T264 48T317 46H339V0H328Z" transform="translate(250, 0)"></path><path data-c="6E" d="M41 46H55Q94 46 102 60V68Q102 77 102 91T102 122T103 161T103 203Q103 234 103 269T102 328V351Q99 370 88 376T43 385H25V408Q25 431 27 431L37 432Q47 433 65 434T102 436Q119 437 138 438T167 441T178 442H181V402Q181 364 182 364T187 369T199 384T218 402T247 421T285 437Q305 442 336 442Q450 438 463 329Q464 322 464 190V104Q464 66 466 59T477 49Q498 46 526 46H542V0H534L510 1Q487 2 460 2T422 3Q319 3 310 0H302V46H318Q379 46 379 62Q380 64 380 200Q379 335 378 343Q372 371 358 385T334 402T308 404Q263 404 229 370Q202 343 195 315T187 232V168V108Q187 78 188 68T191 55T200 49Q221 46 249 46H265V0H257L234 1Q210 2 183 2T145 3Q42 3 33 0H25V46H41Z" transform="translate(611, 0)"></path><path data-c="64" d="M376 495Q376 511 376 535T377 568Q377 613 367 624T316 637H298V660Q298 683 300 683L310 684Q320 685 339 686T376 688Q393 689 413 690T443 693T454 694H457V390Q457 84 458 81Q461 61 472 55T517 46H535V0Q533 0 459 -5T380 -11H373V44L365 37Q307 -11 235 -11Q158 -11 96 50T34 215Q34 315 97 378T244 442Q319 442 376 393V495ZM373 342Q328 405 260 405Q211 405 173 369Q146 341 139 305T131 211Q131 155 138 120T173 59Q203 26 251 26Q322 26 373 103V342Z" transform="translate(1167, 0)"></path><path data-c="65" d="M28 218Q28 273 48 318T98 391T163 433T229 448Q282 448 320 430T378 380T406 316T415 245Q415 238 408 231H126V216Q126 68 226 36Q246 30 270 30Q312 30 342 62Q359 79 369 104L379 128Q382 131 395 131H398Q415 131 415 121Q415 117 412 108Q393 53 349 21T250 -11Q155 -11 92 58T28 218ZM333 275Q322 403 238 411H236Q228 411 220 410T195 402T166 381T143 340T127 274V267H333V275Z" transform="translate(1723, 0)"></path><path data-c="78" d="M201 0Q189 3 102 3Q26 3 17 0H11V46H25Q48 47 67 52T96 61T121 78T139 96T160 122T180 150L226 210L168 288Q159 301 149 315T133 336T122 351T113 363T107 370T100 376T94 379T88 381T80 383Q74 383 44 385H16V431H23Q59 429 126 429Q219 429 229 431H237V385Q201 381 201 369Q201 367 211 353T239 315T268 274L272 270L297 304Q329 345 329 358Q329 364 327 369T322 376T317 380T310 384L307 385H302V431H309Q324 428 408 428Q487 428 493 431H499V385H492Q443 385 411 368Q394 360 377 341T312 257L296 236L358 151Q424 61 429 57T446 50Q464 46 499 46H516V0H510H502Q494 1 482 1T457 2T432 2T414 3Q403 3 377 3T327 1L304 0H295V46H298Q309 46 320 51T331 63Q331 65 291 120L250 175Q249 174 219 133T185 88Q181 83 181 74Q181 63 188 55T206 46Q208 46 208 23V0H201Z" transform="translate(2167, 0)"></path><path data-c="A0" d="" transform="translate(2695, 0)"></path></g><g data-mml-node="TeXAtom" transform="translate(2945, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(3528, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mfrac" transform="translate(4583.8, 0)"><g data-mml-node="msub" transform="translate(904.1, 676)"><g data-mml-node="mtext"><path data-c="A0" d=""></path><path data-c="56" d="M114 620Q113 621 110 624T107 627T103 630T98 632T91 634T80 635T67 636T48 637H19V683H28Q46 680 152 680Q273 680 294 683H305V637H284Q223 634 223 620Q223 618 313 372T404 126L490 358Q575 588 575 597Q575 616 554 626T508 637H503V683H512Q527 680 627 680Q718 680 724 683H730V637H723Q648 637 627 596Q627 595 515 291T401 -14Q396 -22 382 -22H374H367Q353 -22 348 -14Q346 -12 231 303Q114 617 114 620Z" transform="translate(250, 0)"></path><path data-c="61" d="M137 305T115 305T78 320T63 359Q63 394 97 421T218 448Q291 448 336 416T396 340Q401 326 401 309T402 194V124Q402 76 407 58T428 40Q443 40 448 56T453 109V145H493V106Q492 66 490 59Q481 29 455 12T400 -6T353 12T329 54V58L327 55Q325 52 322 49T314 40T302 29T287 17T269 6T247 -2T221 -8T190 -11Q130 -11 82 20T34 107Q34 128 41 147T68 188T116 225T194 253T304 268H318V290Q318 324 312 340Q290 411 215 411Q197 411 181 410T156 406T148 403Q170 388 170 359Q170 334 154 320ZM126 106Q126 75 150 51T209 26Q247 26 276 49T315 109Q317 116 318 175Q318 233 317 233Q309 233 296 232T251 223T193 203T147 166T126 106Z" transform="translate(1000, 0)"></path><path data-c="72" d="M36 46H50Q89 46 97 60V68Q97 77 97 91T98 122T98 161T98 203Q98 234 98 269T98 328L97 351Q94 370 83 376T38 385H20V408Q20 431 22 431L32 432Q42 433 60 434T96 436Q112 437 131 438T160 441T171 442H174V373Q213 441 271 441H277Q322 441 343 419T364 373Q364 352 351 337T313 322Q288 322 276 338T263 372Q263 381 265 388T270 400T273 405Q271 407 250 401Q234 393 226 386Q179 341 179 207V154Q179 141 179 127T179 101T180 81T180 66V61Q181 59 183 57T188 54T193 51T200 49T207 48T216 47T225 47T235 46T245 46H276V0H267Q249 3 140 3Q37 3 28 0H20V46H36Z" transform="translate(1500, 0)"></path><path data-c="69" d="M69 609Q69 637 87 653T131 669Q154 667 171 652T188 609Q188 579 171 564T129 549Q104 549 87 564T69 609ZM247 0Q232 3 143 3Q132 3 106 3T56 1L34 0H26V46H42Q70 46 91 49Q100 53 102 60T104 102V205V293Q104 345 102 359T88 378Q74 385 41 385H30V408Q30 431 32 431L42 432Q52 433 70 434T106 436Q123 437 142 438T171 441T182 442H185V62Q190 52 197 50T232 46H255V0H247Z" transform="translate(1892, 0)"></path><path data-c="61" d="M137 305T115 305T78 320T63 359Q63 394 97 421T218 448Q291 448 336 416T396 340Q401 326 401 309T402 194V124Q402 76 407 58T428 40Q443 40 448 56T453 109V145H493V106Q492 66 490 59Q481 29 455 12T400 -6T353 12T329 54V58L327 55Q325 52 322 49T314 40T302 29T287 17T269 6T247 -2T221 -8T190 -11Q130 -11 82 20T34 107Q34 128 41 147T68 188T116 225T194 253T304 268H318V290Q318 324 312 340Q290 411 215 411Q197 411 181 410T156 406T148 403Q170 388 170 359Q170 334 154 320ZM126 106Q126 75 150 51T209 26Q247 26 276 49T315 109Q317 116 318 175Q318 233 317 233Q309 233 296 232T251 223T193 203T147 166T126 106Z" transform="translate(2170, 0)"></path><path data-c="62" d="M307 -11Q234 -11 168 55L158 37Q156 34 153 28T147 17T143 10L138 1L118 0H98V298Q98 599 97 603Q94 622 83 628T38 637H20V660Q20 683 22 683L32 684Q42 685 61 686T98 688Q115 689 135 690T165 693T176 694H179V543Q179 391 180 391L183 394Q186 397 192 401T207 411T228 421T254 431T286 439T323 442Q401 442 461 379T522 216Q522 115 458 52T307 -11ZM182 98Q182 97 187 90T196 79T206 67T218 55T233 44T250 35T271 29T295 26Q330 26 363 46T412 113Q424 148 424 212Q424 287 412 323Q385 405 300 405Q270 405 239 390T188 347L182 339V98Z" transform="translate(2670, 0)"></path><path data-c="6C" d="M42 46H56Q95 46 103 60V68Q103 77 103 91T103 124T104 167T104 217T104 272T104 329Q104 366 104 407T104 482T104 542T103 586T103 603Q100 622 89 628T44 637H26V660Q26 683 28 683L38 684Q48 685 67 686T104 688Q121 689 141 690T171 693T182 694H185V379Q185 62 186 60Q190 52 198 49Q219 46 247 46H263V0H255L232 1Q209 2 183 2T145 3T107 3T57 1L34 0H26V46H42Z" transform="translate(3226, 0)"></path><path data-c="65" d="M28 218Q28 273 48 318T98 391T163 433T229 448Q282 448 320 430T378 380T406 316T415 245Q415 238 408 231H126V216Q126 68 226 36Q246 30 270 30Q312 30 342 62Q359 79 369 104L379 128Q382 131 395 131H398Q415 131 415 121Q415 117 412 108Q393 53 349 21T250 -11Q155 -11 92 58T28 218ZM333 275Q322 403 238 411H236Q228 411 220 410T195 402T166 381T143 340T127 274V267H333V275Z" transform="translate(3504, 0)"></path><path data-c="A0" d="" transform="translate(3948, 0)"></path></g><g data-mml-node="TeXAtom" transform="translate(4198, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="msub" transform="translate(220, -686)"><g data-mml-node="mtext"><path data-c="A0" d=""></path><path data-c="56" d="M114 620Q113 621 110 624T107 627T103 630T98 632T91 634T80 635T67 636T48 637H19V683H28Q46 680 152 680Q273 680 294 683H305V637H284Q223 634 223 620Q223 618 313 372T404 126L490 358Q575 588 575 597Q575 616 554 626T508 637H503V683H512Q527 680 627 680Q718 680 724 683H730V637H723Q648 637 627 596Q627 595 515 291T401 -14Q396 -22 382 -22H374H367Q353 -22 348 -14Q346 -12 231 303Q114 617 114 620Z" transform="translate(250, 0)"></path><path data-c="61" d="M137 305T115 305T78 320T63 359Q63 394 97 421T218 448Q291 448 336 416T396 340Q401 326 401 309T402 194V124Q402 76 407 58T428 40Q443 40 448 56T453 109V145H493V106Q492 66 490 59Q481 29 455 12T400 -6T353 12T329 54V58L327 55Q325 52 322 49T314 40T302 29T287 17T269 6T247 -2T221 -8T190 -11Q130 -11 82 20T34 107Q34 128 41 147T68 188T116 225T194 253T304 268H318V290Q318 324 312 340Q290 411 215 411Q197 411 181 410T156 406T148 403Q170 388 170 359Q170 334 154 320ZM126 106Q126 75 150 51T209 26Q247 26 276 49T315 109Q317 116 318 175Q318 233 317 233Q309 233 296 232T251 223T193 203T147 166T126 106Z" transform="translate(1000, 0)"></path><path data-c="72" d="M36 46H50Q89 46 97 60V68Q97 77 97 91T98 122T98 161T98 203Q98 234 98 269T98 328L97 351Q94 370 83 376T38 385H20V408Q20 431 22 431L32 432Q42 433 60 434T96 436Q112 437 131 438T160 441T171 442H174V373Q213 441 271 441H277Q322 441 343 419T364 373Q364 352 351 337T313 322Q288 322 276 338T263 372Q263 381 265 388T270 400T273 405Q271 407 250 401Q234 393 226 386Q179 341 179 207V154Q179 141 179 127T179 101T180 81T180 66V61Q181 59 183 57T188 54T193 51T200 49T207 48T216 47T225 47T235 46T245 46H276V0H267Q249 3 140 3Q37 3 28 0H20V46H36Z" transform="translate(1500, 0)"></path><path data-c="69" d="M69 609Q69 637 87 653T131 669Q154 667 171 652T188 609Q188 579 171 564T129 549Q104 549 87 564T69 609ZM247 0Q232 3 143 3Q132 3 106 3T56 1L34 0H26V46H42Q70 46 91 49Q100 53 102 60T104 102V205V293Q104 345 102 359T88 378Q74 385 41 385H30V408Q30 431 32 431L42 432Q52 433 70 434T106 436Q123 437 142 438T171 441T182 442H185V62Q190 52 197 50T232 46H255V0H247Z" transform="translate(1892, 0)"></path><path data-c="61" d="M137 305T115 305T78 320T63 359Q63 394 97 421T218 448Q291 448 336 416T396 340Q401 326 401 309T402 194V124Q402 76 407 58T428 40Q443 40 448 56T453 109V145H493V106Q492 66 490 59Q481 29 455 12T400 -6T353 12T329 54V58L327 55Q325 52 322 49T314 40T302 29T287 17T269 6T247 -2T221 -8T190 -11Q130 -11 82 20T34 107Q34 128 41 147T68 188T116 225T194 253T304 268H318V290Q318 324 312 340Q290 411 215 411Q197 411 181 410T156 406T148 403Q170 388 170 359Q170 334 154 320ZM126 106Q126 75 150 51T209 26Q247 26 276 49T315 109Q317 116 318 175Q318 233 317 233Q309 233 296 232T251 223T193 203T147 166T126 106Z" transform="translate(2170, 0)"></path><path data-c="62" d="M307 -11Q234 -11 168 55L158 37Q156 34 153 28T147 17T143 10L138 1L118 0H98V298Q98 599 97 603Q94 622 83 628T38 637H20V660Q20 683 22 683L32 684Q42 685 61 686T98 688Q115 689 135 690T165 693T176 694H179V543Q179 391 180 391L183 394Q186 397 192 401T207 411T228 421T254 431T286 439T323 442Q401 442 461 379T522 216Q522 115 458 52T307 -11ZM182 98Q182 97 187 90T196 79T206 67T218 55T233 44T250 35T271 29T295 26Q330 26 363 46T412 113Q424 148 424 212Q424 287 412 323Q385 405 300 405Q270 405 239 390T188 347L182 339V98Z" transform="translate(2670, 0)"></path><path data-c="6C" d="M42 46H56Q95 46 103 60V68Q103 77 103 91T103 124T104 167T104 217T104 272T104 329Q104 366 104 407T104 482T104 542T103 586T103 603Q100 622 89 628T44 637H26V660Q26 683 28 683L38 684Q48 685 67 686T104 688Q121 689 141 690T171 693T182 694H185V379Q185 62 186 60Q190 52 198 49Q219 46 247 46H263V0H255L232 1Q209 2 183 2T145 3T107 3T57 1L34 0H26V46H42Z" transform="translate(3226, 0)"></path><path data-c="65" d="M28 218Q28 273 48 318T98 391T163 433T229 448Q282 448 320 430T378 380T406 316T415 245Q415 238 408 231H126V216Q126 68 226 36Q246 30 270 30Q312 30 342 62Q359 79 369 104L379 128Q382 131 395 131H398Q415 131 415 121Q415 117 412 108Q393 53 349 21T250 -11Q155 -11 92 58T28 218ZM333 275Q322 403 238 411H236Q228 411 220 410T195 402T166 381T143 340T127 274V267H333V275Z" transform="translate(3504, 0)"></path><path data-c="A0" d="" transform="translate(3948, 0)"></path></g><g data-mml-node="TeXAtom" transform="translate(4198, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mtext"><path data-c="42" d="M131 622Q124 629 120 631T104 634T61 637H28V683H229H267H346Q423 683 459 678T531 651Q574 627 599 590T624 512Q624 461 583 419T476 360L466 357Q539 348 595 302T651 187Q651 119 600 67T469 3Q456 1 242 0H28V46H61Q103 47 112 49T131 61V622ZM511 513Q511 560 485 594T416 636Q415 636 403 636T371 636T333 637Q266 637 251 636T232 628Q229 624 229 499V374H312L396 375L406 377Q410 378 417 380T442 393T474 417T499 456T511 513ZM537 188Q537 239 509 282T430 336L329 337H229V200V116Q229 57 234 52Q240 47 334 47H383Q425 47 443 53Q486 67 511 104T537 188Z"></path><path data-c="61" d="M137 305T115 305T78 320T63 359Q63 394 97 421T218 448Q291 448 336 416T396 340Q401 326 401 309T402 194V124Q402 76 407 58T428 40Q443 40 448 56T453 109V145H493V106Q492 66 490 59Q481 29 455 12T400 -6T353 12T329 54V58L327 55Q325 52 322 49T314 40T302 29T287 17T269 6T247 -2T221 -8T190 -11Q130 -11 82 20T34 107Q34 128 41 147T68 188T116 225T194 253T304 268H318V290Q318 324 312 340Q290 411 215 411Q197 411 181 410T156 406T148 403Q170 388 170 359Q170 334 154 320ZM126 106Q126 75 150 51T209 26Q247 26 276 49T315 109Q317 116 318 175Q318 233 317 233Q309 233 296 232T251 223T193 203T147 166T126 106Z" transform="translate(708, 0)"></path><path data-c="73" d="M295 316Q295 356 268 385T190 414Q154 414 128 401Q98 382 98 349Q97 344 98 336T114 312T157 287Q175 282 201 278T245 269T277 256Q294 248 310 236T342 195T359 133Q359 71 321 31T198 -10H190Q138 -10 94 26L86 19L77 10Q71 4 65 -1L54 -11H46H42Q39 -11 33 -5V74V132Q33 153 35 157T45 162H54Q66 162 70 158T75 146T82 119T101 77Q136 26 198 26Q295 26 295 104Q295 133 277 151Q257 175 194 187T111 210Q75 227 54 256T33 318Q33 357 50 384T93 424T143 442T187 447H198Q238 447 268 432L283 424L292 431Q302 440 314 448H322H326Q329 448 335 442V310L329 304H301Q295 310 295 316Z" transform="translate(1208, 0)"></path><path data-c="65" d="M28 218Q28 273 48 318T98 391T163 433T229 448Q282 448 320 430T378 380T406 316T415 245Q415 238 408 231H126V216Q126 68 226 36Q246 30 270 30Q312 30 342 62Q359 79 369 104L379 128Q382 131 395 131H398Q415 131 415 121Q415 117 412 108Q393 53 349 21T250 -11Q155 -11 92 58T28 218ZM333 275Q322 403 238 411H236Q228 411 220 410T195 402T166 381T143 340T127 274V267H333V275Z" transform="translate(1602, 0)"></path><path data-c="A0" d="" transform="translate(2046, 0)"></path></g></g></g><rect width="6071.5" height="60" x="120" y="220"></rect></g><g data-mml-node="mo" transform="translate(11117.6, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="mn" transform="translate(12117.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="block"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mtext> Index </mtext><mrow><mi>t</mi></mrow></msub><mo>=</mo><mfrac><msub><mtext> Variable </mtext><mrow><mi>t</mi></mrow></msub><msub><mtext> Variable </mtext><mrow><mtext>Base </mtext></mrow></msub></mfrac><mo>×</mo><mn>100</mn></math></mjx-assistive-mml></mjx-container></span></div>
<div class="preview-paragraph-320 preview-line 320" data_line_start="320" data_line_end="320" data_line="320,321" count_line="1">Level only for time-series comparisons.</div>
<div class="preview-paragraph-322 preview-line 322" data_line_start="322" data_line_end="322" data_line="322,323" count_line="1">Example:</div>
<div class="table_tabular  preview-paragraph-324 preview-line 324 325 326 327 328 329 330 331" style="text-align: center" data_line_start="324" data_line_end="331" data_line="324,332" count_line="8">
<div class="inline-tabular"><table id="tabular">
<tbody>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; " class="_empty"></td>
<td style="text-align: center; border-left: none !important; border-bottom: none !important; border-top: none !important; border-top: none !important; border-bottom: none !important; " colspan="1">2010</td>
<td style="text-align: center; border-left: none !important; border-bottom: none !important; border-top: none !important; border-top: none !important; border-bottom: none !important; " colspan="1">2011</td>
<td style="text-align: center; border-left: none !important; border-bottom: none !important; border-top: none !important; border-top: none !important; border-bottom: none !important; " colspan="1">2012</td>
<td style="text-align: center; border-left: none !important; border-bottom: none !important; border-top: none !important; border-top: none !important; border-bottom: none !important; " colspan="1">2013</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">Level</td>
<td style="text-align: center; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">2603.9</td>
<td style="text-align: right; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">2709.3</td>
<td style="text-align: right; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">2832.8</td>
<td style="text-align: right; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">2954.0</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">% Change</td>
<td style="text-align: center; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; " class="_empty"></td>
<td style="text-align: right; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; "><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.05</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.05</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">4.05%</asciimath><latex style="display: none">4.05 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(778, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>4.05</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></td>
<td style="text-align: right; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; "><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.56</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.56</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">4.56%</asciimath><latex style="display: none">4.56 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(778, 0)"></path><path data-c="36" d="M42 313Q42 476 123 571T303 666Q372 666 402 630T432 550Q432 525 418 510T379 495Q356 495 341 509T326 548Q326 592 373 601Q351 623 311 626Q240 626 194 566Q147 500 147 364L148 360Q153 366 156 373Q197 433 263 433H267Q313 433 348 414Q372 400 396 374T435 317Q456 268 456 210V192Q456 169 451 149Q440 90 387 34T253 -22Q225 -22 199 -14T143 16T92 75T56 172T42 313ZM257 397Q227 397 205 380T171 335T154 278T148 216Q148 133 160 97T198 39Q222 21 251 21Q302 21 329 59Q342 77 347 104T352 209Q352 289 347 316T329 361Q302 397 257 397Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>4.56</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></td>
<td style="text-align: right; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; "><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.28</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.28</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">4.28%</asciimath><latex style="display: none">4.28 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z" transform="translate(778, 0)"></path><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>4.28</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">Index 2011=100</td>
<td style="text-align: center; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">96.11</td>
<td style="text-align: right; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">100.00</td>
<td style="text-align: right; border-right: none !important; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">104.56</td>
<td style="text-align: right; border-bottom: none !important; border-top: none !important; width: auto; vertical-align: middle; ">109.03</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right: none !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">% Change</td>
<td style="text-align: center; border-right: none !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; " class="_empty"></td>
<td style="text-align: right; border-right: none !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; "><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.05</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.05</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">4.05%</asciimath><latex style="display: none">4.05 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z" transform="translate(778, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>4.05</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></td>
<td style="text-align: right; border-right: none !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; "><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.56</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.56</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">4.56%</asciimath><latex style="display: none">4.56 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(778, 0)"></path><path data-c="36" d="M42 313Q42 476 123 571T303 666Q372 666 402 630T432 550Q432 525 418 510T379 495Q356 495 341 509T326 548Q326 592 373 601Q351 623 311 626Q240 626 194 566Q147 500 147 364L148 360Q153 366 156 373Q197 433 263 433H267Q313 433 348 414Q372 400 396 374T435 317Q456 268 456 210V192Q456 169 451 149Q440 90 387 34T253 -22Q225 -22 199 -14T143 16T92 75T56 172T42 313ZM257 397Q227 397 205 380T171 335T154 278T148 216Q148 133 160 97T198 39Q222 21 251 21Q302 21 329 59Q342 77 347 104T352 209Q352 289 347 316T329 361Q302 397 257 397Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>4.56</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></td>
<td style="text-align: right; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; "><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.28</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>4.28</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">4.28%</asciimath><latex style="display: none">4.28 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="5.907ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2611 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="34" d="M462 0Q444 3 333 3Q217 3 199 0H190V46H221Q241 46 248 46T265 48T279 53T286 61Q287 63 287 115V165H28V211L179 442Q332 674 334 675Q336 677 355 677H373L379 671V211H471V165H379V114Q379 73 379 66T385 54Q393 47 442 46H471V0H462ZM293 211V545L74 212L183 211H293Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z" transform="translate(778, 0)"></path><path data-c="38" d="M70 417T70 494T124 618T248 666Q319 666 374 624T429 515Q429 485 418 459T392 417T361 389T335 371T324 363L338 354Q352 344 366 334T382 323Q457 264 457 174Q457 95 399 37T249 -22Q159 -22 101 29T43 155Q43 263 172 335L154 348Q133 361 127 368Q70 417 70 494ZM286 386L292 390Q298 394 301 396T311 403T323 413T334 425T345 438T355 454T364 471T369 491T371 513Q371 556 342 586T275 624Q268 625 242 625Q201 625 165 599T128 534Q128 511 141 492T167 463T217 431Q224 426 228 424L286 386ZM250 21Q308 21 350 55T392 137Q392 154 387 169T375 194T353 216T330 234T301 253T274 270Q260 279 244 289T218 306L210 311Q204 311 181 294T133 239T107 157Q107 98 150 60T250 21Z" transform="translate(1278, 0)"></path></g><g data-mml-node="mi" transform="translate(1778, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>4.28</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span></td>
</tr>
</tbody>
</table>
<tsv style="display: none">	2010	2011	2012	2013
Level	2603.9	2709.3	2832.8	2954.0
% Change		4.05%	4.56%	4.28%
Index 2011=100	96.11	100.00	104.56	109.03
% Change		4.05%	4.56%	4.28%</tsv><table-markdown style="display: none">|  | 2010 | 2011 | 2012 | 2013 |
| :--- | :---: | ---: | ---: | ---: |
| Level | 2603.9 | 2709.3 | 2832.8 | 2954.0 |
| % Change |  | $4.05 \%$ | $4.56 \%$ | $4.28 \%$ |
| Index 2011=100 | 96.11 | 100.00 | 104.56 | 109.03 |
| % Change |  | $4.05 \%$ | $4.56 \%$ | $4.28 \%$ |</table-markdown></div></div>
<div class="preview-paragraph-333 preview-line 333" data_line_start="333" data_line_end="333" data_line="333,334" count_line="1">Used for CPI, real GDP and others.</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-335 preview-line 335" id="consumer-price-index-(cpi)-inflation" data_line_start="335" data_line_end="335" data_line="335,336" count_line="1">
Consumer Price Index (CPI) Inflation</h2>
<div class="preview-paragraph-337 preview-line 337" data_line_start="337" data_line_end="337" data_line="337,338" count_line="1">CPI is based on a weighted average of prices of goods and services that appear in an average consumer's basket of purchase.</div>
<div class="preview-paragraph-339 preview-line 339" data_line_start="339" data_line_end="339" data_line="339,340" count_line="1">Laspeyres index (base-weighted index) uses historical quantities as weights:</div>
<div class="preview-paragraph-341 preview-line 341" data_line_start="341" data_line_end="341" data_line="341,342" count_line="1">CPI (Base <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>0</mn>
  <msub>
    <mo stretchy="false">)</mo>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <mo>&#x22EF;</mo>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
    <mrow>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <mo>&#x22EF;</mo>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
  </mfrac>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <munderover>
        <mo data-mjx-texclass="OP">&#x2211;</mo>
        <mrow>
          <mi>i</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mrow>
          <mi>N</mi>
        </mrow>
      </munderover>
      <msub>
        <mi>P</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
    <mrow>
      <munderover>
        <mo data-mjx-texclass="OP">&#x2211;</mo>
        <mrow>
          <mi>i</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mrow>
          <mi>N</mi>
        </mrow>
      </munderover>
      <msub>
        <mi>P</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>&#xD7;</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
  </mfrac>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo>=</mo>
  <mn>0</mn>
  <msub>
    <mo stretchy="false">)</mo>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <mo>⋯</mo>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
    <mrow>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>1</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mn>2</mn>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>+</mo>
      <mo>⋯</mo>
      <mo>+</mo>
      <msub>
        <mi>P</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mrow>
            <mi mathvariant="normal">N</mi>
          </mrow>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
  </mfrac>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <munderover>
        <mrow>
          <mo data-mjx-texclass="OP">∑</mo>
        </mrow>
        <mrow>
          <mi>i</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mrow>
          <mi>N</mi>
        </mrow>
      </munderover>
      <mrow>
        <mo> </mo>
      </mrow>
      <msub>
        <mi>P</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mi>t</mi>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
    <mrow>
      <munderover>
        <mrow>
          <mo data-mjx-texclass="OP">∑</mo>
        </mrow>
        <mrow>
          <mi>i</mi>
          <mo>=</mo>
          <mn>1</mn>
        </mrow>
        <mrow>
          <mi>N</mi>
        </mrow>
      </munderover>
      <mrow>
        <mo> </mo>
      </mrow>
      <msub>
        <mi>P</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
      <mo>×</mo>
      <msub>
        <mi>q</mi>
        <mrow>
          <mi>i</mi>
          <mo>,</mo>
          <mn>0</mn>
        </mrow>
      </msub>
    </mrow>
  </mfrac>
</math></mathmlword><asciimath style="display: none;">=0)_(t)=(P_(1,t)xxq_(1,0)+P_(2,t)xxq_(2,0)+cdots+P_(N,t)xxq_(N,0))/(P_(1,0)xxq_(1,0)+P_(2,0)xxq_(2,0)+cdots+P_(N,0)xxq_(N,0))=(sum_(i=1)^(N)P_(i,t)xxq_(i,0))/(sum_(i=1)^(N)P_(i,0)xxq_(i,0))</asciimath><latex style="display: none">=0)_{t}=\frac{P_{1, t} \times q_{1,0}+P_{2, t} \times q_{2,0}+\cdots+P_{\mathrm{N}, t} \times q_{\mathrm{N}, 0}}{P_{1,0} \times q_{1,0}+P_{2,0} \times q_{2,0}+\cdots+P_{\mathrm{N}, 0} \times q_{\mathrm{N}, 0}}=\frac{\sum_{i=1}^{N} P_{i, t} \times q_{i, 0}}{\sum_{i=1}^{N} P_{i, 0} \times q_{i, 0}}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -1.723ex" xmlns="http://www.w3.org/2000/svg" width="46.958ex" height="4.577ex" role="img" focusable="false" viewBox="0 -1261.6 20755.4 2023.2" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1055.8, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g><g data-mml-node="msub" transform="translate(1555.8, 0)"><g data-mml-node="mo"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g><g data-mml-node="TeXAtom" transform="translate(389, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(2527.8, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mfrac" transform="translate(3583.6, 0)"><g data-mml-node="mrow" transform="translate(324.2, 543.1) scale(0.707)"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(778, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(1497.4, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(2275.4, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(3675.1, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="msub" transform="translate(4453.1, 0)"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(778, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(5950.5, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(6728.5, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(8128.2, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mo" transform="translate(8906.2, 0)"><path data-c="22EF" d="M78 250Q78 274 95 292T138 310Q162 310 180 294T199 251Q199 226 182 208T139 190T96 207T78 250ZM525 250Q525 274 542 292T585 310Q609 310 627 294T646 251Q646 226 629 208T586 190T543 207T525 250ZM972 250Q972 274 989 292T1032 310Q1056 310 1074 294T1093 251Q1093 226 1076 208T1033 190T990 207T972 250Z"></path></g><g data-mml-node="mo" transform="translate(10078.2, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="msub" transform="translate(10856.2, 0)"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="4E" d="M42 46Q74 48 94 56T118 69T128 86V634H124Q114 637 52 637H25V683H232L235 680Q237 679 322 554T493 303L578 178V598Q572 608 568 613T544 627T492 637H475V683H483Q498 680 600 680Q706 680 715 683H724V637H707Q634 633 622 598L621 302V6L614 0H600Q585 0 582 3T481 150T282 443T171 605V345L172 86Q183 50 257 46H274V0H265Q250 3 150 3Q48 3 33 0H25V46H42Z"></path></g></g><g data-mml-node="mo" transform="translate(750, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(1028, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(12530.3, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(13308.3, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="4E" d="M42 46Q74 48 94 56T118 69T128 86V634H124Q114 637 52 637H25V683H232L235 680Q237 679 322 554T493 303L578 178V598Q572 608 568 613T544 627T492 637H475V683H483Q498 680 600 680Q706 680 715 683H724V637H707Q634 633 622 598L621 302V6L614 0H600Q585 0 582 3T481 150T282 443T171 605V345L172 86Q183 50 257 46H274V0H265Q250 3 150 3Q48 3 33 0H25V46H42Z"></path></g></g><g data-mml-node="mo" transform="translate(750, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(1028, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g></g><g data-mml-node="mrow" transform="translate(220, -345) scale(0.707)"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(1595.7, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(2373.7, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(3773.4, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="msub" transform="translate(4551.4, 0)"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(6147, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(6925, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(778, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(8324.7, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="mo" transform="translate(9102.7, 0)"><path data-c="22EF" d="M78 250Q78 274 95 292T138 310Q162 310 180 294T199 251Q199 226 182 208T139 190T96 207T78 250ZM525 250Q525 274 542 292T585 310Q609 310 627 294T646 251Q646 226 629 208T586 190T543 207T525 250ZM972 250Q972 274 989 292T1032 310Q1056 310 1074 294T1093 251Q1093 226 1076 208T1033 190T990 207T972 250Z"></path></g><g data-mml-node="mo" transform="translate(10274.7, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="msub" transform="translate(11052.7, 0)"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="4E" d="M42 46Q74 48 94 56T118 69T128 86V634H124Q114 637 52 637H25V683H232L235 680Q237 679 322 554T493 303L578 178V598Q572 608 568 613T544 627T492 637H475V683H483Q498 680 600 680Q706 680 715 683H724V637H707Q634 633 622 598L621 302V6L614 0H600Q585 0 582 3T481 150T282 443T171 605V345L172 86Q183 50 257 46H274V0H265Q250 3 150 3Q48 3 33 0H25V46H42Z"></path></g></g><g data-mml-node="mo" transform="translate(750, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(1028, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(12825.2, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(13603.2, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="4E" d="M42 46Q74 48 94 56T118 69T128 86V634H124Q114 637 52 637H25V683H232L235 680Q237 679 322 554T493 303L578 178V598Q572 608 568 613T544 627T492 637H475V683H483Q498 680 600 680Q706 680 715 683H724V637H707Q634 633 622 598L621 302V6L614 0H600Q585 0 582 3T481 150T282 443T171 605V345L172 86Q183 50 257 46H274V0H265Q250 3 150 3Q48 3 33 0H25V46H42Z"></path></g></g><g data-mml-node="mo" transform="translate(750, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(1028, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g></g><rect width="10933.6" height="60" x="120" y="220"></rect></g><g data-mml-node="mo" transform="translate(15035, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mfrac" transform="translate(16090.8, 0)"><g data-mml-node="mrow" transform="translate(254.7, 582.8) scale(0.707)"><g data-mml-node="munderover"><g data-mml-node="mo"><path data-c="2211" d="M61 748Q64 750 489 750H913L954 640Q965 609 976 579T993 533T999 516H979L959 517Q936 579 886 621T777 682Q724 700 655 705T436 710H319Q183 710 183 709Q186 706 348 484T511 259Q517 250 513 244L490 216Q466 188 420 134T330 27L149 -187Q149 -188 362 -188Q388 -188 436 -188T506 -189Q679 -189 778 -162T936 -43Q946 -27 959 6H999L913 -249L489 -250Q65 -250 62 -248Q56 -246 56 -239Q56 -234 118 -161Q186 -81 245 -11L428 206Q428 207 242 462L57 717L56 728Q56 744 61 748Z"></path></g><g data-mml-node="TeXAtom" transform="translate(1056, 477.1) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path></g></g><g data-mml-node="TeXAtom" transform="translate(1056, -285.4) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1123, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g></g></g><g data-mml-node="msub" transform="translate(2420.3, 0)"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(623, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(3808.1, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(4586.1, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(623, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g></g><g data-mml-node="mrow" transform="translate(220, -518.8) scale(0.707)"><g data-mml-node="munderover"><g data-mml-node="mo"><path data-c="2211" d="M61 748Q64 750 489 750H913L954 640Q965 609 976 579T993 533T999 516H979L959 517Q936 579 886 621T777 682Q724 700 655 705T436 710H319Q183 710 183 709Q186 706 348 484T511 259Q517 250 513 244L490 216Q466 188 420 134T330 27L149 -187Q149 -188 362 -188Q388 -188 436 -188T506 -189Q679 -189 778 -162T936 -43Q946 -27 959 6H999L913 -249L489 -250Q65 -250 62 -248Q56 -246 56 -239Q56 -234 118 -161Q186 -81 245 -11L428 206Q428 207 242 462L57 717L56 728Q56 744 61 748Z"></path></g><g data-mml-node="TeXAtom" transform="translate(1056, 477.1) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="4E" d="M234 637Q231 637 226 637Q201 637 196 638T191 649Q191 676 202 682Q204 683 299 683Q376 683 387 683T401 677Q612 181 616 168L670 381Q723 592 723 606Q723 633 659 637Q635 637 635 648Q635 650 637 660Q641 676 643 679T653 683Q656 683 684 682T767 680Q817 680 843 681T873 682Q888 682 888 672Q888 650 880 642Q878 637 858 637Q787 633 769 597L620 7Q618 0 599 0Q585 0 582 2Q579 5 453 305L326 604L261 344Q196 88 196 79Q201 46 268 46H278Q284 41 284 38T282 19Q278 6 272 0H259Q228 2 151 2Q123 2 100 2T63 2T46 1Q31 1 31 10Q31 14 34 26T39 40Q41 46 62 46Q130 49 150 85Q154 91 221 362L289 634Q287 635 234 637Z"></path></g></g><g data-mml-node="TeXAtom" transform="translate(1056, -285.4) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mn" transform="translate(1123, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g></g></g><g data-mml-node="msub" transform="translate(2420.3, 0)"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(623, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g><g data-mml-node="mo" transform="translate(3906.4, 0)"><path data-c="D7" d="M630 29Q630 9 609 9Q604 9 587 25T493 118L389 222L284 117Q178 13 175 11Q171 9 168 9Q160 9 154 15T147 29Q147 36 161 51T255 146L359 250L255 354Q174 435 161 449T147 471Q147 480 153 485T168 490Q173 490 175 489Q178 487 284 383L389 278L493 382Q570 459 587 475T609 491Q630 491 630 471Q630 464 620 453T522 355L418 250L522 145Q606 61 618 48T630 29Z"></path></g><g data-mml-node="msub" transform="translate(4684.4, 0)"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(623, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g></g><rect width="4424.6" height="60" x="120" y="220"></rect></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo>=</mo><mn>0</mn><msub><mo stretchy="false">)</mo><mrow><mi>t</mi></mrow></msub><mo>=</mo><mfrac><mrow><msub><mi>P</mi><mrow><mn>1</mn><mo>,</mo><mi>t</mi></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mn>1</mn><mo>,</mo><mn>0</mn></mrow></msub><mo>+</mo><msub><mi>P</mi><mrow><mn>2</mn><mo>,</mo><mi>t</mi></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mn>2</mn><mo>,</mo><mn>0</mn></mrow></msub><mo>+</mo><mo>⋯</mo><mo>+</mo><msub><mi>P</mi><mrow><mrow><mi mathvariant="normal">N</mi></mrow><mo>,</mo><mi>t</mi></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mrow><mi mathvariant="normal">N</mi></mrow><mo>,</mo><mn>0</mn></mrow></msub></mrow><mrow><msub><mi>P</mi><mrow><mn>1</mn><mo>,</mo><mn>0</mn></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mn>1</mn><mo>,</mo><mn>0</mn></mrow></msub><mo>+</mo><msub><mi>P</mi><mrow><mn>2</mn><mo>,</mo><mn>0</mn></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mn>2</mn><mo>,</mo><mn>0</mn></mrow></msub><mo>+</mo><mo>⋯</mo><mo>+</mo><msub><mi>P</mi><mrow><mrow><mi mathvariant="normal">N</mi></mrow><mo>,</mo><mn>0</mn></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mrow><mi mathvariant="normal">N</mi></mrow><mo>,</mo><mn>0</mn></mrow></msub></mrow></mfrac><mo>=</mo><mfrac><mrow><munderover><mo data-mjx-texclass="OP">∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mrow><mi>N</mi></mrow></munderover><msub><mi>P</mi><mrow><mi>i</mi><mo>,</mo><mi>t</mi></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mi>i</mi><mo>,</mo><mn>0</mn></mrow></msub></mrow><mrow><munderover><mo data-mjx-texclass="OP">∑</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mrow><mi>N</mi></mrow></munderover><msub><mi>P</mi><mrow><mi>i</mi><mo>,</mo><mn>0</mn></mrow></msub><mo>×</mo><msub><mi>q</mi><mrow><mi>i</mi><mo>,</mo><mn>0</mn></mrow></msub></mrow></mfrac></math></mjx-assistive-mml></mjx-container></span></div>
<ul class="preview-paragraph-342 preview-line 342 343 344 345" data_line_start="342" data_line_end="345" data_line="342,346" count_line="4">
<li><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>q</mi>
    <mrow>
      <mi>i</mi>
      <mo>,</mo>
      <mn>0</mn>
    </mrow>
  </msub>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>q</mi>
    <mrow>
      <mi>i</mi>
      <mo>,</mo>
      <mn>0</mn>
    </mrow>
  </msub>
</math></mathmlword><asciimath style="display: none;">q_(i,0)</asciimath><latex style="display: none">q_{i, 0}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.65ex" xmlns="http://www.w3.org/2000/svg" width="2.919ex" height="1.65ex" role="img" focusable="false" viewBox="0 -442 1290.1 729.2" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="71" d="M33 157Q33 258 109 349T280 441Q340 441 372 389Q373 390 377 395T388 406T404 418Q438 442 450 442Q454 442 457 439T460 434Q460 425 391 149Q320 -135 320 -139Q320 -147 365 -148H390Q396 -156 396 -157T393 -175Q389 -188 383 -194H370Q339 -192 262 -192Q234 -192 211 -192T174 -192T157 -193Q143 -193 143 -185Q143 -182 145 -170Q149 -154 152 -151T172 -148Q220 -148 230 -141Q238 -136 258 -53T279 32Q279 33 272 29Q224 -10 172 -10Q117 -10 75 30T33 157ZM352 326Q329 405 277 405Q242 405 210 374T160 293Q131 214 119 129Q119 126 119 118T118 106Q118 61 136 44T179 26Q233 26 290 98L298 109L352 326Z"></path></g><g data-mml-node="TeXAtom" transform="translate(446, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(623, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>q</mi><mrow><mi>i</mi><mo>,</mo><mn>0</mn></mrow></msub></math></mjx-assistive-mml></mjx-container></span> is the base-period quantity of good <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">i</mi>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">i</mi>
  </mrow>
</math></mathmlword><asciimath style="display: none;">i</asciimath><latex style="display: none">\mathrm{i}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: 0" xmlns="http://www.w3.org/2000/svg" width="0.629ex" height="1.514ex" role="img" focusable="false" viewBox="0 -669 278 669" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M69 609Q69 637 87 653T131 669Q154 667 171 652T188 609Q188 579 171 564T129 549Q104 549 87 564T69 609ZM247 0Q232 3 143 3Q132 3 106 3T56 1L34 0H26V46H42Q70 46 91 49Q100 53 102 60T104 102V205V293Q104 345 102 359T88 378Q74 385 41 385H30V408Q30 431 32 431L42 432Q52 433 70 434T106 436Q123 437 142 438T171 441T182 442H185V62Q190 52 197 50T232 46H255V0H247Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mi mathvariant="normal">i</mi></mrow></math></mjx-assistive-mml></mjx-container></span>.</li>
<li><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>P</mi>
    <mrow>
      <mi>i</mi>
      <mo>,</mo>
      <mn>0</mn>
    </mrow>
  </msub>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>P</mi>
    <mrow>
      <mi>i</mi>
      <mo>,</mo>
      <mn>0</mn>
    </mrow>
  </msub>
</math></mathmlword><asciimath style="display: none;">P_(i,0)</asciimath><latex style="display: none">P_{i, 0}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.65ex" xmlns="http://www.w3.org/2000/svg" width="3.362ex" height="2.195ex" role="img" focusable="false" viewBox="0 -683 1486.1 970.2" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mn" transform="translate(623, 0)"><path data-c="30" d="M96 585Q152 666 249 666Q297 666 345 640T423 548Q460 465 460 320Q460 165 417 83Q397 41 362 16T301 -15T250 -22Q224 -22 198 -16T137 16T82 83Q39 165 39 320Q39 494 96 585ZM321 597Q291 629 250 629Q208 629 178 597Q153 571 145 525T137 333Q137 175 145 125T181 46Q209 16 250 16Q290 16 318 46Q347 76 354 130T362 333Q362 478 354 524T321 597Z"></path></g></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>P</mi><mrow><mi>i</mi><mo>,</mo><mn>0</mn></mrow></msub></math></mjx-assistive-mml></mjx-container></span> is the base-period price of good <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">i</mi>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">i</mi>
  </mrow>
</math></mathmlword><asciimath style="display: none;">i</asciimath><latex style="display: none">\mathrm{i}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: 0" xmlns="http://www.w3.org/2000/svg" width="0.629ex" height="1.514ex" role="img" focusable="false" viewBox="0 -669 278 669" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M69 609Q69 637 87 653T131 669Q154 667 171 652T188 609Q188 579 171 564T129 549Q104 549 87 564T69 609ZM247 0Q232 3 143 3Q132 3 106 3T56 1L34 0H26V46H42Q70 46 91 49Q100 53 102 60T104 102V205V293Q104 345 102 359T88 378Q74 385 41 385H30V408Q30 431 32 431L42 432Q52 433 70 434T106 436Q123 437 142 438T171 441T182 442H185V62Q190 52 197 50T232 46H255V0H247Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mi mathvariant="normal">i</mi></mrow></math></mjx-assistive-mml></mjx-container></span>.</li>
<li><span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>P</mi>
    <mrow>
      <mi>i</mi>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <msub>
    <mi>P</mi>
    <mrow>
      <mi>i</mi>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
</math></mathmlword><asciimath style="display: none;">P_(i,t)</asciimath><latex style="display: none">P_{i, t}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.65ex" xmlns="http://www.w3.org/2000/svg" width="3.14ex" height="2.195ex" role="img" focusable="false" viewBox="0 -683 1387.8 970.2" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="TeXAtom" transform="translate(642, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M184 600Q184 624 203 642T247 661Q265 661 277 649T290 619Q290 596 270 577T226 557Q211 557 198 567T184 600ZM21 287Q21 295 30 318T54 369T98 420T158 442Q197 442 223 419T250 357Q250 340 236 301T196 196T154 83Q149 61 149 51Q149 26 166 26Q175 26 185 29T208 43T235 78T260 137Q263 149 265 151T282 153Q302 153 302 143Q302 135 293 112T268 61T223 11T161 -11Q129 -11 102 10T74 74Q74 91 79 106T122 220Q160 321 166 341T173 380Q173 404 156 404H154Q124 404 99 371T61 287Q60 286 59 284T58 281T56 279T53 278T49 278T41 278H27Q21 284 21 287Z"></path></g><g data-mml-node="mo" transform="translate(345, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(623, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>P</mi><mrow><mi>i</mi><mo>,</mo><mi>t</mi></mrow></msub></math></mjx-assistive-mml></mjx-container></span> is the price of good <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">i</mi>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">i</mi>
  </mrow>
</math></mathmlword><asciimath style="display: none;">i</asciimath><latex style="display: none">\mathrm{i}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: 0" xmlns="http://www.w3.org/2000/svg" width="0.629ex" height="1.514ex" role="img" focusable="false" viewBox="0 -669 278 669" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="69" d="M69 609Q69 637 87 653T131 669Q154 667 171 652T188 609Q188 579 171 564T129 549Q104 549 87 564T69 609ZM247 0Q232 3 143 3Q132 3 106 3T56 1L34 0H26V46H42Q70 46 91 49Q100 53 102 60T104 102V205V293Q104 345 102 359T88 378Q74 385 41 385H30V408Q30 431 32 431L42 432Q52 433 70 434T106 436Q123 437 142 438T171 441T182 442H185V62Q190 52 197 50T232 46H255V0H247Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mi mathvariant="normal">i</mi></mrow></math></mjx-assistive-mml></mjx-container></span> at time <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">t</mi>
  </mrow>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mi mathvariant="normal">t</mi>
  </mrow>
</math></mathmlword><asciimath style="display: none;">t</asciimath><latex style="display: none">\mathrm{t}</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.023ex" xmlns="http://www.w3.org/2000/svg" width="0.88ex" height="1.414ex" role="img" focusable="false" viewBox="0 -615 389 625" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M27 422Q80 426 109 478T141 600V615H181V431H316V385H181V241Q182 116 182 100T189 68Q203 29 238 29Q282 29 292 100Q293 108 293 146V181H333V146V134Q333 57 291 17Q264 -10 221 -10Q187 -10 162 2T124 33T105 68T98 100Q97 107 97 248V385H18V422H27Z"></path></g></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mi mathvariant="normal">t</mi></mrow></math></mjx-assistive-mml></mjx-container></span>.</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-346 preview-line 346" id="consumer-price-index-(cpi)-inflation-2" data_line_start="346" data_line_end="346" data_line="346,347" count_line="1">
Consumer Price Index (CPI) Inflation</h2>
<div class="preview-paragraph-347 preview-line 347 348" data_line_start="347" data_line_end="348" data_line="347,349" count_line="2">CPI inflation is the growth rate of the CPI<br>
Year-on-Year inflation:</div>
<div class="preview-paragraph-350 preview-line 350 351 352" data_line_start="350" data_line_end="352" data_line="350,353" count_line="3"><span class="math-block "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mi>&#x3C0;</mi>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <mi>C</mi>
      <mi>P</mi>
      <msub>
        <mi>I</mi>
        <mrow>
          <mi>t</mi>
        </mrow>
      </msub>
    </mrow>
    <mrow>
      <mi>C</mi>
      <mi>P</mi>
      <msub>
        <mi>I</mi>
        <mrow>
          <mi>t</mi>
          <mo>&#x2212;</mo>
          <mn>12</mn>
        </mrow>
      </msub>
    </mrow>
  </mfrac>
  <mo>&#x2212;</mo>
  <mn>1</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mi>π</mi>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <mi>C</mi>
      <mi>P</mi>
      <msub>
        <mi>I</mi>
        <mrow>
          <mi>t</mi>
        </mrow>
      </msub>
    </mrow>
    <mrow>
      <mi>C</mi>
      <mi>P</mi>
      <msub>
        <mi>I</mi>
        <mrow>
          <mi>t</mi>
          <mo>−</mo>
          <mn>12</mn>
        </mrow>
      </msub>
    </mrow>
  </mfrac>
  <mo>−</mo>
  <mn>1</mn>
</math></mathmlword><asciimath style="display: none;">pi_(t)=(CPI_(t))/(CPI_(t-12))-1</asciimath><latex style="display: none">\pi_{t}=\frac{C P I_{t}}{C P I_{t-12}}-1</latex><mjx-container class="MathJax" jax="SVG" display="true" role="presentation" style="position: relative"><svg style="vertical-align: -2.023ex" xmlns="http://www.w3.org/2000/svg" width="17.839ex" height="5.147ex" role="img" focusable="false" viewBox="0 -1381 7884.8 2275" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="3C0" d="M132 -11Q98 -11 98 22V33L111 61Q186 219 220 334L228 358H196Q158 358 142 355T103 336Q92 329 81 318T62 297T53 285Q51 284 38 284Q19 284 19 294Q19 300 38 329T93 391T164 429Q171 431 389 431Q549 431 553 430Q573 423 573 402Q573 371 541 360Q535 358 472 358H408L405 341Q393 269 393 222Q393 170 402 129T421 65T431 37Q431 20 417 5T381 -10Q370 -10 363 -7T347 17T331 77Q330 86 330 121Q330 170 339 226T357 318T367 358H269L268 354Q268 351 249 275T206 114T175 17Q164 -11 132 -11Z"></path></g><g data-mml-node="TeXAtom" transform="translate(570, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(1153, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="mfrac" transform="translate(2208.8, 0)"><g data-mml-node="mrow" transform="translate(848.6, 676)"><g data-mml-node="mi"><path data-c="43" d="M50 252Q50 367 117 473T286 641T490 704Q580 704 633 653Q642 643 648 636T656 626L657 623Q660 623 684 649Q691 655 699 663T715 679T725 690L740 705H746Q760 705 760 698Q760 694 728 561Q692 422 692 421Q690 416 687 415T669 413H653Q647 419 647 422Q647 423 648 429T650 449T651 481Q651 552 619 605T510 659Q484 659 454 652T382 628T299 572T226 479Q194 422 175 346T156 222Q156 108 232 58Q280 24 350 24Q441 24 512 92T606 240Q610 253 612 255T628 257Q648 257 648 248Q648 243 647 239Q618 132 523 55T319 -22Q206 -22 128 53T50 252Z"></path></g><g data-mml-node="mi" transform="translate(760, 0)"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="msub" transform="translate(1511, 0)"><g data-mml-node="mi"><path data-c="49" d="M43 1Q26 1 26 10Q26 12 29 24Q34 43 39 45Q42 46 54 46H60Q120 46 136 53Q137 53 138 54Q143 56 149 77T198 273Q210 318 216 344Q286 624 286 626Q284 630 284 631Q274 637 213 637H193Q184 643 189 662Q193 677 195 680T209 683H213Q285 681 359 681Q481 681 487 683H497Q504 676 504 672T501 655T494 639Q491 637 471 637Q440 637 407 634Q393 631 388 623Q381 609 337 432Q326 385 315 341Q245 65 245 59Q245 52 255 50T307 46H339Q345 38 345 37T342 19Q338 6 332 0H316Q279 2 179 2Q143 2 113 2T65 2T43 1Z"></path></g><g data-mml-node="TeXAtom" transform="translate(440, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g></g><g data-mml-node="mrow" transform="translate(220, -686)"><g data-mml-node="mi"><path data-c="43" d="M50 252Q50 367 117 473T286 641T490 704Q580 704 633 653Q642 643 648 636T656 626L657 623Q660 623 684 649Q691 655 699 663T715 679T725 690L740 705H746Q760 705 760 698Q760 694 728 561Q692 422 692 421Q690 416 687 415T669 413H653Q647 419 647 422Q647 423 648 429T650 449T651 481Q651 552 619 605T510 659Q484 659 454 652T382 628T299 572T226 479Q194 422 175 346T156 222Q156 108 232 58Q280 24 350 24Q441 24 512 92T606 240Q610 253 612 255T628 257Q648 257 648 248Q648 243 647 239Q618 132 523 55T319 -22Q206 -22 128 53T50 252Z"></path></g><g data-mml-node="mi" transform="translate(760, 0)"><path data-c="50" d="M287 628Q287 635 230 637Q206 637 199 638T192 648Q192 649 194 659Q200 679 203 681T397 683Q587 682 600 680Q664 669 707 631T751 530Q751 453 685 389Q616 321 507 303Q500 302 402 301H307L277 182Q247 66 247 59Q247 55 248 54T255 50T272 48T305 46H336Q342 37 342 35Q342 19 335 5Q330 0 319 0Q316 0 282 1T182 2Q120 2 87 2T51 1Q33 1 33 11Q33 13 36 25Q40 41 44 43T67 46Q94 46 127 49Q141 52 146 61Q149 65 218 339T287 628ZM645 554Q645 567 643 575T634 597T609 619T560 635Q553 636 480 637Q463 637 445 637T416 636T404 636Q391 635 386 627Q384 621 367 550T332 412T314 344Q314 342 395 342H407H430Q542 342 590 392Q617 419 631 471T645 554Z"></path></g><g data-mml-node="msub" transform="translate(1511, 0)"><g data-mml-node="mi"><path data-c="49" d="M43 1Q26 1 26 10Q26 12 29 24Q34 43 39 45Q42 46 54 46H60Q120 46 136 53Q137 53 138 54Q143 56 149 77T198 273Q210 318 216 344Q286 624 286 626Q284 630 284 631Q274 637 213 637H193Q184 643 189 662Q193 677 195 680T209 683H213Q285 681 359 681Q481 681 487 683H497Q504 676 504 672T501 655T494 639Q491 637 471 637Q440 637 407 634Q393 631 388 623Q381 609 337 432Q326 385 315 341Q245 65 245 59Q245 52 255 50T307 46H339Q345 38 345 37T342 19Q338 6 332 0H316Q279 2 179 2Q143 2 113 2T65 2T43 1Z"></path></g><g data-mml-node="TeXAtom" transform="translate(440, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g><g data-mml-node="mo" transform="translate(361, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mn" transform="translate(1139, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z" transform="translate(500, 0)"></path></g></g></g></g><rect width="3713.5" height="60" x="120" y="220"></rect></g><g data-mml-node="mo" transform="translate(6384.5, 0)"><path data-c="2212" d="M84 237T84 250T98 270H679Q694 262 694 250T679 230H98Q84 237 84 250Z"></path></g><g data-mml-node="mn" transform="translate(7384.8, 0)"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="block"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi>π</mi><mrow><mi>t</mi></mrow></msub><mo>=</mo><mfrac><mrow><mi>C</mi><mi>P</mi><msub><mi>I</mi><mrow><mi>t</mi></mrow></msub></mrow><mrow><mi>C</mi><mi>P</mi><msub><mi>I</mi><mrow><mi>t</mi><mo>−</mo><mn>12</mn></mrow></msub></mrow></mfrac><mo>−</mo><mn>1</mn></math></mjx-assistive-mml></mjx-container></span></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-354 preview-line 354" id="which-basket%3F" data_line_start="354" data_line_end="354" data_line="354,355" count_line="1">
Which Basket?</h2>
<div class="preview-paragraph-356 preview-line 356" data_line_start="356" data_line_end="356" data_line="356,357" count_line="1">Many different baskets of goods and services</div>
<div class="preview-paragraph-358 preview-line 358" data_line_start="358" data_line_end="358" data_line="358,359" count_line="1">E.g. for consumer prices in the UK:</div>
<ul class="preview-paragraph-359 preview-line 359 360 361 362 363 364 365" data_line_start="359" data_line_end="365" data_line="359,366" count_line="7">
<li>Consumer Price Index <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">(</mo>
  <mrow>
    <mi mathvariant="normal">C</mi>
    <mi mathvariant="normal">P</mi>
    <mi mathvariant="normal">I</mi>
  </mrow>
  <mo>=</mo>
  <mrow>
    <mi mathvariant="normal">H</mi>
    <mi mathvariant="normal">C</mi>
    <mi mathvariant="normal">I</mi>
    <mi mathvariant="normal">P</mi>
  </mrow>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mo stretchy="false">(</mo>
  <mrow>
    <mi mathvariant="normal">C</mi>
    <mi mathvariant="normal">P</mi>
    <mi mathvariant="normal">I</mi>
  </mrow>
  <mo>=</mo>
  <mrow>
    <mi mathvariant="normal">H</mi>
    <mi mathvariant="normal">C</mi>
    <mi mathvariant="normal">I</mi>
    <mi mathvariant="normal">P</mi>
  </mrow>
  <mo stretchy="false">)</mo>
  <mo>=</mo>
</math></mathmlword><asciimath style="display: none;">(CPI=HCIP)=</asciimath><latex style="display: none">(\mathrm{CPI}=\mathrm{HCIP})=</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.566ex" xmlns="http://www.w3.org/2000/svg" width="16.845ex" height="2.262ex" role="img" focusable="false" viewBox="0 -750 7445.3 1000" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mo"><path data-c="28" d="M94 250Q94 319 104 381T127 488T164 576T202 643T244 695T277 729T302 750H315H319Q333 750 333 741Q333 738 316 720T275 667T226 581T184 443T167 250T184 58T225 -81T274 -167T316 -220T333 -241Q333 -250 318 -250H315H302L274 -226Q180 -141 137 -14T94 250Z"></path></g><g data-mml-node="TeXAtom" data-mjx-texclass="ORD" transform="translate(389, 0)"><g data-mml-node="mi"><path data-c="43" d="M56 342Q56 428 89 500T174 615T283 681T391 705Q394 705 400 705T408 704Q499 704 569 636L582 624L612 663Q639 700 643 704Q644 704 647 704T653 705H657Q660 705 666 699V419L660 413H626Q620 419 619 430Q610 512 571 572T476 651Q457 658 426 658Q322 658 252 588Q173 509 173 342Q173 221 211 151Q232 111 263 84T328 45T384 29T428 24Q517 24 571 93T626 244Q626 251 632 257H660L666 251V236Q661 133 590 56T403 -21Q262 -21 159 83T56 342Z"></path></g><g data-mml-node="mi" transform="translate(722, 0)"><path data-c="50" d="M130 622Q123 629 119 631T103 634T60 637H27V683H214Q237 683 276 683T331 684Q419 684 471 671T567 616Q624 563 624 489Q624 421 573 372T451 307Q429 302 328 301H234V181Q234 62 237 58Q245 47 304 46H337V0H326Q305 3 182 3Q47 3 38 0H27V46H60Q102 47 111 49T130 61V622ZM507 488Q507 514 506 528T500 564T483 597T450 620T397 635Q385 637 307 637H286Q237 637 234 628Q231 624 231 483V342H302H339Q390 342 423 349T481 382Q507 411 507 488Z"></path></g><g data-mml-node="mi" transform="translate(1403, 0)"><path data-c="49" d="M328 0Q307 3 180 3T32 0H21V46H43Q92 46 106 49T126 60Q128 63 128 342Q128 620 126 623Q122 628 118 630T96 635T43 637H21V683H32Q53 680 180 680T328 683H339V637H317Q268 637 254 634T234 623Q232 620 232 342Q232 63 234 60Q238 55 242 53T264 48T317 46H339V0H328Z"></path></g></g><g data-mml-node="mo" transform="translate(2430.8, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g><g data-mml-node="TeXAtom" data-mjx-texclass="ORD" transform="translate(3486.6, 0)"><g data-mml-node="mi"><path data-c="48" d="M128 622Q121 629 117 631T101 634T58 637H25V683H36Q57 680 180 680Q315 680 324 683H335V637H302Q262 636 251 634T233 622L232 500V378H517V622Q510 629 506 631T490 634T447 637H414V683H425Q446 680 569 680Q704 680 713 683H724V637H691Q651 636 640 634T622 622V61Q628 51 639 49T691 46H724V0H713Q692 3 569 3Q434 3 425 0H414V46H447Q489 47 498 49T517 61V332H232V197L233 61Q239 51 250 49T302 46H335V0H324Q303 3 180 3Q45 3 36 0H25V46H58Q100 47 109 49T128 61V622Z"></path></g><g data-mml-node="mi" transform="translate(750, 0)"><path data-c="43" d="M56 342Q56 428 89 500T174 615T283 681T391 705Q394 705 400 705T408 704Q499 704 569 636L582 624L612 663Q639 700 643 704Q644 704 647 704T653 705H657Q660 705 666 699V419L660 413H626Q620 419 619 430Q610 512 571 572T476 651Q457 658 426 658Q322 658 252 588Q173 509 173 342Q173 221 211 151Q232 111 263 84T328 45T384 29T428 24Q517 24 571 93T626 244Q626 251 632 257H660L666 251V236Q661 133 590 56T403 -21Q262 -21 159 83T56 342Z"></path></g><g data-mml-node="mi" transform="translate(1472, 0)"><path data-c="49" d="M328 0Q307 3 180 3T32 0H21V46H43Q92 46 106 49T126 60Q128 63 128 342Q128 620 126 623Q122 628 118 630T96 635T43 637H21V683H32Q53 680 180 680T328 683H339V637H317Q268 637 254 634T234 623Q232 620 232 342Q232 63 234 60Q238 55 242 53T264 48T317 46H339V0H328Z"></path></g><g data-mml-node="mi" transform="translate(1833, 0)"><path data-c="50" d="M130 622Q123 629 119 631T103 634T60 637H27V683H214Q237 683 276 683T331 684Q419 684 471 671T567 616Q624 563 624 489Q624 421 573 372T451 307Q429 302 328 301H234V181Q234 62 237 58Q245 47 304 46H337V0H326Q305 3 182 3Q47 3 38 0H27V46H60Q102 47 111 49T130 61V622ZM507 488Q507 514 506 528T500 564T483 597T450 620T397 635Q385 637 307 637H286Q237 637 234 628Q231 624 231 483V342H302H339Q390 342 423 349T481 382Q507 411 507 488Z"></path></g></g><g data-mml-node="mo" transform="translate(6000.6, 0)"><path data-c="29" d="M60 749L64 750Q69 750 74 750H86L114 726Q208 641 251 514T294 250Q294 182 284 119T261 12T224 -76T186 -143T145 -194T113 -227T90 -246Q87 -249 86 -250H74Q66 -250 63 -250T58 -247T55 -238Q56 -237 66 -225Q221 -64 221 250T66 725Q56 737 55 738Q55 746 60 749Z"></path></g><g data-mml-node="mo" transform="translate(6667.3, 0)"><path data-c="3D" d="M56 347Q56 360 70 367H707Q722 359 722 347Q722 336 708 328L390 327H72Q56 332 56 347ZM56 153Q56 168 72 173H708Q722 163 722 153Q722 140 707 133H70Q56 140 56 153Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">(</mo><mrow><mi mathvariant="normal">C</mi><mi mathvariant="normal">P</mi><mi mathvariant="normal">I</mi></mrow><mo>=</mo><mrow><mi mathvariant="normal">H</mi><mi mathvariant="normal">C</mi><mi mathvariant="normal">I</mi><mi mathvariant="normal">P</mi></mrow><mo stretchy="false">)</mo><mo>=</mo></math></mjx-assistive-mml></mjx-container></span> the basis for the Bank of England's <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">2%</asciimath><latex style="display: none">2 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="3.016ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1333 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mi" transform="translate(500, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>2</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> inflation target since 2004</li>
<li>CPIH - includes owner occupiers' housing costs</li>
<li>Retail Price Index (RPI) - the basis for many contracts (e.g. pensions and index-linked bonds) but no longer a 'national statistic'</li>
<li>RPIX = RPI excluding mortgage interest payments - basis for the Bank of England's <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2.5</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2.5</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">2.5%</asciimath><latex style="display: none">2.5 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="4.776ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 2111 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(500, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(778, 0)"></path></g><g data-mml-node="mi" transform="translate(1278, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>2.5</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> inflation target 1997-2003</li>
<li>RPIJ - statistically superior version of RPI</li>
<li>etc.</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-366 preview-line 366" id="upward-bias-of-cpi-from-using-past-basket" data_line_start="366" data_line_end="366" data_line="366,367" count_line="1">
Upward bias of CPI from using past basket</h2>
<ul class="preview-paragraph-368 preview-line 368 369 370 371 372 373" data_line_start="368" data_line_end="373" data_line="368,374" count_line="6">
<li>Substitution bias: More expensive goods are substituted out (for cheaper items in basket).</li>
<li>Outlet substitution bias: Consumers tend to switch from more expensive to less expensive outlets (even if purchase same basket).</li>
<li>New product bias: New products are often cheaper than the ones they replace. And the quality changes generally not measured well (e.g., cell-phones, computers, ...).</li>
<li>Boskin et al. (1996): upward bias up to <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">2%</asciimath><latex style="display: none">2 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="3.016ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1333 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mi" transform="translate(500, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>2</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> in U.S. CPI.</li>
<li>Nowadays under <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>1</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>1</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">1%</asciimath><latex style="display: none">1 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="3.016ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1333 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g><g data-mml-node="mi" transform="translate(500, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>1</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> due to improvements in measurement.</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-374 preview-line 374" id="consumption-baskets-in-thailand-vs-ireland" data_line_start="374" data_line_end="374" data_line="374,375" count_line="1">
Consumption Baskets in Thailand vs Ireland</h2>
<div class="table_tabular  preview-paragraph-376 preview-line 376 377 378 379 380 381 382 383 384 385 386" style="text-align: center" data_line_start="376" data_line_end="386" data_line="376,387" count_line="11">
<div class="inline-tabular"><table id="tabular">
<tbody>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; " class="_empty"></td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2011</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2015</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">Ireland 2015</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Food &amp; Beverages (FB)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">33.0</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">33.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">28.7</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Clothing &amp; Footwears (CF)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">3.0</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">3.1</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">4.4</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Housing &amp; Furnishing (HF)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">23.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">24.1</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">20.4</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Health &amp; Personal Care (HP)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">6.9</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">6.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">14.6</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Transport &amp; Communication (TC)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">26.8</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">25.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">16.6</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Recreation, Reading, Education and Religion (RR)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">5.2</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">6.0</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">10.0</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: left; border-left: none !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Tobacco &amp; Alcoholic Beverages (TA)</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">1.7</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">1.2</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">5.3</td>
</tr>
</tbody>
</table>
<tsv style="display: none">	2011	2015	Ireland 2015
Food &amp; Beverages (FB)	33.0	33.5	28.7
Clothing &amp; Footwears (CF)	3.0	3.1	4.4
Housing &amp; Furnishing (HF)	23.5	24.1	20.4
Health &amp; Personal Care (HP)	6.9	6.5	14.6
Transport &amp; Communication (TC)	26.8	25.5	16.6
Recreation, Reading, Education and Religion (RR)	5.2	6.0	10.0
Tobacco &amp; Alcoholic Beverages (TA)	1.7	1.2	5.3</tsv><table-markdown style="display: none">|  | 2011 | 2015 | Ireland 2015 |
| :--- | :---: | :---: | :---: |
| Food &amp; Beverages (FB) | 33.0 | 33.5 | 28.7 |
| Clothing &amp; Footwears (CF) | 3.0 | 3.1 | 4.4 |
| Housing &amp; Furnishing (HF) | 23.5 | 24.1 | 20.4 |
| Health &amp; Personal Care (HP) | 6.9 | 6.5 | 14.6 |
| Transport &amp; Communication (TC) | 26.8 | 25.5 | 16.6 |
| Recreation, Reading, Education and Religion (RR) | 5.2 | 6.0 | 10.0 |
| Tobacco &amp; Alcoholic Beverages (TA) | 1.7 | 1.2 | 5.3 |</table-markdown></div></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-388 preview-line 388" id="calculating-contributions-by-component" data_line_start="388" data_line_end="388" data_line="388,389" count_line="1">
Calculating contributions by component</h2>
<div class="preview-paragraph-390 preview-line 390" data_line_start="390" data_line_end="390" data_line="390,391" count_line="1">&quot;Group-level price accounting&quot; consists of measuring the contribution of different groups of items to the overall price change.</div>
<div class="preview-paragraph-392 preview-line 392" data_line_start="392" data_line_end="392" data_line="392,393" count_line="1">We can approximate this with:</div>
<div class="preview-paragraph-394 preview-line 394 395 396" data_line_start="394" data_line_end="396" data_line="394,397" count_line="3"><span class="math-block "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mi>&#x3C0;</mi>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>&#x2248;</mo>
  <msub>
    <mi>w</mi>
    <mrow>
      <mn>1</mn>
    </mrow>
  </msub>
  <msub>
    <mi>&#x3C0;</mi>
    <mrow>
      <mn>1</mn>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>+</mo>
  <msub>
    <mi>w</mi>
    <mrow>
      <mn>2</mn>
    </mrow>
  </msub>
  <msub>
    <mi>&#x3C0;</mi>
    <mrow>
      <mn>2</mn>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>+</mo>
  <msub>
    <mi>w</mi>
    <mrow>
      <mn>3</mn>
    </mrow>
  </msub>
  <msub>
    <mi>&#x3C0;</mi>
    <mrow>
      <mn>3</mn>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>&#x2026;</mo>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <msub>
    <mi>π</mi>
    <mrow>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>≈</mo>
  <msub>
    <mi>w</mi>
    <mrow>
      <mn>1</mn>
    </mrow>
  </msub>
  <msub>
    <mi>π</mi>
    <mrow>
      <mn>1</mn>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>+</mo>
  <msub>
    <mi>w</mi>
    <mrow>
      <mn>2</mn>
    </mrow>
  </msub>
  <msub>
    <mi>π</mi>
    <mrow>
      <mn>2</mn>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>+</mo>
  <msub>
    <mi>w</mi>
    <mrow>
      <mn>3</mn>
    </mrow>
  </msub>
  <msub>
    <mi>π</mi>
    <mrow>
      <mn>3</mn>
      <mo>,</mo>
      <mi>t</mi>
    </mrow>
  </msub>
  <mo>…</mo>
</math></mathmlword><asciimath style="display: none;">pi_(t)~~w_(1)pi_(1,t)+w_(2)pi_(2,t)+w_(3)pi_(3,t)dots</asciimath><latex style="display: none">\pi_{t} \approx w_{1} \pi_{1, t}+w_{2} \pi_{2, t}+w_{3} \pi_{3, t} \ldots</latex><mjx-container class="MathJax" jax="SVG" display="true" role="presentation" style="position: relative"><svg style="vertical-align: -0.65ex" xmlns="http://www.w3.org/2000/svg" width="30.831ex" height="1.969ex" role="img" focusable="false" viewBox="0 -583 13627.2 870.2" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="msub"><g data-mml-node="mi"><path data-c="3C0" d="M132 -11Q98 -11 98 22V33L111 61Q186 219 220 334L228 358H196Q158 358 142 355T103 336Q92 329 81 318T62 297T53 285Q51 284 38 284Q19 284 19 294Q19 300 38 329T93 391T164 429Q171 431 389 431Q549 431 553 430Q573 423 573 402Q573 371 541 360Q535 358 472 358H408L405 341Q393 269 393 222Q393 170 402 129T421 65T431 37Q431 20 417 5T381 -10Q370 -10 363 -7T347 17T331 77Q330 86 330 121Q330 170 339 226T357 318T367 358H269L268 354Q268 351 249 275T206 114T175 17Q164 -11 132 -11Z"></path></g><g data-mml-node="TeXAtom" transform="translate(570, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mi"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(1153, 0)"><path data-c="2248" d="M55 319Q55 360 72 393T114 444T163 472T205 482Q207 482 213 482T223 483Q262 483 296 468T393 413L443 381Q502 346 553 346Q609 346 649 375T694 454Q694 465 698 474T708 483Q722 483 722 452Q722 386 675 338T555 289Q514 289 468 310T388 357T308 404T224 426Q164 426 125 393T83 318Q81 289 69 289Q55 289 55 319ZM55 85Q55 126 72 159T114 210T163 238T205 248Q207 248 213 248T223 249Q262 249 296 234T393 179L443 147Q502 112 553 112Q609 112 649 141T694 220Q694 249 708 249T722 217Q722 153 675 104T555 55Q514 55 468 76T388 123T308 170T224 192Q164 192 125 159T83 84Q80 55 69 55Q55 55 55 85Z"></path></g><g data-mml-node="msub" transform="translate(2208.8, 0)"><g data-mml-node="mi"><path data-c="77" d="M580 385Q580 406 599 424T641 443Q659 443 674 425T690 368Q690 339 671 253Q656 197 644 161T609 80T554 12T482 -11Q438 -11 404 5T355 48Q354 47 352 44Q311 -11 252 -11Q226 -11 202 -5T155 14T118 53T104 116Q104 170 138 262T173 379Q173 380 173 381Q173 390 173 393T169 400T158 404H154Q131 404 112 385T82 344T65 302T57 280Q55 278 41 278H27Q21 284 21 287Q21 293 29 315T52 366T96 418T161 441Q204 441 227 416T250 358Q250 340 217 250T184 111Q184 65 205 46T258 26Q301 26 334 87L339 96V119Q339 122 339 128T340 136T341 143T342 152T345 165T348 182T354 206T362 238T373 281Q402 395 406 404Q419 431 449 431Q468 431 475 421T483 402Q483 389 454 274T422 142Q420 131 420 107V100Q420 85 423 71T442 42T487 26Q558 26 600 148Q609 171 620 213T632 273Q632 306 619 325T593 357T580 385Z"></path></g><g data-mml-node="TeXAtom" transform="translate(716, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g></g></g><g data-mml-node="msub" transform="translate(3328.4, 0)"><g data-mml-node="mi"><path data-c="3C0" d="M132 -11Q98 -11 98 22V33L111 61Q186 219 220 334L228 358H196Q158 358 142 355T103 336Q92 329 81 318T62 297T53 285Q51 284 38 284Q19 284 19 294Q19 300 38 329T93 391T164 429Q171 431 389 431Q549 431 553 430Q573 423 573 402Q573 371 541 360Q535 358 472 358H408L405 341Q393 269 393 222Q393 170 402 129T421 65T431 37Q431 20 417 5T381 -10Q370 -10 363 -7T347 17T331 77Q330 86 330 121Q330 170 339 226T357 318T367 358H269L268 354Q268 351 249 275T206 114T175 17Q164 -11 132 -11Z"></path></g><g data-mml-node="TeXAtom" transform="translate(570, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(778, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(4976, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="msub" transform="translate(5976.2, 0)"><g data-mml-node="mi"><path data-c="77" d="M580 385Q580 406 599 424T641 443Q659 443 674 425T690 368Q690 339 671 253Q656 197 644 161T609 80T554 12T482 -11Q438 -11 404 5T355 48Q354 47 352 44Q311 -11 252 -11Q226 -11 202 -5T155 14T118 53T104 116Q104 170 138 262T173 379Q173 380 173 381Q173 390 173 393T169 400T158 404H154Q131 404 112 385T82 344T65 302T57 280Q55 278 41 278H27Q21 284 21 287Q21 293 29 315T52 366T96 418T161 441Q204 441 227 416T250 358Q250 340 217 250T184 111Q184 65 205 46T258 26Q301 26 334 87L339 96V119Q339 122 339 128T340 136T341 143T342 152T345 165T348 182T354 206T362 238T373 281Q402 395 406 404Q419 431 449 431Q468 431 475 421T483 402Q483 389 454 274T422 142Q420 131 420 107V100Q420 85 423 71T442 42T487 26Q558 26 600 148Q609 171 620 213T632 273Q632 306 619 325T593 357T580 385Z"></path></g><g data-mml-node="TeXAtom" transform="translate(716, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g></g></g><g data-mml-node="msub" transform="translate(7095.8, 0)"><g data-mml-node="mi"><path data-c="3C0" d="M132 -11Q98 -11 98 22V33L111 61Q186 219 220 334L228 358H196Q158 358 142 355T103 336Q92 329 81 318T62 297T53 285Q51 284 38 284Q19 284 19 294Q19 300 38 329T93 391T164 429Q171 431 389 431Q549 431 553 430Q573 423 573 402Q573 371 541 360Q535 358 472 358H408L405 341Q393 269 393 222Q393 170 402 129T421 65T431 37Q431 20 417 5T381 -10Q370 -10 363 -7T347 17T331 77Q330 86 330 121Q330 170 339 226T357 318T367 358H269L268 354Q268 351 249 275T206 114T175 17Q164 -11 132 -11Z"></path></g><g data-mml-node="TeXAtom" transform="translate(570, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(778, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(8743.4, 0)"><path data-c="2B" d="M56 237T56 250T70 270H369V420L370 570Q380 583 389 583Q402 583 409 568V270H707Q722 262 722 250T707 230H409V-68Q401 -82 391 -82H389H387Q375 -82 369 -68V230H70Q56 237 56 250Z"></path></g><g data-mml-node="msub" transform="translate(9743.6, 0)"><g data-mml-node="mi"><path data-c="77" d="M580 385Q580 406 599 424T641 443Q659 443 674 425T690 368Q690 339 671 253Q656 197 644 161T609 80T554 12T482 -11Q438 -11 404 5T355 48Q354 47 352 44Q311 -11 252 -11Q226 -11 202 -5T155 14T118 53T104 116Q104 170 138 262T173 379Q173 380 173 381Q173 390 173 393T169 400T158 404H154Q131 404 112 385T82 344T65 302T57 280Q55 278 41 278H27Q21 284 21 287Q21 293 29 315T52 366T96 418T161 441Q204 441 227 416T250 358Q250 340 217 250T184 111Q184 65 205 46T258 26Q301 26 334 87L339 96V119Q339 122 339 128T340 136T341 143T342 152T345 165T348 182T354 206T362 238T373 281Q402 395 406 404Q419 431 449 431Q468 431 475 421T483 402Q483 389 454 274T422 142Q420 131 420 107V100Q420 85 423 71T442 42T487 26Q558 26 600 148Q609 171 620 213T632 273Q632 306 619 325T593 357T580 385Z"></path></g><g data-mml-node="TeXAtom" transform="translate(716, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path></g></g></g><g data-mml-node="msub" transform="translate(10863.2, 0)"><g data-mml-node="mi"><path data-c="3C0" d="M132 -11Q98 -11 98 22V33L111 61Q186 219 220 334L228 358H196Q158 358 142 355T103 336Q92 329 81 318T62 297T53 285Q51 284 38 284Q19 284 19 294Q19 300 38 329T93 391T164 429Q171 431 389 431Q549 431 553 430Q573 423 573 402Q573 371 541 360Q535 358 472 358H408L405 341Q393 269 393 222Q393 170 402 129T421 65T431 37Q431 20 417 5T381 -10Q370 -10 363 -7T347 17T331 77Q330 86 330 121Q330 170 339 226T357 318T367 358H269L268 354Q268 351 249 275T206 114T175 17Q164 -11 132 -11Z"></path></g><g data-mml-node="TeXAtom" transform="translate(570, -150) scale(0.707)" data-mjx-texclass="ORD"><g data-mml-node="mn"><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path></g><g data-mml-node="mo" transform="translate(500, 0)"><path data-c="2C" d="M78 35T78 60T94 103T137 121Q165 121 187 96T210 8Q210 -27 201 -60T180 -117T154 -158T130 -185T117 -194Q113 -194 104 -185T95 -172Q95 -168 106 -156T131 -126T157 -76T173 -3V9L172 8Q170 7 167 6T161 3T152 1T140 0Q113 0 96 17Z"></path></g><g data-mml-node="mi" transform="translate(778, 0)"><path data-c="74" d="M26 385Q19 392 19 395Q19 399 22 411T27 425Q29 430 36 430T87 431H140L159 511Q162 522 166 540T173 566T179 586T187 603T197 615T211 624T229 626Q247 625 254 615T261 596Q261 589 252 549T232 470L222 433Q222 431 272 431H323Q330 424 330 420Q330 398 317 385H210L174 240Q135 80 135 68Q135 26 162 26Q197 26 230 60T283 144Q285 150 288 151T303 153H307Q322 153 322 145Q322 142 319 133Q314 117 301 95T267 48T216 6T155 -11Q125 -11 98 4T59 56Q57 64 57 83V101L92 241Q127 382 128 383Q128 385 77 385H26Z"></path></g></g></g><g data-mml-node="mo" transform="translate(12455.2, 0)"><path data-c="2026" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60ZM525 60Q525 84 542 102T585 120Q609 120 627 104T646 61Q646 36 629 18T586 0T543 17T525 60ZM972 60Q972 84 989 102T1032 120Q1056 120 1074 104T1093 61Q1093 36 1076 18T1033 0T990 17T972 60Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="block"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><msub><mi>π</mi><mrow><mi>t</mi></mrow></msub><mo>≈</mo><msub><mi>w</mi><mrow><mn>1</mn></mrow></msub><msub><mi>π</mi><mrow><mn>1</mn><mo>,</mo><mi>t</mi></mrow></msub><mo>+</mo><msub><mi>w</mi><mrow><mn>2</mn></mrow></msub><msub><mi>π</mi><mrow><mn>2</mn><mo>,</mo><mi>t</mi></mrow></msub><mo>+</mo><msub><mi>w</mi><mrow><mn>3</mn></mrow></msub><msub><mi>π</mi><mrow><mn>3</mn><mo>,</mo><mi>t</mi></mrow></msub><mo>…</mo></math></mjx-assistive-mml></mjx-container></span></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-398 preview-line 398" id="thai-cpi-inflation%3A-contributions-by-component" data_line_start="398" data_line_end="398" data_line="398,399" count_line="1">
Thai CPI Inflation: Contributions by Component</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-399 preview-line 399" id="graph%3A-thai-cpi-(contributions)" data_line_start="399" data_line_end="399" data_line="399,400" count_line="1">
Graph: Thai CPI (Contributions)</h3>
<div class="preview-paragraph-400 preview-line 400 401" data_line_start="400" data_line_end="401" data_line="400,402" count_line="2">The bar graph shows the largest component of Thai CPI inflation between 2007 and 2015. Food and beverage are the most important contributors, with consistent inflation in this category over the period. Transport and communication are also important contributors, but their contribution to CPI was negative in 2009 and 2015, indicating prices declines in this sector of the economy. Housing ad furnishing had a mild positive contribution to CPI inflation.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-47.jpg?height=685&amp;width=1926&amp;top_left_y=457&amp;top_left_x=738" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-404 preview-line 404" id="section-6%3A-monetary-and-fiscal-policy" data_line_start="404" data_line_end="404" data_line="404,405" count_line="1">
Section 6: Monetary and Fiscal Policy</h2>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-406 preview-line 406" id="monetary-policy" data_line_start="406" data_line_end="406" data_line="406,407" count_line="1">
Monetary policy</h2>
<div class="preview-paragraph-408 preview-line 408" data_line_start="408" data_line_end="408" data_line="408,409" count_line="1">Monetary policy is a set of actions (normally by central bank) to influence how much money is in the economy and how much it costs to borrow.</div>
<div class="preview-paragraph-410 preview-line 410" data_line_start="410" data_line_end="410" data_line="410,411" count_line="1">Conventional</div>
<ul class="preview-paragraph-411 preview-line 411 412 413" data_line_start="411" data_line_end="413" data_line="411,414" count_line="3">
<li>Manipulate long-term interest rates indirectly by changing short-term interest rates</li>
<li>Bank of England's Monetary Policy Committee (MPC) meets each month to set interest rates to hit the Government's <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mn>2</mn>
  <mi mathvariant="normal">%</mi>
</math></mathmlword><asciimath style="display: none;">2%</asciimath><latex style="display: none">2 \%</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.127ex" xmlns="http://www.w3.org/2000/svg" width="3.016ex" height="1.824ex" role="img" focusable="false" viewBox="0 -750 1333 806" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="mn"><path data-c="32" d="M109 429Q82 429 66 447T50 491Q50 562 103 614T235 666Q326 666 387 610T449 465Q449 422 429 383T381 315T301 241Q265 210 201 149L142 93L218 92Q375 92 385 97Q392 99 409 186V189H449V186Q448 183 436 95T421 3V0H50V19V31Q50 38 56 46T86 81Q115 113 136 137Q145 147 170 174T204 211T233 244T261 278T284 308T305 340T320 369T333 401T340 431T343 464Q343 527 309 573T212 619Q179 619 154 602T119 569T109 550Q109 549 114 549Q132 549 151 535T170 489Q170 464 154 447T109 429Z"></path></g><g data-mml-node="mi" transform="translate(500, 0)"><path data-c="25" d="M465 605Q428 605 394 614T340 632T319 641Q332 608 332 548Q332 458 293 403T202 347Q145 347 101 402T56 548Q56 637 101 693T202 750Q241 750 272 719Q359 642 464 642Q580 642 650 732Q662 748 668 749Q670 750 673 750Q682 750 688 743T693 726Q178 -47 170 -52Q166 -56 160 -56Q147 -56 142 -45Q137 -36 142 -27Q143 -24 363 304Q469 462 525 546T581 630Q528 605 465 605ZM207 385Q235 385 263 427T292 548Q292 617 267 664T200 712Q193 712 186 709T167 698T147 668T134 615Q132 595 132 548V527Q132 436 165 403Q183 385 203 385H207ZM500 146Q500 234 544 290T647 347Q699 347 737 292T776 146T737 0T646 -56Q590 -56 545 0T500 146ZM651 -18Q679 -18 707 24T736 146Q736 215 711 262T644 309Q637 309 630 306T611 295T591 265T578 212Q577 200 577 146V124Q577 -18 647 -18H651Z"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>2</mn><mi mathvariant="normal">%</mi></math></mjx-assistive-mml></mjx-container></span> inflation target</li>
</ul>
<div class="preview-paragraph-414 preview-line 414" data_line_start="414" data_line_end="414" data_line="414,415" count_line="1">Unconventional</div>
<ul class="preview-paragraph-415 preview-line 415 416 417" data_line_start="415" data_line_end="417" data_line="415,418" count_line="3">
<li>Manipulate long-term interest rates directly by buying financial assets</li>
<li>Quantitative Easing in the UK: Bank of England currently has purchased <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
  <mn>375</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
  <mn>375</mn>
</math></mathmlword><asciimath style="display: none;">£375</asciimath><latex style="display: none">£ 375</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.05ex" xmlns="http://www.w3.org/2000/svg" width="5.133ex" height="1.665ex" role="img" focusable="false" viewBox="0 -714 2269 736" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g><g data-mml-node="mn" transform="translate(769, 0)"><path data-c="33" d="M127 463Q100 463 85 480T69 524Q69 579 117 622T233 665Q268 665 277 664Q351 652 390 611T430 522Q430 470 396 421T302 350L299 348Q299 347 308 345T337 336T375 315Q457 262 457 175Q457 96 395 37T238 -22Q158 -22 100 21T42 130Q42 158 60 175T105 193Q133 193 151 175T169 130Q169 119 166 110T159 94T148 82T136 74T126 70T118 67L114 66Q165 21 238 21Q293 21 321 74Q338 107 338 175V195Q338 290 274 322Q259 328 213 329L171 330L168 332Q166 335 166 348Q166 366 174 366Q202 366 232 371Q266 376 294 413T322 525V533Q322 590 287 612Q265 626 240 626Q208 626 181 615T143 592T132 580H135Q138 579 143 578T153 573T165 566T175 555T183 540T186 520Q186 498 172 481T127 463Z"></path><path data-c="37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z" transform="translate(500, 0)"></path><path data-c="35" d="M164 157Q164 133 148 117T109 101H102Q148 22 224 22Q294 22 326 82Q345 115 345 210Q345 313 318 349Q292 382 260 382H254Q176 382 136 314Q132 307 129 306T114 304Q97 304 95 310Q93 314 93 485V614Q93 664 98 664Q100 666 102 666Q103 666 123 658T178 642T253 634Q324 634 389 662Q397 666 402 666Q410 666 410 648V635Q328 538 205 538Q174 538 149 544L139 546V374Q158 388 169 396T205 412T256 420Q337 420 393 355T449 201Q449 109 385 44T229 -22Q148 -22 99 32T50 154Q50 178 61 192T84 210T107 214Q132 214 148 197T164 157Z" transform="translate(1000, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow><mn>375</mn></math></mjx-assistive-mml></mjx-container></span> billion of financial assets, mostly government debt</li>
</ul>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-418 preview-line 418" id="bank-of-england-interest-rate" data_line_start="418" data_line_end="418" data_line="418,419" count_line="1">
Bank of England interest rate</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-419 preview-line 419" id="graph%3A-bank-rate" data_line_start="419" data_line_end="419" data_line="419,420" count_line="1">
Graph: Bank rate</h3>
<div class="preview-paragraph-420 preview-line 420 421 422" data_line_start="420" data_line_end="422" data_line="420,423" count_line="3">The line graph shows the bank rate (in percentage) from 2002 to 2023.<br>
The rate was around or slightly above 4 percent before 2008, then barely above 0 from 2008 to 2021, and then increased to reach 5.25% in 2023.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-50.jpg?height=1238&amp;width=2194&amp;top_left_y=376&amp;top_left_x=566" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-424 preview-line 424" id="bank-of-england-quantitative-easing" data_line_start="424" data_line_end="424" data_line="424,425" count_line="1">
Bank of England Quantitative Easing</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-425 preview-line 425" id="graph%3A-quantity-of-assets-purchased-by-the-creation-of-central-bank-reserves" data_line_start="425" data_line_end="425" data_line="425,426" count_line="1">
Graph: Quantity of assets purchased by the creation of Central Bank reserves</h3>
<div class="preview-paragraph-426 preview-line 426" data_line_start="426" data_line_end="426" data_line="426,427" count_line="1">The line graph shows three round of quantitative easing: the first occurring in 2009 (QE 1, 200000 million pounds worth of assets purchased), then in 2012 (QE 2, 150000 million pounds) and then in 2017 (QE 3, 10000 million pounds).</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-428 preview-line 428" id="fiscal-policy" data_line_start="428" data_line_end="428" data_line="428,429" count_line="1">
Fiscal policy</h2>
<div class="preview-paragraph-429 preview-line 429 430" data_line_start="429" data_line_end="430" data_line="429,431" count_line="2"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-51.jpg?height=1237&amp;width=2144&amp;top_left_y=368&amp;top_left_x=544" alt="" data-align="center"></figure><br>
Manipulate government spending, taxation and borrowing to achieve macroeconomic goals</div>
<div class="preview-paragraph-432 preview-line 432" data_line_start="432" data_line_end="432" data_line="432,433" count_line="1">UK GOVERNMENT SPENDING: <span class="math-inline "><mathml style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>&#xA3;</mo>
  </mrow>
  <mn>761.9</mn>
</math></mathml><mathmlword style="display: none"><math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>
    <mo>£</mo>
  </mrow>
  <mn>761.9</mn>
</math></mathmlword><asciimath style="display: none;">£761.9</asciimath><latex style="display: none">£ 761.9</latex><mjx-container class="MathJax" jax="SVG" role="presentation" style="position: relative"><svg style="vertical-align: -0.05ex" xmlns="http://www.w3.org/2000/svg" width="6.894ex" height="1.665ex" role="img" focusable="false" viewBox="0 -714 3047 736" aria-hidden="true"><g stroke="currentColor" fill="currentColor" stroke-width="0" transform="matrix(1 0 0 -1 0 0)"><g data-mml-node="math"><g data-mml-node="TeXAtom" data-mjx-texclass="ORD"><g data-mml-node="mo"><path data-c="A3" d="M699 578Q699 473 635 473Q597 473 595 508Q595 559 654 569V576Q654 619 637 648T581 677Q545 677 513 647T463 561Q460 554 437 464T414 371Q414 370 458 370H502Q508 364 508 362Q505 334 495 324H402L382 241Q377 224 373 206T366 180T361 163T358 151T354 142T350 133T344 120Q340 112 338 107T336 101L354 90Q398 63 422 54T476 44Q515 44 539 73T574 133Q578 144 580 146T598 148Q622 148 622 139Q622 138 620 130Q602 74 555 32T447 -11Q395 -11 317 38L294 51Q271 28 233 9T155 -10Q117 -10 103 5T88 39Q88 73 126 106T224 139Q236 139 247 138T266 134L273 132Q275 132 302 239L323 324H259Q253 330 253 332Q253 350 265 370H300L334 371L355 453Q356 457 360 477T366 501T372 522T379 545T387 565T397 587T409 606T425 627Q453 664 497 689T583 714Q640 714 669 676T699 578ZM245 76Q211 85 195 85Q173 85 158 71T142 42Q142 26 160 26H163Q211 30 245 76Z"></path></g></g><g data-mml-node="mn" transform="translate(769, 0)"><path data-c="37" d="M55 458Q56 460 72 567L88 674Q88 676 108 676H128V672Q128 662 143 655T195 646T364 644H485V605L417 512Q408 500 387 472T360 435T339 403T319 367T305 330T292 284T284 230T278 162T275 80Q275 66 275 52T274 28V19Q270 2 255 -10T221 -22Q210 -22 200 -19T179 0T168 40Q168 198 265 368Q285 400 349 489L395 552H302Q128 552 119 546Q113 543 108 522T98 479L95 458V455H55V458Z"></path><path data-c="36" d="M42 313Q42 476 123 571T303 666Q372 666 402 630T432 550Q432 525 418 510T379 495Q356 495 341 509T326 548Q326 592 373 601Q351 623 311 626Q240 626 194 566Q147 500 147 364L148 360Q153 366 156 373Q197 433 263 433H267Q313 433 348 414Q372 400 396 374T435 317Q456 268 456 210V192Q456 169 451 149Q440 90 387 34T253 -22Q225 -22 199 -14T143 16T92 75T56 172T42 313ZM257 397Q227 397 205 380T171 335T154 278T148 216Q148 133 160 97T198 39Q222 21 251 21Q302 21 329 59Q342 77 347 104T352 209Q352 289 347 316T329 361Q302 397 257 397Z" transform="translate(500, 0)"></path><path data-c="31" d="M213 578L200 573Q186 568 160 563T102 556H83V602H102Q149 604 189 617T245 641T273 663Q275 666 285 666Q294 666 302 660V361L303 61Q310 54 315 52T339 48T401 46H427V0H416Q395 3 257 3Q121 3 100 0H88V46H114Q136 46 152 46T177 47T193 50T201 52T207 57T213 61V578Z" transform="translate(1000, 0)"></path><path data-c="2E" d="M78 60Q78 84 95 102T138 120Q162 120 180 104T199 61Q199 36 182 18T139 0T96 17T78 60Z" transform="translate(1500, 0)"></path><path data-c="39" d="M352 287Q304 211 232 211Q154 211 104 270T44 396Q42 412 42 436V444Q42 537 111 606Q171 666 243 666Q245 666 249 666T257 665H261Q273 665 286 663T323 651T370 619T413 560Q456 472 456 334Q456 194 396 97Q361 41 312 10T208 -22Q147 -22 108 7T68 93T121 149Q143 149 158 135T173 96Q173 78 164 65T148 49T135 44L131 43Q131 41 138 37T164 27T206 22H212Q272 22 313 86Q352 142 352 280V287ZM244 248Q292 248 321 297T351 430Q351 508 343 542Q341 552 337 562T323 588T293 615T246 625Q208 625 181 598Q160 576 154 546T147 441Q147 358 152 329T172 282Q197 248 244 248Z" transform="translate(1778, 0)"></path></g></g></g></svg><mjx-assistive-mml role="presentation" unselectable="on" display="inline"><math xmlns="http://www.w3.org/1998/Math/MathML"><mrow><mo>£</mo></mrow><mn>761.9</mn></math></mjx-assistive-mml></mjx-container></span> billion, 2016</div>
<ul class="preview-paragraph-433 preview-line 433 434 435 436 437 438 439" data_line_start="433" data_line_end="439" data_line="433,440" count_line="7">
<li>Pensions (20%)</li>
<li>Health care (18%)</li>
<li>Education (11 %)</li>
<li>Defence (6%)</li>
<li>Welfare (15%)</li>
<li>Remainder (30%)</li>
</ul>
<div class="preview-paragraph-440 preview-line 440" data_line_start="440" data_line_end="440" data_line="440,441" count_line="1"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-52.jpg?height=782&amp;width=796&amp;top_left_y=740&amp;top_left_x=495" alt="" data-align="center"></figure></div>
<div class="preview-paragraph-442 preview-line 442" data_line_start="442" data_line_end="442" data_line="442,443" count_line="1">UK TOTAL DIRECT INCOME £716.5 BILLION, 2016</div>
<ul class="preview-paragraph-444 preview-line 444 445 446 447 448" data_line_start="444" data_line_end="448" data_line="444,449" count_line="5">
<li>Income and Capital Taxes (33%)</li>
<li>National Insurance (18%)</li>
<li>Indirect Taxes (42%)</li>
<li>Business and Other Revenue (7%)</li>
</ul>
<div class="preview-paragraph-449 preview-line 449" data_line_start="449" data_line_end="449" data_line="449,450" count_line="1"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-52.jpg?height=723&amp;width=719&amp;top_left_y=765&amp;top_left_x=1869" alt="" data-align="center"></figure></div>
<div class="preview-paragraph-451 preview-line 451" data_line_start="451" data_line_end="451" data_line="451,452" count_line="1">Any deficit has to be financed by borrowing or printing money</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-453 preview-line 453" id="uk-public-sector-deficit" data_line_start="453" data_line_end="453" data_line="453,454" count_line="1">
UK public sector deficit</h2>
<div class="preview-paragraph-455 preview-line 455" data_line_start="455" data_line_end="455" data_line="455,456" count_line="1">Table: General government deficit, UK, calendar years 2012 to 2019</div>
<div class="table_tabular  preview-paragraph-457 preview-line 457 458 459 460 461 462" style="text-align: center" data_line_start="457" data_line_end="462" data_line="457,463" count_line="6">
<div class="inline-tabular"><table id="tabular">
<tbody>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: center; border-left-style: solid !important; border-left-width: 1px !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">Calendar years</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2012</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2013</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2014</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2015</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2016</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2017</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2018</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top-style: solid !important; border-top-width: 1px !important; width: auto; vertical-align: middle; ">2019</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: center; border-left-style: solid !important; border-left-width: 1px !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">Deficit</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">139.7</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">98.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">103.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">88.0</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">66.8</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">50.8</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">48.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">49.1</td>
</tr>
<tr style="border-top: none !important; border-bottom: none !important;">
<td style="text-align: center; border-left-style: solid !important; border-left-width: 1px !important; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">as % GDP</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">8.2</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">5.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">5.6</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">4.6</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">3.3</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">2.5</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">2.3</td>
<td style="text-align: center; border-right-style: solid !important; border-right-width: 1px !important; border-bottom-style: solid !important; border-bottom-width: 1px !important; border-top: none !important; width: auto; vertical-align: middle; ">2.2</td>
</tr>
</tbody>
</table>
<tsv style="display: none">Calendar years	2012	2013	2014	2015	2016	2017	2018	2019
Deficit	139.7	98.5	103.5	88.0	66.8	50.8	48.5	49.1
as % GDP	8.2	5.5	5.6	4.6	3.3	2.5	2.3	2.2</tsv><table-markdown style="display: none">| Calendar years | 2012 | 2013 | 2014 | 2015 | 2016 | 2017 | 2018 | 2019 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Deficit | 139.7 | 98.5 | 103.5 | 88.0 | 66.8 | 50.8 | 48.5 | 49.1 |
| as % GDP | 8.2 | 5.5 | 5.6 | 4.6 | 3.3 | 2.5 | 2.3 | 2.2 |</table-markdown></div></div>
<div class="preview-paragraph-464 preview-line 464" data_line_start="464" data_line_end="464" data_line="464,465" count_line="1">Source: Office for National Statistics - UK government debt and deficit</div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-466 preview-line 466" id="uk-public-sector-deficit-2" data_line_start="466" data_line_end="466" data_line="466,467" count_line="1">
UK public sector deficit</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-467 preview-line 467" id="graph%3A-general-government-deficit-(net-borrowing)-as-a-percentage-of-gdp%2C-uk" data_line_start="467" data_line_end="467" data_line="467,468" count_line="1">
Graph: General government deficit (net borrowing) as a percentage of GDP, UK</h3>
<div class="preview-paragraph-468 preview-line 468" data_line_start="468" data_line_end="468" data_line="468,469" count_line="1">Quarter 2 (Apr to Jun) 2019 to Quarter 2 (Apr to Jun) 2022</div>
<div class="preview-paragraph-470 preview-line 470 471" data_line_start="470" data_line_end="471" data_line="470,472" count_line="2">The bar graph shows government deficit as a percentage of UK GDP. It increased from about 4 percent in 2019 to 27.9 percent in 2020. It decreased to about 10 percent in 2020, and about 7 percent in 2022.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-54.jpg?height=1020&amp;width=1913&amp;top_left_y=617&amp;top_left_x=668" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-473 preview-line 473" id="uk-public-debt%3A-net" data_line_start="473" data_line_end="473" data_line="473,474" count_line="1">
UK public debt: Net</h2>
<h3 type="subsection" class="sub_section-title preview-paragraph-474 preview-line 474" id="graph%3A-net-debt-as-a-percentage-of-gdp" data_line_start="474" data_line_end="474" data_line="474,475" count_line="1">
<span class="section-number">0.</span><span class="sub_section-number">2.</span> Graph: Net Debt as a percentage of GDP</h3>
<div class="preview-paragraph-475 preview-line 475 476" data_line_start="475" data_line_end="476" data_line="475,477" count_line="2">The line graph shows an increase in Net Debt as a percentage of GDP between 1690 and 1820 (building of the British empire), when it reached 250 percent of GDP, it then decreased to reach 30 percent in 1910. It attained 175 percent of GDP after World was 1, and 230 percent of GDP after world war 2. It declined to about 40 percent in 2000, before increasing to about 75% after the 2008 financial crisis.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-55.jpg?height=1161&amp;width=2492&amp;top_left_y=534&amp;top_left_x=438" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-478 preview-line 478" id="uk-public-debt%3A-gross" data_line_start="478" data_line_end="478" data_line="478,479" count_line="1">
UK public debt: Gross</h2>
<h3 type="subsection" data-unnumbered="true" class="sub_section-title preview-paragraph-479 preview-line 479" id="graph%3A-gross-debt-as-a-%25-of-gdp" data_line_start="479" data_line_end="479" data_line="479,480" count_line="1">
Graph: Gross Debt as a % of GDP</h3>
<div class="preview-paragraph-480 preview-line 480 481" data_line_start="480" data_line_end="481" data_line="480,482" count_line="2">The graph shows that gross debt remained at about 40 percent from 1987 to 2007, then increased to over 80 percent after 2009, and increase to over 100 percent in 2020.<br>
<figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-56.jpg?height=791&amp;width=2054&amp;top_left_y=510&amp;top_left_x=640" alt="" data-align="center"></figure></div>
<div class="preview-paragraph-483 preview-line 483" data_line_start="483" data_line_end="483" data_line="483,484" count_line="1"><figure style="text-align: center"><img src="https://cdn.mathpix.com/cropped/2024_01_16_bfc49829390ae6c1f8e0g-56.jpg?height=185&amp;width=2023&amp;top_left_y=1498&amp;top_left_x=630" alt="" data-align="center"></figure></div>
<h2 type="section" data-unnumbered="true" class="section-title preview-paragraph-485 preview-line 485" id="next-lecture" data_line_start="485" data_line_end="485" data_line="485,486" count_line="1">
Next lecture</h2>
<ul class="preview-paragraph-487 preview-line 487 488 489 490" data_line_start="487" data_line_end="490" data_line="487,491" count_line="4">
<li>Macroeconomics in the long run</li>
<li>Why is today's average Brit more than 10 times richer than 100 years ago?</li>
<li>Why is today's average Brit 50 times richer than the average Ethiopian?</li>
<li>How macroeconomics studies key questions</li>
</ul>

    </div>
  </div>
</body>
</html>
