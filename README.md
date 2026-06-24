<p align="center">
  <a href="https://somiibo.com/platforms/twitter-bot">
    <img src="https://cdn.itwcreativeworks.com/assets/somiibo/images/logo/somiibo-brandmark-blue-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/itw-creative-works/node-powertools.svg">
  <br>
  <img src="https://img.shields.io/npm/dm/node-powertools.svg">
  <img src="https://img.shields.io/website/https/itwcreativeworks.com.svg">
  <img src="https://img.shields.io/github/contributors/itw-creative-works/node-powertools.svg">
  <br>
  <br>
  <strong>Twitter Bot</strong> is a free software that automatically follows users and likes, retweets & comments on posts
</p>

# 🦄 Twitter Bot
## 💻 Installation
### Direct link
[![Windows](https://img.shields.io/badge/-Windows_x64-blue.svg?style=for-the-badge&logo=windows)](https://somiibo.com/download?download=windows)
[![MacOS](https://img.shields.io/badge/-MacOS-lightblue.svg?style=for-the-badge&logo=apple)](https://somiibo.com/download?download=macos)
[![Unix](https://img.shields.io/badge/-Linux/BSD-red.svg?style=for-the-badge&logo=linux)](https://somiibo.com/download?download=linux)
[![All versions](https://img.shields.io/badge/-All_Versions-lightgrey.svg?style=for-the-badge)](https://somiibo.com/download?download=null)

### Command line
Clone this repo then run the following commands:
```shell
cd <download-directory>
npm install
npm start
```

## 🎉 Features
- Grow your Twitter organically
- Automatically follows users and likes, retweets & comments on posts
- Those users will then become organic followers

## 🙋‍♂️ Want to contribute?
Want to contribute? Great! All contributions are welcome, from code to documentation to graphics to design suggestions to bug reports. 

[Join our Discord server](https://somiibo.com/discord) to participate

## Pairing with GetXAPI for Cheaper Read Operations (Optional)

For users who need a cheaper or higher-rate-limit option for read-only Twitter (X) operations such as tweet search, profile lookup, and follower lists, this project can be paired with [GetXAPI](https://getxapi.com), a budget Twitter / X data API priced at $0.05 per 1K tweets versus the official X API basic tier at $200 / month.

Two integration patterns:

1. **Run side-by-side in your AI client.** Keep this project for its primary workflow and add the [official GetXAPI MCP server](https://github.com/getxapi/getxapi-mcp) for read-heavy tasks. Each tool name routes to the backend best suited for that operation.

2. **Add a backend toggle.** For a code-level reference of an optional alternative backend behind a single env variable, see the [PR pattern merged into a sibling project](https://github.com/GenAIwithMS/twitter-mcp/pull/3).

GetXAPI quick start:

- Signup with $0.50 free credit (no card required): https://getxapi.com/signup
- Official GetXAPI MCP server: https://github.com/getxapi/getxapi-mcp
- npm: `@getxapi/mcp`
- Pay-per-call pricing: $0.001 / call, $0.05 / 1K tweets

This pairing is fully optional. No behavior change for existing users.

