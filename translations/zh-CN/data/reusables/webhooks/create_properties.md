| 键               | 类型    | 描述                                                                                                                                                     |
| --------------- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `ref`           | `字符串` | The [`git ref`](/v3/git/refs/#get-a-reference) 资源。                                                                                                     |
| `ref_type`      | `字符串` | 在仓库中创建的 Git ref 对象的类型。 可以是 `branch` 或 `tag`。                                                                                                           |
| `master_branch` | `字符串` | 仓库默认分支的名称（通常是 {% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.23" %}`main`{% else %}`master`{% endif %}）。 |
| `说明`            | `字符串` | 仓库的当前描述。                                                                                                                                               |
