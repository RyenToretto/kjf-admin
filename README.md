## kjf-admin

    个人 npm 包发布测试项目。

    不建议生产使用。

## 发布 修正 npm 下载源

    npm config set registry https://registry.npmjs.org/

## 开发 使用淘宝 npm 下载源

## License

    请查看 [MIT license](./LICENSE).

### 1. 初始化项目
```
    mkdir kjf-admin
    chmod 777 kjf-admin
    cd kjf-admin
    
    npm config set init-author-name "koujianfeng" # 你的名称
    npm config set init-author-email "18273727925@163.com" # 你的邮箱
    npm config set init-author-url "https://juejin.im/user/870468939679469"  # 你的个人网页
    npm config set init-license "MIT"                    # 开源授权协议名
    npm config set init-version "0.0.1"                         # 版本号

    npm init -y
    npm i -g typescript
    tsc --init
```

### 2. 添加 .gitignore

### 3. 添加 tsconfig.json
```
    {
        "compilerOptions": {
            "module": "commonjs",
            "target": "es2017",
            "noImplicitAny": true,
            "moduleResolution": "node",
            "sourceMap": true,
            "outDir": "dist",  // TS 文件编译后会放入到此文件夹内
            "baseUrl": ".",
            "paths": {
                "*": [
                    "node_modules/*",
                    "src/types/*"
                ]
            }
        },
        "exclude": ["node_modules", "dist", "pages", "public"],
        "include": [
            "src/**/*"
        ]
    }
```

### 4. 安装 TypeScript 热更新编译
```
    npm install -D typescript ts-node nodemon
    npm install -g -force ts-node nodemon

    配置一下 package.json 设置
        "scripts": {
            "start": "tsc && node dist/index.js",
            "watch-update": "nodemon --watch src/**/* -e ts,tsx --exec ts-node ./src/index.ts"
        },
```

### 5. 安装
```
    npm install -D
```

### 6. 安装
```
    npm install -D
```

### 7. 安装
```
    npm install -D
```

### 8. 安装
```
    npm install -D
```

### 9. 安装
```
    npm install -D
```

### 10. 安装
```
    npm install -D
```

### 11. 安装
```
    npm install -D
```

### 12. 安装
```
    npm install -D
```
