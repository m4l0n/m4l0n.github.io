---
layout: "post"
title : "DSTR Assignment Roadmap"
categories: assignment
permalink: "/dstr-roadmap/"
---

<!doctype html>
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
<p data-line="11" data-line-end="11"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAmMAAAGVCAIAAAA9iWGzAAAXwElEQVR4nO3cP2wb5/kH8OMPaSGgBZoAAep2kguqMBQBcdugcKWh8kh5UVBUQCc5C9k/KMQMRhYBzmAgg4eKW8UlNdAh0VJ1sJhN7mAh7RK5UF3FYiF5KZwpSeECRpf7DRQpUiQf/XHkE6XPZ0hkinf33Hvv3fd9X9LOpWl69erVe/fuJZy8oaGhTz755NKlS1kXAsBhvZQkyc7Ozvb29vDwcNbFnH1Xr1598uSJpAQYIP+XdQEAcKpJSgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIic7aSslXKlWtZFADDQTmFS1isTE5V625+kHQDZOYVJCQCnyCAlZb0ykWvYm2TWSrmW5ky09VppObNaATgrTmdSrpVHmvE3Ul5rvFavzC7NbKVpmqYryVQzKwuLadPKWHm2Uk9qpamNha00TdOt0Y1qducAwNlwOpNyvBF1aZqmWwvjSZIkSf3u0lozQKeqycaj3U8y9yaaU9UkSZLacnV85lo+SZIkPzdfzOgEADgzTmdS9lFcaU0g78/lkyRJ6pXZ8thKZ6YCwFdoYJIyf21mvLq8/0uwWw/XxkdHkiRJktrt8lqSJCOj42tLd+tJkiT1yi2rrwA8p4FJyiQ/d2dhY2rfl3cKiytjzSXZpFjcfVvSeGk2mTfNBOA55dI0vXjx4urq6vDwcNbFnH1Xr169efPm5ORk1oUAcFiDM6cEgCxISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIhISgCISEoAiEhKAIi81PjfL37xi6GhoWxLOZJnz549ffr01VdfzbqQo1lfXx+sdgYgl6bp5ubmkydPsq7kaD766KMHDx688847WRdyNENDQ1euXMm6CgCO4KUkSS5dunTp0qWsKzmanZ2dzz77bHJyMutCADjjfE4JABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJABFJCQARSQkAEUkJAJFBSspnz579/ve/f/Lkyb4XP/jgg/X19ayqAuBseynrAo5gaGjo008//c53vnPp0qUkSb744ouf/OQnH3/88YULF7a3t7OuDoCzKZemadY1HMGTJ08uXrz47Nmz9hd/97vflcvlrEoC4GwbpNXXJEkuXLjwy1/+Mn4FAL5CA5aUSZK88847Q0ND/f4IAF+twUvK9kmkCSUAJ23wkjJpm0eaUAJw0gbsGz0tb7/99gcffLC9vS0pAThRuTRNl5eXB+7vIz59+nRzc/ONN97IupCjefDgweuvv551FefCa6+99q9//Wvf16Q5IT/+8Y//9re/ZV3FeaG1X6Ryufzyyy//X5Ikb7/99pdffpl1PUfzzW9+c+Bicmdn569//WvWVZwLX3755a9//esPP/ww60LOhcePH//mN7/5y1/+knUh58KDBw9++9vfPn78OOtCzoU///nPy8vLSetfHpibmxseHs60pLPv3r17//jHP959992sCzn7dnZ2/vjHP16+fFlrvwD37t27d+/eT3/6U639AvzhD3/4+9//Pjs7Ozk5mXUtZ19rRDKQ3+gBgBdGUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSAkBEUgJARFICQERSHk+tlCvVsi6CLJz+S3/6Kzxx9crERKXe55e92yfc5LnezGHVKxOntecelJT1ykRun749pFbKNXtgR0dqe/0IaqUDDxgUfbRtnuNYp99X+Nz8Ci7rQOno/SfWNWqljr3L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" alt="clipboard.png"></p>
<p data-line="13" data-line-end="13"><strong data-line="13" data-line-end="13">Tutor Linked List</strong></p>
<p data-line="15" data-line-end="15"><img src="data:image/png;base64,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" alt="clipboard.png"></p>
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
<p data-line="171" data-line-end="171"><img src="data:image/png;base64,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" alt="clipboard.png"></p>
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

