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
  src: url(data:font/woff;charset=utf-8;base64,d09GRgABAAAAAAYcAA0AAAAACjQAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABGRlRNAAABMAAAABwAAAAca8vGTk9TLzIAAAFMAAAARAAAAFZG1VHVY21hcAAAAZAAAAA+AAABQgAP9AdjdnQgAAAB0AAAAAQAAAAEACICiGdhc3AAAAHUAAAACAAAAAj//wADZ2x5ZgAAAdwAAADRAAABEKyikaNoZWFkAAACsAAAAC0AAAA2AtXoA2hoZWEAAALgAAAAHAAAACQHngNFaG10eAAAAvwAAAAQAAAAEAwAACJsb2NhAAADDAAAAAoAAAAKALIAVG1heHAAAAMYAAAAHwAAACABEAB2bmFtZQAAAzgAAALBAAAFu3I9x/Nwb3N0AAAF/AAAAB0AAAAvaoFvbwAAAAEAAAAAzBdyYwAAAADP2IQvAAAAAM/bz7t4nGNgZGFgnMDAysDB1Ml0hoGBoR9CM75mMGLkYGBgYmBlZsAKAtJcUxgcPsR8iGF2+O/AEMPsznAYKMwIkgMA5REMOXicY2BgYGaAYBkGRgYQsAHyGMF8FgYFIM0ChED+h5j//yEk/3KoSgZGNgYYk4GRCUgwMaACRoZhDwCs7QgGAAAAIgKIAAAAAf//AAJ4nHWMMQrCQBBF/0zWrCCIKUQsTDCL2EXMohYGSSmorScInsRGL2DOYJe0Ntp7BK+gJ1BxF1stZvjz/v8DRghQzEc4kIgKwiAppcA9LtzKLSkdNhKFY3HF4lK69ExKslx7Xa+vPRVS43G98vG1DnkDMIBUgFN0MDXflU8tbaZOUkXUH0+U27RoRpOIyCKjbMCVejwypzJJG4jIwb43rfl6wbwanocrJm9XFYfskuVC5K/TPyczNU7b84CXcbxks1Un6H6tLH9vf2LRnn8Ax7A5WQAAAHicY2BkYGAA4teL1+yI57f5ysDNwgAC529f0kOmWRiYVgEpDgYmEA8AUzEKsQAAAHicY2BkYGB2+O/AEMPCAAJAkpEBFbAAADgKAe0EAAAiAAAAAAQAAAAEAAAAAAAAKgAqACoAiAAAeJxjYGRgYGBhsGFgYgABEMkFhAwM/xn0QAIAD6YBhwB4nI1Ty07cMBS9QwKlQapQW3VXySvEqDCZGbGaHULiIQ1FKgjWMxknMfLEke2A+IJu+wntrt/QbVf9gG75jK577Lg8K1qQPCfnnnt8fX1NRC/pmjrk/zprC+8D7tBy9DHgBXoWfQ44Av8t4Bj4Z8CLtBL9CniJluPXASf0Lm4CXqFX8Q84dOLnMB17N4c7tBo1AS/Qi+hTwBH4rwHHwN8DXqQ30XXAS7QaLwSc0Gn8NuAVWou/gFmnjLrEaEh9GmDdDGgL3B4JsrRPDU2hTOiMSuJUIdKQQayiAth69r6akSSFqIJuA19TrzCIaY8sIoxyrNIrL//pw7A2iMygkX5vDj+G+kuoLdX4GlGK/8Lnlz6/h9MpmoO9rafrz7ILXEHHaAx95s9lsI7AHNMBWEZHULnfAXwG9/ZqdzLI08iuwRloXE8kfhXYAvE23+23DU3t626rbs8/8adv+9DWknsHp3E17oCf+Z48rvEQNZ78paYM38qfk3v/u3l3u3GXN2Dmvmvpf1Srwk3pB/VSsp512bA/GG5i2WJ7wu430yQ5K3nFGiOqgtmSB5pJVSizwaacmUZzZhXLlZTq8qGGFY2YcSkqbth6aW1tRmlaCFs2016m5qn36SbJrqosG4uMV4aP2PHBmB3tjtmgN2izkGQyLWprekbIntJFing32a5rKWCN/SdSoga45EJykyQ7asZvHQ8PTm6cslIpwyeyjbVltNikc2HTR7YKh9LBl9DADC0U/jLcBZDKrMhUBfQBvXRzLtFtjU9eNHKin0x5InTqb8lNpfKv1s1xHzTXRqgKzek/mb7nB8RZTCDhGEX3kK/8Q75AmUM/eLkfA+0Hi908Kx4eNsMgudg5GLdRD7a84npi+YxNr5i5KIbW5izXas7cHXIMAau1OueZhfj+cOcP3P8MNIWLyYOBuxL6DRylJ4cAAAB4nGNgYoAALjDJyIAOWMCiTIxMLDmZedkABtIBygAAAA==) format('woff');
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
<p data-line="6" data-line-end="6"><strong data-line="6" data-line-end="6">(TBD by Powell)</strong></p>
<h3 data-line="8" data-line-end="8">Functions</h3>
<div class="custom-block admonition-info" data-line="10" data-line-end="13"><div class="custom-block-heading">Requirements</div><div class="custom-block-body"><ul>
<li>Workflow Diagram in Flowchart</li>
<li>Explanation of algorithm</li>
<li>Justification of decision</li>
</ul></div></div>
<br data-line="15" data-line-end="15">
<ul class="contains-task-list" data-line="17" data-line-end="17">
<li class="task-list-item" data-line="17" data-line-end="17"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong data-line="17" data-line-end="17">Done</strong></li>
</ul>























































<table data-line="19" data-line-end="29"><thead data-line="19" data-line-end="19"><tr data-line="19" data-line-end="19"><th data-line="19" data-line-end="19">Function</th><th data-line="19" data-line-end="19">Member</th><th data-line="19" data-line-end="19">Status</th></tr></thead><tbody data-line="21" data-line-end="29"><tr data-line="21" data-line-end="21"><td data-line="21" data-line-end="21">Add a Tutor Record</td><td data-line="21" data-line-end="21">Ang Ru Xian</td><td data-line="21" data-line-end="21">☑</td></tr><tr data-line="22" data-line-end="22"><td data-line="22" data-line-end="22">Display All Records</td><td data-line="22" data-line-end="22">Ang Ru Xian</td><td data-line="22" data-line-end="22">☑</td></tr><tr data-line="23" data-line-end="23"><td data-line="23" data-line-end="23">Search a Tutor by Tutor ID</td><td data-line="23" data-line-end="23">Ang Ru Xian</td><td data-line="23" data-line-end="23">☑</td></tr><tr data-line="24" data-line-end="24"><td data-line="24" data-line-end="24">Search Tutors by overall performance (Rating)</td><td data-line="24" data-line-end="24">Ang Ru Xian</td><td data-line="24" data-line-end="24">☑</td></tr><tr data-line="25" data-line-end="25"><td data-line="25" data-line-end="25">Sort and display by Tutors ID in ascending order</td><td data-line="25" data-line-end="25">Wong Jie Hao</td><td data-line="25" data-line-end="25">☐</td></tr><tr data-line="26" data-line-end="26"><td data-line="26" data-line-end="26">Sort and display by Tutors Hourly Pay Rate in ascending order</td><td data-line="26" data-line-end="26">Wong Jie Hao</td><td data-line="26" data-line-end="26">☐</td></tr><tr data-line="27" data-line-end="27"><td data-line="27" data-line-end="27">Sort and display by Tutors Overall Performance in ascending order</td><td data-line="27" data-line-end="27">Wong Jie Hao</td><td data-line="27" data-line-end="27">☐</td></tr><tr data-line="28" data-line-end="28"><td data-line="28" data-line-end="28">Modify a Tutor Record</td><td data-line="28" data-line-end="28">Ang Ru Xian</td><td data-line="28" data-line-end="28">☑</td></tr><tr data-line="29" data-line-end="29"><td data-line="29" data-line-end="29">Delete Tutor Record</td><td data-line="29" data-line-end="29">Wong Jie Hao</td><td data-line="29" data-line-end="29">☐</td></tr></tbody></table>
<h3 data-line="33" data-line-end="33">Struct</h3>
<ul class="contains-task-list" data-line="35" data-line-end="35">
<li class="task-list-item" data-line="35" data-line-end="35"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="35" data-line-end="35">Done (Tong Zheng Hee)</strong></li>
</ul>
<span class="code-title"> Structs in Linked-List Program</span>
<pre data-line="37" data-line-end="84"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-comment">// Doubly Linked List - Contains prev pointer and tail pointer</span><span class="">
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
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreName</span><span class="">;</span><span class="">
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
<div class="custom-block admonition-note" data-line="86" data-line-end="89"><div class="custom-block-heading">Justification</div><div class="custom-block-body"><p>Line 2 to 23 in the figure above shows the struct for Tutor Linked List containing various attributes of Tutor. They represent the data members in each node. *next and *prev attribute on line 21 and 22 represents the pointer which points to the next node and previous node in the linked list respectively.*head and *tail on line 23 represents the head pointer and tail pointer, which points to the first node and last node in the linked list respectively.</p><p>Line 26 to 35 in the figure above shows the struct for Tuition Center Linked List containing various attributes of a Tuition Center. Just like Tutor Linked List, each attributes represent a data member in each node. *next on line 34 represents a pointer which points to the next node in the Tuition Center linked list, while *head on line 35 represents a pointer which points to the first node of the linked list. </p></div></div>
<h3 data-line="91" data-line-end="91">Classes</h3>
<ul class="contains-task-list" data-line="93" data-line-end="93">
<li class="task-list-item" data-line="93" data-line-end="93"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="93" data-line-end="93">Done (Ang Ru Xian)</strong></li>
</ul>
<span class="code-title">Classes in Linked-List Program</span>
<pre data-line="95" data-line-end="118"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-keyword">class</span><span class=""> </span><span class="cm-def">TutorLinkedList</span><span class="">
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
<div class="custom-block admonition-note" data-line="120" data-line-end="121"><div class="custom-block-heading">Justification</div><div class="custom-block-body"><p>Line 1 to 15 in the figure above shows the class structure for Tutor Linked List. Line 17 to 22 shows the class structure for Tuition Center Linked List. Both classes contain various functions required in the application to fulfill the requirements specified by the admin manager of eXcel Tuition Center. The public keyword indicates that the functions below it are accessible by other classes.</p></div></div>
<h3 data-line="123" data-line-end="123">Proposal</h3>
<div class="custom-block admonition-note" data-line="125" data-line-end="130"><div class="custom-block-heading">1. Explanation of Singly Linked List (Tuition Center)</div><div class="custom-block-body"><ul>
<li>What is it</li>
<li>Components</li>
<li>Why we chose this</li>
<li>Benefits</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong>Done (Wong Jie Hao)</strong></li>
</ul></div></div>
<br data-line="132" data-line-end="132">
<div class="custom-block admonition-note" data-line="134" data-line-end="139"><div class="custom-block-heading">2. Explanation of Doubly Linked List (Tutor)</div><div class="custom-block-body"><ul>
<li>What is it</li>
<li>Components</li>
<li>Why we chose this</li>
<li>Benefits</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong>Done (Wong Jie Hao)</strong></li>
</ul></div></div>
<br data-line="141" data-line-end="141">
<div class="custom-block admonition-note" data-line="144" data-line-end="146"><div class="custom-block-heading">3. Explanation of Classes &amp; Struct</div><div class="custom-block-body"><ul>
<li>Justifications</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong>Done (Ang Ru Xian)</strong></li>
</ul></div></div>
<br data-line="148" data-line-end="148">
<hr data-line="150" data-line-end="150">
<br data-line="152" data-line-end="152">
<h2 data-line="154" data-line-end="154">Array Program - Tong Zheng Hee</h2>
<h3 data-line="156" data-line-end="156">Visualisation of Data Structure</h3>
<p data-line="158" data-line-end="158"><strong data-line="158" data-line-end="158">(TBD by Powell)</strong></p>
<ul class="contains-task-list" data-line="160" data-line-end="160">
<li class="task-list-item" data-line="160" data-line-end="160"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong data-line="160" data-line-end="160">Done (Wong Jie Hao)</strong></li>
</ul>
<h3 data-line="162" data-line-end="162">Functions</h3>
<div class="custom-block admonition-info" data-line="164" data-line-end="167"><div class="custom-block-heading">Requirements</div><div class="custom-block-body"><ul>
<li>Workflow Diagram in Flowchart</li>
<li>Explanation of algorithm</li>
<li>Justification of decision</li>
</ul></div></div>
<br data-line="169" data-line-end="169">
<ul class="contains-task-list" data-line="171" data-line-end="171">
<li class="task-list-item" data-line="171" data-line-end="171"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong data-line="171" data-line-end="171">Done</strong></li>
</ul>























































<table data-line="173" data-line-end="183"><thead data-line="173" data-line-end="173"><tr data-line="173" data-line-end="173"><th data-line="173" data-line-end="173">Function</th><th data-line="173" data-line-end="173">Status</th><th data-line="173" data-line-end="173">Member</th></tr></thead><tbody data-line="175" data-line-end="183"><tr data-line="175" data-line-end="175"><td data-line="175" data-line-end="175">Add a Tutor Record</td><td data-line="175" data-line-end="175">☑</td><td data-line="175" data-line-end="175">Ang Ru Xian</td></tr><tr data-line="176" data-line-end="176"><td data-line="176" data-line-end="176">Display All Records</td><td data-line="176" data-line-end="176">☑</td><td data-line="176" data-line-end="176">Ang Ru Xian</td></tr><tr data-line="177" data-line-end="177"><td data-line="177" data-line-end="177">Search a Tutor by Tutor ID</td><td data-line="177" data-line-end="177">☐</td><td data-line="177" data-line-end="177">Tong Zheng Hee</td></tr><tr data-line="178" data-line-end="178"><td data-line="178" data-line-end="178">Search Tutors by overall performance (Rating)</td><td data-line="178" data-line-end="178">☐</td><td data-line="178" data-line-end="178">Tong Zheng Hee</td></tr><tr data-line="179" data-line-end="179"><td data-line="179" data-line-end="179">Sort and display by Tutors ID in ascending order</td><td data-line="179" data-line-end="179">☐</td><td data-line="179" data-line-end="179">Tong Zheng Hee</td></tr><tr data-line="180" data-line-end="180"><td data-line="180" data-line-end="180">Sort and display by Tutors Hourly Pay Rate in ascending order</td><td data-line="180" data-line-end="180">☐</td><td data-line="180" data-line-end="180">Tong Zheng Hee</td></tr><tr data-line="181" data-line-end="181"><td data-line="181" data-line-end="181">Sort and display by Tutors Overall Performance in ascending order</td><td data-line="181" data-line-end="181">☐</td><td data-line="181" data-line-end="181">Tong Zheng Hee</td></tr><tr data-line="182" data-line-end="182"><td data-line="182" data-line-end="182">Modify a Tutor Record</td><td data-line="182" data-line-end="182">☑</td><td data-line="182" data-line-end="182">Ang Ru Xian</td></tr><tr data-line="183" data-line-end="183"><td data-line="183" data-line-end="183">Delete a Tutor Record</td><td data-line="183" data-line-end="183">☑</td><td data-line="183" data-line-end="183">Ang Ru Xian</td></tr></tbody></table>
<h3 data-line="186" data-line-end="186">Struct</h3>
<ul class="contains-task-list" data-line="188" data-line-end="188">
<li class="task-list-item" data-line="188" data-line-end="188"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="188" data-line-end="188">Done (Tong Zheng Hee)</strong></li>
</ul>
<span class="code-title"> Structs in Array Program</span>
<pre data-line="190" data-line-end="225"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">Tutors</span><span class="">
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
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreName</span><span class="">;</span><span class="">
</span><span class="">}</span><span class="">

</span><span class="cm-keyword">struct</span><span class=""> </span><span class="cm-def">TuitionCenter</span><span class="">
</span><span class="">{</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreCode</span><span class="">;</span><span class="">
</span><span class="">  </span><span class="cm-variable">string</span><span class=""> </span><span class="cm-variable">TuitionCentreName</span><span class="">;</span><span class="">
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
<h3 data-line="227" data-line-end="227">Classes (Done by Nigel)</h3>
<ul class="contains-task-list" data-line="229" data-line-end="229">
<li class="task-list-item" data-line="229" data-line-end="229"><span class="ui checkbox"><input type="checkbox" checked=""><label></label></span> <strong data-line="229" data-line-end="229">Done (Nigel)</strong></li>
</ul>
<span class="code-title">Classes in Array Program</span>
<pre data-line="231" data-line-end="254"><div class="with-title-block"><code class="inline cm-s-default"><span class="cm-keyword">class</span><span class=""> </span><span class="cm-def">TutorArray</span><span class=""> </span><span class="">
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
<h3 data-line="256" data-line-end="256">Proposal</h3>
<div class="custom-block admonition-note" data-line="258" data-line-end="263"><div class="custom-block-heading">1. Explanation of Array (Tuition Center and Tutor)</div><div class="custom-block-body"><ul>
<li>What is it</li>
<li>Components</li>
<li>Why we chose this</li>
<li>Benefits</li>
</ul><ul class="contains-task-list">
<li class="task-list-item"><span class="ui checkbox"><input type="checkbox"><label></label></span> <strong>Done (Tong Zheng Hee)</strong></li>
</ul></div></div></div>
  </body>
</html>

