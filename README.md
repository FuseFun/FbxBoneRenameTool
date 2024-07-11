外部引用：Assimp, mini

【使用方法】

0. 为保证您的资产安全，请先做好对原始资产的备份

1. 编辑配置文件：
    在 BoneRenameTool.ini 的 [RenameBones] 分栏下添加 “骨骼重命名条目”，格式为 [原始骨骼名称]=[新骨骼名称]
    在 BoneRemoveTool.ini 的 [RemoveBones] 分栏下添加 “骨骼移除条目”，格式为 [要删除的新骨骼名称]=[将拥有被删除骨骼权重的新骨骼名称（可使用默认值 $default 将权重指定给父骨骼）]

2. 拖拽 fbx资产文件 或 包含有fbx资产文件的文件夹 放置到 AssetPreprocessor.exe 上，AssetPreprocessor.exe 将启动并处理资产

3. 查看返回信息是否成功处理，新的 fbx 文件会保存在原始 fbx 文件路径下，新文件名包含 _Processed 后缀
