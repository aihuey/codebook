# codebook

## DeepSeek api in Claude Code
```json
"claudeCode.environmentVariables": [
        {
        "name": "ANTHROPIC_BASE_URL",
        "value": "https://api.deepseek.com/anthropic"
        },
        {
            "name": "ANTHROPIC_AUTH_TOKEN",
            "value": "<你的 DeepSeek API Key>"
        },
        {
            "name": "ANTHROPIC_MODEL",
            "value": "deepseek-v4-pro[1m]"
        },
        {
            "name": "ANTHROPIC_DEFAULT_OPUS_MODEL",
            "value": "deepseek-v4-pro[1m]"
        },
        {
            "name": "ANTHROPIC_DEFAULT_SONNET_MODEL",
            "value": "deepseek-v4-pro[1m]"
        },
        {
            "name": "ANTHROPIC_DEFAULT_HAIKU_MODEL",
            "value": "deepseek-v4-flash"
        },
        {
            "name": "CLAUDE_CODE_SUBAGENT_MODEL",
            "value": "deepseek-v4-flash"
        },
        {
            "name": "CLAUDE_CODE_EFFORT_LEVEL",
            "value": "max"
        }
    ]
```


## Mimo api in Claude Code
```json
{
  "claudeCode.preferredLocation": "panel",
  "claudeCode.selectedModel": "mimo-v2.5-pro",
  "claudeCode.environmentVariables": [
    {
      "name": "ANTHROPIC_BASE_URL",
      "value": "BASE_URL"
    },
    {
      "name": "ANTHROPIC_AUTH_TOKEN",
      "value": "MIMO_API_KEY"
    },
    {
      "name": "ANTHROPIC_DEFAULT_SONNET_MODEL",
      "value": "mimo-v2.5-pro"
    },
    {
      "name": "ANTHROPIC_DEFAULT_OPUS_MODEL",
      "value": "mimo-v2.5-pro"
    },
    {
      "name": "ANTHROPIC_DEFAULT_HAIKU_MODEL",
      "value": "mimo-v2.5-pro"
    }
  ]
}
```
