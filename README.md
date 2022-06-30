* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background: #002240;
}

.header-wrap {
  margin: 120px 0;
  text-align: center;
  font-family: sans-serif;
  color: #ddd;
}

.header-wrap h1 {
  margin-bottom: 16px;
  font-weight: 300;
  font-size: 46px;
}



/*ace*/
.ace_editor {
	font-size: 14px !important;
}

#ide-parent {
  width: 90%;
  height: auto;
  border-radius: 1em;
  overflow: hidden;
  margin: auto;
  box-shadow: 0 0 10px 1px rgba(0, 0, 0, 0.3);
}

#button-wrapper {
  display: flex;
  width: 100%;
  height: 60px;
}

#button-wrapper button {
  width: 25%;
  border: none;
  background: #00325E;
  cursor: pointer;
  text-transform: uppercase;
  color: #ddd;
  font-family: "Arial", sans-serif;
  letter-spacing: 2px;
  font-size: 13px;
  outline: none;
  transition-duration: 300ms;
}

#button-wrapper button:hover {
  background: #000E1B;
}

#ide-container {
  width: 100%;
  height: 400px;
  overflow: auto;
}

.panel-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
}

#html {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

#css {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

#js {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

#result {
  width: 100%;
  height: 100%;
  background: #002240;
  border: none;
}

.ace-dracula {
  background-color: #162447 !important;
}

.ace-dracula .ace_gutter {
  background: #162447 !important;
}

.ace_scrollbar-h {
  scrollbar-color: #1f4068 #162447 !important;
  scrollbar-width: thin !important;
  cursor: pointer;
}

.ace_scrollbar-v {
  scrollbar-color: #1f4068 #162447 !important;
  scrollbar-width: thin !important;
  cursor: pointer;
}

.ace_scrollbar-h::-webkit-scrollbar {
  border: none;
  height: 0.6em;
}

.ace_scrollbar-h::-webkit-scrollbar-thumb {
  background: #1f4068;
  border: none;
}

.ace_scrollbar-h::-webkit-scrollbar-thumb:hover {
  background: #173458;
}

.ace_scrollbar-h::-webkit-scrollbar-track {
  background: transparent;
}

.ace_scrollbar-v::-webkit-scrollbar {
  border: none;
  width: 0.6em;
}

.ace_scrollbar-v::-webkit-scrollbar-thumb {
  background: #1f4068;
  border: none;
}

.ace_scrollbar-v::-webkit-scrollbar-thumb:hover {
  background: #173458;
}

.ace_scrollbar-v::-webkit-scrollbar-track {
  background: transparent;
}

.description {
  max-width: 500px;
  margin: auto;
  margin-top: 120px;
  margin-bottom: 120px;
  text-align: center;
  color: #ddd;
  font-family: sans-serif;
  font-size: 14px;
}

.description p {
  line-height: 24px;
}

.description svg {
  width: 50px;
  cursor: pointer;
  height: auto;
  margin-top: 24px;
}

.description svg path {
  fill: #e43f5a;
}

.description a {
  color: #e43f5a;
}

.footer {
  text-align: center;
  color: rgba(221, 221, 221, 0.6);
  font-family: sans-serif;
  font-size: 13px;
  background: #000E1B;
  padding: 70px 0;
}

.inner-wrap {
  width: 90%;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}

.inner-wrap img {
  width: 24px;
  height: auto;
}

.inner-wrap a {
  margin-left: 24px;
}

.icons-wrap {
	display: flex;
	align-items: center;
}
