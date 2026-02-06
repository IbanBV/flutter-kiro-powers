# Flutter Powers Collection

Collection of Kiro Powers for Flutter development. Each Power provides specialized knowledge, tools, and best practices to accelerate Flutter application development.

## 🚀 Available Powers

| Power | Description | Keywords |
|-------|-------------|----------|
| [flutter-expert](./powers/flutter-expert/) | **Complete Flutter development** - BLoC/Cubit, easy_localization, GoRouter, testing, widgets, performance | flutter, dart, mobile, bloc, cubit |

## ⭐ flutter-expert

The `flutter-expert` power is the all-in-one power for Flutter development. It includes:

- **BLoC/Cubit State Management** - Always use Cubit for state (no Riverpod)
- **easy_localization** - Always use for internationalization
- **GoRouter Navigation** - Declarative routing and deep linking
- **Widget Patterns** - Const optimization, composition, responsive design
- **Project Structure** - Feature-first architecture with clean layers
- **Testing** - Unit tests, widget tests, Cubit tests, integration tests
- **Performance** - Profiling, optimization, and best practices

Use `flutter-expert` for any Flutter development task.

## 📦 Power Structure

```text
power-name/
├── POWER.md           # Main documentation with frontmatter
├── mcp.json           # MCP configuration (optional)
└── steering/          # Additional guides (optional)
    └── workflow.md
```

## 🔧 Installation

### From GitHub

1. Open Kiro IDE
2. Go to the Powers panel
3. Click "Import from GitHub"
4. Enter the specific Power URL

### Local

1. Clone this repository
2. In Kiro, import from the local Power folder

### Always Activate (Recommended)

Powers activate when keywords are mentioned in your prompt. To ensure `flutter-expert` activates for **all tasks** (including "fix issue 97"), create this file in your Flutter project:

**`.kiro/steering/flutter-project.md`**

```markdown
---
inclusion: always
---

# Flutter Project

This is a Flutter project. Always activate the **flutter-expert** Power for any code-related tasks.

```

This steering file ensures the Power activates even when your prompt doesn't contain Flutter-specific keywords.

## 📝 Create a New Power

1. Create a directory in `powers/`
2. Add a `POWER.md` with frontmatter:

```yaml
---
name: "My Power"
description: "Power description"
keywords:
  - keyword1
  - keyword2
---
```

3. Document workflows and best practices
4. (Optional) Add `mcp.json` if it includes an MCP server
5. (Optional) Add files in `steering/` for specific workflows

## 📚 Documentation

- [Create Powers](https://kiro.dev/docs/powers/create/)
- [Install Powers](https://kiro.dev/docs/powers/installation/)
- [Official examples](https://github.com/kirodotdev/powers)

## 🤝 Contributing

1. Fork this repository
2. Create your Power in `powers/your-power/`
3. Follow the structure and conventions
4. All documentation and code comments must be in English
5. Submit a Pull Request

## 📄 License

MIT
