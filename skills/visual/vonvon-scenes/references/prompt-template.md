# 生图提示词模板

每张独立生成，并把 `assets/vonvon-character-reference.png` 作为角色身份参考输入。

## 标准模式

```text
Generate one standalone 16:9 horizontal Chinese article illustration in Vonvon Scenes style.

Input roles:
Use the provided Vonvon reference only for character identity. Use the selected scene master only for object scale, whitespace, physical conflict and visual hierarchy. Never inherit the centered logo pose from the identity reference. Vonvon is a flat hand-drawn sticker-like cat integrated into a real photographed object scene: pear-shaped white body, thick black outline, two pure black circular eyes without pupils/highlights, tiny black nose and w-shaped mouth, three whiskers, orange circular cheeks, orange inner ears/tail tip/body patches, and a wide-brim cat-ear hat whose tiny cat-face ornament stays attached and is never a second cat. Keep Vonvon 2D and flat: no fur, no 3D, no plastic toy, no plush.

Cat anatomy and pose:
Before drawing, define chest/belly support, two short front-paw contact points, two short hind-paw positions, tail balance, occlusion and force direction. Vonvon may stand upright only with very short hind legs, rounded low center of gravity, visible tail, and both front paws complete. Front paws are short rounded cat paws; no human shoulders or elbows, no forearm longer than body width, no arms above the head. Never use cheering hands, a human horse stance, kneeling, one-knee pose, long-legged stride, upright human walking, runner arms, or missing paw. Prefer seated two-paw bracing, belly-low feline crouch, four-paw pulling, lying at an edge, or a tiny stool with both short hind paws supported.

Studio DNA:
Seamless pure #FFFFFF background and white studio surface. One real main object or compact object group, shared perspective and very light contact shadows. Vonvon physically grips, pushes, pulls, supports or repairs the object with correct occlusion and contact. Sparse handwritten Chinese labels and tiny blue/pink/yellow/green/red accents; preserve Vonvon's brand orange markings.

Master lock:
Use {母版文件} only as a quality anchor. Preserve {比例/留白/物件真实感/动作清晰/标签密度}. Required mutations: {至少 3 个}. Do not copy the master's exact object combination, topology, Vonvon pose, props or label positions.

3-second conflict: {画面 3 秒读懂句}
Theme: {主题}
Reader situation: {处境}
Physical metaphor: {动作}
Real object scene: {主物件、位置、最多 1-2 个配件}
Vonvon action: {明确动词与接触方式}
Chinese labels (verbatim): {2-4 个短标签}

Constraints:
One core physical action. Medium-light scene footprint, not close-up and not miniature. Vonvon occupies about 12%-20% of canvas height, never more than 24%; the real object remains larger or narratively dominant. Cute identity, never mascot-first. No UI, Logo, screenshot, office background, PPT, infographic, big title, long text, collage, ordinary cat, realistic cat, 3D mascot, black bean character, detached hat ornament or second cat.
```

## 彩蛋长卷

```text
Generate one ultra-wide 2.6:1 to 3:1 Vonvon long-scroll story image.

Use the provided Vonvon identity reference only for identity and the selected long-scroll master for spatial rhythm. Repeat the same flat 2D Vonvon character at each milestone as continuous action states, never as different cats. Preserve all identity invariants and keep the hat-top cat face attached. Each Vonvon is about 7%-11% of canvas height and stays smaller than or equal to its node's real object.

Premium near-white #FAFAF8 / #FBFBFA studio background. A thin organic hand-drawn black route moves left to right with irregular vertical rhythm and uneven spacing: quiet stretch, sudden climb, shallow arc, deeper dip, calm finish. Along it place 5-8 real photographed object nodes with very light contact shadows. Vonvon physically interacts with every node. Handwritten notes sit freely in open space, not inside cards or sticky notes.

Story: {主题}
Left opening: {身份/起点}
Milestones (unnumbered):
- {节点 | 真实物件 | Vonvon 动作 | 短注释}
- {节点 | 真实物件 | Vonvon 动作 | 短注释}
- {节点 | 真实物件 | Vonvon 动作 | 短注释}
- {节点 | 真实物件 | Vonvon 动作 | 短注释}
- {节点 | 真实物件 | Vonvon 动作 | 短注释}
Right closing: {现在/结论/下一阶段}

Every repeated Vonvon pose must be meaningfully different and preserve short legs, low feline balance, visible tail, two complete short front paws and explicit object contact. No human walking, kneeling, horse stance, raised arms, long forearms or missing limbs.

No timeline boxes, numbers, equal spacing, sine wave, dense row, six-cat horizontal lineup, repeated logo pose, giant cat, giant central object, PPT, UI, collage, invented facts, ordinary cat, 3D, fur, detached ornament or multiple different cats.
```

## 角色局部修复

```text
Edit only Vonvon using the provided identity reference. Keep all photographed objects, shadows, labels and composition unchanged. Restore a flat 2D pear-shaped white cat with thick black outline, pure black round eyes, orange cheeks/ear interiors/patches, wide-brim cat-ear hat and attached hat-top cat-face ornament. Rebuild the pose with two short complete front paws, short supported hind legs, visible tail balance, correct grip and occlusion. No long arms, raised hands, human shoulders/elbows, fur, 3D or extra cat.
```
