# AI Mode Switcher （AI Personalities [EN/JP]）

## Open Sauce Links

[![Visit Difyshare](https://img.shields.io/badge/Visit-Difyshare-blue?style=for-the-badge)](https://difyshare.com/flow/6772a34b00331202d768)
[![Explore Diflowy](https://img.shields.io/badge/Explore-Diflowy-green?style=for-the-badge)](https://diflowy.greenerai.top/ja/explore/workflow/?id=3367zl5roibi2a4j)


## English Version

### **Inspiration**
This application is a simulation of feature modifications found in ChatGPT and Gemini models, recreated using Dify. It draws particular inspiration from Gemini's Gem ([details here](https://gemini.google.com)), using it as a reference to implement mode-switching functionality.


---


### **Key Features**

1. **Mode Switching**  
   - Users can switch between the following modes during a chat session:  
     - **Default**: Free conversation without any specific prompts.  
     - **AI Task**: Supports task management and execution.  
     - **AI M.T.**: Provides machine translation, primarily between Japanese and English.  
     - **AI Chat**: Enables character-based conversational modes.  
     - **AI Code**: Generates code in Python, JavaScript, and other specified languages.  
   - Modes can be selected via input or button clicks, and the selected mode remains active until explicitly changed.

2. **AI Models**  
   - The application uses Gemini 1.5 Flash as the default LLM with the following optimized settings:  
     - Memory Window Size: 10  
     - Max Tokens: 4096  
     - Temperature: 0.7 (optimized for speed and efficiency)  
   - Users can switch to other LLMs, such as ChatGPT or Claude, if needed.

3. **Additional Features**  
   - Automatically retries up to three times in case of errors and displays an error message if unresolved.  
   - Provides mode-change notifications and a user-friendly HTML button interface for quick adjustments.


---


### **How to Use**

1. **Start a Chat**  
   - Begin a conversation directly without entering any specific input.  
2. **Specify a Mode**  
   - Change the mode during a chat session through input or buttons. The selected mode remains active until modified.  


---


### **Dify Version Requirements**
No specific requirements are needed.


---


### **Copyright**
This workflow is based on Gemini Gem and has been adapted for Dify. It is freely available for use, modification, and sharing by both individuals and organizations.


---


## 日本語版

### **インスピレーション**
本アプリは、ChatGPTやGeminiモデルの機能変更をDifyで疑似的に再現したものです。特にGeminiのGem（[詳細はこちら](https://gemini.google.com)）を参考に、モード変更機能を設計しました。


---


### **主要機能**

1. **モード切り替え**  
   - チャット中に以下のモードを指定可能です：  
     - **デフォルト**：自由な会話（プロンプトなし）  
     - **AI Task**：タスク処理サポート  
     - **AI M.T.**：日本語・英語翻訳  
     - **AI Chat**：キャラクター設定を活かした会話  
     - **AI Code**：PythonやJavaScriptなどのコード生成  
   - モード指定は入力またはボタンで行い、設定内容はチャット内で長期的に保持されます。  

2. **AIモデル**  
   - デフォルトでGemini 1.5 Flashを使用。以下の設定に最適化されています：  
     - メモリウィンドウサイズ：10  
     - 最大トークン数：4096  
     - Temperature：0.7（高速応答重視）  
   - 必要に応じてChatGPTモデルやClaudeモデルに切り替え可能です。

3. **追加機能**  
   - エラー発生時は自動的に再試行（最大3回）。解決不能な場合、エラーメッセージを表示。  
   - モード変更時に変更内容を通知し、HTMLボタンで再変更を促すUIを提供。  


---


### **使い方**

1. **チャット開始**  
   - 開始画面で入力なしで自由な会話を開始可能。  
2. **モード指定**  
   - チャット中にモードを指定することで、機能を切り替えられます（モードは変更するまで有効）。  


---


### **Difyバージョン要件**
特別な要件はありません。


---


### **著作権**
本アプリは、Gemini Gemを参考にし、Dify向けに改変したものです。法人・個人問わず、自由に利用・改変・共有が可能です。


---


## 中文版

### **灵感来源**
本应用模拟了ChatGPT和Gemini模型的功能修改，并通过Dify实现。其设计灵感主要来源于Gemini的Gem（[详细信息](https://gemini.google.com)），并基于此实现了模式切换功能。


---


### **主要功能**

1. **模式切换**  
   - 用户可以在聊天过程中切换以下模式：  
     - **默认模式**：自由对话，无特定提示。  
     - **AI任务模式（AI Task）**：支持任务处理和执行。  
     - **AI翻译模式（AI M.T.）**：提供日语和英语之间的机器翻译。  
     - **AI角色模式（AI Chat）**：进行基于角色设置的对话。  
     - **AI代码模式（AI Code）**：生成Python、JavaScript等指定编程语言的代码。  
   - 模式可通过输入或按钮选择，选择的模式在未修改前将持续生效。

2. **AI模型**  
   - 默认使用Gemini 1.5 Flash作为语言模型，优化配置如下：  
     - 内存窗口大小：10  
     - 最大令牌数：4096  
     - 温度值（Temperature）：0.7（注重响应速度与效率）  
   - 用户可根据需要切换至其他语言模型，例如ChatGPT或Claude。

3. **附加功能**  
   - 当发生错误时，系统将自动重试最多三次，若问题未解决则显示错误提示。  
   - 在模式切换时提供切换通知，并通过HTML按钮展示便捷的调整选项。


---


### **使用方法**

1. **开始聊天**  
   - 无需输入任何特定内容即可直接开始自由对话。  
2. **选择模式**  
   - 在聊天过程中可通过输入或按钮切换模式，选定模式在未更改前将保持有效。  


---


### **Dify版本要求**
无特殊版本要求。


---


### **版权声明**
本工作流基于Gemini Gem设计，并针对Dify进行了改编。任何个人或组织均可自由使用、修改或共享。


---

