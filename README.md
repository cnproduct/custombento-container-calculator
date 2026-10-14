# 耐科便当盒 3D 集装箱装箱装柜智能测算工作台
## Naike Tableware 3D Container Loading Studio & Smart Packing Calculator

[![GitHub Pages Deployment](https://github.com/cnproduct/custombento-container-calculator/actions/workflows/deploy.yml/badge.svg)](https://github.com/cnproduct/custombento-container-calculator/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-008290?style=flat&logo=googlechrome)](https://cnproduct.github.io/custombento-container-calculator/)
[![Factory Partner](https://img.shields.io/badge/Factory-Naike%20Tableware-0ea5b6)](https://www.custombentofactory.com)
[![Audits](https://img.shields.io/badge/Audits-Disney%20FAMA%20%7C%20Coca--Cola%20SGP%20%7C%20Sedex-10b981)](#)

专门为 **晋江市耐克礼品玩具有限公司 (Naike Tableware / [www.custombentofactory.com](https://www.custombentofactory.com))** 定制开发的 B2B 出海 3D 集装箱装柜测算与物理堆码仿真工作台。

---

## 🌐 在线体验地址 (Live Demo)

- **GitHub Pages 演示地址**：[https://cnproduct.github.io/custombento-container-calculator/](https://cnproduct.github.io/custombento-container-calculator/)
- **耐科官方出海独立站**：[https://www.custombentofactory.com](https://www.custombentofactory.com)
- **工厂资质背书**：Disney FAMA (`W128-4829-1`) · Coca-Cola SGP (`ZC421894101`) · Sedex 4-Pillar SMETA · 厦门港 60km 快速集港

---

## ✨ 核心功能与工业级特性

### 1. 🍱 预置耐科 14 大核心品类外箱参数库
免去手动测量输入，系统直接内嵌耐科主力出口产品的标准外箱（Outer Carton）工程数据：
1. **儿童 5 格防漏便当盒 (Bentgo 同款销冠)** · `NK-KB5-001` (54 × 38 × 42 cm, 24 pcs/箱, 14.5 kg)
2. **可注水保冷便当盒 (带冷凝托盘)** · `NK-CHL-002` (48 × 36 × 28 cm, 16 pcs/箱, 12.0 kg)
3. **经典四格成人分餐便当盒** · `NK-CLS4-003` (50 × 36 × 32 cm, 24 pcs/箱, 13.0 kg)
4. **日式双层成人手提便当盒** · `NK-STK2-004` (46 × 39 × 28 cm, 24 pcs/箱, 10.8 kg)
5. **幼童首选人体工学餐盒 (2-5岁)** · `NK-TD4-009` (46 × 32 × 24 cm, 24 pcs/箱, 10.2 kg)
6. **天然小麦秸秆环保三格盒** · `NK-WS3-006` (44 × 42 × 46 cm, 36 pcs/箱, 11.5 kg)
7. **重装 304 不锈钢三格盒** · `NK-SS3-003` (50 × 38 × 32 cm, 20 pcs/箱, 13.8 kg)
8. **黑科技微波 304 不锈钢便当盒** · `NK-MSS-008` (48 × 35 × 39 cm, 24 pcs/箱, 13.2 kg)
9. **TikTok 爆款八格便携零食盒 (Snackle Box)** · `NK-SNK-007` (51 × 34 × 44 cm, 12 pcs/箱, 7.8 kg)
10. **54oz 超大容量沙拉保鲜大碗** · `NK-SLD-005` (61 × 41.5 × 38.5 cm, 18 pcs/箱, 9.2 kg)
11. **600D rPET 环保保温便当包** · `NK-BAG-010` (55 × 43 × 36 cm, 40 pcs/箱, 10.5 kg)
12. **16oz 真空不锈钢保温汤罐** · `NK-THM-011` (42 × 32 × 34 cm, 24 pcs/箱, 9.6 kg)
13. **静音零晃动便携餐具三件套** · `NK-CUT-012` (45 × 28 × 26 cm, 100 sets/箱, 12.0 kg)
14. **食品级折叠硅胶便当盒** · `NK-COL-014` (48 × 36 × 30 cm, 36 pcs/箱, 11.2 kg)

### 2. ⚡ 双模式测算：一键单品满柜 (FCL) 与 多品类混装拼柜 (Mixed Cargo)
- **一键整柜装满 (Fill Full Container)**：自动匹配集装箱容积安全因子（88% 填充率）与限重极限，一秒完成单品大宗满柜规划。
- **多品类拼柜与排柜 (Mixed Packing)**：支持多个品类按不同采购箱数自由拼装，由 EMS 3D 空白最大空间启发式算法自动求解。

### 3. 🚢 国际海运与商务指标测算
- **单只产品平摊海运费**：输入当前航线整柜海运费预算（如 \$2,800），实时计算平摊到每只餐盒的运费成本（如 \$0.134/pc），供海外大买家财务核算。
- **安全载重与超限预警**：实时对照 20GP (21.8T), 40GP (26.68T), 40HQ (26.58T) 安全载重线，杜绝甩柜与海关重货罚金。
- **装载重心偏移监测**：实时计算前后、左右重心偏差率，守护长途海运航行安全。

### 4. 🎮 交互式 3D 集装箱渲染 (Three.js WebGL)
- **自由交互**：鼠标左键拖拽旋转、滚轮多级平滑缩放、右键平移；支持手机平板双指手势。
- **多视角快速切换**：等轴 3D、箱门正视图、侧面透视图、正上方俯视图。
- **射线检测 (Raycasting Tooltip)**：鼠标划过集装箱内的任意纸箱，即时弹出浮动卡片展示 SKU、箱规、只数、重量、空间三维坐标与层数。
- **高级透视**：柜壁半透明切换、箱体描边、分层爆炸图（Exploded View）、垂直高度切片（Slice Slider）、逐箱入库动态流水线动画。

### 5. 📄 外贸装柜方案与装箱单一键导出 (Loading Manifest)
- 弹出标准的《耐科外贸集装箱装载方案与装箱单 (Loading Manifest & Packing List)》。
- 包含工厂抬头（Jinjiang Naike Gifts Co., Ltd.）、集装箱号、出货港（Xiamen Port XMN）、品类 SKU 明细、总箱数、总件数、总体积 CBM 与总毛重。
- 支持一键调起浏览器打印，另存为专业 PDF 报表。

### 6. 🌐 中英双语一键切换 (Bilingual Support)
- 支持中文 / English 一键即时切换，方便国内业务员核算，亦可直接分享给欧美大买家采购团队协同决策。

---

## 🛠️ 本地运行开发

纯原生前端架构，无需安装 Node.js 或构建工具：

```bash
# 克隆仓库
git clone https://github.com/cnproduct/custombento-container-calculator.git
cd custombento-container-calculator

# 启动本地静态服务器 (任何工具均可)
python3 -m http.server 8080

# 访问浏览器
open http://localhost:8080
```

---

## 📦 项目文件结构

```
custombento-container-calculator/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions 自动化部署 Pages 工作流
├── images/                     # 耐科主力产品实拍图、外箱图与官方 Logo
│   ├── logo.png
│   ├── eazylunch_kids_5_bento.jpg
│   ├── eazylunch_chill_icepack_bento.jpg
│   ├── eazylunch_4_bento_classic.jpg
│   ├── eazylunch_stackable_2tier_bento.jpg
│   ├── eazylunch_toddler_bento.jpg
│   ├── wheat_straw_bento_box.jpg
│   ├── eazylunch_stainless_3_bento.jpg
│   ├── microwave_stainless_bento_hero.jpg
│   ├── snackle_box_hero.jpg
│   ├── salad_bento_bowl_hero.jpg
│   ├── insulated_lunch_bag.jpg
│   ├── eazylunch_thermos_jar_combo.jpg
│   ├── rattle_free_cutlery_hero.jpg
│   └── collapsible_silicone_bento_hero.jpg
├── index.html                  # 3D 装柜测算工作台主程序 (HTML5 + CSS3 + Three.js)
└── README.md                   # 详细项目技术与业务说明文档
```

---

## 🏭 工厂联系方式 (Naike Tableware)

- **企业名称**：晋江市耐克礼品玩具有限公司 (Jinjiang Naike Gifts Co., Ltd.)
- **官方独立站**：[https://www.custombentofactory.com](https://www.custombentofactory.com)
- **业务邮箱**：`info@naikegroup.com`
- **业务电话 / WhatsApp**：`+86 135 9922 0505`
- **工厂地址**：中国福建省泉州晋江市内坑镇紫东工业区 18 号 (距厦门港 60 公里)
