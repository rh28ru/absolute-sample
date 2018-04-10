- .env파일에 NODE_PATH=src/ 설정.
- jsconfig.json 추가.
```javascript
{
    "compilerOptions": {
        // This must be specified if "paths" is set
        "baseUrl": ".",
        // Relative to "baseUrl"
        "paths": {
            "*": [
                "*",
                "src/*",
                "assets/*"
            ]
        }
    }
}
```
