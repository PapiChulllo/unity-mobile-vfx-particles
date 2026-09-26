# Unity Mobile VFX Particles

**A Unity URP + Visual Effect Graph starter project with two sample VFX assets and almost no authored gameplay code.** The repo is effectively a template/sandbox for particle VFX exploration, not a game.

---

## Honest scope

What is actually here:

- Unity **2022.3.46f1** project shell with **URP** and **Visual Effect Graph**
- Two VFX Graph assets: `Assets/VFX/MyEffect.vfx`, `Assets/VFX/MyEffect 1.vfx`
- Default `Assets/Scenes/SampleScene.unity` plus URP settings under `Assets/Settings/`
- Template **TutorialInfo** scripts only (`Readme.cs` / `ReadmeEditor.cs`) — Unity’s project-readme helpers, not gameplay

**Status / limitations:** little to no authored application code. No custom gameplay scripts, no documented mobile packaging steps in-repo, no automated tests. Unity was unavailable for Play mode or device verification in this documentation pass. Treat this as an asset/template snapshot, not a shipped VFX demo product.

## Tech stack

| Area | What it uses |
|---|---|
| Engine | **Unity** `2022.3.46f1` |
| Render pipeline | **URP** 14.0.11 |
| VFX | **Visual Effect Graph** 14.0.11 |
| Other packages | TextMesh Pro, Timeline, uGUI, Visual Scripting (manifest defaults) |

## What's in the project

| Item | Path | Notes |
|---|---|---|
| Sample VFX graphs | `Assets/VFX/MyEffect.vfx`, `MyEffect 1.vfx` | Primary content of interest |
| Sample scene | `Assets/Scenes/SampleScene.unity` | Default scene |
| URP / project settings | `Assets/Settings/`, `ProjectSettings/` | Template configuration |
| Tutorial readme helpers | `Assets/TutorialInfo/Scripts/` | Only C# in the repo (~2 files) |

### Code / system highlights

There is **no authored gameplay or custom VFX controller C#**. The only scripts are Unity’s TutorialInfo readme pair. Any particle look comes from the two `.vfx` assets and the VFX Graph package, not from custom code in this repository.

## Scenes

| Scene | Purpose |
|---|---|
| `Assets/Scenes/SampleScene.unity` | Default URP sample scene for viewing VFX in the Editor |

## Third-party assets

| Asset | Notes |
|---|---|
| Unity URP / VFX Graph template content | Project shell, TutorialInfo, settings |
| `MyEffect*.vfx` | Present under `Assets/VFX/`; no separate Asset Store license file is committed documenting provenance beyond the Unity packages |

## About this repository

Public portfolio entry under **PapiChulllo**. Documented honestly: **mostly template + VFX assets, little authored code.** Prefer other repositories in this account for gameplay or networking showcases.
