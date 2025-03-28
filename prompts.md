# PuffChat App UI/UX设计提示词

## 总体需求

请设计一个PuffChat健身饮食App原型，采用现代简约风格设计，集成AI聊天功能。所有页面通过index.html进行展示，提供完整的用户界面流程。设计将分阶段完成，确保内容的完整性和一致性。

## 设计规范

1. **风格**: 现代简约，玻璃拟态(Glassmorphism)设计，渐变背景
2. **主色调**: 使用蓝绿色(#34D399)作为主色，搭配暗灰色(#1F2937)作为文字色
3. **字体**: 使用无衬线字体，如SF Pro或Roboto
4. **图标**: 使用纯图标导航，不含文字标签
5. **布局**: 采用卡片式布局，内容清晰分区
6. **设备尺寸**: 按iPhone尺寸(390x844px)设计

## 分阶段开发提示词

### 第一阶段：基础架构与首页设计

```
请设计PuffChat健身饮食App的HTML原型，采用现代简约风格。
首先创建index.html作为展示页，其中应包含所有App页面的展示框架。

在这第一阶段，请先完成以下内容：
1. 创建基础HTML结构和CSS样式
2. 设计App首页，包含:
   - 顶部用户信息和问候语
   - 今日健身和饮食数据摘要卡片（仅显示已消耗卡路里和已训练时间）
   - AI健身教练推荐模块
   - 快速访问功能区
   - 底部导航栏(仅包含图标，无文字)

使用以下技术:
- HTML5语义化标签
- Tailwind CSS (通过CDN)
- Font Awesome图标
- 玻璃拟态设计风格
- 渐变色背景和动画效果

确保代码结构清晰，添加必要的注释。
```

### 第二阶段：健身页面设计

```
请继续开发PuffChat健身饮食App的HTML原型，现在聚焦于健身页面设计。

健身页面应包含:
1. 顶部标题栏和搜索功能
2. 每周训练目标进度环形图表
3. 今日推荐训练计划卡片(包含难度、时长、主要锻炼部位)
4. 训练分类浏览区域(力量训练、有氧训练、灵活性训练等)
5. 热门训练课程横向滚动列表
6. 保持底部导航栏仅显示图标，中间为聊天功能入口

应用玻璃拟态效果和渐变色背景，保持与首页设计风格一致。
确保更新index.html以同时展示首页和健身页面。
```

### 第三阶段：饮食页面设计

```
请继续开发PuffChat健身饮食App的HTML原型，现在聚焦于饮食页面设计。

饮食页面应包含:
1. 顶部标题栏和过滤选项
2. 今日营养摄入进度卡片(蛋白质、碳水、脂肪)
3. 推荐膳食计划(早餐、午餐、晚餐)
4. 水分摄入追踪器
5. AI营养师建议模块
6. 食谱推荐和收藏区域
7. 与其他页面一致的图标导航栏

保持玻璃拟态设计风格，使用独特的渐变色表示饮食相关内容。
更新index.html以同时展示首页、健身页面和饮食页面。
```

### 第四阶段：AI聊天页面设计

```
请继续开发PuffChat健身饮食App的HTML原型，现在聚焦于AI聊天页面设计。

AI聊天页面应包含:
1. 公共聊天窗口界面，用于与AI健身教练和营养师交流
2. 聊天对象选择功能（AI健身教练、营养师、健康顾问）
3. 聊天历史记录展示区域
4. 消息输入框和发送按钮
5. 滑动动画效果，点击底部聊天图标时向上滑出
6. 关闭按钮，可返回上一页面

设计应体现出科技感和现代感的结合，使用蓝色调表示AI相关内容。
更新index.html，添加AI聊天页面展示。
```

### 第五阶段：个人中心页面设计

```
请继续开发PuffChat健身饮食App的HTML原型，完成个人中心页面设计。

个人中心页面应包含:
1. 用户资料概览(头像、用户名、关注/粉丝数据)
2. 数据统计卡片(消耗卡路里、累计训练、体重变化、体脂率)
3. 健康服务模块(健康报告、预约服务、客户服务)
4. 与其他页面一致的图标导航栏

注意：不包含会员等级和徽章功能。

保持玻璃拟态设计风格，使用中性色调。
更新index.html，添加个人中心页面，完成所有页面的展示。
```

### 第六阶段：细节完善与交互设计

```
请对PuffChat健身饮食App的HTML原型进行细节完善和简单交互设计。

细节完善内容包括:
1. 添加渐变背景和玻璃拟态效果
2. 实现卡片悬停动画效果
3. 添加适当的阴影和层次感
4. 确保底部导航栏在所有页面保持一致，仅使用图标
5. 优化AI聊天页面的弹出动画
6. 完善index.html中的布局，确保所有页面清晰可见

所有设计保持现代简约风格，增加适当的微交互提升用户体验。
```

## 特殊考虑

1. **一致性**: 确保所有页面使用统一的设计语言和导航模式
2. **简化导航**: 底部导航栏仅使用图标，中间的聊天图标作为AI聊天入口
3. **功能聚焦**: 专注于核心健身、饮食功能，不包含心率监测、会员等级、徽章系统
4. **玻璃拟态**: 所有卡片和模块使用玻璃拟态效果，提升视觉质感
5. **渐变色彩**: 使用渐变背景和按钮，增强视觉吸引力

## 参考元素

1. **健身追踪**: 环形进度条、每周目标完成度
2. **饮食记录**: 营养成分比例图表、水分摄入进度
3. **AI功能**: 聊天界面、快速切换AI角色、对话历史
4. **数据可视化**: 简洁的图表和统计信息
5. **导航系统**: 清晰的图标导航，中间突出聊天入口 