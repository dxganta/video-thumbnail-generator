# video_thumbnail_generator

The plugin generates thumbnails from a video URL. It returns an Flutter Image Widget. You can also output the image as Uint8List. Supports Android, IOS & Web.

## Getting Started

### 1. Get Thumbnail as a Flutter Image Widget

![image_info](images/ss1.png=x300)

```dart
ThumbnailImage(
          videoUrl:
              "https://file-examples-com.github.io/uploads/2017/04/file_example_MP4_480_1_5MG.mp4",
          width: 400,
          height: 400,
        )
```

