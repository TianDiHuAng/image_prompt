# PoseWear 衣姿 · 全站参考库（姿势 / 发型 / 服装 / 动画服装 / 人像）

> 来源站点：**https://posewear.pages.dev/#pose** （开源仓库：https://github.com/atuizz/posewear ，作者 @giaaibusi）
> 本文件 = "可授权部分全量收录 + 禁止批量抓的部分给结构与在线入口"。抓取/整理日期：2026-11-22。
> 图片均为 AI 生成。**使用前先看第 0 节授权说明。**

## 0. 全站板块与授权（务必先看）

| 板块 | 数量 | 内容 | 授权 / 限制 | 本库处理 |
|---|---|---|---|---|
| 姿势 `/pose` | 站点 98 组(490 图)，master 文本 288 条 | 全身姿态，每姿势 5 机位角度，中/英提示词 | 上游"未标明授权，转载商用请联系作者" | **文本全量收录**（第 1 节） |
| 深度姿势(depth) | 约250–300 姿势(4 系统线) | 姿态**深度图**，每姿势5角度，用于 ControlNet | 图片热链上游 `ai-pose-depth-gallery`；2人絡み需18+ | 收录分类与用法（第 8 节） |
| 服装 `/costume` | 1068 套（春215/夏254/秋244/冬253/派对48/泳装54） | 穿搭，中/英提示词 + 标签 | ⚠️ **上游明确禁止批量下载/再分发** | 只收"结构+写法+示例"，不镜像（第 3 节） |
| 动画服装 `/anime` | 984 套公开（197/237/230/232/36/52） | 同上，动画风 | ⚠️ 同上，禁批量 | 同上（第 3 节） |
| 人像 `/portrait` | 1499 张 | 脸模 / 发长参考 | **CC0 1.0（可自由使用）** | 收录发型文本（第 2 节）+ 在线入口 |
| 表情 / 历代 / 场景 / 光影 / 道具 / 家具 | 0（当前空） | 预留板块 | — | 记录结构（第 4 节） |
| 试穿 studio / 收藏 favorites | — | 在线 AI 试穿、收藏组合 | 站内功能 | 仅说明 |

> 结论：**姿势与发型文本可全量收录**（来自开源仓库的翻译数据）；**服装/动画因上游禁止批量抓取，不镜像**，只给写法与在线入口（按编码在线取单条）。这样既不违反源站条款，又覆盖用户需要的"动作 + 动作提示词 + 服装写法"。

## 1. 姿势提示词总库（master · 中|英 全量，按姿态归类）

> 共 **288** 条。英文片段可直接拼进提示词（再补 `, full body, solo`）；中文给中文平台。分类为按关键词自动归类，个别跨界属正常。

### 可爱（20）

- 下巴下比双剪刀手 — double peace sign under the chin
- 兔耳手势 — bunny ears pose with hands on head
- 拜托姿势（双手合十） — pleading pose, palms pressed together
- 嗷呜怪兽爪姿势 — playful "rawr" monster claw pose
- 嘘（食指抵唇） — shush gesture, index finger on lips
- 辣妹剪刀手（手背朝外） — gyaru peace sign, back of hand facing out
- 握拳贴脸（装可爱） — fists on cheeks, cutesy pose
- 双手捧脸 — cupping cheeks with both hands
- 食指戳脸颊 — poking cheek with index finger
- 飞吻 — blowing a kiss
- 招财猫猫爪手 — maneki-neko cat paw gesture
- 手指含在嘴边 — finger in mouth
- 手指取景框 — finger frame gesture
- 敬礼姿势 — salute pose
- 单手比心＋另一手放胸前 — one-hand heart, other hand on chest
- 胸前双手比心 — heart shape with both hands in front of chest
- 俯身亲吻胸口 — leaning over, kissing the chest
- 脸颊旁比指尖心 — finger heart beside cheek
- 头顶双臂比心 — big heart with arms over head
- 歪头＋手遮一眼（眨眼风） — head tilt, hand over one eye, wink style

### 躺卧（52）

- 俯卧撑起上身大幅后仰 — lying prone, upper body raised in a deep backbend
- 俯卧高抬臀部 — lying face down with hips raised high
- 俯卧青蛙腿（双膝向外打开） — lying prone in frog-leg position, knees spread to the sides
- 俯卧回眸·单膝侧屈 — lying prone looking back, one knee bent to the side
- 俯卧单手托胸 — lying prone, lifting chest with one hand
- 俯卧抬起一条腿 — lying prone, lifting one leg
- 俯卧撑肘·双腿伸直微张 — lying prone on elbows, legs straight and slightly apart
- 俯卧托腮·双脚上翘 — lying prone with chin in hands, both feet kicked up
- 俯卧托腮·抬起一腿 — lying prone with chin in hand, one leg raised
- 俯卧·枕臂 — lying prone, head resting on arms
- 俯卧·双脚上翘 — lying prone with feet up
- 俯卧撑肘挤胸 — lying prone on elbows, squeezing chest together
- 站姿后仰 — standing backbend
- 折叠仰卧（侧面·抱大腿） — lying on back folded, legs over head, hugging thighs, side view
- 折叠仰卧（侧面·腿伸过头顶） — plow pose, legs extended past head, side view
- 折叠仰卧（侧面·膝盖贴地于头侧） — deep plow pose, knees on floor beside head, side view
- 桥式高抬腰·双膝打开 — bridge pose with hips high and knees apart
- 下腰桥（手脚撑地） — full backbend bridge on hands and feet
- 床上侧卧邀约姿势 — lying on side in bed, inviting pose
- 叠躺在上·双腿伸直 — lying on top of partner with legs extended
- 上下交错相叠 — lying on top of each other in opposite directions
- 双肘撑地半躺 — reclining on both elbows
- 仰卧V字开腿（抬腿） — lying on back, legs raised in a V
- 仰卧双手放胸前 — lying on back, both hands on chest
- 仰卧双臂上伸后仰 — lying on back, arms stretched overhead, arching
- 仰卧并膝倒向一侧 — lying on back, knees together tilted to one side
- 仰卧屈双膝·一臂举过头顶 — lying on back, knees up, one arm overhead
- 仰卧抱双膝至胸 — lying on back, knees pulled to chest
- 仰卧单膝外展 — lying on back, one knee dropped open to the side
- 仰卧拱背·双臂举过头顶 — lying on back, back arched, arms overhead
- 仰卧拱背·高抬一腿 — lying on back, back lifted, one leg raised high
- 仰卧·双腿垂直向上 — lying on back, both legs straight up
- 仰卧·双臂举过头顶 — lying on back, arms overhead
- 仰卧·单膝立起 — lying on back, one knee bent up
- 仰卧·挺胸 — lying on back, chest arched up
- 下巴搁在手背·前倾 — leaning forward, chin resting on back of hands
- 侧卧突出腰臀曲线·屈一腿 — lying on side, emphasizing hip curve, one leg bent
- 侧卧·一臂举过头顶 — lying on side, one arm overhead
- 侧卧·腰臀曲线 — lying on side, showing waist curve
- 侧卧·托腮 — lying on side, head propped on hand
- 侧卧抱胸 — lying on side hugging chest
- 侧卧高抬上方腿握脚踝 — lying on side, top leg raised high, holding ankle
- 侧卧举臂呈S形 — lying on side, arms overhead in an S-curve
- 单腿桥式（抬腰一腿指向天花板） — single-leg bridge, one leg toward ceiling
- 背身侧卧展示臀线 — lying on side facing away, showing hip line
- 俯卧依偎在对方双腿间 — lying prone nestled between partner's legs
- 搭腿相拥而眠 — lying together with a leg draped over
- 伸腿相叠 — lying stacked with legs extended
- 仰卧腰部被高高抱起 — lying on back, hips lifted high by partner
- 仰卧·用膝托起腰部 — lying on back, hips supported on partner's knees
- 跪立后仰手触脚跟 — kneeling backbend, hands to heels
- 跪立大幅后仰双手握脚跟 — kneeling deep backbend, holding heels (camel pose)

### 跪立（40）

- 扭身·跪立回头 — kneeling upright, twisting to look back
- 后仰坐·单膝立起 — sitting leaning back, one knee raised
- 四肢着地塌腰仰视 — on all fours, back arched, looking up
- 四肢着地·一手放胸前 — on all fours, one hand at chest
- 四肢着地·一腿高抬向后 — on all fours, one leg raised high behind
- 四肢着地塌腰·目视前方 — on all fours, back arched, looking forward
- 在四肢着地者身后跪立 — kneeling upright behind a partner on all fours
- 四肢着地俯视（胸前视角） — on all fours, high angle down the neckline
- 跪坐挺胸后仰 — kneeling seiza, chest out, back arched
- 跪坐撩发 — kneeling seiza, sweeping hair up
- 单膝立起双手后撑 — one knee up, hands propped behind
- 单膝跪·手放大腿 — half-kneeling, hand on thigh
- 单膝跪·手放膝上 — half-kneeling, hand on knee
- 单膝跪·仰视 — half-kneeling, looking up
- 单膝立起·托腮 — one knee up, chin in hand
- 单膝立起·手抚发 — one knee up, hand in hair
- 撑肘抬上身·单膝立起 — propped on elbows, one knee up
- 在对方双腿间四肢着地 — on all fours between partner's legs
- 大开膝跪立沉腰 — kneeling with knees wide, hips lowered
- 开膝跪坐双手前撑（撒娇姿势） — kneeling with knees apart, hands on floor in front, begging pose
- 跪立后仰双手触地 — kneeling, bending back with hands to floor
- 跪立侧撑·身体呈弧形 — kneeling, hand down to the side, body curved
- 跪立后仰·双手抱后脑 — kneeling, arching back, hands behind head
- 跪立双手前撑挤胸 — kneeling, hands forward, squeezing chest
- 跪立·双手抱后脑 — kneeling upright, hands behind head
- 跪立后仰单手触脚跟 — kneeling, arching, one hand reaching to heel
- 跪立扭腰举一臂 — kneeling, twisting waist, one arm raised
- 跪立向前顶胯 — kneeling, hips pushed forward
- 跪立·上身后仰 — kneeling, upper body arched back
- 跪立·双手放大腿 — kneeling upright, hands on thighs
- 跪立·双手抱头 — kneeling upright, hands behind head
- 跪立·双臂上伸 — kneeling upright, arms stretched up
- 跪立·后撑后仰 — kneeling, hands behind, arching back
- 跪立·侧倾手撑地 — kneeling, leaning sideways, hand on floor
- 跪立·一手抚发一手叉腰 — kneeling, one hand in hair, other on hip
- 跪立·手叉腰后仰 — kneeling, hands on hips, arching
- 跪立·摆腰举一臂 — kneeling, swaying hips, one arm raised
- 单膝立起手握脚踝 — one knee up, holding ankle
- 反向桌式撑地顶腰 — reverse tabletop pose, hips thrust up
- 跪跨在对方脸上方 — kneeling astride above partner's face

### 蹲姿（10）

- 踮脚蹲·双手撑地 — squatting on tiptoes, both hands on the floor
- 蹲姿·回头 — squatting, looking back over shoulder
- 蹲姿·单手撑地 — squatting, one hand on the floor
- 蹲姿·手放膝上 — squatting, hands on knees
- 蹲姿·托腮 — squatting, chin resting on hand
- 蹲姿·手抚头发 — squatting, hand in hair
- 开腿蹲·双手抱头 — wide-leg squat, hands behind head
- 开腿蹲（不良少年蹲） — deep wide squat, delinquent-style
- 踮脚开腿蹲·双手触地 — tiptoe wide squat, both hands to the floor
- 背对蹲在对方膝上 — squatting on partner's lap facing away

### 侧坐·鸭子坐（13）

- 鸭子坐双手前撑挤胸 — W-sitting, hands on floor in front, squeezing bust
- 鸭子坐·双手放腿上 — W-sitting, hands on thighs
- 鸭子坐·双手抱头 — W-sitting, hands behind head
- 鸭子坐·双手前撑 — W-sitting, hands on floor in front
- 鸭子坐·双手后撑 — W-sitting, hands propped behind
- 鸭子坐·手放颈间 — W-sitting, hand at neck
- 侧坐单手撑地·身体弯成弧线 — side-sitting, one hand down, body curved
- 侧坐高抬一腿 — side-sitting, one leg extended high
- 侧坐撩发 — side-sitting, sweeping hair up
- 侧坐·双腿斜向右侧 — side-sitting, legs swept to the right
- 侧坐·一臂上伸 — side-sitting, one arm stretched up
- 侧坐·手贴脸颊 — side-sitting, hand on cheek
- 侧坐膝上被拥抱 — side-sitting on lap, being held

### 坐姿（23）

- M字开腿（坐姿·双手放膝上） — sitting in M-shaped spread legs, both hands on knees
- M字开腿（坐姿·双手后撑） — sitting in M-shaped spread legs, hands propped behind
- 盘腿相拥 — hugging while sitting on partner's crossed legs
- 扭身·坐姿扭转上身 — seated, twisting the upper body
- 抱膝坐·膝盖倒向左侧 — sitting with knees up, knees tilted to the left
- 抱膝坐·膝盖微张 — sitting with knees hugged, knees slightly apart
- 面对面坐在对方腰上 — sitting on partner's lap facing them
- 大V字开腿·双手后撑 — wide V-split sitting, hands propped behind
- 左右一字马坐·上身直立 — side split on floor, upper body upright
- 坐姿高抬一腿手握脚踝 — sitting, one leg extended high, holding ankle
- 坐姿抱腿打开 — sitting, holding legs open
- 单腿大开坐（半M字） — sitting with one leg spread wide, half-M pose
- 抱单膝后仰坐 — sitting hugging one knee, back arched
- 坐姿倚靠立起的膝盖 — sitting leaning on raised knee
- 背对坐在对方腰上 — sitting on partner's hips facing away
- 从背后抱坐膝上 — hugged from behind, sitting on lap
- 伸腿侧撑肘坐 — sitting legs extended, propped on elbow to the side
- 伸腿向前坐 — sitting with legs stretched forward
- 坐膝上前倾 — sitting on lap leaning forward
- 坐膝上双腿环腰 — on lap, legs wrapped around waist
- 雏偶坐姿（双手放膝） — hina doll pose, hands on knees
- 跨坐风·开膝沉腰撩发 — straddling pose, knees apart, hips lowered, sweeping hair
- 跨坐风·开膝前撑沉腰 — straddling pose, knees apart, hands forward, hips lowered

### 前倾（15）

- 前倾挤胸 — leaning forward, squeezing chest together with arms
- 站立劈叉（前屈一腿高抬向后） — standing split, bending forward with one leg raised high behind
- 前倾·手放大腿内侧 — leaning forward, hands on inner thighs
- 前倾·手扶膝盖 — leaning forward, hands on knees
- 前倾·手触小腿 — bending forward, touching shins
- 前倾·一手叉腰·仰视 — leaning forward, hand on hip, looking up
- 前倾·一腿后抬 — leaning forward, one leg kicked back
- 前倾·双臂自然下垂 — bending forward, arms hanging loose
- 前倾·手扶大腿·收臀 — leaning forward, hands on thighs, hips pushed back
- 前倾·手放膝上 — leaning forward, hands on knees
- 从后扶住前倾者的腰 — holding a bent-over partner's waist from behind
- 深度前屈·手触地面 — deep forward bend, hands on floor
- 一肩下沉身体前倾 — one shoulder dropped, leaning forward
- 站立前屈翘臀双手触地 — standing forward fold, hips out, hands to floor
- 手扶膝前倾站立 — standing bent forward, hands on knees

### 后仰（12）

- M字开腿（双肘撑地向后仰） — M-shaped spread legs, leaning back on both elbows
- 后仰·双臂上举 — arching back with both arms raised
- 双手撩发大幅后仰 — both hands sweeping hair up, deep back arch
- 双手抱头·挺胸后仰 — hands behind head, chest arched
- 后仰双腿悬空 — leaning back with both legs lifted
- 前后劈叉·上身后仰 — front split with upper body arched back
- 后仰双臂夹胸 — arching back, squeezing chest with both arms
- 被公主抱·背部后仰 — carried bridal-style, back arched
- 站立抱单膝至胸·后仰 — standing, hugging one knee to chest, back arched
- 拱背双手撩发 — back arched, both hands sweeping hair up
- 双手叉腰·单膝内扣后仰 — hands on hips, one knee turned in, arching
- 抓住后颈后仰 — gripping nape, arching back

### 扭身（6）

- 扭身·站立展臂 — standing twist with arms spread
- 双臂上伸伸懒腰·扭腰 — stretching both arms overhead, twisting waist
- 背身回眸·突出臀部 — back to camera, looking over shoulder, emphasizing hips
- 站姿·越肩回眸 — standing, looking back over shoulder
- 手肘挤胸扭腰 — squeezing with elbows, twisting waist
- 翘臀回眸 — hips pushed out, looking back

### 站姿（19）

- S形站姿·胯部侧顶 — S-curve standing pose, hip pushed out to the side
- 手扶墙壁翘臀 — hands on wall, hips pushed out back
- 站立V字（一腿侧向高抬） — standing V, one leg raised high to the side
- 站姿·双手放后颈 — standing, both hands on nape
- 站姿·踮脚双臂V字 — standing on tiptoes, arms in a V
- 站姿·对立式手叉腰 — standing contrapposto, hand on hip
- 站姿·双手撩发 — standing, both hands sweeping hair up
- 站姿·双手叉腰 — standing, hands on hips
- 站姿·双臂举过头顶 — standing, arms stretched overhead
- 站姿·一手放后脑 — standing, one hand behind head
- 站姿·一腿抬至肩握脚踝（I字） — standing I-balance, leg raised to shoulder holding ankle
- 站姿·举一臂顶胯 — standing, one arm raised, hip pushed out
- 站姿·一脚向后抬起 — standing, one foot kicked up behind
- 站姿·开腿双手叉腰 — standing legs apart, hands on hips
- 站姿·手背后挺胸 — standing, arms behind back, chest out
- 站姿·手放颈间与大腿 — standing, hands on neck and thigh
- 站姿·秀发飘扬 — standing, hair flowing in the wind
- 站立挤胸 — standing, pressing bust together
- 肩倒立双腿V字打开 — shoulder stand, legs open in a V

### 其他·复合（78）

- 打哈欠伸懒腰（一手掩口） — yawning stretch, one hand at mouth
- 指向镜头 — pointing at the camera
- 淋浴感撩发 — running hands through hair like in the shower
- 胸部倚在桌上 — resting chest on a table
- 抱住抬起的一条腿 — hugging one raised leg
- 双手掐腰挺胸 — hands gripping waist, chest pushed out
- 双手由下托起胸部 — lifting breasts from below with both hands
- 双手挤胸前挺 — squeezing chest together and pushing forward
- 双手从两侧挤胸 — pressing breasts together from the sides with both hands
- 双手捂胸 — covering breasts with both hands
- 双手揉胸 — groping own breasts with both hands
- 双手托下巴（花朵姿势） — chin resting on both palms, flower pose
- 从指缝间偷看 — peeking through fingers
- 双手按在胸口上方聚拢 — hands on upper chest, pressing together
- 双手抱头露腋 — hands behind head showing armpits
- 双手后撑·挺胸 — hands propped behind, chest pushed out
- 双手腕被按在头顶 — wrists pinned above head
- 双腿架肩俯身压上 — partner leaning over with legs on shoulders
- 双臂环抱胸部 — hugging chest with both arms
- 双膝抱向胸前 — pulling both knees to chest
- 前臂竖起从两侧夹胸 — forearms vertical, squeezing chest from both sides
- 手指抵唇＋一手放胸 — finger to lips, other hand on chest
- 向右倾斜·手肘支撑 — leaning right, propped on elbow
- 面对面抱起对方一膝 — facing each other, lifting partner's knee
- 猫式伸展（正面） — cat-like stretch, front view
- 手撑地·双腿被抱起 — hands on floor, legs held up by partner
- 背手解开内衣扣 — unhooking bra behind back
- 背手挺胸 — hands behind back, chest out
- 双手后撑挺胸 — propped on hands behind, chest pushed out
- 双手后撑·双腿交缠 — propped on hands behind, legs crossed
- 背后十指相扣挺胸 — hands clasped behind back, chest out
- 手胸罩（双手遮挡） — hand bra, covering chest with both hands
- 手腕交叠头顶·抱膝 — wrists crossed overhead, hugging knees
- 相拥双腿交缠 — hugging with legs intertwined
- 指尖遮挡胸前 — covering nipples with fingertips
- 侧身·一腿搭在对方肩上 — side-on, one leg resting on partner's shoulder
- 一手挤胸一手抚发 — one hand pressing chest, other in hair
- 一手揉胸一手撩发 — one hand groping chest, other sweeping hair
- 一手放胸·一手抚过小腹 — one hand on chest, other tracing belly
- 一手遮挡一手托起 — one hand covering, other lifting
- 一手遮挡一手叉腰 — one hand covering, other on hip
- 单手支撑·双腿前伸 — propped on one hand, legs swept forward
- 单肘撑膝托腮 — elbow on knee, chin in hand
- 单臂托起胸部 — scooping up chest with one arm
- 一臂环腰一手抚颈 — one arm around waist, other hand on nape
- 猫式（胸贴地高抬腰·侧面） — cat pose, chest to floor, hips high, side view
- 耳边低语轻抚脸颊 — whispering in ear, touching cheek
- 撑肘从旁俯视 — propped on elbow, looking down from beside
- 褪下肩带 — slipping off a shoulder strap
- 耸肩挤胸（双手交叠于下） — shrugging shoulders to squeeze chest, hands clasped low
- 背靠对方大开双膝 — leaning back on partner, knees spread wide
- 从背后将手覆于胸前 — reaching around from behind to the chest
- 踮脚伸展·一脚后抬 — stretching on tiptoes, one foot back
- 从背后环抱胸前 — embraced around the chest from behind
- 手指划过胸下 — tracing finger under chest
- 手探入乳沟 — slipping hand into cleavage
- 胸贴地抬臀 — chest to floor, hips raised
- 在对方双腿间托腮 — chin in hands between partner's legs
- 双腿交叉·一腿搭肩 — legs crossed, one leg on partner's shoulder
- 斜伸双腿手叉腰 — legs extended diagonally, hand on hip
- 双腿交缠互拉手臂 — legs entwined, pulling each other's arms
- 双腿缠腰相拥 — legs wrapped around waist, embracing
- 双腿搭放倚靠对方膝上 — legs draped, leaning on partner's lap
- 前伸手臂·腰被扶住 — arms stretched forward, waist supported by partner
- 双臂胸下交叉托起 — arms crossed under chest, lifting
- 抱臂托胸 — crossed arms lifting chest
- 高抬腰部·贴近脸庞 — hips lifted high, faces close
- 屈膝双手抱头 — knees up, hands behind head
- 膝拉至肩握脚踝 — knees pulled to shoulders, holding ankles
- 抱住膝弯大幅打开 — holding behind knees, spreading wide
- 害羞自抱 — shyly hugging oneself
- 萌袖风双手掩嘴 — covering mouth with both hands, sweater-paw style
- 俯拍双手放胸·上目线 — high angle, hands on chest, looking up through lashes
- 俯拍构图双手放锁骨 — high angle shot, hands on collarbone
- 手扶脚踝 — hand on ankle
- 抓起脚踝V字打开 — holding ankles up, legs in a V
- 倒抱交错 — lifted upside down, opposite directions
- 将头发别到耳后 — tucking hair behind ear


## 2. 发型库（人像·发型，中|英）

> 共 **50** 条。发型名可直接放进发型段；配 `hair-design`/造型第 6 层使用。

- 齐剪直发波波头（无刘海） — blunt straight bob, no bangs
- 前长后短菱形短波波（黑发） — A-line rounded short bob, black hair
- 别耳帅气短发（无刘海） — tucked-behind-ear pixie cut, no bangs
- 收腰短发（后颈留长·空气刘海） — layered short hair with longer nape, see-through bangs
- 圆润短波波（空气刘海·深棕色） — rounded short bob, see-through bangs, dark brown hair
- 迷你波波头（眉上齐刘海） — mini bob with blunt bangs above the eyebrows
- 韩式锁骨流苏波波（侧分刘海） — Korean tassel bob, side-swept bangs
- 蘑菇短发（长刘海） — mushroom short cut, long bangs
- 迷你波波烫（自然卷感） — mini bob perm, natural wavy texture
- 短款狼尾（迷你狼尾） — short wolf cut
- 浅色奶茶色短波波 — light milk-tea blonde short bob
- 挑染圆润短发 — rounded short hair with highlights
- 层次短波波（脸周层次） — layered short bob, face-framing layers
- 内扣波波（薰衣草灰紫） — inward-curled bob, lavender ash hair
- 八字刘海内扣中长波波 — medium bob with one inward curl, curtain bangs
- 中长羊毛卷 — medium-length tight curly perm
- 齐刘海中长直发 — medium straight hair with blunt bangs
- 蝴蝶剪（榛子棕） — butterfly cut, hazel brown hair
- 酒红色空气层次 — burgundy see-through layered hair
- 中长慵懒卷（卷发棒卷感） — medium soft wavy perm, curling-iron waves
- 长波波层次（薄荷米色） — layered lob, mint beige hair
- 齐剪外翻中长波波 — blunt medium bob with flipped-out ends
- 前长后短中长波波（栗子米色） — A-line medium bob, marron beige hair
- 光泽顺直中长波波（无刘海） — glossy straight medium bob, no bangs
- 厚重中长层次（渐变挑染） — heavy medium layers with balayage
- 锁骨长度层次波波（灰米色） — collarbone-length layered bob, ash greige hair
- 湿发感长刘海短波波 — wet-look short bob with long bangs
- 螺旋烫短波波（黑发） — spiral perm short bob, black hair
- 收腰波波（内层挑染） — layered bob with hidden inner color
- 浅色奶茶灰米中长发 — light milk-tea greige medium hair
- 羽毛剪（韩系） — Korean hush cut
- 中长层次内扣（柔米色） — medium layers with inward curl, soft beige hair
- 外翻波波（深色发） — flipped-out bob, dark hair
- 中长狼尾烫 — medium wolf cut perm
- 八字刘海韩系层次 — Korean layered hair with curtain bangs
- 空气齐刘海碎层次 — shaggy layers with see-through blunt bangs
- 韩式螺旋烫半长发 — Korean-style spiral perm, shoulder-length hair
- 半长狼尾（樱桃红） — shoulder-length wolf cut, cherry red hair
- 半长直发（有刘海·深色发） — shoulder-length straight hair with bangs, dark hair
- 半长慵懒卷 — shoulder-length soft wavy perm
- 半长脸周层次（奶茶米色） — shoulder-length face-framing layers, milk-tea beige hair
- 半长黑发光泽层次 — glossy shoulder-length black layered hair
- 羽毛剪（灰米色） — hush cut, greige hair
- 内扣层次加碎发（巧克力棕） — layers with one curl and loose face strands, chocolate brown hair
- 斜刘海空气卷 — airy curls with side-swept bangs
- 多层次（薰衣草灰米） — heavily layered hair, lavender greige
- 长狼尾（水母头） — long wolf cut, jellyfish haircut
- 收腰半长发（透亮发色） — layered shoulder-length hair, translucent color
- 高层次 + 发尾挑染（金色） — high layers with blonde tips
- 蝴蝶剪（薄荷米色·空气刘海） — butterfly cut, mint beige hair, see-through bangs

## 3. 服装 / 动画服装（结构与写法，不批量镜像）

**分类**：6 个季节/场合 —— 春/夏/秋/冬/派对礼服/泳装；另按**单品+颜色** 38 个标签（黑517·半身裙422·靴323·凉鞋287·连衣裙281·白255·棕246·连裤袜231·开衫208·夹克188·长裤179·象牙白175·吊带160·灰153·米143·金127·蓝121·银104·大衣96·运动鞋92·藏青89·红80·衬衫77·绿75·短裤69·牛仔68·奶油63·薄荷59·泳衣54·粉50·黄35·卡其35·高跟33·酒红32·橙30·毛衣22·橄榄20·长袜6）。
**编码**：`SPR/SUM/AUT/WIN/PTY/SWM-####`（动画服装在 `/a/` 下用同编码）。

**提示词结构（实测）**：`{季节} outfit, {主件}, {下装}, {袜}, {鞋}, {配饰}`；中文="春季穿搭，{主件}，{下装}…{鞋}…{配饰}"。
**写法示例（仅示范，非全量）**：
- SPR-0001 — EN `spring outfit, ivory frill knit denim mini skirt, coat, socks, white sneakers` ｜中「春季穿搭，外穿大衣，下身配象牙白荷叶边针织牛仔短裙，配袜子，脚踩白色运动鞋」
- SPR-0005 — EN `spring outfit, beige floral midi dress, white socks, sandals, bag, ribbon` ｜中「春季穿搭，一条米色碎花中长连衣裙，搭配白色袜子，脚踩凉鞋，点缀手提包与蝴蝶结」
- SUM-0001 — EN `summer outfit, orange yellow trousers, shirt, white sneakers, bag, gold necklace` ｜中「夏季穿搭，上身穿衬衣，下身配橙色拼黄色长裤，脚踩白色运动鞋，配手提包与金色项链」
- PTY-0001 — EN `party outfit, red camisole, mini dress, tights, high heels` ｜中「派对礼服穿搭，穿短款连衣裙，叠穿红色吊带，腿上是连裤袜，鞋子选高跟鞋」
- SWM-0001 — EN `swimsuit outfit, mint floral trousers, cardigan, sandals, necklace, tote bag` ｜中「泳装穿搭，外搭开衫，下身配薄荷绿碎花长裤，穿凉鞋，配项链与托特包」
（秋/冬同格式，示例略；规律一致）

**在线取用**：`https://posewear.pages.dev/costume/` 与 `/anime/`；单条 `https://posewear.pages.dev/costume/SPR-0001/`。需要哪套按编码在线看，本库不存全量。
> ⚠️ 18+/内衣/性感类默认隐藏（顶部「18+」开关）；不批量抓取；仅作服装品类参考，不写露骨。

## 4. 其他板块（当前为空，预留结构）
表情 / 历代服饰 / 场景 / 光影 / 道具 / 家具 —— 站点当前计数均为 **0**。预计结构同为"名称 + 中/英提示词 + 缩略图"；上线后按第 1、3 节同法收录。

## 5. 机位角度 token（每个姿势 5 个角度，拼进提示词）
| 角度 | 英文 token |
|---|---|
| 正面 | front view |
| 俯拍 | high angle, from above |
| 仰拍 | low angle, from below |
| 侧面 | side view |
| 斜侧 | three-quarter view |

## 6. 与本 skill 的融合用法
- **姿势** → 主体姿态段（补充/替代 `pose-and-anatomy.md` 的逐肢体描述）；英文片段直接拼，中文平台用中文。
- **服装** → 造型六层第 2 层"主件" + 第 4 层配色；服装英文提示词可整体借用。
- **发型** → 造型六层第 6 层（妆发）。
- **角度** → 机位/镜头（配合 `pose-and-anatomy.md` 的机位数字化）。
- **组合模板**：`{人物/长相}, {pose english}, {costume english}, {angle token}, {light}, {scene}, full body, solo`
- **安全**：仍守 SKILL 成年锚点；18+/内衣类只作服装品类参考，不写露骨。

## 7. 再同步（仅文本部分）
- 姿势文本：`https://raw.githubusercontent.com/atuizz/posewear/main/tr_pose.txt`
- 发型文本：`https://raw.githubusercontent.com/atuizz/posewear/main/tr_portrait.txt`
- 镜像（raw 抖动时）：`https://cdn.jsdelivr.net/gh/atuizz/posewear@main/tr_pose.txt`
- 服装/动画：上游画廊禁止批量抓，**在线浏览**即可（第 3 节入口）。
- 抓取日期 2026-11-22；上游更新后按同法重拉文本部分。

## 8. 深度姿势（Depth poses · ControlNet 深度参考）

> 独立板块：**深度姿势**（与姿势同源，@giaaibusi）。给的是**深度图 (depth map)**，用于 ControlNet 控姿态，不是普通参考图。
> 数据：`depth/packs/gia-depth/items.json` + `manifest.json`（开源仓库）；**图片热链上游** `https://ai-pose-depth-gallery.pages.dev/`，本站/本库**不保存图**。
> 字段：`id / 系統(line) / ポーズ番号(no) / 分類(cat) / ポーズ名(name) / アングル(angle) / サムネ / 原寸`。

- **系统线（4）**：全身1人・セクシー系 / 全身1人・標準系 / 上半身1人 / 2人絡み（**双人互动，需开 18+**）。
- **分类**：立ち / 座り / 膝立ち・四つん這い / 寝そべり / 特殊（bridge、まんぐり返し 等）。
- **每姿势 5 个角度**：正面 / 上から(俯) / 下から(仰) / 横(侧) / 斜め(斜侧) —— token 同第 5 节。
- **姿势名与第 1 节同源同名**，可对照取中/英文提示词；深度图直接喂 ControlNet(depth) 锁姿态。
- 用法：`{第1节取 pose 英文} + {ControlNet depth = 上游 img/<id>.png} + {服装/光/景}`。
- 规模：完整数据集约 250–300 姿势（截断样本已见 109 个，跨 2 条系统线）。
- ⚠️ 图片由上游托管、**不批量下载**；`2人絡み` 属 18+。



> 版本：2026-11-22 建立；收录姿势 288 条、发型 50 条。
