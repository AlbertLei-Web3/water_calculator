# Water Calculation Tools / 水计算工具

This project contains two specialized calculators for industrial water and slurry management applications.

本项目包含两个专业的工业用水和浆料管理应用计算器。

## Files / 文件

### 1. index.html - Slurry Addition Calculator / 浆料添加量计算器
- **Purpose / 目的**: Calculate the amount of additives needed for slurry based on solid content and weight
- **目的**: 根据固含量和重量计算浆料所需的添加剂量

**Features / 功能**:
- Input solid content percentage / 输入固含量百分比
- Input slurry weight in kg / 输入浆料重量（千克）
- Fixed addition ratio of 5.5% (hidden from user) / 固定添加比例5.5%（对用户隐藏）
- Real-time calculation with validation / 带验证的实时计算

### 2. water_calculator.html - Pure Water Addition Calculator / 纯水加入量计算器
- **Purpose / 目的**: Calculate the amount of pure water to be added based on material weight
- **目的**: 根据物料重量计算需要添加的纯水量

**Formula / 公式**: 
```
Pure Water Addition = (Material Weight ÷ 40%) - Material Weight
纯水加入量 = （物料重量 ÷ 40%）- 物料重量
```

**Features / 功能**:
- Input material weight in kg / 输入物料重量（千克）
- Fixed solid content ratio of 40% (hidden from user) / 固定固含量比例40%（对用户隐藏）
- Precision calculation to 4 decimal places / 精确到4位小数的计算
- Input validation and error handling / 输入验证和错误处理

## How to Use / 使用方法

### For Slurry Addition Calculator / 浆料添加量计算器使用方法:
1. Open `index.html` in your web browser / 在网页浏览器中打开 `index.html`
2. Enter the solid content percentage / 输入固含量百分比
3. Enter the slurry weight in kg / 输入浆料重量（千克）
4. Click "计算添加量" to get the result / 点击"计算添加量"获取结果

### For Pure Water Addition Calculator / 纯水加入量计算器使用方法:
1. Open `water_calculator.html` in your web browser / 在网页浏览器中打开 `water_calculator.html`
2. Enter the material weight in kg / 输入物料重量（千克）
3. Click "计算纯水加入量" to get the result / 点击"计算纯水加入量"获取结果

## Technical Details / 技术详情

Both calculators are built with:
两个计算器都使用以下技术构建：

- HTML5 for structure / HTML5用于结构
- CSS3 for styling / CSS3用于样式
- Vanilla JavaScript for calculations / 原生JavaScript用于计算
- Client-side validation / 客户端验证
- Responsive design / 响应式设计

## Browser Compatibility / 浏览器兼容性

- Chrome / 谷歌浏览器
- Firefox / 火狐浏览器
- Safari / 苹果浏览器
- Edge / 微软浏览器
- Mobile browsers / 移动端浏览器 