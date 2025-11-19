# Episodes.json 添加新集数模板

## 格式说明

在 `episodes.json` 中添加新集数时，请按照以下格式：

```json
{
  "id": 2,
  "title": "集数标题",
  "mdFile": "Folge2.md",
  "videoUrl": "https://player.bilibili.com/player.html?bvid=你的BV号&page=1&high_quality=1",
  "description": "视频描述"
}
```

## 示例

```json
{
  "episodes": [
    {
      "id": 1,
      "title": "Hallo",
      "mdFile": "Folge1.md",
      "videoUrl": "https://player.bilibili.com/player.html?bvid=BV1pb41137g6&page=1&high_quality=1",
      "description": "本片段包含了多种场景下的正式与非正式问候，以及如何询问和回答\"近况如何\"。"
    },
    {
      "id": 2,
      "title": "你的标题",
      "mdFile": "Folge2.md",
      "videoUrl": "你的B站视频链接",
      "description": "视频描述"
    }
  ]
}
```

## 注意事项

1. 每个集数对象之间用逗号分隔
2. 最后一个集数对象后面不要加逗号
3. `id` 必须是数字，按顺序递增
4. `mdFile` 必须与实际的 Markdown 文件名一致
5. `videoUrl` 支持 B站播放器链接格式
6. 确保 JSON 格式正确（可以使用 JSON 验证工具检查）

## 批量添加

当需要添加多个集数时，可以按照以下步骤：

1. 确保所有对应的 `.md` 文件已创建
2. 在 `episodes.json` 的 `episodes` 数组中按顺序添加所有集数
3. 检查 JSON 格式是否正确
4. 测试加载功能

