# element-plus-components

## 简介
对element-plus一些组件的二次封装，支持完整引入和按需引入，目前只有pagination、test两个组件

## 使用方法

### 完整引入
```
// main.js
import elementPlusComponents from 'element-plus-components'
createApp(App).use(elementPlusComponents)

// vue template
<pagination
  v-model:currentPage="currentPage"
  :total="total"
  @getList="getListHandle"
  >
</pagination>
```

### 按需导入
```
// vue template
import { pagination } from 'element-plus-components'

<pagination
  v-model:currentPage="currentPage"
  :total="total"
  @getList="getListHandle"
  >
</pagination>
```
# element-plus-components-sca
