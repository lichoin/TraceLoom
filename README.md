# TraceLoom

TraceLoom 是[沥泉科技](https://www.lichoin.com/)自研的 **AI 自动化源码审计产品**，用于在 GitHub 上持续发现开源项目源码，并自动化开展白盒代码审计，将发现的高价值安全漏洞按规范渠道进行披露。

## 产品能力

- 持续监测 GitHub 开源项目源码与变更
- AI 驱动的白盒代码审计与漏洞挖掘
- 人工复核与 PoC 验证
- 通过 GitHub Security Advisory / CVE 体系负责任披露

## 工作流程

1. 发现目标：持续扫描 GitHub 开源项目；
2. 白盒审计：AI 自动化审计 + 人工验证；
3. 漏洞披露：
   - 对具备 GitHub Security Advisory 接收渠道的项目，提交到对应仓库/组织的 Security Advisory；
   - 对没有 GitHub Security & Quality 接收渠道的项目，提交至 CVE 编号体系；
4. 成果沉淀：在本仓库持续更新已公开成果。

## 已公开成果

| CVE / GHSA | 受影响项目 | 严重程度 | 漏洞类型 | 公告链接 |
| --- | --- | --- | --- | --- |
| CVE-2026-34047 / GHSA-652w-qv22-2r7c | [coollabsio/coolify](https://github.com/coollabsio/coolify) | Critical | CWE-863 越权访问，可致远程代码执行 | [Security Advisory](https://github.com/coollabsio/coolify/security/advisories/GHSA-652w-qv22-2r7c) |

> 更多成果持续更新中。

## 关于沥泉科技

沥泉科技成立于 2022 年，是一家以技术创新为核心驱动力的创新型网络安全企业，围绕网络空间资产发现、风险检测、安全验证等关键场景，为政府、金融、能源、运营商及各类企业客户提供专业、高效的安全解决方案。

- 官网：[https://www.lichoin.com/](https://www.lichoin.com/)
- 加入我们：[https://www.lichoin.com/jobs/](https://www.lichoin.com/jobs/)
- 联系邮箱：[info@lichoin.com](mailto:info@lichoin.com)
