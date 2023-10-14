---
description: 错误码列表
---

# 错误码

一触而就使用标准的HTTP响应代码来指示API请求的成功或失败。2xx范围内的代码表示成功。4xx范围内的代码表示由于提供的信息有误而导致的错误（例如，省略了必需的参数，请求被限制速率，提供了无效的API密钥等）。5xx范围内的代码表示一触而就i服务器出现错误。

| **Status code summary**     |                                              |
| --------------------------- | -------------------------------------------- |
| **200 - OK**                | 成功                                           |
| **400 - Bad Request**       | _Invalid requst parameter._                  |
| **401 - Unauthorized**      | _Invalid API Key provided._                  |
| **402 - Payment Required**  | _Quota exceeded._                            |
| **429 - Too Many Requests** | _Too many requests hit the API too quickly._ |
| **404 - Not Found**         | _The resource doesn't exist._                |
| **500 - Server Error**      | _Something went wrong on our end._           |
