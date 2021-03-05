

1. 自定义一个 `Classloader`，加载一个 `Hello.xlass` 文件，执行 `hello` 方法



从 `Classloader` 到模块化，动态加载的插件机制:

1. 10-使用自定义 `Classloader` 机制，实现 `xlass` 的加载（`xlass` 提供材料）。
2. 20-实现 `xlass` 打包的 `xar`（类似 `class` 文件打包的 `jar`）的加载：`xar` 里是 `xlass`。
3. 30-基于自定义 `Classloader` 实现类的动态加载和卸载：需要设计加载和卸载。
4. 30-基于自定义 `Classloader` 实现模块化机制：需要设计模块化机制。
5. 30-使用 `xar` 作为模块，实现 `xar` 动态加载和卸载：综合应用前面的内容。



