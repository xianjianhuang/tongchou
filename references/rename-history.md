# 统筹 — 命名沿革

**创建时间**：2026-06-09
**原名**：meta-skill（OpenSquilla 的 MetaSkill 概念启发）
**更名**：2026-06-09 → 统筹（tongchou）
**原因**：用户要求改名，「MetaSkill」太抽象，「统筹」更直观

## 变更记录

1. 创建 `meta-skill`（参考 OpenSquilla 的自然语言→自动编排技能流程概念）
2. 用户要求改名 → 创建 `tongchou`，内容吸收 `meta-skill`
3. 删除 `meta-skill`（absorbed_into=tongchou）
4. skills-router 中所有 `meta-skill` 触发词改为 `tongchou`
5. darwin-skill 的 related_skills 中 `meta-skill` → `tongchou`
6. xiaoh-core v2.17.0 新增 A23 三位一体章节，不再提 MetaSkill

## 三位一体关系

| 角色 | 技能 | 职责 |
|------|------|------|
| 女娲（造） | huashu-nuwa | 从0到1创建新技能 |
| 达尔文（改） | darwin-skill | 对已有技能评估优化 |
| 统筹（编） | tongchou | 分析需求→编排技能→交付 |

以后只说「统筹」，不再说「Meta」或「MetaSkill」。
