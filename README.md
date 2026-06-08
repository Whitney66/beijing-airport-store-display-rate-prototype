# 🎨 数据报表原型库 (Prototypes)

一个集中管理和展示数据报表高保真原型的GitHub Pages项目。

## 📖 项目特点

- ✅ 使用GitHub Pages实现永久在线托管
- ✅ 支持多个原型并存，互不影响
- ✅ 固定链接，方便分享给其他团队成员
- ✅ 后续修改可直接在原链接上更新
- ✅ 响应式设计，支持不同设备预览

## 🚀 已发布原型

### 1. 北京机场店商品出样率统计表
- **地址**: https://whitney66.github.io/prototypes/bj-airport-sample-rate/
- **描述**: 展示两家门店（7222、7223）的库存分布及商品出样状况
- **功能**:
  - 日期、门店、商品新分类、大类、品牌多维度筛选
  - 包含正品SKU出样率、免值品出样率等关键指标
  - 支持表格固定表头、分页、数据导出
  - 预期展示30行数据

## 📁 项目结构

```
prototypes/
├── index.html                          # 首页 - 原型库导航
├── README.md                           # 项目说明（本文件）
├── .gitignore                          # Git忽略配置
└── bj-airport-sample-rate/
    └── index.html                      # 北京机场店原型页面
```

## 🔄 如何添加新原型

1. 在 `prototypes/` 下创建新文件夹，命名规则：`项目名-类型` (如: `sales-dashboard`)
2. 将原型HTML文件放入该文件夹，命名为 `index.html`
3. 在根目录 `index.html` 的原型列表中添加新卡片
4. 提交到GitHub：
   ```bash
   git add .
   git commit -m "新增原型：xxx"
   git push origin main
   ```
5. 生成分享链接：`https://whitney66.github.io/prototypes/项目名-类型/`

## 🌐 分享原型

每个原型都有独立的永久链接，可以直接分享给：
- 产品团队
- 设计团队
- 开发团队
- 利益相关者

示例分享链接：
- 首页导航：https://whitney66.github.io/prototypes/
- 具体原型：https://whitney66.github.io/prototypes/bj-airport-sample-rate/

## 🛠️ 技术栈

- HTML5 + CSS3
- 原生JavaScript（无需编译）
- GitHub Pages（自动部署）

## 📝 更新日志

### v1.0.0 (2026-06-08)
- ✅ 初始化项目
- ✅ 添加北京机场店商品出样率统计表原型
- ✅ 配置GitHub Pages

## 📞 联系方式

项目维护者：Whitney66  
GitHub: https://github.com/Whitney66/prototypes
