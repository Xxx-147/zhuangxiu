# 装修效果图生成记录

记录时间：2026-06-04

## 当前状态

已完成本轮图片生成、检查总览和新网站制作。已生成并保存 37 张图：整体俯视 1 张，9 个空间各 4 个方向视图。

## 已完成图片

- `00-overall-isometric.png`：整体俯视图，已重生成，客卫/家政间按无淋浴处理。
- `01-foyer-dining-north.png`
- `02-foyer-dining-south.png`
- `03-foyer-dining-east.png`
- `04-foyer-dining-west.png`
- `05-living-north.png`
- `06-living-south.png`
- `07-living-east.png`
- `08-living-west.png`
- `09-kitchen-north.png`
- `10-kitchen-south.png`
- `11-kitchen-east.png`
- `12-kitchen-west.png`
- `13-upper-bath-north.png`
- `14-upper-bath-south.png`
- `15-upper-bath-east.png`
- `16-upper-bath-west.png`
- `17-guest-bath-housekeeping-north.png`
- `18-guest-bath-housekeeping-south.png`
- `19-guest-bath-housekeeping-east.png`
- `20-guest-bath-housekeeping-west.png`
- `21-master-bedroom-north.png`
- `22-master-bedroom-south.png`
- `23-master-bedroom-east.png`
- `24-master-bedroom-west.png`
- `25-gaming-room-north.png`
- `26-gaming-room-south.png`
- `27-gaming-room-east.png`
- `28-gaming-room-west.png`
- `29-secondary-bedroom-north.png`
- `30-secondary-bedroom-south.png`
- `31-secondary-bedroom-east.png`
- `32-secondary-bedroom-west.png`
- `33-passage-storage-north.png`
- `34-passage-storage-south.png`
- `35-passage-storage-east.png`
- `36-passage-storage-west.png`

## 已确认的核心约束

- 户型方向：北上、南下、东右、西左。
- 客厅：电视在西墙，朝东；沙发在东侧，朝西；南侧大窗。
- 厨房：位于中东侧，约 `3600mm × 2250mm`；西侧入口；北侧/窗边水槽；东侧灶台；入口侧冰箱和高柜。
- 客卫/家政间：位于厨房南侧、主卧北侧，约 `3600mm × 1950mm`；三段式布局：干区台盆、独立马桶小间、尽端家政洗烘收纳；不要生成淋浴房、浴缸、花洒或玻璃淋浴隔断。
- 主卧：位于东南侧，约 `3600mm × 4700mm`；床头靠东墙，床尾朝西；东侧为金属衣柜；南窗前梳妆台。
- 电竞房：位于东北侧，约 `2500mm × 3500mm`；电竞桌在北窗下；椅子朝北；西墙收纳柜；东墙展示墙。

## 已完成网页

新网站：

- `outputs/render-prompt-gallery.html`

辅助检查图：

- `outputs/render-contact-sheet.jpg`

## 后续可选优化

1. 如需更严格施工表达，可继续按单张重生成局部视角。
2. 如需上线，可把 `outputs/render-prompt-gallery.html` 作为 GitHub Pages 或静态站点入口。
