# 👨‍💻 Directory Structure

```
$ tree -I 'node_modules'
.
├── package.json
├── pnpm-lock.yaml
├── src
│   ├── controllers
│   │   ├── cloudwatch.controllers.ts
│   │   ├── ec2.controllers.ts
│   │   ├── lambda.controllers.ts
│   │   ├── s3.controllers.ts
│   │   ├── vpc.create.controllers.ts
│   │   └── vpc.describe.controllers.ts
│   ├── index.ts
│   ├── middleware
│   │   └── cloudwatch-logs.ts
│   ├── routes
│   │   ├── cloudwatch.routes.ts
│   │   ├── ec2.routes.ts
│   │   ├── lambda.routes.ts
│   │   ├── s3.routes.ts
│   │   └── vpc.routes.ts
│   └── utils
│       └── api-response.ts
└── tsconfig.json

6 directories, 17 files
```
