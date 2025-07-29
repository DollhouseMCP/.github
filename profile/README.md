# DollhouseMCP Organization

## Professional AI Persona Management Platform

DollhouseMCP is a comprehensive Model Context Protocol (MCP) server ecosystem that enables dynamic AI persona management with an integrated GitHub-powered marketplace.

### 🎯 Our Mission

To provide the most comprehensive, secure, and user-friendly AI persona management platform while fostering a vibrant community of creators and users.

> **Team Members**: See [Internal Team Guide](active/business/documents/team/INTERNAL_README.md) for internal repositories and resources.

---

## 🎭 What is DollhouseMCP?

**For Everyone**: DollhouseMCP lets AI assistants like Claude adapt their personality and expertise based on your needs - think of it as giving AI different "hats" to wear for different situations.

**For Developers**: A production-ready MCP server implementation with 23+ tools for complete persona lifecycle management, following Anthropic's Model Context Protocol specification.

**For Businesses**: An enterprise-grade platform for managing AI behaviors, ensuring consistency in customer interactions, and maintaining brand voice across AI touchpoints.

---

## 📦 Our Public Projects

### **[mcp-server](https://github.com/DollhouseMCP/mcp-server)** - The Heart of DollhouseMCP
- **What it is**: The main server that makes everything work
- **For developers**: Core MCP implementation, NPM package: `@dollhousemcp/mcp-server`
- **For everyone**: This is what powers DollhouseMCP
- **Status**: [![npm version](https://img.shields.io/npm/v/@dollhousemcp/mcp-server.svg)](https://www.npmjs.com/package/@dollhousemcp/mcp-server) [![Tests](https://github.com/DollhouseMCP/mcp-server/actions/workflows/core-build-test.yml/badge.svg)](https://github.com/DollhouseMCP/mcp-server/actions)

### **[collection](https://github.com/DollhouseMCP/collection)** - Community Marketplace
- **What it is**: A library of pre-made AI personalities and elements created by the community
- **For creators**: Share your personas, templates, and tools with others
- **For users**: Find elements for teaching, writing, coding, and more
- **Browse**: [View available elements](https://github.com/DollhouseMCP/collection/tree/main/library)

### **[developer-kit](https://github.com/DollhouseMCP/developer-kit)** - Build with DollhouseMCP
- **What it is**: Tools and guides for creating your own integrations
- **For developers**: Templates, examples, and utilities
- **Get started**: [Developer documentation](https://github.com/DollhouseMCP/developer-kit/blob/main/docs/getting-started.md)

---

## 🚀 Getting Started

### For Users

1. **Install Claude Desktop** or another MCP-compatible AI assistant
2. **Configure MCP** to use DollhouseMCP server
3. **Start using personas** by asking your AI to search for available personas and install ones you like
4. **Create elements** instantly by describing what you need

[📖 Full Setup Guide](https://github.com/DollhouseMCP/mcp-server/blob/main/docs/QUICK_START.md)

### For Independent Developers

```bash
# Clone and set up the MCP server
git clone https://github.com/DollhouseMCP/mcp-server.git
cd mcp-server
npm install
npm test

# Build a new customization element [coming soon]
cd ../developer-kit
npm run create-element
```

[🛠️ Developer Documentation](https://github.com/DollhouseMCP/mcp-server/blob/main/docs/DEVELOPER_GUIDE.md)

---

## 📊 Platform Statistics

- 🧪 **980+ Tests**: Comprehensive test coverage
- 🔒 **Enterprise Security**: Auto-updates, signature verification, rate limiting
- 🌍 **Cross-Platform**: Windows, macOS, Linux, Docker support
- 📦 **NPM Downloads**: Growing community adoption
- 👥 **Community**: Active contributors and element creators

---

## 🤝 Contributing

We welcome contributions from developers, designers, writers, and community members!

### Ways to Contribute

- **Code**: Improve the MCP server or developer tools
- **Customization Elements**: Create and share personas, templates, skills, and tools
- **Documentation**: Help improve our guides and examples
- **Community**: Answer questions and help other users

See [CONTRIBUTING.md](https://github.com/DollhouseMCP/mcp-server/blob/main/CONTRIBUTING.md) for guidelines.

---

## 🤖 For AI Agents

```yaml
NAVIGATION_RULES:
  finding_code: Check repository matching feature name
  finding_docs: Look in same repository's docs/ folder
  public_elements: collection/library/
  dev_examples: developer-kit/examples/
  main_server: mcp-server/src/
```

---

## 📫 Contact & Support

- **Founder**: [Mick Darling](https://github.com/mickdarling)
- **Support**: [GitHub Issues](https://github.com/DollhouseMCP/mcp-server/issues)
- **Discussions**: [GitHub Discussions](https://github.com/DollhouseMCP/mcp-server/discussions)
- **Website**: https://dollhousemcp.com (coming soon)

---

## 📜 License

DollhouseMCP is open source software licensed under AGPL-3.0. See individual repositories for specific license details.

---

*Building the future of AI persona management, one personality at a time.* 🎭

**Last updated**: July 29, 2025