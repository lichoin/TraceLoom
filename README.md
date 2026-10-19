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

| CVE / GHSA     | 受影响项目                                                  | CVSS评分 | 漏洞类型                           | 公告链接                                                     |
| -------------- | ----------------------------------------------------------- | -------- | ---------------------------------- | ------------------------------------------------------------ |
| CVE-2026-34047 | [coollabsio/coolify](https://github.com/coollabsio/coolify) | 9.9      | CWE-863 越权访问，可致远程代码执行 | [Security Advisory](https://github.com/coollabsio/coolify/security/advisories/GHSA-652w-qv22-2r7c) |
| CVE-2026-79304 | [usmannasir/cyberpanel](https://github.com/usmannasir/cyberpanel) | 6.5 | CWE-22 路径遍历（任意文件读取） | [CVE-2026-79304](https://www.cve.org/CVERecord?id=CVE-2026-79304) |
| CVE-2026-79306 | [usmannasir/cyberpanel](https://github.com/usmannasir/cyberpanel) | 6.5 | CWE-22 路径遍历（任意文件读取） | [CVE-2026-79306](https://www.cve.org/CVERecord?id=CVE-2026-79306) |
| CVE-2026-79310 | [webpy/webpy](https://github.com/webpy/webpy) | 8.5 | CWE-94 代码注入（可致远程代码执行） | [CVE-2026-79310](https://www.cve.org/CVERecord?id=CVE-2026-79310) |
| CVE-2026-79311 | [webpy/webpy](https://github.com/webpy/webpy) | 6.1 | CWE-79 跨站脚本（XSS） | [CVE-2026-79311](https://www.cve.org/CVERecord?id=CVE-2026-79311) |
| CVE-2026-79312 | [webpy/webpy](https://github.com/webpy/webpy) | 6.8 | CWE-384 会话固定（Session Fixation） | [CVE-2026-79312](https://www.cve.org/CVERecord?id=CVE-2026-79312) |
| CVE-2026-79313 | [webpy/webpy](https://github.com/webpy/webpy) | 4.8 | CWE-613 会话过期不充分 | [CVE-2026-79313](https://www.cve.org/CVERecord?id=CVE-2026-79313) |
| CVE-2026-79314 | [vaxilu/x-ui](https://github.com/vaxilu/x-ui) | 6.5 | CWE-639 越权访问（用户可控键授权绕过 / IDOR） | [CVE-2026-79314](https://www.cve.org/CVERecord?id=CVE-2026-79314) |
| CVE-2026-79315 | [vaxilu/x-ui](https://github.com/vaxilu/x-ui) | 4.1 | CWE-79 反射型跨站脚本（XSS） | [CVE-2026-79315](https://www.cve.org/CVERecord?id=CVE-2026-79315) |
| CVE-2026-79316 | [vaxilu/x-ui](https://github.com/vaxilu/x-ui) | 7.5 | CWE-284 访问控制不当 / CWE-16 配置缺陷 | [CVE-2026-79316](https://www.cve.org/CVERecord?id=CVE-2026-79316) |
| CVE-2026-79317 | [vaxilu/x-ui](https://github.com/vaxilu/x-ui) | 4.8 | CWE-613 会话过期不充分 | [CVE-2026-79317](https://www.cve.org/CVERecord?id=CVE-2026-79317) |
| CVE-2026-79318 | [web2py/web2py](https://github.com/web2py/web2py) | 6.5 | CWE-22 路径遍历 | [CVE-2026-79318](https://www.cve.org/CVERecord?id=CVE-2026-79318) |
| CVE-2026-79319 | [stenciljs/core](https://github.com/stenciljs/core) | 5.3 | CWE-200 敏感信息暴露 | [CVE-2026-79319](https://www.cve.org/CVERecord?id=CVE-2026-79319) |
| CVE-2026-79320 | [stenciljs/core](https://github.com/stenciljs/core) | 6.1 | CWE-79 跨站脚本（DOM 型） | [CVE-2026-79320](https://www.cve.org/CVERecord?id=CVE-2026-79320) |
| CVE-2026-100696| [vrana/adminer](https://github.com/vrana/adminer)| 5.3 | CWE-918 服务端请求伪造（Server-Side Request Forgery，SSRF）| [CVE-2026-100696](https://www.cve.org/CVERecord?id=CVE-2026-100696) |
| CVE-2026-100697| [vrana/adminer](https://github.com/vrana/adminer)| 6.9 | CWE-918 服务端请求伪造（Server-Side Request Forgery，SSRF）| [CVE-2026-100697](https://www.cve.org/CVERecord?id=CVE-2026-100697) |
| CVE-2026-111627 | [hestiacp/hestiacp](https://github.com/hestiacp/hestiacp) | 8.6 | CWE-863 授权不当（越权命令执行） | [CVE-2026-111627](https://www.cve.org/CVERecord?id=CVE-2026-111627) |
| CVE-2026-111631 | [10up/distributor](https://github.com/10up/distributor) | 5.3 | CWE-862 缺少授权检查（凭据泄露） | [CVE-2026-111631](https://www.cve.org/CVERecord?id=CVE-2026-111631) |
| CVE-2026-111625 | [10up/distributor](https://github.com/10up/distributor) | 5.3 | CWE-862 缺少授权检查（跨站越权发布） | [CVE-2026-111625](https://www.cve.org/CVERecord?id=CVE-2026-111625) |
| CVE-2026-111628 | [10up/distributor](https://github.com/10up/distributor) | 2.3 | CWE-502 不可信数据反序列化（PHP 对象注入） | [CVE-2026-111628](https://www.cve.org/CVERecord?id=CVE-2026-111628) |
| CVE-2026-111624 | [umbraco/Umbraco-CMS](https://github.com/umbraco/Umbraco-CMS) | 6.3 | CWE-862 缺少授权检查（信息泄露） | [CVE-2026-111624](https://www.cve.org/CVERecord?id=CVE-2026-111624) |
> 更多成果持续更新中。

## 关于沥泉科技

沥泉科技成立于 2022 年，是一家以技术创新为核心驱动力的创新型网络安全企业，围绕网络空间资产发现、风险检测、安全验证等关键场景，为政府、金融、能源、运营商及各类企业客户提供专业、高效的安全解决方案。

- 官网：[https://www.lichoin.com/](https://www.lichoin.com/)
- 加入我们：[https://www.lichoin.com/jobs/](https://www.lichoin.com/jobs/)
- 联系邮箱：[info@lichoin.com](mailto:info@lichoin.com)
