# overall-architecture/group-1

[解析トップへ戻る](../../README.md)

このグループは表示用の区切りです。独立した実行モジュールではありません。


```mermaid
graph TD
    n-anthropic-c03a8d["anthropic\nanthropic"]
    n-api-a033a5["api\napi"]
    n-app-7d1043["app\napp"]
    n-auth-66a36e["auth\nauth"]
    n-cmake-934c9b["cmake\ncmake"]
    n-cmd-abac36["cmd\ncmd"]
    n-convert-20a70a["convert\nconvert"]
    n-discover-1eb0b8["discover\ndiscover"]
```

## 要素の説明

### n-anthropic-c03a8d

確認したパス: `anthropic`。配下の登録ファイルは3件。

- `anthropic/anthropic.go`（一覧のみ）
- `anthropic/anthropic_test.go`（一覧のみ）
- `anthropic/trace.go`（一覧のみ）

[詳細な図と説明を見る](n-anthropic-c03a8d/README.md)

### n-api-a033a5

確認したパス: `api`。配下の登録ファイルは12件。

- `api/client.go`（内容確認済み）
- `api/client_test.go`（一覧のみ）
- `api/examples/README.md`（一覧のみ）
- `api/examples/chat/main.go`（一覧のみ）
- `api/examples/generate-streaming/main.go`（一覧のみ）
- `api/examples/generate/main.go`（一覧のみ）
- `api/examples/multimodal/main.go`（一覧のみ）
- `api/examples/pull-progress/main.go`（一覧のみ）
- `api/metrics_test.go`（一覧のみ）
- `api/types.go`（一覧のみ）
- `api/types_test.go`（一覧のみ）
- `api/types_typescript_test.go`（一覧のみ）

[詳細な図と説明を見る](n-api-a033a5/README.md)

### n-app-7d1043

確認したパス: `app`。配下の登録ファイルは254件。

- `app/.gitignore`（一覧のみ）
- `app/README.md`（一覧のみ）
- `app/assets/app.ico`（一覧のみ）
- `app/assets/assets.go`（一覧のみ）
- `app/assets/background.png`（一覧のみ）
- `app/assets/setup.bmp`（一覧のみ）
- `app/assets/tray.ico`（一覧のみ）
- `app/assets/tray_upgrade.ico`（一覧のみ）
- `app/auth/connect.go`（一覧のみ）
- `app/cmd/app/AppDelegate.h`（一覧のみ）
- `app/cmd/app/app.go`（一覧のみ）
- `app/cmd/app/app_darwin.go`（一覧のみ）
- `app/cmd/app/app_darwin.h`（一覧のみ）
- `app/cmd/app/app_darwin.m`（一覧のみ）
- `app/cmd/app/app_darwin_test.go`（一覧のみ）
- `app/cmd/app/app_test.go`（一覧のみ）
- `app/cmd/app/app_windows.go`（一覧のみ）
- `app/cmd/app/claude_desktop_bindings_darwin.go`（一覧のみ）
- `app/cmd/app/claude_desktop_bindings_windows.go`（一覧のみ）
- `app/cmd/app/claude_desktop_installer_darwin.go`（一覧のみ）
- `app/cmd/app/claude_desktop_installer_darwin_test.go`（一覧のみ）
- `app/cmd/app/claude_desktop_status.go`（一覧のみ）
- `app/cmd/app/codex_app_bindings_darwin.go`（一覧のみ）
- `app/cmd/app/codex_app_bindings_windows.go`（一覧のみ）
- `app/cmd/app/codex_app_darwin.go`（一覧のみ）
- `app/cmd/app/codex_app_darwin_test.go`（一覧のみ）
- `app/cmd/app/codex_desktop_installer_darwin.go`（一覧のみ）
- `app/cmd/app/codex_desktop_installer_darwin_test.go`（一覧のみ）
- `app/cmd/app/menu.h`（一覧のみ）
- `app/cmd/app/webview.go`（一覧のみ）
- `app/cmd/squirrel/Info.plist`（一覧のみ）
- `app/darwin/Ollama.app/Contents/Info.plist`（一覧のみ）
- `app/darwin/Ollama.app/Contents/Library/LaunchAgents/com.ollama.ollama.plist`（一覧のみ）
- `app/darwin/Ollama.app/Contents/Resources/chatgpt.svg`（一覧のみ）
- `app/darwin/Ollama.app/Contents/Resources/claude.svg`（一覧のみ）

[詳細な図と説明を見る](n-app-7d1043/README.md)

### n-auth-66a36e

確認したパス: `auth`。配下の登録ファイルは1件。

- `auth/auth.go`（一覧のみ）

### n-cmake-934c9b

確認したパス: `cmake`。配下の登録ファイルは7件。

- `cmake/apply-git-patches.cmake`（一覧のみ）
- `cmake/generate_go_license.cmake`（一覧のみ）
- `cmake/local.cmake`（一覧のみ）
- `cmake/mlx/CMakeLists.txt`（一覧のみ）
- `cmake/mlx/CMakePresets.json`（一覧のみ）
- `cmake/vendor-mlx-c-headers.cmake`（一覧のみ）
- `cmake/windows-arm64-llvm-mingw.cmake`（一覧のみ）

### n-cmd-abac36

確認したパス: `cmd`。配下の登録ファイルは89件。

- `cmd/bench/README.md`（一覧のみ）
- `cmd/bench/bench.go`（一覧のみ）
- `cmd/bench/bench_test.go`（一覧のみ）
- `cmd/cloud_suggest.go`（一覧のみ）
- `cmd/cloud_suggest_test.go`（一覧のみ）
- `cmd/cmd.go`（一覧のみ）
- `cmd/cmd_launcher_test.go`（一覧のみ）
- `cmd/cmd_test.go`（一覧のみ）
- `cmd/config/config.go`（一覧のみ）
- `cmd/config/config_cloud_test.go`（一覧のみ）
- `cmd/config/config_test.go`（一覧のみ）
- `cmd/editor_unix.go`（一覧のみ）
- `cmd/editor_windows.go`（一覧のみ）
- `cmd/interactive.go`（一覧のみ）
- `cmd/interactive_test.go`（一覧のみ）
- `cmd/internal/fileutil/files.go`（一覧のみ）
- `cmd/internal/fileutil/files_test.go`（一覧のみ）
- `cmd/launch/account.go`（一覧のみ）
- `cmd/launch/claude.go`（一覧のみ）
- `cmd/launch/claude_desktop.go`（一覧のみ）
- `cmd/launch/claude_desktop_test.go`（一覧のみ）
- `cmd/launch/claude_test.go`（一覧のみ）
- `cmd/launch/cline.go`（一覧のみ）
- `cmd/launch/cline_test.go`（一覧のみ）
- `cmd/launch/codex.go`（一覧のみ）
- `cmd/launch/codex_app.go`（一覧のみ）
- `cmd/launch/codex_app_profile.go`（一覧のみ）
- `cmd/launch/codex_app_test.go`（一覧のみ）
- `cmd/launch/codex_test.go`（一覧のみ）
- `cmd/launch/command_test.go`（一覧のみ）
- `cmd/launch/context_window.go`（一覧のみ）
- `cmd/launch/context_window_test.go`（一覧のみ）
- `cmd/launch/copilot.go`（一覧のみ）
- `cmd/launch/copilot_test.go`（一覧のみ）
- `cmd/launch/deepseek_harness.go`（一覧のみ）

[詳細な図と説明を見る](n-cmd-abac36/README.md)

### n-convert-20a70a

確認したパス: `convert`。配下の登録ファイルは74件。

- `convert/convert.go`（一覧のみ）
- `convert/convert_bert.go`（一覧のみ）
- `convert/convert_commandr.go`（一覧のみ）
- `convert/convert_deepseek2.go`（一覧のみ）
- `convert/convert_deepseekocr.go`（一覧のみ）
- `convert/convert_embeddinggemma.go`（一覧のみ）
- `convert/convert_embeddinggemma_test.go`（一覧のみ）
- `convert/convert_gemma.go`（一覧のみ）
- `convert/convert_gemma2.go`（一覧のみ）
- `convert/convert_gemma2_adapter.go`（一覧のみ）
- `convert/convert_gemma3.go`（一覧のみ）
- `convert/convert_gemma3_test.go`（一覧のみ）
- `convert/convert_gemma3n.go`（一覧のみ）
- `convert/convert_gemma3n_test.go`（一覧のみ）
- `convert/convert_gemma4.go`（一覧のみ）
- `convert/convert_gemma4_test.go`（一覧のみ）
- `convert/convert_glm4moelite.go`（一覧のみ）
- `convert/convert_glm4moelite_test.go`（一覧のみ）
- `convert/convert_glmocr.go`（一覧のみ）
- `convert/convert_gptoss.go`（一覧のみ）
- `convert/convert_gptoss_test.go`（一覧のみ）
- `convert/convert_laguna.go`（一覧のみ）
- `convert/convert_laguna_test.go`（一覧のみ）
- `convert/convert_lfm2.go`（一覧のみ）
- `convert/convert_lfm2_test.go`（一覧のみ）
- `convert/convert_lfm2_vl.go`（一覧のみ）
- `convert/convert_lfm2_vl_test.go`（一覧のみ）
- `convert/convert_llama.go`（一覧のみ）
- `convert/convert_llama4.go`（一覧のみ）
- `convert/convert_llama_adapter.go`（一覧のみ）
- `convert/convert_llama_test.go`（一覧のみ）
- `convert/convert_mistral.go`（一覧のみ）
- `convert/convert_mistral_causal.go`（一覧のみ）
- `convert/convert_mistral_test.go`（一覧のみ）
- `convert/convert_mixtral.go`（一覧のみ）

[詳細な図と説明を見る](n-convert-20a70a/README.md)

### n-discover-1eb0b8

確認したパス: `discover`。配下の登録ファイルは25件。

- `discover/amd.go`（一覧のみ）
- `discover/amd_test.go`（一覧のみ）
- `discover/cpu_linux.go`（一覧のみ）
- `discover/cpu_windows.go`（一覧のみ）
- `discover/cuda_compat.go`（一覧のみ）
- `discover/cuda_compat_test.go`（一覧のみ）
- `discover/gpu.go`（一覧のみ）
- `discover/gpu_darwin.go`（一覧のみ）
- `discover/gpu_info_darwin.h`（一覧のみ）
- `discover/gpu_info_darwin.m`（一覧のみ）
- `discover/llama_server.go`（一覧のみ）
- `discover/llama_server_test.go`（一覧のみ）
- `discover/native_probe.go`（一覧のみ）
- `discover/native_probe_linux.go`（一覧のみ）
- `discover/native_probe_linux_nocgo.go`（一覧のみ）
- `discover/native_probe_platform.go`（一覧のみ）
- `discover/native_probe_stub.go`（一覧のみ）
- `discover/native_probe_test.go`（一覧のみ）
- `discover/native_probe_windows.go`（一覧のみ）
- `discover/runner.go`（一覧のみ）
- `discover/runner_test.go`（一覧のみ）
- `discover/types.go`（一覧のみ）
- `discover/vulkan.go`（一覧のみ）
- `discover/vulkan_refine_stub.go`（一覧のみ）
- `discover/vulkan_refine_windows.go`（一覧のみ）

[詳細な図と説明を見る](n-discover-1eb0b8/README.md)

