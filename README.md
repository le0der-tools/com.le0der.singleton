# Le0der 单例工具包（Singleton Toolkit）

这是一个轻量级的 Unity 单例工具，支持两种常用的单例实现方式：

- `Singleton<T>`：用于纯 C# 类的线程安全单例
- MonoSingleton<T>`：用于继承自 MonoBehaviour 的单例类

该工具已按 Unity Package Manager（UPM）规范封装，可通过 Git 地址直接集成到 Unity 项目中。

---

## 📦 包信息
**包名**：`com.le0der.singleton`

**最低支持 Unity 版本**：`2020.3` 

**作者**：[Le0der](https://github.com/le0der)

---

## ✨ 功能特色

- ✅ 支持纯 C# 单例类，线程安全、无需 Mono 依赖
- ✅ 支持 Unity MonoBehaviour 单例类，自动创建 GameObject 并常驻场景
- ✅ 防止重复创建，自动销毁冗余实例
- ✅ 无额外依赖，可独立使用

---

## 📥 安装方式

你可以通过以下任一方式将该工具包集成到你的 Unity 项目中：

---
### ✅ 方法 1：使用 Unity 编辑器内的 Package Manager 添加 Git 地址（推荐）

1. 打开 Unity 的菜单：Window > Package Manager

2. 点击左上角的 + 号按钮

3. 选择 Add package from Git URL...

4. 输入：
```arduino
https://github.com/le0der-tools/com.le0der.singleton.git
```
### ✅ 方法 2：使用 Git URL 添加依赖

1. 打开你的 Unity 项目
2. 编辑文件：`Packages/manifest.json`
3. 在 `"dependencies"` 节点中添加如下内容：

```json
"com.le0der.singleton": "https://github.com/le0der-tools/com.le0der.singleton.git"
```
