# video_thumbnail_generator

The plugin generates thumbnails from a video URL. Just enter the url of the video into the ThumbnailImage() widget. You can also output the image as Uint8List. Supports Android, IOS & Web.

## Getting Started

### 1. Get Thumbnail as a Flutter Image Widget

<img src="https://user-images.githubusercontent.com/47485188/97113417-2dc91300-1710-11eb-8c3b-0f1e2843dca4.png" alt="Screenshot" height="500" width="250"/>

```dart
ThumbnailImage(
          videoUrl:
              "https://file-examples-com.github.io/uploads/2017/04/file_example_MP4_480_1_5MG.mp4",
          width: 400,
          height: 400,
        )
```

### 2. Get Thumbnail Image as Uint8List

```dart
Uint8List bytes = await VideoThumbnail.getBytes(
    "https://file-examples-com.github.io/uploads/2017/04/file_example_MP4_480_1_5MG.mp4"
);
