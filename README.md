云学堂集证有礼·码力全开 AI自动答题
# AI 自动答题系统 - 使用说明

## 功能介绍

本系统已升级支持多个AI服务商，包括：
- **DeepSeek** - 深度求索
- **OpenAI** - GPT系列模型
- **Google Gemini** - 谷歌双子座
- **自定义** - 支持OpenAI API协议的其他服务商

## 使用步骤

### 1. 选择AI服务商
在控制面板中选择您要使用的AI服务商：
- **DeepSeek**: 默认API地址 `https://api.deepseek.com`
- **OpenAI**: 默认API地址 `https://api.openai.com/v1`
- **Google Gemini**: 默认API地址 `https://generativelanguage.googleapis.com/v1beta`
- **自定义**: 可填入任何支持OpenAI API协议的服务商地址

### 2. 配置API信息
- **API URL**: 系统会根据选择的服务商自动填入默认地址，您也可以手动修改
- **API Key**: 填入您的API密钥

### 3. 获取并选择模型
- 点击 **"获取模型"** 按钮，系统会自动拉取该服务商的可用模型列表
- 从下拉框中选择您要使用的AI模型

### 4. 测试连接（可选）
- 点击 **"测试连接"** 按钮验证API配置是否正确

### 5. 启用自动答题
- 开启 **"启用 AI 自动答题"** 开关
- 点击 **"开始/停止答题"** 按钮开始自动答题

## 各服务商配置说明

### DeepSeek 配置
```
服务商: DeepSeek
API URL: https://api.deepseek.com
API Key: 您的DeepSeek API Key
常用模型: deepseek-chat, deepseek-reasoner
```

### OpenAI 配置
```
服务商: OpenAI  
API URL: https://api.openai.com/v1
API Key: 您的OpenAI API Key
常用模型: gpt-3.5-turbo, gpt-4, gpt-4-turbo
```

### Google Gemini 配置
```
服务商: Google Gemini
API URL: https://generativelanguage.googleapis.com/v1beta
API Key: 您的Google AI API Key
常用模型: gemini-pro, gemini-pro-vision
```

### 自定义服务商配置
```
服务商: 自定义 (OpenAI API协议)
API URL: 您的自定义API地址
API Key: 您的API Key
模型: 根据服务商提供的模型列表选择
```

## 注意事项

1. **API密钥安全**: 请妥善保管您的API密钥，不要在不安全的环境中使用
2. **模型选择**: 不同模型的性能和费用可能不同，请根据需要选择
3. **连接测试**: 建议在正式使用前先进行连接测试，确保配置正确
4. **日志查看**: 系统会记录详细的操作日志，可通过"复制日志"按钮获取
5. **状态监控**: 注意观察状态栏信息，了解当前配置和运行状态

## 常见问题

### Q: 获取模型列表失败怎么办？
A: 请检查API URL和API Key是否正确，网络连接是否正常，可先尝试"测试连接"功能。

### Q: 支持哪些自定义服务商？
A: 支持所有兼容OpenAI Chat Completions API格式的服务商，如Claude API、国产大模型API等。

### Q: 如何切换不同的AI服务商？
A: 在下拉框中选择新的服务商，系统会自动更新相关配置，然后重新获取模型列表即可。

### Q: API调用失败怎么办？
A: 查看日志信息了解具体错误，常见原因包括API额度不足、网络问题、API密钥错误等。

## 更新日志

- ✅ 新增多AI服务商支持（DeepSeek、OpenAI、Gemini、自定义）
- ✅ 新增模型列表自动获取功能
- ✅ 新增API连接测试功能
- ✅ 优化用户界面和操作体验
- ✅ 增强错误提示和状态显示
