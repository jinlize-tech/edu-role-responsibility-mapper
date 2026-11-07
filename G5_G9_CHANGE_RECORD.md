# G5/G9 产品修改记录

- 产品编号：$(@{number=88; product_id=JLZ-EDU-SK-070; chinese_name=组织与岗位职责映射; english_name=Role Responsibility Mapper; repository_name=edu-role-responsibility-mapper; repository_url=https://github.com/jinlize-tech/edu-role-responsibility-mapper; product_type=Skill; category_code=08; category=08 校区标准化与多校区管理中心; description=组织架构和岗位职责映射。; target_users=System.Object[]; core_input=现有部门、岗位、人员、关键任务、协作关系和流程节点; main_output=组织架构图文本、职责矩阵、重叠/空白区、RACI建议和待确认项; product_risk=按个人而非岗位设计或权限集中过度; dedup_label=存在部分功能交叉; dedup_note=与岗位说明书区别：本产品是组织级职责映射；与校长经营OS LITE区分不输出综合经营系统。; development_status=Planned / 待研发; license=Apache-2.0; spec_version=1.0.0; workbuddy_status=PLANNED_FOR_WORKBUDDY}.product_id)
- 产品名称：组织与岗位职责映射
- 基线：EDUCATION_BASELINE_V1.0.0
- 基线提交：$BaselineCommit
- 原版本：1.0.0
- 新版本：1.0.1

## 本次修改

1. 强化产品专属执行流程、输入核对和输出验收规则。
2. 新增 scripts/validate_input.js，实际检查必填字段、冲突、未确认数据和敏感信息。
3. 新增正常、缺失、冲突、敏感信息和非法JSON场景输入。
4. 测试升级为 T1–T7 分层并保存逐项检查结果。
5. 安装包加入 Apache-2.0 LICENSE 和 THIRD_PARTY_NOTICES.md。
6. 安装包升级为 1.0.1，加入许可证、第三方声明和输入校验脚本，保留 1.0.0 ZIP。
7. 按本产品冻结规格补充专属处理规则、输入到成果的核对矩阵和去重边界。

## 产品专属增强

- 核心任务：组织架构和岗位职责映射。
- 主要风险：按个人而非岗位设计或权限集中过度
- 去重边界：与岗位说明书区别：本产品是组织级职责映射；与校长经营OS LITE区分不输出综合经营系统。

- 先明确标准版本、适用校区、检查范围、证据来源和例外条件。
- 按流程节点核对责任人、输入、完成标准、输出和升级机制。
- 区分现状证据、标准要求、差距、影响、整改动作和复验标准。
- 不代替机构作出处罚、人事、财务或行政批准决定。

## 运行边界

- 本地模型行为：NOT_RUNTIME_VERIFIED
- WorkBuddy平台验证：WORKBUDDY_VALIDATION_NOT_IN_SCOPE
- 本轮不执行上传、安装、审核或正式发布。
