# CodeBuddy CN Editor Package for Unity

This package provides Unity integration for CodeBuddy CN editor, a powerful AI-powered code editor.

## Features

- Automatic discovery of CodeBuddy CN installations
- Proper C# project generation for IntelliSense support
- Debugging capabilities with Unity
- File opening and line navigation support
- Workspace management

## How to Install

1. Open Unity -> Window -> Package Manager
2. Click "+" at the top left corner
3. Select "Add package from git URL"
4. Insert `https://github.com/boxqkrtm/com.boxqkrtm.ide.codebuddy.git`
5. Click "Add"
6. Done!

## Usage

After installation:

1. Go to **Edit -> Preferences -> External Tools**
2. Set "External Script Editor" to "CodeBuddy CN"
3. Optionally enable "Reuse existing CodeBuddy window" to open files in an existing window

## Project Generation Settings

You can customize which packages generate .csproj files:
- Embedded packages
- Local packages
- Registry packages
- Git packages
- Built-in packages
- Local tarball
- Packages from unknown sources
- Player projects

Click "Regenerate project files" to apply changes.

## Important Notice for Users Updating from Older Versions

Starting from version **v2.0.24**, the package name has been changed from  
`com.unity.ide.cursor` to `com.unity.ide.CodeBuddy` to prevent potential issues with Unity regarding attribution.  
Violating these attribution rules may trigger warnings in Unity.  
If you experience errors during the update, please remove the existing package before reinstalling the new one to avoid conflicts.

## Troubleshooting

### CodeBuddy CN Not Found

Ensure CodeBuddy CN is installed in a standard location:
- **Windows**: `%LOCALAPPDATA%\Programs\CodeBuddy\` or `%PROGRAMFILES%\CodeBuddy\`
- **macOS**: `/Applications/CodeBuddy*.app`
- **Linux**: `/usr/bin/codebuddy` or `/usr/local/bin/codebuddy`

### IntelliSense Not Working

1. Click "Regenerate project files" in External Tools settings
2. Restart CodeBuddy CN
3. Ensure the Unity extension is installed in CodeBuddy CN

## Requirements

- Unity 2019.4 or later
- CodeBuddy CN editor installed

## License

MIT License
