---
title: Taro.setBackgroundTextStyle(option)
sidebar_label: setBackgroundTextStyle
---

动态设置下拉背景字体、loading 图的样式

> [参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/ui/background/wx.setBackgroundTextStyle.html)

## 类型

```tsx
(option: Option) => Promise<CallbackResult>
```

## 参数

### Option

| 参数 | 类型 | 必填 | 说明 |
| --- | --- | :---: | --- |
| textStyle | `"dark" | "light"` | 是 | 下拉背景字体、loading 图的样式。<br /><br />可选值：<br />- 'dark': dark 样式;<br />- 'light': light 样式; |
| complete | `(res: CallbackResult) => void` | 否 | 接口调用结束的回调函数（调用成功、失败都会执行） |
| fail | `(res: CallbackResult) => void` | 否 | 接口调用失败的回调函数 |
| success | `(res: CallbackResult) => void` | 否 | 接口调用成功的回调函数 |

## 示例代码

```tsx
Taro.setBackgroundTextStyle({
  textStyle: 'dark' // 下拉背景字体、loading 图的样式为dark
})
```

## API 支持度

| API | 微信小程序 | 百度小程序 | 支付宝小程序 | 字节跳动小程序 | QQ 小程序 | H5 | React Native | 快应用 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Taro.setBackgroundTextStyle | ✔️ |  |  |  |  |  |  |  |
