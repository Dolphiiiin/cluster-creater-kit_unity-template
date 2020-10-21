# Changelog
All notable changes to this project template will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [4.2.8] - 2020-02-18
- Stopped using the legacy probe sample count. 

## [4.2.7] - 2020-02-12
- EditorSettings.lineEndingsForNewScripts property now defaults to OSNative. 

## [4.2.6] - 2020-01-15
- Turn off Auto generate lighting on the Sample Scene since it is not needed. 

## [4.2.5] - 2019-10-10
- Enlighten and realtime GI is being deprecated and we should not have it on by default.

## [4.2.4] - 2019-09-18
- ProjectSettings files are all serialized as text to match the default.

## [4.2.3] - 2019-09-11
- Setting m_AllowEnlightenSupportForUpgradedProject in GraphicsSettings.asset to false to make sure that new projects can't support Enlighten features for SRPs. 

## [4.2.2] - 2019-08-09
- Added Stadia to QualitySettings.asset

## [4.2.1] - 2019-08-05
- PlayerSettings.graphicsJobs is now false for Mac, iOS, Android, tvOS platforms

## [4.2.0] - 2019-06-03
- PlayerSettings.graphicsJobs property now defaults to true
- Added internal editor test for CI template validation

## [4.1.0] - 2019-05-13
- Testing new version in updated CDS. 
- Removing dependencies from manifest so the editor will populate new defaults on load. 

## [4.0.0] - 2019-05-13
- Version bump to match editor version bump while migrating repository. 

## [3.1.2] - 2019-03-15
- Fixed incorrect default property setting for ProjectSettings.SupportedNpadStyles 

## [3.1.1] - 2019-03-13
- PlayerSettings.legacyClampBlendShapeWeights property now defaults to false.

## [3.1.0] - 2019-03-12
- Updating text mesh pro version tp 2.0.0.

## [3.0.1] - 2019-03-05
- PlayerSettings.displayResolutionDialog property now defaults to false.

## [3.0.0] - 2019-02-12
- Removing deprecated packages from manifest

## [2.1.0] - 2019-02-04
- Corrected some default values in project settings.

## [2.0.0] - 2019 - 01 - 30
- Enabled HoloLens `depthBufferSharingEnabled` by default.

## [1.0.11] - 2019 - 01 - 22
- Removed unneeded packages from manifest

## [1.0.10] - 2018 - 12 - 06
- Android: enable Vulkan, disable x86
- Update new project templates to use 4.x scripting runtime
- Updated default manifest entries

## [1.0.9] - 2018-11-08
- Physics.reuseCollisionCallbacks property now defaults to true.
- Physics2D.reuseCollisionCallbacks property now defaults to true.
- Physics.autoSyncTransforms property now defaults to false.
- Physics2D.autoSyncTransforms property now defaults to false.

## [1.0.8] - 2018-24-10
- AndroidTVCompatibility to false

### Changed
- Oculus XR settings default to dash support and depth export enabled.

## [1.0.7] - 2018-24-09

### Changed
- Oculus XR settings default to dash support and depth export enabled.

## [1.0.6] - 2018-19-09

### Changed
- Removing Preview tag

## [1.0.4] - 2018-17-07

### Changed
- Deleting scene file so camera and directional light are once more generated from code

## [1.0.3] - 2018-17-07

### Changed
- moved to package format
- set camera tag

## [1.0.2] - 2018-06-06

### Changed
- removing forceIntoRenderTexture
- removing "UNITY_POST_PROCESSING_STACK_V2" from Player Settings' Scripting Define Symbols field since post processing is not in this scene

## [1.0.1] - 2018-xx-xx

### Added
- blendshape clamp

## [1.0.0] - 2018-25-02

### Added 
- empty 3D project*Unity Package \com.unity.template3d*. 
