## OpenCV: Open Source Computer Vision Library

### Note

The source code is of version 4.1.1, however, there is some modification:

* in <opencv-4.1.1>3rdparty/ippicv/ippicv.cmake, the following content

  ```bash
  "https://raw.githubusercontent.com/opencv/opencv_3rdparty/${IPPICV_COMMIT}ippicv/"
  ```

  is revised to

  ```bash
  "file://${HOME}/soft/ippicv"
  ```

  To make it effect, you need to do the following:

  ```bash
  cd ~/soft/
  git clone https://gitee.com/dj-zhou_zhoudingjiang/ippicv.git
  ```

If **dj-convenience** is used, the following command will do it for installing OpenCV:

```bash
dj setup opencv-4.1.1 [with-contrib/no-contrib]
```



### Resources

* Homepage: <https://opencv.org>
* Docs: <https://docs.opencv.org/master/>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <https://github.com/opencv/opencv/issues>

### Contributing

Please read the [contribution guidelines](https://github.com/opencv/opencv/wiki/How_to_contribute) before starting work on a pull request.

#### Summary of the guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the [coding style guide](https://github.com/opencv/opencv/wiki/Coding_Style_Guide).
