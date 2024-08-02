[toc]

# Typora Theme - Marble

## 主题特点

- 采用**自然矿石色系配色**，视觉效果柔和。[^1]
- 字体较为美观
  - 采用*霞鹜文楷*取代~~思源宋体~~作为中文字体，英文使用[Cantarell](https://fonts.google.com/specimen/Cantarell)字体。
  - 代码字体使用 ==Fira Code==。链接：https://github.com/tonsky/FiraCode

---

> 下面是其他的样式演示：

对于 `main()`一类的行内代码和$\mathrm{e}^{\mathrm{i} \pi} + 1 = 0$一类的行内公式，Marble 有良好的渲染。公式块和代码块也是如此。

### 公式块

$$
\Gamma (z) := \int _{0} ^{+ \infty} x^{z - 1} \mathrm{e} ^ {-x} \mathrm{d}x,\mathrm{Re}(z) > 0.
$$

### 代码块

```c++
#include <iostream> // 引入头文件
using namespace std;

int main()
{
    cout << "hello world!" << endl;
    return 0;
}
```

### 表格

| 编程语言   | 类型   | 发布年份 | 主要用途           | 代码示例                                 |
| ---------- | ------ | -------- | ------------------ | ---------------------------------------- |
| Python     | 解释型 | 1991     | 通用编程、数据科学 | `print("Hello, World!")`               |
| Java       | 编译型 | 1995     | 跨平台应用开发     | `System.out.println("Hello, World!");` |
| C++        | 编译型 | 1983     | 系统编程、游戏开发 | `cout << "Hello, World!" << endl;`     |
| JavaScript | 解释型 | 1995     | 前端开发、后端开发 | `console.log("Hello, World!");`        |
| Ruby       | 解释型 | 1995     | Web开发、脚本编程  | `puts "Hello, World!"`                 |
| Swift      | 编译型 | 2014     | iOS/macOS应用开发  | `print("Hello, World!")`               |

### 图像

![图源：Unsplash](imgs/demopic.avif)

1. Marble 的意思是大理石，这个词概括了主题的风格，也致敬了原本的 Lapis 主题。
2. 但是我们的主题还有需要改进的地方。

- [ ] 对黑暗模式的支持
- [ ] 样式的进一步改良
- [ ] 向 Typora 主题商店提交这一主题
- [ ] ……

[^1]: 脚注：我们在代码注释中列出了一些元素的配色来源。
