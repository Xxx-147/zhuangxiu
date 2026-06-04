# 装修效果图生成暂停记录

记录时间：2026-06-04

## 当前暂停点

已暂停继续生成图片。最后完成并保存的图片是：

- `outputs/generated-renders/25-gaming-room-north.png`

## 已完成图片

- `00-overall-isometric.png`：整体俯视图，候选图。注意：早期生成，客卫/家政间可能仍带有淋浴表达，最终检查时建议优先重生成。
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

## 已确认的核心约束

- 户型方向：北上、南下、东右、西左。
- 客厅：电视在西墙，朝东；沙发在东侧，朝西；南侧大窗。
- 厨房：位于中东侧，约 `3600mm × 2250mm`；西侧入口；北侧/窗边水槽；东侧灶台；入口侧冰箱和高柜。
- 客卫/家政间：位于厨房南侧、主卧北侧，约 `3600mm × 1950mm`；三段式布局：干区台盆、独立马桶小间、尽端家政洗烘收纳；不要生成淋浴房、浴缸、花洒或玻璃淋浴隔断。
- 主卧：位于东南侧，约 `3600mm × 4700mm`；床头靠东墙，床尾朝西；东侧为金属衣柜；南窗前梳妆台。
- 电竞房：位于东北侧，约 `2500mm × 3500mm`；电竞桌在北窗下；椅子朝北；西墙收纳柜；东墙展示墙。

## 待继续任务

1. 继续生成电竞房剩余三张：南视角、东视角、西视角。
2. 生成西北普通次卧四张：北、南、东、西视角。
3. 生成衣帽/过道区四张：北、南、东、西视角。
4. 最终检查已生成图片是否符合统一提示词。
5. 如需修正，优先重生成：
   - `00-overall-isometric.png`：客卫/家政间可能带淋浴。
   - `24-master-bedroom-west.png`：主卧西视角中衣柜方向表达可再优化。
6. 新建网站，把每张图和对应提示词放在同一页面中，并优化网页展示。

