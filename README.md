# Qt Sample Application

- Using cmake.
- Based on http://doc.qt.io/qt-5/qtwidgets-mainwindows-application-example.html

- If you Qt is not in the path / not in a standard path you have to add the explicit path in the `CMakeLists.txt` file  
  `find_package(Qt5Widgets PATHS /Users/yourname/Development/lib/Qt5.11.2/5.11.2/clang_64/lib/cmake/Qt5Widgets)`  
  where `PATHS` points to the cmake file in your Qt directory.
