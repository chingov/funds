# 钱多多养鸡场

钱多多养鸡场，可以用来查看您的自选基金的实时估值情况，助您快速获取实时数据。

## 介绍

买了基金后一直想找一款pc端的chrome扩展插件，毕竟股票的交易时间都是在工作日进行的，可惜找不到，便打算自己写一个。扩展插件很适合上班族，不用打开网站，仅以小窗口的形式展示，方便快捷。

输入基金代码添加基金，将基金添加特别关注后，可以以角标的形式展示在浏览器中，更加简便直观。

可以在设置中单独开启显示份额与收益选项，在编辑中输入持有的份额，可以计算出每个基金的实时估值与收益，以及总收益。

## 主要功能

- 实时角标提醒
- 单个基金特别关注
- 角标内容自定义，单个与全部基金，收益额与收益率
- 支持标准与暗色两种主题
- 支持查看最近3/7/30天基金涨跌幅
- 基金列表与配置信息支持导入与导出
- 智能判断节假日，切换休市状态
- 支持设置份额或金额，查看当日估值收益
- 支持设置持仓成本价，查看持有收益
- 支持手动加仓减仓功能
- 交易日更新当日实际净值后，对应基金有 √ 提示
- 支持查看估值走势图，净值、收益等走势图
- 支持支持查看基金的股票持仓明细
- 支持查看基金基本信息与基金经理信息
- 自定义顶部指数内容
- 自定义基金列表展示内容
- 指数与基金拖拽排序功能
- 基金按照指定项排序功能
- 添加基金时支持按拼音、汉字、编码模糊搜索，支持批量添加
- 行情中心展示，两市资金、行业板块、北向资金、南向资金

## 框架介绍

基于[Vue](https://github.com/vuejs/vue) + [Webpack](https://github.com/webpack/webpack )构建的 vue 项目，使用了[vue-web-extension](https://github.com/Kocal/vue-web-extension/tree/v1)模板快速构建Chrome扩展项目，用到了[Element UI](https://github.com/ElemeFE/element)样式库与ECharts图表库。

## 如何使用

执行 `npm i` 安装依赖
然后执行 `npm run build` 生成dist文件夹，浏览器选择“加载已解压的扩展程序”

![主界面1](https://upload-images.jianshu.io/upload_images/1720399-76cf58c2eeb19860.png)

![主界面2](https://gitee.com/rabt/Picture/raw/master/img/20200916120011.png)

![主界面3](https://gitee.com/rabt/Picture/raw/master/img/20200916120012.png)

## 协议许可

在 [GPL-3.0 License](https://github.com/chingov/funds/blob/master/LICENSE) 许可下可用。 有关更多信息，请参见LICENSE文件。
