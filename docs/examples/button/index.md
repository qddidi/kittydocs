<script setup>
    import {Button} from "kitty-ui"
</script>
<style>
    .example{
        border: 1px solid #f5f5f5;
        border-radius: 5px;
        padding:20px
    }
    .k-button {
        margin:10px 5px
    }
    
    details > summary:first-of-type {
        font-size: 10px;
        padding: 8px 0;
        cursor: pointer;
        color: #1989fa;
    }
</style>

# Button 按钮

## 基础用法

使用 type、plain、round 和 circle 来定义按钮的样式。

<div class="example">
    <div>
        <Button>默认按钮</Button>
        <Button type="primary">主要按钮</Button>
        <Button type="success">成功按钮</Button>
        <Button type="info">信息按钮</Button>
        <Button type="warning">警告按钮</Button>
        <Button type="danger">危险按钮</Button>
        <Button type="text">文字按钮</Button>
        <br>
        <br>
        <Button plain>朴素按钮</Button>
        <Button type="primary" plain>主要按钮</Button>
        <Button type="success" plain>成功按钮</Button>
        <Button type="info" plain>信息按钮</Button>
        <Button type="warning" plain>警告按钮</Button>
        <Button type="danger" plain>危险按钮</Button>
        <br>
        <br>
        <Button round>圆角按钮</Button>
        <Button type="primary" round>主要按钮</Button>
        <Button type="success" round>成功按钮</Button>
        <Button type="info" round>信息按钮</Button>
        <Button type="warning" round>警告按钮</Button>
        <Button type="danger" round>危险按钮</Button>
    </div>
</div>

<details>
<summary>展开查看</summary>

```vue
<template>
  <div>
    <Button>默认按钮</Button>
    <Button type="primary">主要按钮</Button>
    <Button type="success">成功按钮</Button>
    <Button type="info">信息按钮</Button>
    <Button type="warning">警告按钮</Button>
    <Button type="danger">危险按钮</Button>
    <Button type="text">文字按钮</Button>
    <br />
    <br />
    <Button plain>朴素按钮</Button>
    <Button type="primary" plain>主要按钮</Button>
    <Button type="success" plain>成功按钮</Button>
    <Button type="info" plain>信息按钮</Button>
    <Button type="warning" plain>警告按钮</Button>
    <Button type="danger" plain>危险按钮</Button>
    <br />
    <br />
    <Button round>圆角按钮</Button>
    <Button type="primary" round>主要按钮</Button>
    <Button type="success" round>成功按钮</Button>
    <Button type="info" round>信息按钮</Button>
    <Button type="warning" round>警告按钮</Button>
    <Button type="danger" round>危险按钮</Button>
  </div>
</template>
<script lang="ts" setup>
import { Button } from "kitty-ui";
</script>
<style>
.k-button {
  margin-right: 10px;
}
</style>
```

</details>

## 禁用状态

<div class="example">
    <div>
        <Button disabled>禁用按钮</Button>
        <Button type="primary" disabled>主要按钮</Button>
        <Button type="success" disabled>成功按钮</Button>
        <Button type="info" disabled>信息按钮</Button>
        <Button type="warning" disabled>警告按钮</Button>
        <Button type="danger" disabled>危险按钮</Button>
        <br>
        <br>
        <Button disabled>禁用按钮</Button>
        <Button type="primary" disabled plain>主要按钮</Button>
        <Button type="success" disabled plain>成功按钮</Button>
        <Button type="info" disabled plain>信息按钮</Button>
        <Button type="warning" disabled plain>警告按钮</Button>
        <Button type="danger" disabled plain>危险按钮</Button>
    </div>
</div>

<details>
<summary>展开查看</summary>

```vue
<template>
  <div>
    <Button disabled>禁用按钮</Button>
    <Button type="primary" disabled>主要按钮</Button>
    <Button type="success" disabled>成功按钮</Button>
    <Button type="info" disabled>信息按钮</Button>
    <Button type="warning" disabled>警告按钮</Button>
    <Button type="danger" disabled>危险按钮</Button>
    <br />
    <br />
    <Button disabled>禁用按钮</Button>
    <Button type="primary" disabled plain>主要按钮</Button>
    <Button type="success" disabled plain>成功按钮</Button>
    <Button type="info" disabled plain>信息按钮</Button>
    <Button type="warning" disabled plain>警告按钮</Button>
    <Button type="danger" disabled plain>危险按钮</Button>
  </div>
</template>
<script lang="ts" setup>
import { Button } from "kitty-ui";
</script>
<style>
.k-button {
  margin-right: 10px;
}
</style>
```

</details>

## 调整尺寸

<div class="example">
    <div>
        <Button>默认按钮</Button>
        <Button size="medium">中等按钮</Button>
        <Button size="small">小型按钮</Button>
        <Button size="mini">超小按钮</Button>
    </div>
</div>

<details>
<summary>展开查看</summary>

```vue
<template>
  <div>
    <Button>默认按钮</Button>
    <Button size="medium">中等按钮</Button>
    <Button size="small">小型按钮</Button>
    <Button size="mini">超小按钮</Button>
  </div>
</template>
<script lang="ts" setup>
import { Button } from "kitty-ui";
</script>
<style>
.k-button {
  margin-right: 10px;
}
</style>
```

</details>
