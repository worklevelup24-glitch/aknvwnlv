# OpenAI Proxy for Voximplant

This is a proxy server to bypass restrictions and access OpenAI API from Voximplant.

## Usage

Endpoint: `https://your-project.vercel.app/api/proxy`

### Example request:
```javascript
POST /api/proxy
Headers:
- Authorization: Bearer YOUR_OPENAI_API_KEY
- Content-Type: application/json

Body:
{
  "model": "gpt-3.5-turbo",
  "messages": [{"role": "user", "content": "Hello"}],
  "max_tokens": 150
}
