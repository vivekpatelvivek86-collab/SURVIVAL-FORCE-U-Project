::: {align="center"}
# 鈿旓笍 SURVIVAL FORCE

### SURVIVE THE DROP. OUTPLAY THE OPPONENTS. BE THE LAST ONE STANDING.

An independent Android battle-royale game development project focused on
intense survival gameplay, mobile-friendly controls, and a
classic-inspired action experience.

`<br>`{=html}

`<img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-orange?style=for-the-badge" alt="Project status">`{=html}
`<img src="https://img.shields.io/badge/PLATFORM-ANDROID-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">`{=html}
`<img src="https://img.shields.io/badge/ENGINE-UNREAL%20ENGINE%205.4-313131?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine">`{=html}
`<img src="https://img.shields.io/badge/LANGUAGE-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">`{=html}

`<br>`{=html}`<br>`{=html}

**One battlefield. Limited resources. One goal: survive.**

[Overview](#-overview) 路 [Gameplay Vision](#-gameplay-vision) 路
[Development Status](#-development-status) 路
[Technology](#-technology-stack) 路
[Builds](#-android-builds-and-releases) 路 [Contributing](#-contributing)

`<br>`{=html}

猸� Follow the project to track development, review changes, and help
improve the experience. 猸�
:::

------------------------------------------------------------------------

## 馃幃 Overview

**SURVIVAL FORCE** is an independent game development project built
around the idea of a mobile survival shooter with a battle-royale feel.
The goal is to create an engaging, action-focused experience designed
with Android devices and touch-screen play in mind.

The project takes inspiration from the broader survival and
battle-royale genre while aiming to develop its own implementation,
presentation, gameplay systems, and identity. Its direction emphasizes
quick-to-understand controls, tactical movement, combat encounters,
exploration, and the pressure of staying alive in a hostile environment.

The project is associated with **Unreal Engine 5.4** and **C++**, with
**Android** as the intended target platform. Project files, source code,
assets, and configuration are being developed and validated over time. A
configured project is not automatically a working game: compilation,
packaging, installation, and real-device gameplay must each be tested
before they can be considered verified.

> **Development standard:** be transparent about what exists, test what
> is built, and publish only artifacts that have been checked.

## 馃幆 Project at a Glance

  -----------------------------------------------------------------------
  Item                                Details
  ----------------------------------- -----------------------------------
  Game title                          **SURVIVAL FORCE**

  Project category                    Independent survival /
                                      battle-royale-style game

  Intended platform                   Android

  Engine                              Unreal Engine 5.4

  Main programming language           C++

  Project hosting                     GitHub

  Input direction                     Touch-friendly mobile controls

  Current release status              No verified public APK release

  Development approach                Iterative implementation,
                                      validation, and testing
  -----------------------------------------------------------------------

## 鈿旓笍 Gameplay Vision

SURVIVAL FORCE is being shaped around the core tension of a survival
shooter: explore the environment, prepare for encounters, make tactical
decisions, and try to stay alive.

The following points describe the intended direction of the game. They
should not be read as a claim that every system is already implemented
or playable.

-   **馃獋 Survival-focused matches** --- work toward a match structure
    built around entering a combat area, finding useful resources, and
    surviving encounters.
-   **馃敨 Combat and weapons** --- develop responsive shooting and combat
    mechanics with clear feedback and controls suitable for mobile play.
-   **馃帓 Loot and equipment** --- work toward item collection and
    equipment systems that support player preparation and tactical
    choices.
-   **馃實 Exploration and environments** --- create spaces that encourage
    movement, discovery, positioning, and encounters.
-   **馃 AI opponents** --- explore bot-controlled opponents where
    supported by the implemented gameplay systems.
-   **馃摫 Mobile-first interaction** --- design interface elements and
    controls with touch input, screen sizes, and readability in mind.
-   **鈿欙笍 Performance awareness** --- evaluate graphics, memory use,
    loading, and responsiveness for a range of Android hardware.
-   **馃弫 Match flow** --- work toward a coherent experience from launch
    and menus through gameplay and match completion.

## 馃Л Design Principles

### Responsive mobile gameplay

Controls should be understandable and practical on a touchscreen. Button
placement, sizing, camera movement, and input responsiveness should be
evaluated on real devices rather than assumed from editor previews.

### Readable combat

Players should be able to understand what is happening during an
encounter. Visual feedback, weapon response, hit feedback, and interface
clarity are important areas to validate as combat systems develop.

### Survival and decision-making

The intended experience should reward awareness, positioning, resource
management, and thoughtful movement---not just rapid firing.

### Performance-conscious development

Android devices vary significantly in processing power, graphics
capability, memory, and thermal limits. Performance decisions should be
based on measurements and testing instead of unsupported FPS or
compatibility promises.

### Honest progress

A source file, asset, menu mock-up, or configuration setting does not
prove a feature works in a running build. Development claims should
reflect actual implementation and test results.

## 鉁� Development Status

The project is in development. The status below describes the current
verification position, not a promise that each planned gameplay system
already works.

  -----------------------------------------------------------------------
  Area                                Current status
  ----------------------------------- -----------------------------------
  Project identity and naming         Configured for **SURVIVAL FORCE**;
                                      check all references during future
                                      changes

  Android target                      Intended target; device
                                      compatibility not yet established

  Unreal project and source           Requires validation in the matching
                                      Unreal Engine environment

  Main menu and navigation            Runtime behavior must be verified

  Touch controls                      Requires gameplay and device
                                      testing

  Combat and weapons                  Implementation and runtime behavior
                                      must be verified

  Loot and equipment                  Implementation and runtime behavior
                                      must be verified

  AI opponents                        Gameplay behavior not yet verified

  Android packaging                   No verified installable APK release
                                      listed

  Physical-device testing             Pending a build that can be
                                      installed and tested

  Public release                      Not released
  -----------------------------------------------------------------------

**Status guide:** 馃煝 Verified 路 馃煛 In progress 路 馃數 Intended direction 路
鈿� Not yet verified

Status labels should be updated only when there is evidence from the
project, build output, or a reproducible test.

## 馃О Technology Stack

  -----------------------------------------------------------------------
  Technology                          Purpose
  ----------------------------------- -----------------------------------
  **Unreal Engine 5.4**               Intended game engine and project
                                      environment

  **C++**                             Native gameplay and project code

  **Android SDK**                     Android platform build tools

  **Android NDK**                     Native Android compilation
                                      toolchain

  **JDK**                             Java tooling required by the
                                      Android build environment

  **Git and GitHub**                  Source control, change history, and
                                      collaboration

  **GitHub Actions**                  Potential build automation when a
                                      compatible Unreal Engine
                                      environment is available
  -----------------------------------------------------------------------

Exact SDK, NDK, JDK, Gradle, CMake, and Build Tools requirements depend
on the selected Unreal Engine version and project configuration. Use the
engine's matching Android setup guidance and the actual build logs when
diagnosing problems.

## 馃彈锔� Project Structure

The exact directory layout can change as development continues. In a
typical Unreal Engine project, the main areas to look for include:

-   **`.uproject` file** --- the Unreal Engine project entry point.
-   **`Source/`** --- C++ modules and source code, when the project uses
    C++.
-   **`Config/`** --- project and platform configuration.
-   **`Content/`** --- game assets such as maps, materials, textures,
    audio, and interface resources.
-   **`Plugins/`** --- optional engine or project extensions.
-   **Build and automation files** --- scripts or workflows used to
    validate and package the project.

Not every project contains every directory. Preserve the actual project
structure and avoid renaming modules or asset paths without updating
their references.

## 馃摫 Android Compatibility & Performance

Android is the intended platform, but compatibility is not guaranteed
until a packaged build has been installed and tested on specific
devices.

Important factors include:

-   CPU and GPU capability
-   Available RAM and storage
-   Android version and device drivers
-   Rendering settings and graphics quality
-   Map and asset complexity
-   Shader compilation and loading behavior
-   Thermal throttling and sustained performance
-   Touch input, aspect ratio, and screen layout
-   Packaging configuration and native dependencies

No universal device-support list, guaranteed frame rate, or minimum-spec
claim is made without test evidence. When testing becomes available,
record the device model, Android version, graphics settings, observed
performance, crashes, and known limitations.

## 馃摝 Android Builds and Releases

::: {align="center"}
### 馃毀 NO VERIFIED PUBLIC APK RELEASE YET

An APK should be linked here only after the build has produced a real
artifact and the file has been checked. Runtime claims should follow
installation and testing.

**[鉃★笍 View GitHub Releases](../../releases)**
:::

A useful release should include:

-   Version number and release date
-   APK artifact, if a build has been successfully produced
-   Source commit or build reference
-   Installation instructions
-   Android versions and devices tested
-   Known issues and limitations
-   Relevant build notes

A successful automation workflow alone does not prove that an APK exists
or that the game runs. Verify the artifact, install it, and test the
actual gameplay separately.

## 鈿欙笍 Build Automation

The project may use GitHub Actions to make build attempts more
repeatable. A reliable workflow should:

1.  Check out the correct source revision.
2.  Locate and validate the Unreal project.
3.  Confirm the required engine and Android tools are available.
4.  Run the appropriate Unreal build and packaging commands.
5.  Stop and report useful logs if compilation, cooking, or packaging
    fails.
6.  Confirm the expected APK exists and is non-empty before uploading
    it.
7.  Preserve logs and identify the source revision associated with each
    artifact.

### Unreal Engine environment

Standard GitHub-hosted runners do not automatically provide a
ready-to-use Unreal Engine 5.4 installation. The workflow needs a
compatible environment where the engine is installed and accessible,
such as a properly configured build machine or self-hosted runner.
Engine access, storage, memory, Android dependencies, build duration,
and project errors can all affect success.

A workflow file alone cannot install or guarantee the full engine build
environment. Build status and release notes must report the actual
command results and artifacts.

## 馃柤锔� Screenshots and Media

Screenshots should represent the actual running game or editor. Concept
art, reference images, and promotional artwork should be labelled
clearly and must not be presented as genuine gameplay footage.

As verified visuals become available, add them here with a short caption
and, where possible, the build version or source revision they
represent.

## 馃И Testing & Quality

Testing should cover more than whether the project opens.

-   **Project validation:** confirm that the `.uproject` file, modules,
    configuration, and referenced assets are available.
-   **Compilation:** record the engine version, build target,
    configuration, and actual errors.
-   **Packaging:** confirm that the Android packaging process completes
    and creates the expected output.
-   **Installation:** install the APK on a physical device and record
    the result.
-   **Startup:** check launch behavior, loading, crashes, and error
    messages.
-   **Input:** test movement, camera control, firing, and interface
    interaction where implemented.
-   **Performance:** observe frame pacing, memory use, loading times,
    heat, and stability.
-   **Regression checks:** retest affected areas after changes to names,
    assets, configuration, or source code.

Report problems with enough detail that another developer can reproduce
them.

## 馃 Contributing

Suggestions and technical feedback are welcome. Useful contributions
include:

-   馃悰 Reproducible bug reports
-   馃洜锔� Build troubleshooting backed by logs
-   馃摫 Android device test results
-   馃摉 Documentation improvements
-   鈾� Interface clarity and usability feedback
-   馃挕 Focused suggestions for gameplay and performance

### Bug report checklist

When relevant, include:

1.  A clear description of the problem.
2.  Steps to reproduce it.
3.  Expected behavior and actual behavior.
4.  Unreal Engine version and build configuration.
5.  Device model and Android version.
6.  Relevant logs or genuine screenshots.
7.  The tested release version or commit.

Do not publish passwords, access tokens, signing keys, private
credentials, or other secrets in public issues or commits.

## 馃攼 Assets, Licensing & Distribution

Use original assets, assets you have permission to use, or third-party
materials whose licenses allow the intended use. Keep any required
copyright notices and attributions.

Do not assume that every asset included in a project is freely
redistributable. Review the terms for engine content, plugins, fonts,
audio, textures, models, and other third-party materials before
distributing a build.

No project-wide open-source license is specified here. Unless a license
is added, do not assume the project code or assets may be reused,
modified, redistributed, or used commercially. Any applicable
third-party licenses continue to apply.

## 鈿栵笍 Independence Disclaimer

**SURVIVAL FORCE** is an independent game development project. It is not
an official product of, and is not affiliated with, sponsored by, or
endorsed by Garena or any other third-party game publisher.

The project aims to establish its own name, implementation,
presentation, and appropriately licensed assets. Any references to other
games or trademarks are for identification or genre context only; those
marks remain the property of their respective owners.

No claim is made that the project reproduces another game's proprietary
content, provides identical gameplay, or is compatible with every
Android device.

## 馃摐 License

**Project license: not specified yet.**

A clear license should be added before inviting others to reuse or
redistribute project code. Until then, permission to reuse the project
should not be assumed. Third-party assets and dependencies remain
subject to their own licenses.

------------------------------------------------------------------------

::: {align="center"}
# 鈿旓笍 SURVIVAL FORCE

### Explore. Adapt. Fight to survive.

**INDEPENDENT ANDROID GAME PROJECT 路 IN DEVELOPMENT**

`<br>`{=html}

Follow the repository for verified development updates, technical notes,
and future release announcements.

`<br>`{=html}

`<sub>`{=html}Build carefully 路 Test honestly 路 Improve
continuously`</sub>`{=html}
:::
