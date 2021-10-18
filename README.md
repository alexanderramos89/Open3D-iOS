# Open3D-iOS

This swift package enables you to use Open3D in your iOS apps.

## Installation

```
.package(url: "https://github.com/palmin/Open3D-iOS.git", .branch("main"))
```

## Usage

```
import Open3DSupport
import NumPySupport
import PythonSupport
import PythonKit

PythonSupport.initialize()
Open3DSupport.sitePackageUrl.insertPythonPath()
NumPySupport.sitePackageUrl.insertPythonPath()
let o3d = Python.import("open3d")
...
```

If you want to build XCFrameworks yourself, see https://github.com/kewlbear/Open3D.

## License

MIT
