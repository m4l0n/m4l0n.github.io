---
layout: "post"
title : "DSTR Assignment Roadmap"
categories: assignment
permalink: "/dstr-roadmap/"
---

<html>
  <head>
    <meta charset="UTF-8" />
    <title>Data Structures</title>
    <style source-path="global-text-editor-styles">.mde-cm-wrapper .CodeMirror {
      font-size: 13px;
      font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;
      font-weight: normal;
      line-height: 1.5;
    }
    .mde-preview pre code, .mde-preview code {
      font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,Courier,monospace;
    }</style><style source-path="global-preview-styles">.mde-preview {
      font-size: 15px
    }</style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\admonition\styles\admonition.less" priority="0">.admonition {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
}
.admonition > summary {
  cursor: pointer;
}
.admonition > .custom-block-body {
  margin: 1em 0;
}
.admonition-icon,
.admonition-note > .custom-block-heading:before,
.admonition-info > .custom-block-heading:before,
.admonition-danger > .custom-block-heading:before,
.admonition-warning > .custom-block-heading:before,
.admonition-success > .custom-block-heading:before,
.admonition-fail > .custom-block-heading:before,
.admonition-question > .custom-block-heading:before,
.admonition-abstract > .custom-block-heading:before,
.admonition-example > .custom-block-heading:before {
  position: absolute;
  left: 1.2rem;
  font-family: "FontAwesome";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  width: 24px;
  display: inline-block;
  line-height: 1;
  text-transform: none;
  letter-spacing: normal;
  text-align: center;
  word-wrap: normal;
  white-space: nowrap;
  direction: ltr;
  /* Support for all WebKit browsers. */
  -webkit-font-smoothing: antialiased;
  /* Support for Safari and Chrome. */
  text-rendering: optimizeLegibility;
  /* Support for Firefox. */
  -moz-osx-font-smoothing: grayscale;
  /* Support for IE. */
  font-feature-settings: 'liga';
}
.admonition-title,
.admonition-note > .custom-block-heading,
.admonition-info > .custom-block-heading,
.admonition-danger > .custom-block-heading,
.admonition-warning > .custom-block-heading,
.admonition-success > .custom-block-heading,
.admonition-fail > .custom-block-heading,
.admonition-question > .custom-block-heading,
.admonition-abstract > .custom-block-heading,
.admonition-example > .custom-block-heading,
.admonition-spoiler > .custom-block-heading {
  margin: 0 -1.2rem;
  padding: 0.8rem 1.2rem 0.8rem 4rem;
  border-bottom: 0.1rem solid rgba(68, 138, 255, 0.1);
  background-color: rgba(68, 138, 255, 0.1);
  font-weight: 700;
}
.admonition-note {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #448aff;
}
.admonition-note > summary {
  cursor: pointer;
}
.admonition-note > .custom-block-body {
  margin: 1em 0;
}
.admonition-note > .custom-block-heading {
  background-color: rgba(68, 138, 255, 0.1);
}
.admonition-note > .custom-block-heading:before {
  color: #448aff;
  content: "\f249";
}
.admonition-info {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #009688;
}
.admonition-info > summary {
  cursor: pointer;
}
.admonition-info > .custom-block-body {
  margin: 1em 0;
}
.admonition-info > .custom-block-heading {
  background-color: rgba(0, 150, 136, 0.1);
}
.admonition-info > .custom-block-heading:before {
  color: #009688;
  content: "\f05a";
}
.admonition-danger {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #c2185b;
}
.admonition-danger > summary {
  cursor: pointer;
}
.admonition-danger > .custom-block-body {
  margin: 1em 0;
}
.admonition-danger > .custom-block-heading {
  background-color: rgba(194, 24, 91, 0.1);
}
.admonition-danger > .custom-block-heading:before {
  color: #c2185b;
  content: "\f0e7";
}
.admonition-warning {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #ff9100;
}
.admonition-warning > summary {
  cursor: pointer;
}
.admonition-warning > .custom-block-body {
  margin: 1em 0;
}
.admonition-warning > .custom-block-heading {
  background-color: rgba(255, 145, 0, 0.1);
}
.admonition-warning > .custom-block-heading:before {
  color: #ff9100;
  content: "\f071";
}
.admonition-success {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #00c853;
}
.admonition-success > summary {
  cursor: pointer;
}
.admonition-success > .custom-block-body {
  margin: 1em 0;
}
.admonition-success > .custom-block-heading {
  background-color: rgba(0, 200, 83, 0.1);
}
.admonition-success > .custom-block-heading:before {
  color: #00c853;
  content: "\f00c";
}
.admonition-fail {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #d32f2f;
}
.admonition-fail > summary {
  cursor: pointer;
}
.admonition-fail > .custom-block-body {
  margin: 1em 0;
}
.admonition-fail > .custom-block-heading {
  background-color: rgba(211, 47, 47, 0.1);
}
.admonition-fail > .custom-block-heading:before {
  color: #d32f2f;
  content: "\f00d";
}
.admonition-question {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #64dd17;
}
.admonition-question > summary {
  cursor: pointer;
}
.admonition-question > .custom-block-body {
  margin: 1em 0;
}
.admonition-question > .custom-block-heading {
  background-color: rgba(100, 221, 23, 0.1);
}
.admonition-question > .custom-block-heading:before {
  color: #64dd17;
  content: "\f059";
}
.admonition-abstract {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #00b0ff;
}
.admonition-abstract > summary {
  cursor: pointer;
}
.admonition-abstract > .custom-block-body {
  margin: 1em 0;
}
.admonition-abstract > .custom-block-heading {
  background-color: rgba(0, 176, 255, 0.1);
}
.admonition-abstract > .custom-block-heading:before {
  color: #00b0ff;
  content: "\f02d";
}
.admonition-example {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #651fff;
}
.admonition-example > summary {
  cursor: pointer;
}
.admonition-example > .custom-block-body {
  margin: 1em 0;
}
.admonition-example > .custom-block-heading {
  background-color: rgba(101, 31, 255, 0.1);
}
.admonition-example > .custom-block-heading:before {
  color: #651fff;
  content: "\f0cb";
}
.admonition-spoiler {
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 1.5625em 0;
  padding: 0 1.2rem;
  border-left: 0.4rem solid #448aff;
  border-radius: 0.2rem;
  overflow: auto;
  border-left-color: #455a64;
}
.admonition-spoiler > summary {
  cursor: pointer;
}
.admonition-spoiler > .custom-block-body {
  margin: 1em 0;
}
.admonition-spoiler > .custom-block-heading {
  padding-left: 1rem;
  background-color: rgba(69, 90, 100, 0.1);
}
</style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\code-title\styles\code-title.css" priority="0">span.code-title {
  color: var(--text-color);
  background-color: rgba(120, 120, 120, 0.25);
  font-size: 0.9em;
  padding: 0 0.4em;
  display: inline-block;
  line-height: 1.6em;
  border-radius: 3px 0 3px 0;
  margin-bottom: -1.6em;
  display: table;
  position: relative;
  z-index: 2;
  vertical-align: center;
}

div.with-title-block {
  padding-top: 1.6em;
}

pre > div > code {
  font-size: 100% !important;
}
</style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\copy-code-to-clipboard\styles\copy-code-to-clipboard.less" priority="0">.copy-code-to-clipboard {
  position: relative;
  display: inline;
}
pre {
  position: relative;
}
pre .copy-code-to-clipboard {
  position: unset;
}
div.copy-code-to-clipboard .copy-code-to-clipboard-button.ui.button {
  padding: 0.25em 0.5em 0.25em 0.5em !important;
  margin-left: 0.3rem;
  display: none;
}
pre div.copy-code-to-clipboard .copy-code-to-clipboard-button {
  position: absolute;
  top: 0;
  right: 0;
}
pre:hover div.copy-code-to-clipboard .copy-code-to-clipboard-button.ui.button,
div.copy-code-to-clipboard:hover .copy-code-to-clipboard-button.ui.button {
  display: inline-block;
}
span.copy-code-to-clipboard-button-hide-icon {
  display: none;
}
span.copy-code-to-clipboard-button-hide-text {
  display: none;
}
</style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\dblclick-expansion-image\styles\dblclick-expansion-image.less" priority="0">.dblclick-expansion-image {
  width: 100% !important;
}
.dblclick-expansion-image .header {
  display: none !important;
}
.dblclick-expansion-image .content {
  padding: 0px !important;
  background: rgba(0, 0, 0, 0.87) !important;
  text-align: center;
}
.dblclick-expansion-image .actions {
  display: none !important;
}
</style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\link-card\styles\link-card.less" priority="0">/* Variables */
.link-card-anchor:hover {
  text-decoration: none !important;
}
.link-card {
  border: 1px solid rgba(120, 120, 120, 0.6);
  border-radius: 10px;
  display: flex;
  overflow: hidden;
  align-items: center;
  height: 7em;
}
.link-card:hover {
  background-color: rgba(160, 160, 160, 0.1);
}
.link-card-image {
  display: flex;
  height: 7em;
  min-height: 7em;
}
.link-card-image.square {
  width: 7em;
  min-width: 7em;
}
.link-card-image.square > img {
  width: 7em;
  height: 7em;
  object-fit: cover;
}
.link-card-image.wide {
  width: 13.3em;
  min-width: 13.3em;
}
.link-card-image.wide > img {
  width: 13.3em;
  height: 7em;
  object-fit: cover;
}
.link-card-image > span {
  justify-content: center;
  align-items: center;
  margin: auto;
}
.link-card-image > span::before {
  font-family: "FontAwesome";
  content: "\f15c";
  font-size: 2em;
  color: rgba(120, 120, 120, 0.8);
  vertical-align: middle;
}
.link-card-text {
  display: flex;
  flex-direction: column;
  height: 7em;
  justify-content: center;
  padding: 0 0.8em;
  border-left: 1px solid rgba(120, 120, 120, 0.6);
}
.link-card-title {
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
  color: var(--text-color);
  line-height: 1.3em;
  margin-bottom: 3px;
}
.link-card-description {
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
  color: var(--light-text-color);
  font-size: 0.9em;
  line-height: 1.2em;
}
</style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\paste-url\styles\paste-url.less" priority="0"></style><style source-path="C:\Users\nigel\AppData\Roaming\inkdrop\packages\plantuml\styles\plantuml.less" priority="0">.plantuml-container {
  padding: 0 !important;
  background: none !important;
  border: none !important;
  border-radius: 0 !important;
}
.plantuml-error {
  white-space: normal;
}
</style><style source-path="C:\Users\nigel\AppData\Local\inkdrop\app-5.5.0\resources\app.asar\node_modules\github-preview\styles\github-markdown.css" context="inkdrop-preview" priority="1">@font-face {
  font-family: octicons-anchor;
  src: url(data:font/woff;charset=utf-8;base64,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) format('woff');
}
.mde-preview {
  -webkit-text-size-adjust: 100%;
  text-size-adjust: 100%;
  color: #333;
  font-family: "Helvetica Neue", Helvetica, "Segoe UI", Arial, freesans, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  line-height: 1.6;
  word-wrap: break-word;
}
.mde-preview:before {
  display: table;
  content: "";
}
.mde-preview:after {
  display: table;
  clear: both;
  content: "";
}
.mde-preview a {
  background-color: transparent;
}
.mde-preview a:active,
.mde-preview a:hover {
  outline: 0;
}
.mde-preview strong {
  font-weight: bold;
  color: black;
}
.mde-preview em {
  color: black;
}
.mde-preview h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
.mde-preview img {
  border: 0;
}
.mde-preview hr {
  box-sizing: content-box;
  height: 0;
}
.mde-preview pre {
  overflow: auto;
}
.mde-preview code,
.mde-preview kbd,
.mde-preview pre {
  font-family: SFMono-Regular, Consolas, Liberation Mono, Menlo, Courier, monospace;
  font-size: 1em;
}
.mde-preview input {
  color: inherit;
  font: inherit;
  margin: 0;
}
.mde-preview html input[disabled] {
  cursor: default;
}
.mde-preview input {
  line-height: normal;
}
.mde-preview input[type="checkbox"] {
  box-sizing: border-box;
  padding: 0;
}
.mde-preview table {
  border-collapse: collapse;
  border-spacing: 0;
}
.mde-preview td,
.mde-preview th {
  padding: 0;
}
.mde-preview * {
  box-sizing: border-box;
}
.mde-preview input {
  font: 13px / 1.4 Helvetica, arial, nimbussansl, liberationsans, freesans, clean, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
.mde-preview a {
  color: #4078c0;
  text-decoration: none;
}
.mde-preview a:hover,
.mde-preview a:active {
  text-decoration: underline;
}
.mde-preview hr {
  height: 0;
  margin: 15px 0;
  overflow: hidden;
  background: transparent;
  border: 0;
  border-bottom: 1px solid #ddd;
}
.mde-preview hr:before {
  display: table;
  content: "";
}
.mde-preview hr:after {
  display: table;
  clear: both;
  content: "";
}
.mde-preview h1,
.mde-preview h2,
.mde-preview h3,
.mde-preview h4,
.mde-preview h5,
.mde-preview h6 {
  margin-top: 0;
  padding-top: 15px;
  margin-bottom: 15px;
  line-height: 1.1;
}
.mde-preview h1 {
  font-size: 30px;
}
.mde-preview h2 {
  font-size: 21px;
}
.mde-preview h3 {
  font-size: 16px;
}
.mde-preview h4 {
  font-size: 14px;
}
.mde-preview h5 {
  font-size: 12px;
}
.mde-preview h6 {
  font-size: 11px;
}
.mde-preview blockquote {
  margin: 0;
}
.mde-preview ul,
.mde-preview ol {
  padding: 0;
  margin-top: 0;
  margin-bottom: 0;
}
.mde-preview ol ol,
.mde-preview ul ol {
  list-style-type: lower-roman;
}
.mde-preview ul ul ol,
.mde-preview ul ol ol,
.mde-preview ol ul ol,
.mde-preview ol ol ol {
  list-style-type: lower-alpha;
}
.mde-preview dd {
  margin-left: 0;
}
.mde-preview code {
  font-size: 12px;
}
.mde-preview pre {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 12px;
}
.mde-preview .select::-ms-expand {
  opacity: 0;
}
.mde-preview .octicon {
  font: normal normal normal 16px/1 octicons-anchor;
  display: inline-block;
  text-decoration: none;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.mde-preview .octicon-link:before {
  content: '\f05c';
}
.mde-preview .mde-preview > *:first-child {
  margin-top: 0 !important;
}
.mde-preview .mde-preview > *:last-child {
  margin-bottom: 0 !important;
}
.mde-preview a:not([href]) {
  color: inherit;
  text-decoration: none;
}
.mde-preview .anchor {
  display: inline-block;
  padding-right: 2px;
  margin-left: -18px;
}
.mde-preview .anchor:focus {
  outline: none;
}
.mde-preview h1 .octicon-link,
.mde-preview h2 .octicon-link,
.mde-preview h3 .octicon-link,
.mde-preview h4 .octicon-link,
.mde-preview h5 .octicon-link,
.mde-preview h6 .octicon-link {
  color: #000;
  vertical-align: middle;
  visibility: hidden;
}
.mde-preview h1:hover .anchor,
.mde-preview h2:hover .anchor,
.mde-preview h3:hover .anchor,
.mde-preview h4:hover .anchor,
.mde-preview h5:hover .anchor,
.mde-preview h6:hover .anchor {
  text-decoration: none;
}
.mde-preview h1:hover .anchor .octicon-link,
.mde-preview h2:hover .anchor .octicon-link,
.mde-preview h3:hover .anchor .octicon-link,
.mde-preview h4:hover .anchor .octicon-link,
.mde-preview h5:hover .anchor .octicon-link,
.mde-preview h6:hover .anchor .octicon-link {
  visibility: visible;
}
.mde-preview h1 {
  padding-bottom: 0.3em;
  font-size: 2.25em;
  line-height: 1.2;
  border-bottom: 1px solid #eee;
}
.mde-preview h1 .anchor {
  line-height: 1;
}
.mde-preview h2 {
  padding-bottom: 0.3em;
  font-size: 1.75em;
  line-height: 1.225;
  border-bottom: 1px solid #eee;
}
.mde-preview h2 .anchor {
  line-height: 1;
}
.mde-preview h3 {
  font-size: 1.5em;
  line-height: 1.43;
}
.mde-preview h3 .anchor {
  line-height: 1.2;
}
.mde-preview h4 {
  font-size: 1.25em;
}
.mde-preview h4 .anchor {
  line-height: 1.2;
}
.mde-preview h5 {
  font-size: 1em;
}
.mde-preview h5 .anchor {
  line-height: 1.1;
}
.mde-preview h6 {
  font-size: 1em;
  color: #777;
}
.mde-preview h6 .anchor {
  line-height: 1.1;
}
.mde-preview p,
.mde-preview blockquote,
.mde-preview ul,
.mde-preview ol,
.mde-preview dl,
.mde-preview table,
.mde-preview pre {
  margin-top: 0;
  margin-bottom: 16px;
}
.mde-preview hr {
  height: 4px;
  padding: 0;
  margin: 16px 0;
  background-color: #e7e7e7;
  border: 0 none;
}
.mde-preview ul,
.mde-preview ol {
  padding-left: 2em;
}
.mde-preview ul ul,
.mde-preview ul ol,
.mde-preview ol ol,
.mde-preview ol ul {
  margin-top: 0;
  margin-bottom: 0;
}
.mde-preview li > p {
  margin: 0;
}
.mde-preview dl {
  padding: 0;
}
.mde-preview dl dt {
  padding: 0;
  margin-top: 16px;
  font-size: 1em;
  font-style: italic;
  font-weight: bold;
}
.mde-preview dl dd {
  padding: 0 16px;
  margin-bottom: 16px;
}
.mde-preview blockquote {
  padding: 0 15px;
  color: #777;
  border-left: 4px solid #ddd;
}
.mde-preview blockquote > :first-child {
  margin-top: 0;
}
.mde-preview blockquote > :last-child {
  margin-bottom: 0;
}
.mde-preview table {
  display: block;
  width: 100%;
  overflow: auto;
  word-break: keep-all;
}
.mde-preview table th {
  font-weight: bold;
}
.mde-preview table th,
.mde-preview table td {
  padding: 6px 13px;
  border: 1px solid #ddd;
}
.mde-preview table tr {
  background-color: #fff;
  border-top: 1px solid #ccc;
}
.mde-preview table tr:nth-child(2n) {
  background-color: #f8f8f8;
}
.mde-preview img {
  max-width: 100%;
  box-sizing: content-box;
  background-color: #fff;
}
.mde-preview code {
  padding: 0;
  padding-top: 0.2em;
  padding-bottom: 0.2em;
  margin: 0;
  font-size: 85%;
  background-color: rgba(0, 0, 0, 0.04);
  border-radius: 3px;
}
.mde-preview code:before,
.mde-preview code:after {
  letter-spacing: -0.2em;
  content: "\00a0";
}
.mde-preview pre > code {
  padding: 0;
  margin: 0;
  font-size: 100%;
  word-break: normal;
  white-space: pre;
  background: transparent;
  border: 0;
}
.mde-preview pre {
  padding: 16px;
  overflow: auto;
  word-wrap: normal;
  font-size: 85%;
  line-height: 1.45;
  background-color: #f7f7f7;
  border-radius: 3px;
}
.mde-preview pre code {
  display: inline;
  max-width: initial;
  padding: 0;
  margin: 0;
  overflow: initial;
  line-height: inherit;
  word-wrap: normal;
  background-color: transparent;
  border: 0;
}
.mde-preview pre code:before,
.mde-preview pre code:after {
  content: normal;
}
.mde-preview kbd {
  display: inline-block;
  padding: 3px 5px;
  font-size: 11px;
  line-height: 10px;
  color: #555;
  vertical-align: middle;
  background-color: #fcfcfc;
  border: solid 1px #ccc;
  border-bottom-color: #bbb;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 #bbb;
}
.mde-preview .cm-header {
  color: blue;
}
.mde-preview .cm-quote {
  color: #090;
  font-style: italic;
}
.mde-preview .cm-negative {
  color: #d44;
}
.mde-preview .cm-positive {
  color: #292;
}
.mde-preview .cm-header,
.mde-preview .cm-strong {
  font-weight: bold;
}
.mde-preview .cm-em {
  font-style: italic;
}
.mde-preview .cm-link {
  text-decoration: underline;
}
.mde-preview .cm-strikethrough {
  text-decoration: line-through;
}
.mde-preview .cm-keyword {
  color: #333;
  font-weight: bold;
}
.mde-preview .cm-atom {
  color: #219;
}
.mde-preview .cm-number {
  color: #164;
}
.mde-preview .cm-def {
  color: #00f;
}
.mde-preview .cm-property {
  color: #00c;
}
.mde-preview .cm-operator {
  color: #708;
}
.mde-preview .cm-variable-2 {
  color: #05a;
}
.mde-preview .cm-variable-3,
.mde-preview .cm-s-default .cm-type {
  color: #085;
}
.mde-preview .cm-comment {
  color: #a50;
  font-style: italic;
}
.mde-preview .cm-string {
  color: #a11;
}
.mde-preview .cm-string-2 {
  color: #f50;
}
.mde-preview .cm-meta {
  color: #555;
}
.mde-preview .cm-qualifier {
  color: #555;
}
.mde-preview .cm-builtin {
  color: #30a;
}
.mde-preview .cm-bracket {
  color: #997;
}
.mde-preview .cm-tag {
  color: #170;
}
.mde-preview .cm-attribute {
  color: #00c;
}
.mde-preview .cm-hr {
  color: #999;
}
.mde-preview .cm-link {
  color: #00c;
}
.mde-preview .cm-error {
  color: #f00;
}
.mde-preview kbd {
  display: inline-block;
  padding: 3px 5px;
  font: 11px Consolas, "Liberation Mono", Menlo, Courier, monospace;
  line-height: 10px;
  color: #555;
  vertical-align: middle;
  background-color: #fcfcfc;
  border: solid 1px #ccc;
  border-bottom-color: #bbb;
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 #bbb;
}
.mde-preview .task-list-item {
  list-style-type: none;
}
.mde-preview .task-list-item + .task-list-item {
  margin-top: 0px;
}
.mde-preview .task-list-item input {
  /* margin: 0 0.35em 0.25em -1.6em; */
  vertical-align: middle;
}
.mde-preview :checked + .radio-label {
  z-index: 1;
  position: relative;
  border-color: #4078c0;
}
@media print {
  .mde-preview table {
    overflow: hidden;
    word-break: break-word;
  }
  .mde-preview pre > code {
    word-wrap: break-word;
    white-space: pre-wrap;
  }
}
</style><style source-path="C:\Users\nigel\AppData\Local\inkdrop\app-5.5.0\resources\app.asar\node_modules\github-preview\styles\github-markdown-dark.css" context="inkdrop-preview" priority="1">body[class*="dark-ui"] .mde-preview {
  color: rgba(255, 255, 255, 0.7);
}
body[class*="dark-ui"] .mde-preview a {
  background-color: transparent;
}
body[class*="dark-ui"] .mde-preview img {
  border: 0;
}
body[class*="dark-ui"] .mde-preview input {
  color: inherit;
}
body[class*="dark-ui"] .mde-preview a {
  color: #6987AF;
}
body[class*="dark-ui"] .mde-preview strong,
body[class*="dark-ui"] .mde-preview em {
  color: white;
}
body[class*="dark-ui"] .mde-preview h1,
body[class*="dark-ui"] .mde-preview h2,
body[class*="dark-ui"] .mde-preview h3,
body[class*="dark-ui"] .mde-preview h4,
body[class*="dark-ui"] .mde-preview h5,
body[class*="dark-ui"] .mde-preview h6 {
  color: rgba(255, 255, 255, 0.875);
}
body[class*="dark-ui"] .mde-preview h6 {
  color: rgba(255, 255, 255, 0.625);
}
body[class*="dark-ui"] .mde-preview h1,
body[class*="dark-ui"] .mde-preview h2 {
  border-bottom-color: rgba(255, 255, 255, 0.4);
}
body[class*="dark-ui"] .mde-preview hr {
  background-color: rgba(255, 255, 255, 0.3);
}
body[class*="dark-ui"] .mde-preview blockquote {
  color: rgba(255, 255, 255, 0.4);
  border-left: 4px solid rgba(255, 255, 255, 0.1);
}
body[class*="dark-ui"] .mde-preview table th {
  background-color: rgba(255, 255, 255, 0.1);
}
body[class*="dark-ui"] .mde-preview table th,
body[class*="dark-ui"] .mde-preview table td {
  border: 1px solid rgba(255, 255, 255, 0.25);
}
body[class*="dark-ui"] .mde-preview table tr {
  background-color: transparent;
  border-top: 1px solid rgba(255, 255, 255, 0.25);
}
body[class*="dark-ui"] .mde-preview table tr:nth-child(2n) {
  background-color: rgba(255, 255, 255, 0.05);
}
body[class*="dark-ui"] .mde-preview img {
  background-color: transparent;
}
body[class*="dark-ui"] .mde-preview .highlight pre,
body[class*="dark-ui"] .mde-preview pre {
  background-color: rgba(0, 0, 0, 0.1);
}
body[class*="dark-ui"] .mde-preview .cm-header {
  color: #ffcc66;
}
body[class*="dark-ui"] .mde-preview .cm-quote {
  color: #969896;
  font-style: italic;
}
body[class*="dark-ui"] .mde-preview .cm-negative {
  color: #d44;
}
body[class*="dark-ui"] .mde-preview .cm-positive {
  color: #292;
}
body[class*="dark-ui"] .mde-preview .cm-header,
body[class*="dark-ui"] .mde-preview .cm-strong {
  font-weight: bold;
}
body[class*="dark-ui"] .mde-preview .cm-em {
  font-style: italic;
}
body[class*="dark-ui"] .mde-preview .cm-link {
  text-decoration: underline;
}
body[class*="dark-ui"] .mde-preview .cm-strikethrough {
  text-decoration: line-through;
}
body[class*="dark-ui"] .mde-preview .cm-keyword {
  color: #cc99cc;
  font-weight: normal;
}
body[class*="dark-ui"] .mde-preview .cm-atom {
  color: #8abeb7;
}
body[class*="dark-ui"] .mde-preview .cm-number {
  color: #f99157;
}
body[class*="dark-ui"] .mde-preview .cm-def {
  color: #b5bd68;
}
body[class*="dark-ui"] .mde-preview .cm-property {
  color: #b5bd68;
}
body[class*="dark-ui"] .mde-preview .cm-operator {
  color: #cc99cc;
}
body[class*="dark-ui"] .mde-preview .cm-variable-2 {
  color: #4A664A;
}
body[class*="dark-ui"] .mde-preview .cm-variable-3,
body[class*="dark-ui"] .mde-preview .cm-type {
  color: rgba(255, 255, 255, 0.8);
}
body[class*="dark-ui"] .mde-preview .cm-comment {
  color: #969896;
  font-style: italic;
}
body[class*="dark-ui"] .mde-preview .cm-string {
  color: #8abeb7;
}
body[class*="dark-ui"] .mde-preview .cm-string-2 {
  color: #8abeb7;
}
body[class*="dark-ui"] .mde-preview .cm-meta {
  color: #f99157;
}
body[class*="dark-ui"] .mde-preview .cm-qualifier {
  color: #555;
}
body[class*="dark-ui"] .mde-preview .cm-builtin {
  color: #8abeb7;
}
body[class*="dark-ui"] .mde-preview .cm-bracket {
  color: #f99157;
}
body[class*="dark-ui"] .mde-preview .cm-tag {
  color: #a54543;
}
body[class*="dark-ui"] .mde-preview .cm-attribute {
  color: #fda331;
}
body[class*="dark-ui"] .mde-preview .cm-hr {
  color: #999;
}
body[class*="dark-ui"] .mde-preview .cm-link {
  color: #f99157;
}
body[class*="dark-ui"] .mde-preview .cm-error {
  color: #f00;
}
</style>
  </head>
  <body class="mde-preview">
    <div><h1 data-line="1" data-line-end="1">Tasks</h1>
<h2 data-line="2" data-line-end="2">Linked-List Program - Ang Ru Xian &amp; Wong Jie Hao</h2>
<h3 data-line="4" data-line-end="4">Visualisation of Data Structure</h3>
<ul class="contains-task-list" data-line="6" data-line-end="6">
<li class="task-list-item" data-line="6" data-line-end="6"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="6" data-line-end="6">Done (Powell)</strong></li>
</ul>
<p data-line="9" data-line-end="9"><strong data-line="9" data-line-end="9">Tuition Center Linked List</strong></p>
<p data-line="11" data-line-end="11"><img src="https://imgur.com/tZC9H8f.png" alt="clipboard.png"></p>
<p data-line="13" data-line-end="13"><strong data-line="13" data-line-end="13">Tutor Linked List</strong></p>
<p data-line="15" data-line-end="15"><img src="https://imgur.com/IKlawod.png" alt="clipboard.png"></p>
<h3 data-line="17" data-line-end="17">Functions</h3>
<div class="custom-block admonition-info" data-line="19" data-line-end="22"><div class="custom-block-heading">Requirements</div><div class="custom-block-body"><ul>
<li>Workflow Diagram in Flowchart</li>
<li>Explanation of algorithm</li>
<li>Justification of decision</li>
</ul></div></div>
<br data-line="24" data-line-end="24">
<ul class="contains-task-list" data-line="26" data-line-end="26">
<li class="task-list-item" data-line="26" data-line-end="26"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong data-line="26" data-line-end="26">Done</strong></li>
</ul>























































<table data-line="28" data-line-end="38"><thead data-line="28" data-line-end="28"><tr data-line="28" data-line-end="28"><th data-line="28" data-line-end="28">Function</th><th data-line="28" data-line-end="28">Member</th><th data-line="28" data-line-end="28">Status</th></tr></thead><tbody data-line="30" data-line-end="38"><tr data-line="30" data-line-end="30"><td data-line="30" data-line-end="30">Add a Tutor Record</td><td data-line="30" data-line-end="30">Ang Ru Xian</td><td data-line="30" data-line-end="30">☑</td></tr><tr data-line="31" data-line-end="31"><td data-line="31" data-line-end="31">Display All Records</td><td data-line="31" data-line-end="31">Ang Ru Xian</td><td data-line="31" data-line-end="31">☑</td></tr><tr data-line="32" data-line-end="32"><td data-line="32" data-line-end="32">Search a Tutor by Tutor ID</td><td data-line="32" data-line-end="32">Ang Ru Xian</td><td data-line="32" data-line-end="32">☑</td></tr><tr data-line="33" data-line-end="33"><td data-line="33" data-line-end="33">Search Tutors by overall performance (Rating)</td><td data-line="33" data-line-end="33">Ang Ru Xian</td><td data-line="33" data-line-end="33">☑</td></tr><tr data-line="34" data-line-end="34"><td data-line="34" data-line-end="34">Sort and display by Tutors ID in ascending order</td><td data-line="34" data-line-end="34">Wong Jie Hao</td><td data-line="34" data-line-end="34">☐</td></tr><tr data-line="35" data-line-end="35"><td data-line="35" data-line-end="35">Sort and display by Tutors Hourly Pay Rate in ascending order</td><td data-line="35" data-line-end="35">Wong Jie Hao</td><td data-line="35" data-line-end="35">☐</td></tr><tr data-line="36" data-line-end="36"><td data-line="36" data-line-end="36">Sort and display by Tutors Overall Performance in ascending order</td><td data-line="36" data-line-end="36">Wong Jie Hao</td><td data-line="36" data-line-end="36">☐</td></tr><tr data-line="37" data-line-end="37"><td data-line="37" data-line-end="37">Modify a Tutor Record</td><td data-line="37" data-line-end="37">Ang Ru Xian</td><td data-line="37" data-line-end="37">☑</td></tr><tr data-line="38" data-line-end="38"><td data-line="38" data-line-end="38">Delete Tutor Record</td><td data-line="38" data-line-end="38">Wong Jie Hao</td><td data-line="38" data-line-end="38">☐</td></tr></tbody></table>
<h3 data-line="42" data-line-end="42">Struct</h3>
<ul class="contains-task-list" data-line="44" data-line-end="44">
<li class="task-list-item" data-line="44" data-line-end="44"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="44" data-line-end="44">Done (Tong Zheng Hee)</strong></li>
</ul>
<span class="code-title"> Structs in Linked-List Program</span>
<pre data-line="46" data-line-end="92"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-comment">// Doubly Linked List - Contains prev pointer and tail pointer</span><span class="">
</span><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">Tutors</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorName</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">DateJoined</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">DateTerminated</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">float</span><span class="">  </span><span class="cm-variable">HourlyPayRate</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Phone</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Address</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-comment">/*</span><span class="">
</span><span class="">  </span><span class="cm-comment">One tutor is allowed to teach on the subject in their specialized field only. Must check for condition Specialization==SubjectName during implementation</span><span class="">
</span><span class="">  </span><span class="cm-comment">*/</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Specialization</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">SubjectCode</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">SubjectName</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">float</span><span class=""> </span><span class="cm-variable">rating</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCenterName</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCenterCode</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="">
</span><span class="">  </span><span class="cm-variable">Tutors</span><span class="cm-operator">*</span><span class=""> </span><span class="cm-variable">next</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">Tutors</span><span class="cm-operator">*</span><span class=""> </span><span class="cm-variable">prev</span><span class="">;</span><span class="">
</span><span class="">}</span><span class="cm-operator">*</span><span class="cm-variable">head</span><span class=""> </span><span class="cm-operator">*</span><span class="cm-variable">tail</span><span class="">;</span><span class="">

</span><span class="cm-comment">// Singly Linked List - Contains only head pointer (without tail pointer) and no prev pointer</span><span class="">
</span><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">TuitionCenter</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreCode</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Location</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">PhoneNumber</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">AvailableSlots</span><span class="">; </span><span class="cm-comment">//Total number of Tutors it can accomodate</span><span class="">
</span><span class="">  </span><span class="">
</span><span class="">  </span><span class="cm-variable">TuitionCenter</span><span class="cm-operator">*</span><span class=""> </span><span class="cm-variable">next</span><span class="">;</span><span class="">
</span><span class="">} </span><span class="cm-operator">*</span><span class="cm-variable">head</span><span class="">


</span><span class="cm-comment">// Logic for Pagination</span><span class="">
</span><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">PageInfo</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">page</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">pageCount</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">size</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">startIndex</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">endIndex</span><span class="">;</span><span class="">
</span><span class="">}</span><span class="">
</span></code></div><div class="copy-code-to-clipboard"><button type="button" class="ui button copy-code-to-clipboard-button"><span class=""><i class="fa fa-clipboard"></i></span><span class="copy-code-to-clipboard-button-hide-text">Copy</span></button></div></pre>
<div class="custom-block admonition-note" data-line="94" data-line-end="97"><div class="custom-block-heading">Justification</div><div class="custom-block-body"><p>Line 2 to 23 in the figure above shows the struct for Tutor Linked List containing various attributes of Tutor. They represent the data members in each node. *next and *prev attribute on line 21 and 22 represents the pointer which points to the next node and previous node in the linked list respectively.*head and *tail on line 23 represents the head pointer and tail pointer, which points to the first node and last node in the linked list respectively.</p><p>Line 26 to 35 in the figure above shows the struct for Tuition Center Linked List containing various attributes of a Tuition Center. Just like Tutor Linked List, each attributes represent a data member in each node. *next on line 34 represents a pointer which points to the next node in the Tuition Center linked list, while *head on line 35 represents a pointer which points to the first node of the linked list. </p></div></div>
<h3 data-line="99" data-line-end="99">Classes</h3>
<ul class="contains-task-list" data-line="101" data-line-end="101">
<li class="task-list-item" data-line="101" data-line-end="101"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="101" data-line-end="101">Done (Ang Ru Xian)</strong></li>
</ul>
<span class="code-title">Classes in Linked-List Program</span>
<pre data-line="103" data-line-end="126"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-keyword">class</span><span class=""> </span><span class="cm-def">TutorLinkedList</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="cm-keyword">public</span><span class="">:</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">addTutor</span><span class="">(</span><span class="cm-variable">Tutor</span><span class=""> </span><span class="cm-variable">tutor</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">displayPatron</span><span class="">();</span><span class="">
</span><span class="">  </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">displayInList</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">searchTutorByID</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">searchTutorByRating</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Rating</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">sortTutorByID</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">sortTutorByPay</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">sortTutorByRating</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">modifyTutor</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">deleteTutor</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">);</span><span class="">
</span><span class="">  </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">checkTerminationDate</span><span class="">();</span><span class="">
</span><span class="">};</span><span class="">

</span><span class="cm-keyword">class</span><span class=""> </span><span class="cm-def">TuitionCenterLinkedList</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="cm-keyword">public</span><span class="">:</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">checkVacancy</span><span class="">();</span><span class="">
</span><span class="">  </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">generateReport</span><span class="">();</span><span class="">
</span><span class="">}</span><span class="">
</span></code></div><div class="copy-code-to-clipboard"><button type="button" class="ui button copy-code-to-clipboard-button"><span class=""><i class="fa fa-clipboard"></i></span><span class="copy-code-to-clipboard-button-hide-text">Copy</span></button></div></pre>
<div class="custom-block admonition-note" data-line="128" data-line-end="129"><div class="custom-block-heading">Justification</div><div class="custom-block-body"><p>Line 1 to 15 in the figure above shows the class structure for Tutor Linked List. Line 17 to 22 shows the class structure for Tuition Center Linked List. Both classes contain various functions required in the application to fulfill the requirements specified by the admin manager of eXcel Tuition Center. The public keyword indicates that the functions below it are accessible by other classes.</p></div></div>
<h3 data-line="131" data-line-end="131">Proposal</h3>
<div class="custom-block admonition-note" data-line="133" data-line-end="138"><div class="custom-block-heading">1. Explanation of Singly Linked List (Tuition Center)</div><div class="custom-block-body"><ul>
<li>What is it</li>
<li>Components</li>
<li>Why we chose this</li>
<li>Benefits</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong>Done (Wong Jie Hao)</strong></li>
</ul></div></div>
<br data-line="140" data-line-end="140">
<div class="custom-block admonition-note" data-line="142" data-line-end="147"><div class="custom-block-heading">2. Explanation of Doubly Linked List (Tutor)</div><div class="custom-block-body"><ul>
<li>What is it</li>
<li>Components</li>
<li>Why we chose this</li>
<li>Benefits</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong>Done (Wong Jie Hao)</strong></li>
</ul></div></div>
<br data-line="149" data-line-end="149">
<div class="custom-block admonition-note" data-line="152" data-line-end="154"><div class="custom-block-heading">3. Explanation of Classes &amp; Struct</div><div class="custom-block-body"><ul>
<li>Justifications</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong>Done (Ang Ru Xian)</strong></li>
</ul></div></div>
<br data-line="156" data-line-end="156">
<hr data-line="158" data-line-end="158">
<br data-line="160" data-line-end="160">
<h2 data-line="162" data-line-end="162">Array Program - Tong Zheng Hee</h2>
<h3 data-line="164" data-line-end="164">Visualisation of Data Structure</h3>
<ul class="contains-task-list" data-line="166" data-line-end="166">
<li class="task-list-item" data-line="166" data-line-end="166"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="166" data-line-end="166">Done (Powell)</strong></li>
</ul>
<p data-line="169" data-line-end="169"><strong data-line="169" data-line-end="169">Tuition Center Array</strong></p>
<p data-line="171" data-line-end="171"><img src="https://imgur.com/VSiFRWF.png" alt="clipboard.png"></p>
<p data-line="174" data-line-end="174"><strong data-line="174" data-line-end="174">Tuition Center Linked List</strong></p>
<p data-line="176" data-line-end="176"><img src="data:image/png;base64,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WMvLy0tLS0VPAQDzItfm7he/+MX//d///fVf/3XRgyyszz///OjoSLEBsKjk2vuwtLT06aefFj3Fwrp7927RIwDAHPmoAQBAaHINACA0uQYAEJpcAwAITa4BAIQm1wAAQpNrAAChyTUAgNDkGgBAaHINACA0uQYAEJpcAwAITa4BAIQm1xSZJysAABP0SURBVAAAQpNrAAChyTUAgNDkGgBAaHINACA0uQYAEJpcAwAITa4BAIQm1wAAQpNrAAChyTUAgNDkGgBAaHINACA0uQYAEJpcAwAITa4BAIQm1wAAQpNrAAChyTUAgNDkGgBAaHINACA0uQYAEJpcAwAITa4BAIQm17go61ar3azoKQCAKbl2Ywya6cR3b6lBM02bg+s67OXAe+MTAYCr3Sl6AN7MoFk/7IzzVilJBs3mINmtfYeL1Xbz/PoOu8YTAYCX2a7dPLXdSasNmmmz261eWLlls1fO7bdOVnNptZudbMNOX710Zzc97MxRl52Vdavl9mjULp9e43TbdubY2TjnxraDA4ArybUborbbXztbRBO9veRRnud53l9rb3azJMm6m3sb48lLSf20kOqHncmr+UGrdOai+czsApfeenJEI6lsrJdeOuvJ+sG4U6l0xuevnSRJ1q2e3HfcOayfzN5rP92aXLJXF2wAcAW5dmPUdvM8H2/snW22xtY0kGr3G6On4yR7sjfZc6VpWu8lh88mK67HvUloveR0FVfvvf7ug2b9sPNocrc3PWv8dHQyYKm11RjtPZnM3ehP9oO1+403/dMDwO0l126WUusg7592z2Ua/ZPl14Vt10VZd7O9Nj163Km85shBs570D2ax9qZnvWTtk9fOAwBcRq7dDFm3OntqmD07POme3s5kz5Z1d3qV1XJSWt+o9B5ffLxYXq1cGnjjp6PKajlJkiQZPGyPXnPvetI/+WzDG541ue9swJMJAYC3JdduhlJrK6lPHkCW22sn7dTYSDZnrx20SklSaj3qHNYvfHqg1HrUSaaPSM+++W32frg0TetJ41XPJbMne6OkVz/5aMAlZ5XWN5KX31iXlFoHJ4eeTAgAvKU09yMX5mx/f397e3s4HF73hQfN9PH9/Dv9RI/FsLKyMhwOl5eXix4EAObCdg0AIDQ/Jvfmqu3mNmsAsPhs1wAAQpNrAAChyTUAgNDkGgBAaHINACA0uQYA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" alt="clipboard.png"></p>
<h3 data-line="178" data-line-end="178">Functions</h3>
<div class="custom-block admonition-info" data-line="180" data-line-end="183"><div class="custom-block-heading">Requirements</div><div class="custom-block-body"><ul>
<li>Workflow Diagram in Flowchart</li>
<li>Explanation of algorithm</li>
<li>Justification of decision</li>
</ul></div></div>
<br data-line="185" data-line-end="185">
<ul class="contains-task-list" data-line="187" data-line-end="187">
<li class="task-list-item" data-line="187" data-line-end="187"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong data-line="187" data-line-end="187">Done</strong></li>
</ul>























































<table data-line="189" data-line-end="199"><thead data-line="189" data-line-end="189"><tr data-line="189" data-line-end="189"><th data-line="189" data-line-end="189">Function</th><th data-line="189" data-line-end="189">Status</th><th data-line="189" data-line-end="189">Member</th></tr></thead><tbody data-line="191" data-line-end="199"><tr data-line="191" data-line-end="191"><td data-line="191" data-line-end="191">Add a Tutor Record</td><td data-line="191" data-line-end="191">☑</td><td data-line="191" data-line-end="191">Ang Ru Xian</td></tr><tr data-line="192" data-line-end="192"><td data-line="192" data-line-end="192">Display All Records</td><td data-line="192" data-line-end="192">☑</td><td data-line="192" data-line-end="192">Ang Ru Xian</td></tr><tr data-line="193" data-line-end="193"><td data-line="193" data-line-end="193">Search a Tutor by Tutor ID</td><td data-line="193" data-line-end="193">☐</td><td data-line="193" data-line-end="193">Tong Zheng Hee</td></tr><tr data-line="194" data-line-end="194"><td data-line="194" data-line-end="194">Search Tutors by overall performance (Rating)</td><td data-line="194" data-line-end="194">☐</td><td data-line="194" data-line-end="194">Tong Zheng Hee</td></tr><tr data-line="195" data-line-end="195"><td data-line="195" data-line-end="195">Sort and display by Tutors ID in ascending order</td><td data-line="195" data-line-end="195">☐</td><td data-line="195" data-line-end="195">Tong Zheng Hee</td></tr><tr data-line="196" data-line-end="196"><td data-line="196" data-line-end="196">Sort and display by Tutors Hourly Pay Rate in ascending order</td><td data-line="196" data-line-end="196">☐</td><td data-line="196" data-line-end="196">Tong Zheng Hee</td></tr><tr data-line="197" data-line-end="197"><td data-line="197" data-line-end="197">Sort and display by Tutors Overall Performance in ascending order</td><td data-line="197" data-line-end="197">☐</td><td data-line="197" data-line-end="197">Tong Zheng Hee</td></tr><tr data-line="198" data-line-end="198"><td data-line="198" data-line-end="198">Modify a Tutor Record</td><td data-line="198" data-line-end="198">☑</td><td data-line="198" data-line-end="198">Ang Ru Xian</td></tr><tr data-line="199" data-line-end="199"><td data-line="199" data-line-end="199">Delete a Tutor Record</td><td data-line="199" data-line-end="199">☑</td><td data-line="199" data-line-end="199">Ang Ru Xian</td></tr></tbody></table>
<h3 data-line="202" data-line-end="202">Struct</h3>
<ul class="contains-task-list" data-line="204" data-line-end="204">
<li class="task-list-item" data-line="204" data-line-end="204"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="204" data-line-end="204">Done (Tong Zheng Hee)</strong></li>
</ul>
<span class="code-title"> Structs in Array Program</span>
<pre data-line="206" data-line-end="239"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">Tutors</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Name</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Phone</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Address</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">DateJoined</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">DateTerminated</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">float</span><span class="">  </span><span class="cm-variable">HourlyPayRate</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">SubjectCode</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">SubjectName</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">float</span><span class=""> </span><span class="cm-variable">rating</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreCode</span><span class="">;</span><span class="">
</span><span class="">}</span><span class="">

</span><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">TuitionCenter</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreCode</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Location</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">PhoneNumber</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">AvailableSlots</span><span class="">; </span><span class="cm-comment">//Total number of Tutors it can accomodate</span><span class="">
</span><span class="">} </span><span class="">


</span><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">PageInfo</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">page</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">pageCount</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">size</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">startIndex</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">endIndex</span><span class="">;</span><span class="">
</span><span class="">}</span><span class="">
</span></code></div><div class="copy-code-to-clipboard"><button type="button" class="ui button copy-code-to-clipboard-button"><span class=""><i class="fa fa-clipboard"></i></span><span class="copy-code-to-clipboard-button-hide-text">Copy</span></button></div></pre>
<h3 data-line="241" data-line-end="241">Classes (Done by Nigel)</h3>
<ul class="contains-task-list" data-line="243" data-line-end="243">
<li class="task-list-item" data-line="243" data-line-end="243"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="243" data-line-end="243">Done (Nigel)</strong></li>
</ul>
<span class="code-title">Classes in Array Program</span>
<pre data-line="245" data-line-end="268"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-keyword">class</span><span class=""> </span><span class="cm-def">TutorArray</span><span class=""> </span><span class="">
</span><span class="">{</span><span class="">
</span><span class="cm-keyword">public</span><span class="">:</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">addTutor</span><span class="">(</span><span class="cm-variable">Tutor</span><span class=""> </span><span class="cm-variable">tutor</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">displayPatron</span><span class="">();</span><span class="">
</span><span class="">  </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">displayInList</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">searchTutorByID</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">searchTutorByRating</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">Rating</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">sortTutorByID</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">sortTutorByPay</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">sortTutorByRating</span><span class="">();</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">modifyTutor</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">);</span><span class="">
</span><span class="">    </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">deleteTutor</span><span class="">(</span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TutorID</span><span class="">);</span><span class="">
</span><span class="">  </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">checkTerminationDate</span><span class="">();</span><span class="">
</span><span class="">};</span><span class="">

</span><span class="cm-keyword">class</span><span class=""> </span><span class="cm-def">TuitionCenterArray</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="cm-keyword">public</span><span class="">:</span><span class="">
</span><span class="">  </span><span class="cm-type">int</span><span class=""> </span><span class="cm-variable">checkVacancy</span><span class="">();</span><span class="">
</span><span class="">  </span><span class="cm-type">void</span><span class=""> </span><span class="cm-variable">generateReport</span><span class="">();</span><span class="">
</span><span class="">}</span><span class="">
</span></code></div><div class="copy-code-to-clipboard"><button type="button" class="ui button copy-code-to-clipboard-button"><span class=""><i class="fa fa-clipboard"></i></span><span class="copy-code-to-clipboard-button-hide-text">Copy</span></button></div></pre>
<h3 data-line="270" data-line-end="270">Proposal</h3>
<div class="custom-block admonition-note" data-line="272" data-line-end="277"><div class="custom-block-heading">1. Explanation of Array (Tuition Center and Tutor)</div><div class="custom-block-body"><ul>
<li>What is it</li>
<li>Components</li>
<li>Why we chose this</li>
<li>Benefits</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong>Done (Tong Zheng Hee)</strong></li>
</ul></div></div></div>
  </body>
</html>


