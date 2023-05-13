# Airbnb Clone

我们将构建全站 Airbnb 克隆项目，将采用 `Next.js 13`、`React`、`Prisma`、`MongoDB`、`TailwindCSS` 等技术开发该项目。

## 一、构建项目

创建项目
```bash
npx create-react-app --typescript
```

> √ What is your project named? ... `airbnb-clone`

> √ Would you like to use ESLint with this project? ... No / `Yes`

> √ Would you like to use Tailwind CSS with this project? ... No / `Yes`

> √ Would you like to use `src/` directory with this project? ... `No` / Yes

> √ Would you like to use experimental `app/` directory with this project? ... No / `Yes`

> √ What import alias would you like configured? ... `@/*`

运行项目
```bash
npm run dev
```

安装 `react-icons`
```bash
npm install react-icons --save
```

## 二、注册模态框UI

安装 `zustand`
```bash
npm install zustand
```

安装 `axios`
```bash
npm install axios
```

安装 `react-hook-form`
```bash
npm install react-hook-form
```

安装 `react-hot-toast`
```bash
npm install react-hot-toast
```

## 三、使用NextAuth完成注册功能

安装 `prisma`
```bash
npm install -D prisma
```

初始化 `prisma`
```bash
npx prisma init
```

vscode安装 `prisma` 扩展

将 `prisma` 定义的 `schema` 推送到 MongoDB数据库中
```bash
npx prisma db push
```

安装 `next-auth`
```bash
npm install next-auth @prisma/client @next-auth/prisma-adapter
```

安装 `bcrypt`
```bash
npm install bcrypt
npm install -D @types/bcrypt
```

## 四、登录功能

使用 `NextAuth` 进行登录。

## 五、使用Github进行登录

## 六、类别UI

安装 `query-string`
```bash
npm install query-string
```

## 七、类别选择

## 八、位置选择

安装 `world-countries`
```bash
npm install world-countries
```

安装 `react-select`
```bash
npm install react-select
```

安装 `leaflet`
```bash
npm install leaflet
npm install -D @types/leaflet
npm install react-leaflet
```

## 九、计数器组件

## 十、上传组件

安装 `next-cloudinary`
```bash
npm install next-cloudinary
```

## 十一、完成创建功能

## 十二、列表卡组件

安装 `date-fns`
```bash
npm install date-fns
```

## 十三、收藏功能

## 十四、个人列表

## 十五、预定组件

安装 `react-date-range`
```bash
npm install react-date-range
npm install -D @types/react-date-range
```

## 十六、行程功能

## 十七、预定功能

## 十八、收藏功能

## 十九、属性功能