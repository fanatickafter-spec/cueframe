# CueFrame

**CueFrame** is a Windows desktop utility for preparing media for **Disguise Designer** and **Resolume**. Check a folder before ingest, manage file versions and generate frame-accurate IN / LOOP pairs.

## Workflows

**Media Check** opens on startup. Select a folder, server profile and FPS preset, then click **Check**. Format and frame rate are evaluated separately. The **Problems only** filter shows the files that need attention.

**Smart Copy** matches names within the corresponding destination subfolder and picks the next version. **Rename** applies a naming rule to a batch.

**IN / LOOP** trims videos by frame number, preserves the folder structure and assigns one version to both outputs. Each output is checked before the pair is saved.

## Installation

1. Download **CueFrame_11.0.0_Windows.zip** from [Releases](https://github.com/fanatickafter-spec/cueframe/releases).
2. Extract the entire folder to a writable location.
3. Launch **CueFrame.exe**. The package includes FFmpeg and FFprobe.

## Compatibility

Media Check evaluates the file container, codec variant and selected FPS rules using FFprobe. It flags HAP Q Alpha for Disguise and uses DXV3 as the video delivery profile for Resolume. PNG and JPEG are supported by both profiles.

CueFrame was previously called RenameTool.
