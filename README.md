https://levelup.gitconnected.com/prototyping-large-language-model-llm-applications-using-drag-and-drop-components-4bc3ac2b4a46

Common issues

- **Linux, Fedora:** Make sure some libraries are installed. Source: https://github.com/oobabooga/text-generation-webui/issues/1534

```
g++ gdb make ninja-build rsync zip gcc
```

- **Mac:** Make sure to set some environment variables. Source: https://github.com/rails/rails/issues/38560

```bash
export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES
```

https://levelup.gitconnected.com/langflow-prototyping-a-llm-based-openai-application-using-your-own-data-45054d9b4278