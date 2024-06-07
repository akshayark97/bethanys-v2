# To run local server
```json-server db.json --host 192.168.0.109```

# To build web
```npx expo export -p web```

```npx serve dist --single```

# Compiling a Release build

```npm install -g eas-cli```

```eas login```

```eas build:configure```

```eas build --platform android```

# Testing on physical device

```eas login```

```eas build --profile preview --platform android```