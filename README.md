# beevast-rfc0213-proving-ground

RFC 0213 WP0 G2/G4 停止门的真环境试验场（proving ground）。

- 只放**合成夹具**（synthetic fixtures），无任何真实凭证/客户数据/生产代码
- rulesets 分支保护由 gatekeeper/prover 通过 API 读取与启用
- G4：坏 Skill 提交可保留（Git 历史），但绝不能被 release/双投影/loader 接受
- G2：管理员 bypass 合入后，分发链各环节拒绝，补证后恢复

设计单源：beevast 仓库 docs/rfcs/rfc-0213-tool-credential-vault.md + 0213-skill-market-runtime-and-supply-chain.md
