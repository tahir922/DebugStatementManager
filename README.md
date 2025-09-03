# Debug-Statement-Manager
Debug Statement Manager is an open-source Unity Editor extension that helps you automatically manage UnityEngine.Debug statements across your project.
✨ Features

Comment out all Debug statements (Debug.Log, Debug.LogError, etc.).

Wrap debug calls with #if UNITY_EDITOR so they only run in the editor.

Restore your original files from safe backups.

Dry-run mode for preview before applying changes.

🚀 Installation

Clone or download this repository into Assets/DebugStatementManager/.

Open via Unity menu: Tools → Debug Statement Manager.

📖 Usage

Select the folder to scan (default = Assets/).

Click Scan Project.

Preview and apply one of the following:

Comment All

Make Editor-Only

Uncomment (Restore)

Backups are stored in Assets/DebugToolBackups/.

⚠️ Notes

Editor-only tool — will not be included in builds.

Always commit your project before applying changes.
