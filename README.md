### OpenCV: Open Source Computer Vision Library

THIS BRANCH IS MAINTAINED ONLY TO SUPPORT CUDA8.

The following bug patches have been pulled forward into the OpenCV3.1.0 release. ONLY these bug fixes/patches have been added to 3.1.0:
* #6016 (https://github.com/opencv/opencv/issues/6016) Build error for python bindings with opencv_contrib modules. This solves the #includ <hdf5.h> which is hardcoded somewhere
* #6050 (https://github.com/opencv/opencv/issues/6050) Opencv build for python crashes on link to hdf5.h on Ubuntu 15.10. (Also affects Ubuntu 16.04 FWIW). Same issue as #6016
* #6677 (https://github.com/opencv/opencv/issues/6677) OpenCV3.10 does not support Cuda8.0rc (and does not support CUDA8 at released).

These patches are pulled forward either from the ticket, or from the origin master of opencv. I will continue to keep this fork up to date until the next release of opencv.


[![Gittip](http://img.shields.io/gittip/OpenCV.png)](https://www.gittip.com/OpenCV/)

#### Resources

* Homepage: <http://opencv.org>
* Docs: <http://docs.opencv.org/master/>
* Q&A forum: <http://answers.opencv.org>
* Issue tracking: <https://github.com/Itseez/opencv/issues>

#### Contributing

Please read before starting work on a pull request: <https://github.com/Itseez/opencv/wiki/How_to_contribute>

Summary of guidelines:

* One pull request per issue;
* Choose the right base branch;
* Include tests and documentation;
* Clean up "oops" commits before submitting;
* Follow the coding style guide.
