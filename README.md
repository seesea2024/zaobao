# zaobao

1. 用户 setting 下面新建 Personal Access Token，允许读写 Repo
2. 项目 Setting -> Security -> Secrets and variable -> Actions下面新建 repository Secrets. Name:ACTION_TOKEN, 值为上一步生成的 PST。注意新建的是*Repository secrets*, 不是*Environment secrets*
3. Actions下面启用项目中的 workflows 并运行