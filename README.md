# iOS-Experiments Contents

Table of Contents of [iOS-Experiments](https://github.com/shu223/iOS-Experiments) repository.

## Table of Contents

### Metal on watchOS

Metal shader examples on watchOS. Though Metal framework is NOT supported on watchOS, SceneKit framework and `SCNShadable` protocol is supported and it actually works! It contains toon shading sample and grayscale sample written in MSL (Metal Shading Language).

![](resources/watch-toonshader.gif)

- Source code: [iOS-Experiments/watchOS-Metal](https://github.com/shu223/iOS-Experiments/tree/master/watchOS-Metal)

`watchOS`, `Metal`, `Metal Shading Language`, `shader modifier`, `SceneKit`, `MSL`, `GPU`

### AnimeSpeakerClassifier

An experimental app to classify speakers in an anime movie using `SoundAnalysis` framework. It worked well. Used Create ML to train the model. 

SoundAnalysisフレームワークを用いてアニメ動画の話者を識別できるか試した。かなりうまくいった。学習はCreate MLを使用。

<img src="resources/anime_soundanalysis.gif" width="200">

- Source code: [iOS-Experiments/AnimeSpeakerClassifier](https://github.com/shu223/iOS-Experiments/tree/master/AnimeSpeakerClassifier)
  - The Core ML model and video data have been removed from the project in consideration of copyright, so you can **NOT** build & run this project. 
  - 著作権に配慮してCore MLモデルと動画データをプロジェクトから除去しているので**ビルド不可**
  - The Create ML project file to train the model and the training data are **NOT** contained in the repo. 
  - Create MLのプロジェクトと学習用の音声データも同梱していません

`SoundAnalysis`, `Speaker Classification`, `Video Processing`


### PodcastSpeakerClassifier

An experimental app to classify speakers in a podcast audio using `SoundAnalysis` framework. It did **NOT** well. Used Create ML to train the model. 

SoundAnalysisフレームワークを用いてPodcastの話者を識別できるか試した。あまりうまくいってない。学習用の音声データが少なかったかもしれない。学習はCreate MLを使用。

<img src="resources/speakerclassification.png" width="200">

- Source code: [iOS-Experiments/PodcastSpeakerClassifier](https://github.com/shu223/iOS-Experiments/tree/master/PodcastSpeakerClassifier)
  - The Create ML project file to train the model and the training data are **NOT** contained in the repo. 
  - Create MLのプロジェクトと学習用の音声データは同梱していない。どこかにあるはずなので見つけたらアップするかも。

`SoundAnalysis`, `Sound Analysis`, `Speaker Classification`, `Audio Processing`


### Scene Reconstruction with SceneKit + ARKit

Visualizing `ARMeshGeometry` from LiDAR **without RealityKit** (with SceneKit)

![](resources/arkit_scenereconstruction.gif)

- Source code: [iOS-Experiments/ARKit_SceneReconstruction](https://github.com/shu223/iOS-Experiments/tree/master/ARKit_SceneReconstruction)

`ARKit 3.5`, `LiDAR`, `Depth`

### Rectangle Detection & Correction

A real-time camera sample to detect a rectangle using Vision (`VNDetectRectanglesRequest`, `VNRectangleObservation`) and correct it using Core Image (`CIPerspectiveCorrection`).

<img src="resources/rectdetection.gif" width="200">

- Source code: [iOS-Experiments/RectangleDetection](https://github.com/shu223/iOS-Experiments/tree/master/RectangleDetection)

`Vision`, `Core Image`, `Image Processing`


### ZundokoBLE

- https://twitter.com/shu223/status/715946579585314820
- https://qiita.com/shu223/items/2c7b2e1ed058a1e3b33f

![](resources/zundoko-HQ.gif)

- Source code: [iOS-Experiments/ZundokoBLE](https://github.com/shu223/iOS-Experiments/tree/master/ZundokoBLE)
  - It can **NOT** be built with the latest Xcode because written in Swift 3.x.

`CoreBluetooth`, `Core Bluetooth`, `BLE`

## How to access to `iOS-Experiments`?

Here are some way to get access to the private repo:

- Become a sponsor (`premium` or higher): https://github.com/sponsors/shu223
