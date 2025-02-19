#### 1.2.28
- 2023-08-29 - [commits](https://github.com/koral--/android-gif-drawable/compare/v1.2.27...v1.2.28)
- Remove check for > 1 frame when seeking, fixes [(#830)](https://github.com/koral--/android-gif-drawable/pull/830), thanks @hgourvest for reporting
- Update dependency versions
- Update Android Gradle plugin to 8.1.1

#### 1.2.27
- 2023-07-03 - [commits](https://github.com/koral--/android-gif-drawable/compare/v1.2.26...v1.2.27)
- Revert java to 1.8, fixes [(#826)](https://github.com/koral--/android-gif-drawable/pull/826), thanks @droplet-js for reporting

#### 1.2.26
- 2023-06-30 - [commits](https://github.com/koral--/android-gif-drawable/compare/v1.2.25...v1.2.26)
- Update dependency versions
- Update NDK to 25.2.9519653
- Update Android Gradle plugin to 8.0.2
- Use Java 17 for building
- Switch to upstream ReLinker and update to 1.4.5
- Update compile and target SDK to 33

#### 1.2.25
- 2022-08-18 - [commits](https://github.com/koral--/android-gif-drawable/compare/v1.2.24...v1.2.25)
- Fix sample size not taken into account [(#797)](https://github.com/koral--/android-gif-drawable/pull/797) [(#798)](https://github.com/koral--/android-gif-drawable/pull/798)
- Stop further decoding on error [(#801)](https://github.com/koral--/android-gif-drawable/pull/801)
- Clear GifTextureView when removing source [(#745)](https://github.com/koral--/android-gif-drawable/pull/745)
- Fix negative current position [(#657)](https://github.com/koral--/android-gif-drawable/pull/657)

#### 1.2.24
- 2022-01-17 - [commits](https://github.com/koral--/android-gif-drawable/compare/v1.2.23...v1.2.24)
- Limit comment maximum length [(#766)](https://github.com/koral--/android-gif-drawable/pull/766)
- Update dependency versions
- Update compile and target SDK to 31

<sup><sup>*Release notes were automatically generated by [Shipkit](http://shipkit.org/)*</sup></sup>

#### 1.2.23
 - 2021-03-08 - [1 commit](https://github.com/koral--/android-gif-drawable/compare/v1.2.22...v1.2.23) by [Dwaipayan Munshi](https://github.com/dwaipayan05) - published to [![Bintray](https://img.shields.io/badge/Bintray-1.2.23-green.svg)](https://bintray.com/koral/maven/pl.droidsonroids.gif:android-gif-drawable/1.2.23)
 - Updated Latest Version of gif-drawable in Readme.md [(#765)](https://github.com/koral--/android-gif-drawable/pull/765)

#### 1.2.22
 - 2021-02-03 - [2 commits](https://github.com/koral--/android-gif-drawable/compare/v1.2.21...v1.2.22) by [Karol Wrótniak](https://github.com/koral--) - published to [![Bintray](https://img.shields.io/badge/Bintray-1.2.22-green.svg)](https://bintray.com/koral/maven/pl.droidsonroids.gif:android-gif-drawable/1.2.22)
 - Maintenance [(#749)](https://github.com/koral--/android-gif-drawable/pull/749)
 - have you any plan about new version giflib? like usage of realloc() in case of failure [(#743)](https://github.com/koral--/android-gif-drawable/issues/743)

#### 1.2.21
 - 2020-08-26 - [1 commit](https://github.com/koral--/android-gif-drawable/compare/v1.2.20...v1.2.21) by [默默](https://github.com/wangqiang1588) - published to [![Bintray](https://img.shields.io/badge/Bintray-1.2.21-green.svg)](https://bintray.com/koral/maven/pl.droidsonroids.gif:android-gif-drawable/1.2.21)
 - fix bug "Abort message: 'attempted to close file descriptor 165, expe… [(#747)](https://github.com/koral--/android-gif-drawable/pull/747)

#### 1.2.20
 - Update NDK version to 21 [(#734)](https://github.com/koral--/android-gif-drawable/pull/734)
 - Fix artifacts when disposal to previous frame method is used
 - Revert "Let's clear rasterBits if failed to read frame's header." and… [(#714)](https://github.com/koral--/android-gif-drawable/pull/714)


### 1.2.19
- Fix out of bounds read/write in gif decoding - [#697](https://github.com/koral--/android-gif-drawable/issue/697)

### 1.2.18
- Add AndroidX annotations warnings supperssion - [#671](https://github.com/koral--/android-gif-drawable/issue/671)
- Use relocated ReLinker - [#665](https://github.com/koral--/android-gif-drawable/issues/665)
- Fix double free on 0-sized images - [#673](https://github.com/koral--/android-gif-drawable/pull/673)
- Fix heap corruption caused by malformed images - [#678](https://github.com/koral--/android-gif-drawable/pull/678)
- Do not give up when image contains unknown record type - [#667](https://github.com/koral--/android-gif-drawable/issues/667)
- Gradle wrapper regenerated with 5.6.2
- Android Gradle plugin updated to 3.5.0

### 1.2.17
- Built-in ReLinker part replaced with complete ReLinker 1.3.1 - [#636](https://github.com/koral--/android-gif-drawable/issue/636)
- Android Gradle plugin updated to 3.4.1
- Gradle wrapper regenerated with 5.4.1

### 1.2.16
- Fixed setting color drawable from Java code - [#606](https://github.com/koral--/android-gif-drawable/issue/606)
- Fixed extraneous file descriptor closing - [#600](https://github.com/koral--/android-gif-drawable/issue/600)
- Fixed missing null check for NewGlobalRef - [#594](https://github.com/koral--/android-gif-drawable/issue/594)
- Fixed missing free of info buffer - [#595](https://github.com/koral--/android-gif-drawable/issue/595)
- Android Gradle plugin updated to 3.2.1
- Gradle wrapper regenerated with 4.10.2
- NDK updated to r18, minimum API level increased to 17

### 1.2.15
- Fix VerifyError on API level older than Lollipop - [#570](https://github.com/koral--/android-gif-drawable/issue/570)
- Gradle wrapper regenerated with 4.9

### 1.2.14
- Fix release packaging

### 1.2.13
- Kotlin updated to 1.2.51
- Compile and target SDK version updated to 28
- Android Support library updated to 27.1.1
- Android Gradle plugin updated to 3.1.3
- Gradle wrapper regenerated with 4.8.1
- Removed private FileDescriptor field usage on Android P and above
- Added explicit FileDescriptor closing
- Removed unused code in LibraryLoader
- Dropped MIPS and MIPS64 targets
- Added support for NDK r17 and newer (with optional armeabi target built using NDK < r17)
- Fixed possible race conditions in GifTexImage2D 

### 1.2.12
- `GifDrawable` invalidation fixed - [#510](https://github.com/koral--/android-gif-drawable/issue/510)
- SIGILL on arm CPUs without NEON fixed - [#522](https://github.com/koral--/android-gif-drawable/issue/522)
- Gradle wrapper regenerated with 4.6
- Kotlin updated to 1.2.30
- Android Support library updated to 27.1.0

### 1.2.11
- Gradle wrapper regenerated with 4.5.1
- Kotlin updated to 1.2.21
- Added `GifTexImage2D#getCurrentFrameIndex()` - [#506](https://github.com/koral--/android-gif-drawable/pull/506)

### 1.2.10
- Gradle wrapper regenerated with 4.4.1
- `armeabi` and `mips` family targets restored - [#494](https://github.com/koral--/android-gif-drawable/pull/494)

### 1.2.9
- Android Support library updated to 27.0.2
- Android gradle plugin updated to 3.0.1
- Kotlin updated to 1.2.10
- Gradle wrapper regenerated with 4.4
- Build tools updated to 27.0.2
- Minimum SDK version increased to 14
- Improved bound passing to transforms - [#450](https://github.com/koral--/android-gif-drawable/pull/450)
- Add compound drawables animation start when `GifTextView` attached to window - [#474](https://github.com/koral--/android-gif-drawable/pull/474)

### 1.2.8
- `app:loopCount` XML attribute added to `GifImageView`, `GifImageButton`, `GifTextView` and `GifTextureView` - [#176](https://github.com/koral--/android-gif-drawable/issues/176)
- Added `mipmap` resources support in XML attributes of `GifTextView`
- Robolectric updated to 3.4
- Fixed segmentation fault for GIFs with 0-sized block in application extension - [#433](https://github.com/koral--/android-gif-drawable/pull/433) 
- Fixed Loop count interpretation - [#430](https://github.com/koral--/android-gif-drawable/pull/430) 
- Fixed direct byte buffer input source handling - [#434](https://github.com/koral--/android-gif-drawable/issues/434) 
- Fixed changing input source in `GifTextureView` - [#429](https://github.com/koral--/android-gif-drawable/issues/429) 
- Fixed InputStream reading - [#442](https://github.com/koral--/android-gif-drawable/pull/442) 
- Android Support library updated to 26.0.1
- Android gradle plugin updated to 2.3.3
- Gradle wrapper regenerated with 4.1
- NDK version updated to r15c
- Mockito updated to 2.7.48
- Build tools updated to 26.0.1

### 1.2.7
- `GifDrawable` subclassing simplified - [#399](https://github.com/koral--/android-gif-drawable/pull/399)
- Malformed input support improved - [#394](https://github.com/koral--/android-gif-drawable/issues/394)
- `GifTextureView` animation freezing fixed - [#392](https://github.com/koral--/android-gif-drawable/issues/392)
- Android Support library updated to 25.3.1
- Android gradle plugin updated to 2.3.1
- Gradle wrapper regenerated with 3.5
- Mockito updated to 2.7.22
- Robolectric updated to 3.3.2

### 1.2.6
- Native build system changed to cmake, fixes unnecessary removed actions - [#389](https://github.com/koral--/android-gif-drawable/issues/389)
- JNI method ids obtaining fixed - [#391](https://github.com/koral--/android-gif-drawable/issues/391)
- Fixed source InputStream closing on recycle
- Added `GifTexImage2D#getDuration()`   
- Robolectric updated to 3.3.1
- Assertj updated to 3.6.2
- Mockito updated to 2.7.15
- Gradle wrapper regenerated with 3.4.1
- Support library dependency version updated to 25.2.0

### 1.2.5
- Unneeded debugging symbols removed, fixes - [#383](https://github.com/koral--/android-gif-drawable/issues/383)
- Fixed loading native library for additional ABIs on API level < 21 - [#379](https://github.com/koral--/android-gif-drawable/issues/379)
- Robolectric updated to 3.2.2
- Mockito updated to 2.7.0
- Gradle wrapper regenerated with 3.3
- Support library dependency version updated to 25.1.1

### 1.2.4
- Added errno text to GifIOException messages, fixes - [#340](https://github.com/koral--/android-gif-drawable/issues/340)
- Added missing file descriptor closing in case of open fail
- Support library dependency version updated to 25.1.0
- Gradle wrapper updated to 3.3
- Mockito updated to 2.5.5
- mockwebserver updated to 3.5.0
- Build tools version updated to 25.0.2
- fixed clearing canvas with background color

### 1.2.3
- Support library dependency version updated to 25.0.0
- Android gradle plugin updated to 2.2.2
- custom NDK buildscript replaced with `externalNativeBuild`
- Gradle wrapper updated to 3.1
- Build tools version updated to 25
- compile and target SDK versions bumped to 25
- NDK version updated to 13b
- native code optimizations
- fixed `GifDrawable#getAllocationByteCount()` to return value consistent with docs (taking optional dispose to previous into account)
- added `GifDrawable#getMetadataByteCount()` - [#348](https://github.com/koral--/android-gif-drawable/issues/348)
- added `GifAnimationMetadata#getMetadataByteCount()` - [#342](https://github.com/koral--/android-gif-drawable/issues/342#issuecomment-252519140)
- added `GifAnimationMetadata#getDrawableAllocationByteCount()` - [#342](https://github.com/koral--/android-gif-drawable/issues/342#issuecomment-252519140)

### 1.2.2
- Fixed NPE in `GifTexImage2D` finalizer when constructor threw an exception
- GifLib error code propagation fixed
 
### 1.2.1
- Build tools version updated to 24.0.2
- Support library dependency version updated to 24.2.0
- `GifTexImage2D` releasing race condition fixed

### 1.2.0
- Native libraries joined into one file - reduced complexity, minimum API level increased to 9
- Disposal first frame to previous treated as disposal to background instead of ignoring - [#330](https://github.com/koral--/android-gif-drawable/issues/330)
- Robolectric version updated to 3.1.2
- Mutexes and conditional variables initialization and destroying error checking fixed 
- Gradle wrapper updated to 2.14.1
- Build tools version updated to 24.0.1
- Support library dependency version updated to 24.1.1
- `LibraryLoader` visibility fixed - [#333](https://github.com/koral--/android-gif-drawable/issues/333)
- Android gradle plugin updated to 2.1.3

### 1.1.17
- Mutex destroying in `GifTexImage2D` fixed 
- Erroneous `GifDrawableBuilder#options()` argument modification after calling `GifDrawableBuilder#sampleSize()` fixed
- Javadoc improvements
- Added passing opacity hint from `GifOptions` to `Bitmap` (framebuffer) in `GifDrawable`
- Default GCB reworked - fixes possible artifacts - [#305](https://github.com/koral--/android-gif-drawable/issues/305)
- Android gradle plugin updated to 2.1.2
- Gradle wrapper updated to 2.14
- Tearing in `GifTexImage2D` fixed
- Compile SDK version updated to 24
- Build tools version updated to 24

### 1.1.16
- Saved state which is not instance of `GifViewSavedState` allowed by all the Gif*Views - [#303](https://github.com/koral--/android-gif-drawable/issues/303)
- `GifOptions` added introducing subsampling and opacity controlling in `GifDrawable`, `GifTexImage2D` and `GifDecoder`
- Fixed segmentation fault when decoding oversized frames - [#290](https://github.com/koral--/android-gif-drawable/pull/290)
- Native window redraw narrowed to dirty region only - [#287](https://github.com/koral--/android-gif-drawable/issues/287#issuecomment-215517405)  
- `View#invalidate()` support added to `MultiCallback` - [#260](https://github.com/koral--/android-gif-drawable/issues/260#issuecomment-201949696)
- `glTexSubImage2D()` support added to `GifTexImage2D` - [#288](https://github.com/koral--/android-gif-drawable/pull/288)
- Support library dependency version updated to 23.4.0
- Build tools version updated to 23.0.3
- Android gradle plugin updated to 2.1.0
- Gradle wrapper version updated to 2.13

### 1.1.15
- Fixed possible infinite surface binding
- Added beta OpenGL support - `GifTexImage2D`
- Added ability to specify a custom transformation to apply to the current Bitmap - [#259](https://github.com/koral--/android-gif-drawable/pull/259)
- Gradle wrapper version updated to 2.12
- Support library dependency version updated to 23.2.1
- remainder accounting in `GifDrawable#getCurrentPosition()` fixed

### 1.1.14
- Gradle wrapper version updated to 2.11
- Duplicated frame offset correction removed
- Subsampling added - [#239](https://github.com/koral--/android-gif-drawable/issues/239)
- Width, height and number of frames storage in recycled objects removed
- Native code cleanup
- Support library dependency version updated to 23.2.0

### 1.1.13
- Fixed regression (heap corruption if frame size is lower than canvas size) - [#250](https://github.com/koral--/android-gif-drawable/issues/250)

### 1.1.12
- Added `mipmap` resources support in XML attributes
- ReLinker code cleanup
- Gradle wrapper version updated to 2.10
- Fixed ANR on disposing `GifTextureView` - [#240](https://github.com/koral--/android-gif-drawable/issues/240)
- Added `GifDecoder` for access GIF frames without `Drawable` or `View` - [#206](https://github.com/koral--/android-gif-drawable/issues/206)
- Upstream changes from GIFLib 5.1.2 integrated
- Fixed `ZipFile` closing on API level < 19 - [#244](https://github.com/koral--/android-gif-drawable/issues/244)
- Invalid offsets handling fixed to prevent OOMEs - [#243](https://github.com/koral--/android-gif-drawable/issues/243) 

### 1.1.11
- `MultiCallback` now accepts `Drawable.Callback`s, not only `View`s
- `UnsatisfiedLinkError` worked around - [#51](https://github.com/koral--/android-gif-drawable/issues/51)
- Support library dependency version updated to 23.1.1
- Build tools version updated to 23.0.2
- Android gradle plugin updated to 1.5.0
- Gradle wrapper version updated to 2.9

### 1.1.10
- Gradle wrapper version updated to 2.7
- Build tools updated to 23.0.1
- Android gradle plugin updated to 1.3.1
- Support library dependency version updated to 23.0.1
- compileSdkVersion updated to 23
- density is now taken into consideration when constructing `GifDrawable` from Resources - [#181](https://github.com/koral--/android-gif-drawable/issues/181)
- animation restarting fixed - [#208](https://github.com/koral--/android-gif-drawable/issues/208), [#209](https://github.com/koral--/android-gif-drawable/issues/209)
- `GifTextureView` memory usage optimizations
- native code cleaning
- loopNumber parameter added to `AnimationListener#onAnimationCompleted()` - fixes [#204](https://github.com/koral--/android-gif-drawable/issues/204)
- rounded corners support added - [#202](https://github.com/koral--/android-gif-drawable/issues/202)

### 1.1.9
- Proguard configuration is now bundled with the library - [#193](https://github.com/koral--/android-gif-drawable/pull/193)
- Android gradle plugin updated to 1.3.0
- fixed segfault when frame is not confined to canvas - [#196](https://github.com/koral--/android-gif-drawable/issues/196), [#194](https://github.com/koral--/android-gif-drawable/issues/194)
- fixed relationship between drawable visibility and animation state - [#195](https://github.com/koral--/android-gif-drawable/issues/195)

### 1.1.8
- toolchain changed to clang
- `InputStream` source reading optimization
- fixed support for API level 8 - [#173](https://github.com/koral--/android-gif-drawable/issues/173)
- fixed seeking in paused state - [#180](https://github.com/koral--/android-gif-drawable/issues/180)
- added missing default frame duration - [#186](https://github.com/koral--/android-gif-drawable/issues/186)
- Gradle wrapper version updated to 2.5
- support annotations version updated to 22.2.1

### 1.1.7
- fixed warning about attaching nameless thread on ART
- support annotations version updated to 22.1.1
- Android gradle plugin updated to 1.2.3
- fixed NPE when `GifTextureView` is constructed without attributes
- fixed background artifacts - [#167](https://github.com/koral--/android-gif-drawable/issues/167)
- single drawable assigned to multiple views support added (`MultiCallback`)
- NDK version updated to r10e
- `GifDrawable#setLoopCount()` added
- fixed firing `AnimationListener#onAnimationCompleted()`
- Gradle wrapper version updated to 2.4

Updates also contain documentation updates, typofixes, and trivial code clean-ups.
