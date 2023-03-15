TypeScript 语言实现的算法集。

第一期目标：实现《算法导论》中的全部算法。

### 环境：
1. 下载并安装 [node.js](https://nodejs.org/en/download/)；
2. 全局安装 TypeScript: `npm i -g typescript`；
3. 全局安装 ts-node: `npm i -g ts-node`；
4. 下载本项目：`git clone https://github.com/linzier/algo-ts.git`；
5. 进入项目根目录并安装依赖：`cd $proj_dir && npm i`；
6. 运行某个算法的单元测试：`npm run test test/insertsort.test.ts`；
7. 或者运行所有的单元测试：`npm run test:all`；

### 开发指南：
- src 目录：存放源码；
- test 目录：单元测试目录，目录结构同 src；
- 为了让不太熟悉 TypeScript 的同学也能容易看懂算法实现代码，本项目在代码编写上尽量不使用复杂的语法（如大部分时候直接使用基本数据类型，而不是泛型），让大家在阅读代码时将注意力集中在算法实现本身，而不是语言特定语法中；
- 注释：为便于阅读，代码尽可能包含详尽的注释。一般一个文件就是一个特定算法实现，在该文件顶部会包含一段注释，说明算法名称、说明、算法实现思路。另外大部分函数以及函数内部也都会包含详细的注释说明算法实现逻辑；
- 目录：
  - 每个算法都在下方目录中有对应索引，方便快速检阅；
  - 一个算法可能属于多个目录，如归并算法同时属于“排序”和“分治算法”；
  - 正因为如此，src 中并没有对各算法做进一步的目录划分；

**相关算法和数据结构持续更新中，欢迎参与。**

目录
------

### 数据结构:
- [堆](./src/heap.ts)

### 排序：
- [插入排序](./src/insert-sort.ts)
- [选择排序](./src/select-sort.ts)
- [归并排序](./src/merge-sort.ts)
- [堆排序](./src/heap-sort.ts)

### 动态规划：
- [最大子数组（O(n)复杂度解法）](./src/maximum-subarray2.ts)

### 贪心算法：

### 分治算法：
- [归并排序](./src/merge-sort.ts)
- [逆序对](./src/inversion-pair.ts)
- [最大子数组（最大子序和）](./src/maximum-subarray1.ts)
