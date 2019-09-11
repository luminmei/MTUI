# imcat-ui

> Mobile UI for Vue2.0

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

import imcatUi from 'imcat-ui';
import 'imcat-ui/lib/index.css';
Vue.use(imcatUi)

```


### v1.7.22
修改 uploader 组件，增加 props.data 作为上传时附带的参数；增加 props.uploadType 作为选择上传的类型，默认值为 base64 , 可选值为 file ,值为file 时则不能使用微信选择图片和图片压缩等功能。

### v1.7.23
修复 uploader 组件上传成功后的处理出错问题
