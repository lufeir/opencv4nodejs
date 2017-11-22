---
layout: default
---

###  API Overview

Missing some function bindings? No problem! - <a href="https://github.com/justadudewhohacks/opencv4nodejs/#request-features"><b>Requesting new Features</b></a>

* <a href="./core/core"><b>core</b></a>
  * <a href="./core/core#partition">partition</a>
  * <a href="./core/core#kmeans">kmeans</a>
  * <a href="./core/Mat"><b>Mat</b></a>
    * <a href="./core/Mat#operators">operators</a>
      * <a href="./core/Mat#operators">add</a>
      * <a href="./core/Mat#operators">sub</a>
      * <a href="./core/Mat#operators">mul</a>
      * <a href="./core/Mat#operators">div</a>
      * <a href="./core/Mat#operators">hMul</a>
      * <a href="./core/Mat#operators">hDiv</a>
      * <a href="./core/Mat#operators">absdiff</a>
      * <a href="./core/Mat#operators">exp</a>
      * <a href="./core/Mat#operators">mean</a>
      * <a href="./core/Mat#operators">sqrt</a>
      * <a href="./core/Mat#operators">dot</a>
      * <a href="./core/Mat#operators">and</a>
      * <a href="./core/Mat#operators">or</a>
      * <a href="./core/Mat#operators">bitwiseAnd</a>
      * <a href="./core/Mat#operators">bitwiseOr</a>
      * <a href="./core/Mat#operators">bitwiseXor</a>
      * <a href="./core/Mat#operators">bitwiseNot</a>
      * <a href="./core/Mat#operators">abs</a>
      * <a href="./core/Mat#operators">determinant</a>
      * <a href="./core/Mat#operators">transpose</a>
    * <a href="./core/Mat#at">at</a>
    * <a href="./core/Mat#atRaw">atRaw</a>
    * <a href="./core/Mat#set">set</a>
    * <a href="./core/Mat#getData">getData</a>
    * <a href="./core/Mat#getDataAsync">getDataAsync</a>
    * <a href="./core/Mat#getDataAsArray">getDataAsArray</a>
    * <a href="./core/Mat#getRegion">getRegion</a>
    * <a href="./core/Mat#copy">copy</a>
    * <a href="./core/Mat#copyAsync">copyAsync</a>
    * <a href="./core/Mat#copyTo">copyTo</a>
    * <a href="./core/Mat#copyToAsync">copyToAsync</a>
    * <a href="./core/Mat#convertTo">convertTo</a>
    * <a href="./core/Mat#convertToAsync">convertToAsync</a>
    * <a href="./core/Mat#norm">norm</a>
    * <a href="./core/Mat#normalize">normalize</a>
    * <a href="./core/Mat#splitChannels">splitChannels</a>
    * <a href="./core/Mat#splitChannelsAsync">splitChannelsAsync</a>
    * <a href="./core/Mat#addWeighted">addWeighted</a>
    * <a href="./core/Mat#addWeightedAsync">addWeightedAsync</a>
    * <a href="./core/Mat#minMaxLoc">minMaxLoc</a>
    * <a href="./core/Mat#minMaxLocAsync">minMaxLocAsync</a>
    * <a href="./core/Mat#dct">dct</a>
    * <a href="./core/Mat#dctAsync">dctAsync</a>
    * <a href="./core/Mat#idct">idct</a>
    * <a href="./core/Mat#idctAsync">idctAsync</a>
    * <a href="./core/Mat#dft">dft</a>
    * <a href="./core/Mat#dftAsync">dftAsync</a>
    * <a href="./core/Mat#idft">idft</a>
    * <a href="./core/Mat#idftAsync">idftAsync</a>
    * <a href="./core/Mat#mulSpectrums">mulSpectrums</a>
    * <a href="./core/Mat#mulSpectrumsAsync">mulSpectrumsAsync</a>
    * <a href="./core/Mat#rescale">rescale</a>
    * <a href="./core/Mat#rescaleAsync">rescaleAsync</a>
    * <a href="./core/Mat#resize">resize</a>
    * <a href="./core/Mat#resizeAsync">resizeAsync</a>
    * <a href="./core/Mat#resizeToMax">resizeToMax</a>
    * <a href="./core/Mat#resizeToMaxAsync">resizeToMaxAsync</a>
    * <a href="./core/Mat#threshold">threshold</a>
    * <a href="./core/Mat#thresholdAsync">thresholdAsync</a>
    * <a href="./core/Mat#adaptiveThreshold">adaptiveThreshold</a>
    * <a href="./core/Mat#adaptiveThresholdAsync">adaptiveThresholdAsync</a>
    * <a href="./core/Mat#inRange">inRange</a>
    * <a href="./core/Mat#inRangeAsync">inRangeAsync</a>
    * <a href="./core/Mat#cvtColor">cvtColor</a>
    * <a href="./core/Mat#cvtColorAsync">cvtColorAsync</a>
    * <a href="./core/Mat#bgrToGray">bgrToGray</a>
    * <a href="./core/Mat#bgrToGrayAsync">bgrToGrayAsync</a>
    * <a href="./core/Mat#warpAffine">warpAffine</a>
    * <a href="./core/Mat#warpAffineAsync">warpAffineAsync</a>
    * <a href="./core/Mat#warpPerspective">warpPerspective</a>
    * <a href="./core/Mat#warpPerspectiveAsync">warpPerspectiveAsync</a>
    * <a href="./core/Mat#dilate">dilate</a>
    * <a href="./core/Mat#dilateAsync">dilateAsync</a>
    * <a href="./core/Mat#erode">erode</a>
    * <a href="./core/Mat#erodeAsync">erodeAsync</a>
    * <a href="./core/Mat#morphologyEx">morphologyEx</a>
    * <a href="./core/Mat#morphologyExAsync">morphologyExAsync</a>
    * <a href="./core/Mat#distanceTransform">distanceTransform</a>
    * <a href="./core/Mat#distanceTransformAsync">distanceTransformAsync</a>
    * <a href="./core/Mat#distanceTransformWithLabels">distanceTransformWithLabels</a>
    * <a href="./core/Mat#distanceTransformWithLabelsAsync">distanceTransformWithLabelsAsync</a>
    * <a href="./core/Mat#grabCut">grabCut</a>
    * <a href="./core/Mat#grabCutAsync">grabCutAsync</a>
    * <a href="./core/Mat#blur">blur</a>
    * <a href="./core/Mat#blurAsync">blurAsync</a>
    * <a href="./core/Mat#gaussianBlur">gaussianBlur</a>
    * <a href="./core/Mat#gaussianBlurAsync">gaussianBlurAsync</a>
    * <a href="./core/Mat#medianBlur">medianBlur</a>
    * <a href="./core/Mat#medianBlurAsync">medianBlurAsync</a>
    * <a href="./core/Mat#connectedComponents">connectedComponents</a>
    * <a href="./core/Mat#connectedComponentsAsync">connectedComponentsAsync</a>
    * <a href="./core/Mat#connectedComponentsWithStats">connectedComponentsWithStats</a>
    * <a href="./core/Mat#connectedComponentsWithStatsAsync">connectedComponentsWithStatsAsync</a>
    * <a href="./core/Mat#findContours">findContours</a>
    * <a href="./core/Mat#findContoursAsync">findContoursAsync</a>
    * <a href="./core/Mat#moments">moments</a>
    * <a href="./core/Mat#momentsAsync">momentsAsync</a>
    * <a href="./core/Mat#drawContours">drawContours</a>
    * <a href="./core/Mat#drawLine">drawLine</a>
    * <a href="./core/Mat#drawCircle">drawCircle</a>
    * <a href="./core/Mat#drawRectangle">drawRectangle</a>
    * <a href="./core/Mat#drawEllipse">drawEllipse</a>
    * <a href="./core/Mat#putText">putText</a>
    * <a href="./core/Mat#matchTemplate">matchTemplate</a>
    * <a href="./core/Mat#matchTemplateAsync">matchTemplateAsync</a>
    * <a href="./core/Mat#canny">canny</a>
    * <a href="./core/Mat#cannyAsync">cannyAsync</a>
    * <a href="./core/Mat#sobel">sobel</a>
    * <a href="./core/Mat#sobelAsync">sobelAsync</a>
    * <a href="./core/Mat#scharr">scharr</a>
    * <a href="./core/Mat#scharrAsync">scharrAsync</a>
    * <a href="./core/Mat#laplacian">laplacian</a>
    * <a href="./core/Mat#laplacianAsync">laplacianAsync</a>
    * <a href="./core/Mat#pyrDown">pyrDown</a>
    * <a href="./core/Mat#pyrDownAsync">pyrDownAsync</a>
    * <a href="./core/Mat#pyrUp">pyrUp</a>
    * <a href="./core/Mat#pyrUpAsync">pyrUpAsync</a>
    * <a href="./core/Mat#buildPyramid">buildPyramid</a>
    * <a href="./core/Mat#buildPyramidAsync">buildPyramidAsync</a>
    * <a href="./core/Mat#houghLines">houghLines</a>
    * <a href="./core/Mat#houghLinesAsync">houghLinesAsync</a>
    * <a href="./core/Mat#houghLinesP">houghLinesP</a>
    * <a href="./core/Mat#houghLinesPAsync">houghLinesPAsync</a>
    * <a href="./core/Mat#houghCircles">houghCircles</a>
    * <a href="./core/Mat#houghCirclesAsync">houghCirclesAsync</a>
    * <a href="./core/Mat#rodrigues">rodrigues</a>
    * <a href="./core/Mat#rodriguesAsync">rodriguesAsync</a>
    * <a href="./core/Mat#rqDecomp3x3">rqDecomp3x3</a>
    * <a href="./core/Mat#rqDecomp3x3Async">rqDecomp3x3Async</a>
    * <a href="./core/Mat#decomposeProjectionMatrix">decomposeProjectionMatrix</a>
    * <a href="./core/Mat#decomposeProjectionMatrixAsync">decomposeProjectionMatrixAsync</a>
    * <a href="./core/Mat#matMulDeriv">matMulDeriv</a>
    * <a href="./core/Mat#matMulDerivAsync">matMulDerivAsync</a>
    * <a href="./core/Mat#findChessboardCorners">findChessboardCorners</a>
    * <a href="./core/Mat#findChessboardCornersAsync">findChessboardCornersAsync</a>
    * <a href="./core/Mat#drawChessboardCorners">drawChessboardCorners</a>
    * <a href="./core/Mat#drawChessboardCornersAsync">drawChessboardCornersAsync</a>
    * <a href="./core/Mat#find4QuadCornerSubpix">find4QuadCornerSubpix</a>
    * <a href="./core/Mat#find4QuadCornerSubpixAsync">find4QuadCornerSubpixAsync</a>
    * <a href="./core/Mat#calibrationMatrixValues">calibrationMatrixValues</a>
    * <a href="./core/Mat#calibrationMatrixValuesAsync">calibrationMatrixValuesAsync</a>
    * <a href="./core/Mat#stereoRectify">stereoRectify</a>
    * <a href="./core/Mat#stereoRectifyAsync">stereoRectifyAsync</a>
    * <a href="./core/Mat#rectify3Collinear">rectify3Collinear</a>
    * <a href="./core/Mat#rectify3CollinearAsync">rectify3CollinearAsync</a>
    * <a href="./core/Mat#getOptimalNewCameraMatrix">getOptimalNewCameraMatrix</a>
    * <a href="./core/Mat#getOptimalNewCameraMatrixAsync">getOptimalNewCameraMatrixAsync</a>
    * <a href="./core/Mat#decomposeEssentialMat">decomposeEssentialMat</a>
    * <a href="./core/Mat#decomposeEssentialMatAsync">decomposeEssentialMatAsync</a>
    * <a href="./core/Mat#triangulatePoints">triangulatePoints</a>
    * <a href="./core/Mat#triangulatePointsAsync">triangulatePointsAsync</a>
    * <a href="./core/Mat#correctMatches">correctMatches</a>
    * <a href="./core/Mat#correctMatchesAsync">correctMatchesAsync</a>
    * <a href="./core/Mat#filterSpeckles">filterSpeckles</a>
    * <a href="./core/Mat#filterSpecklesAsync">filterSpecklesAsync</a>
    * <a href="./core/Mat#validateDisparity">validateDisparity</a>
    * <a href="./core/Mat#validateDisparityAsync">validateDisparityAsync</a>
    * <a href="./core/Mat#reprojectImageTo3D">reprojectImageTo3D</a>
    * <a href="./core/Mat#reprojectImageTo3DAsync">reprojectImageTo3DAsync</a>
    * <a href="./core/Mat#decomposeHomographyMat">decomposeHomographyMat</a>
    * <a href="./core/Mat#decomposeHomographyMatAsync">decomposeHomographyMatAsync</a>
    * <a href="./core/Mat#findEssentialMat">findEssentialMat</a>
    * <a href="./core/Mat#findEssentialMatAsync">findEssentialMatAsync</a>
    * <a href="./core/Mat#recoverPose">recoverPose</a>
    * <a href="./core/Mat#recoverPoseAsync">recoverPoseAsync</a>
  * <a href="./core/Vec"><b>Vec</b></a>
    * <a href="./core/Vec#operators">operators</a>
      * <a href="./core/Vec#operators">add</a>
      * <a href="./core/Vec#operators">sub</a>
      * <a href="./core/Vec#operators">mul</a>
      * <a href="./core/Vec#operators">div</a>
      * <a href="./core/Vec#operators">hMul</a>
      * <a href="./core/Vec#operators">hDiv</a>
      * <a href="./core/Vec#operators">absdiff</a>
      * <a href="./core/Vec#operators">exp</a>
      * <a href="./core/Vec#operators">mean</a>
      * <a href="./core/Vec#operators">sqrt</a>
      * <a href="./core/Vec#operators">norm</a>
      * <a href="./core/Vec#operators">cross</a>
    * <a href="./core/Vec#at">at</a>
  * <a href="./core/Point"><b>Point</b></a>
    * <a href="./core/Point#operators">operators</a>
      * <a href="./core/Point#operators">add</a>
      * <a href="./core/Point#operators">sub</a>
      * <a href="./core/Point#operators">mul</a>
      * <a href="./core/Point#operators">div</a>
      * <a href="./core/Point#operators">norm</a>
    * <a href="./core/Point#at">at</a>
  * <a href="./core/Size"><b>Size</b></a>
  * <a href="./core/Rect"><b>Rect</b></a>
  * <a href="./core/RotatedRect"><b>RotatedRect</b></a>
    * <a href="./core/RotatedRect#boundingRect">boundingRect</a>
  * <a href="./core/TermCriteria"><b>TermCriteria</b></a>
* <a href="./io/io"><b>io</b></a>
  * <a href="./io/io#imread">imread</a>
  * <a href="./io/io#imreadAsync">imreadAsync</a>
  * <a href="./io/io#imwrite">imwrite</a>
  * <a href="./io/io#imwriteAsync">imwriteAsync</a>
  * <a href="./io/io#imshow">imshow</a>
  * <a href="./io/io#imshowWait">imshowWait</a>
  * <a href="./io/io#waitKey">waitKey</a>
  * <a href="./io/io#imencode">imencode</a>
  * <a href="./io/io#imencodeAsync">imencodeAsync</a>
  * <a href="./io/io#imdecode">imdecode</a>
  * <a href="./io/io#imdecodeAsync">imdecodeAsync</a>
  * <a href="./io/VideoCapture"><b>VideoCapture</b></a>
    * <a href="./io/VideoCapture#read">read</a>
    * <a href="./io/VideoCapture#readAsync">readAsync</a>
    * <a href="./io/VideoCapture#reset">reset</a>
    * <a href="./io/VideoCapture#get">get</a>
    * <a href="./io/VideoCapture#set">set</a>
    * <a href="./io/VideoCapture#release">release</a>
  * <a href="./io/VideoWriter"><b>VideoWriter</b></a>
    * <a href="./io/VideoWriter#fourcc">fourcc</a>
    * <a href="./io/VideoWriter#write">write</a>
    * <a href="./io/VideoWriter#writeAsync">writeAsync</a>
    * <a href="./io/VideoWriter#get">get</a>
    * <a href="./io/VideoWriter#set">set</a>
    * <a href="./io/VideoWriter#release">release</a>
* <a href="./imgproc/imgproc"><b>imgproc</b></a>
  * <a href="./imgproc/imgproc#getStructuringElement">getStructuringElement</a>
  * <a href="./imgproc/imgproc#getRotationMatrix2D">getRotationMatrix2D</a>
  * <a href="./imgproc/imgproc#getAffineTransform">getAffineTransform</a>
  * <a href="./imgproc/imgproc#getPerspectiveTransform">getPerspectiveTransform</a>
  * <a href="./imgproc/imgproc#calcHist">calcHist</a>
  * <a href="./imgproc/imgproc#plot1DHist">plot1DHist</a>
  * <a href="./imgproc/imgproc#fitLine">fitLine</a>
  * <a href="./imgproc/imgproc#canny">canny</a>
  * <a href="./imgproc/Moments"><b>Moments</b></a>
    * <a href="./imgproc/Moments#huMoments">huMoments</a>
  * <a href="./imgproc/Contour"><b>Contour</b></a>
    * <a href="./imgproc/Contour#getPoints">getPoints</a>
    * <a href="./imgproc/Contour#arcLength">arcLength</a>
    * <a href="./imgproc/Contour#convexHull">convexHull</a>
    * <a href="./imgproc/Contour#convexityDefects">convexityDefects</a>
    * <a href="./imgproc/Contour#boundingRect">boundingRect</a>
    * <a href="./imgproc/Contour#minEnclosingCircle">minEnclosingCircle</a>
    * <a href="./imgproc/Contour#minEnclosingTriangle">minEnclosingTriangle</a>
    * <a href="./imgproc/Contour#minAreaRect">minAreaRect</a>
    * <a href="./imgproc/Contour#fitEllipse">fitEllipse</a>
    * <a href="./imgproc/Contour#approxPolyDP">approxPolyDP</a>
    * <a href="./imgproc/Contour#pointPolygonTest">pointPolygonTest</a>
    * <a href="./imgproc/Contour#matchShapes">matchShapes</a>
    * <a href="./imgproc/Contour#moments">moments</a>
* <a href="./ximgproc/ximgproc"><b>ximgproc</b></a>
  * <a href="./ximgproc/SuperpixelSEEDS"><b>SuperpixelSEEDS</b></a>
    * <a href="./ximgproc/SuperpixelSEEDS#iterate">iterate</a>
  * <a href="./ximgproc/SuperpixelSLIC"><b>SuperpixelSLIC</b></a>
    * <a href="./ximgproc/SuperpixelSLIC#iterate">iterate</a>
  * <a href="./ximgproc/SuperpixelLSC"><b>SuperpixelLSC</b></a>
    * <a href="./ximgproc/SuperpixelLSC#iterate">iterate</a>
* <a href="./objdetect/objdetect"><b>objdetect</b></a>
  * <a href="./objdetect/CascadeClassifier"><b>CascadeClassifier</b></a>
    * <a href="./objdetect/CascadeClassifier#detectMultiScale">detectMultiScale</a>
    * <a href="./objdetect/CascadeClassifier#detectMultiScaleAsync">detectMultiScaleAsync</a>
    * <a href="./objdetect/CascadeClassifier#detectMultiScaleWithRejectLevels">detectMultiScaleWithRejectLevels</a>
    * <a href="./objdetect/CascadeClassifier#detectMultiScaleWithRejectLevelsAsync">detectMultiScaleWithRejectLevelsAsync</a>
  * <a href="./objdetect/HOGDescriptor"><b>HOGDescriptor</b></a>
    * <a href="./objdetect/HOGDescriptor#.getDaimlerPeopleDetector">getDaimlerPeopleDetector</a>
    * <a href="./objdetect/HOGDescriptor#.getDefaultPeopleDetector">getDefaultPeopleDetector</a>
    * <a href="./objdetect/HOGDescriptor#.compute">compute</a>
    * <a href="./objdetect/HOGDescriptor#.computeAsync">computeAsync</a>
    * <a href="./objdetect/HOGDescriptor#.computeGradient">computeGradient</a>
    * <a href="./objdetect/HOGDescriptor#.computeGradientAsync">computeGradientAsync</a>
    * <a href="./objdetect/HOGDescriptor#.detect">detect</a>
    * <a href="./objdetect/HOGDescriptor#.detectAsync">detectAsync</a>
    * <a href="./objdetect/HOGDescriptor#.detectROI">detectROI</a>
    * <a href="./objdetect/HOGDescriptor#.detectROIAsync">detectROIAsync</a>
    * <a href="./objdetect/HOGDescriptor#.detectMultiScale">detectMultiScale</a>
    * <a href="./objdetect/HOGDescriptor#.detectMultiScaleAsync">detectMultiScaleAsync</a>
    * <a href="./objdetect/HOGDescriptor#.detectMultiScaleROI">detectMultiScaleROI</a>
    * <a href="./objdetect/HOGDescriptor#.detectMultiScaleROIAsync">detectMultiScaleROIAsync</a>
    * <a href="./objdetect/HOGDescriptor#.groupRectangles">groupRectangles</a>
    * <a href="./objdetect/HOGDescriptor#.groupRectanglesAsync">groupRectanglesAsync</a>
    * <a href="./objdetect/HOGDescriptor#.checkDetectorSize">checkDetectorSize</a>
    * <a href="./objdetect/HOGDescriptor#.setSVMDetector">setSVMDetector</a>
    * <a href="./objdetect/HOGDescriptor#.save">save</a>
    * <a href="./objdetect/HOGDescriptor#.load">load</a>
  * <a href="./objdetect/DetectionROI"><b>DetectionROI</b></a>
* <a href="./machinelearning/machinelearning"><b>machinelearning</b></a>
  * <a href="./machinelearning/ParamGrid"><b>ParamGrid</b></a>
  * <a href="./machinelearning/TrainData"><b>TrainData</b></a>
  * <a href="./machinelearning/SVM"><b>SVM</b></a>
    * <a href="./machinelearning/SVM#setParams">setParams</a>
    * <a href="./machinelearning/SVM#train">train</a>
    * <a href="./machinelearning/SVM#trainAsync">trainAsync</a>
    * <a href="./machinelearning/SVM#trainAuto">trainAuto</a>
    * <a href="./machinelearning/SVM#trainAutoAsync">trainAutoAsync</a>
    * <a href="./machinelearning/SVM#predict">predict</a>
    * <a href="./machinelearning/SVM#save">save</a>
    * <a href="./machinelearning/SVM#load">load</a>
    * <a href="./machinelearning/SVM#getSupportVectors">getSupportVectors</a>
    * <a href="./machinelearning/SVM#calcError">calcError</a>
* <a href="./dnn/dnn"><b>dnn</b></a>
  * <a href="./dnn/Net"><b>Net</b></a>
    * <a href="./dnn/Net#setInput">setInput</a>
    * <a href="./dnn/Net#setInputAsync">setInputAsync</a>
    * <a href="./dnn/Net#forward">forward</a>
    * <a href="./dnn/Net#forwardAsync">forwardAsync</a>
  * <a href="./dnn/dnn#readNetFromTensorflow">readNetFromTensorflow</a>
  * <a href="./dnn/dnn#readNetFromTensorflowAsync">readNetFromTensorflowAsync</a>
  * <a href="./dnn/dnn#blobFromImage">blobFromImage</a>
  * <a href="./dnn/dnn#blobFromImageAsync">blobFromImageAsync</a>
  * <a href="./dnn/dnn#blobFromImages">blobFromImages</a>
  * <a href="./dnn/dnn#blobFromImagesAsync">blobFromImagesAsync</a>
* <a href="./video/video"><b>video</b></a>
  * <a href="./video/BackgroundSubtractorMOG2"><b>BackgroundSubtractorMOG2</b></a>
    * <a href="./video/BackgroundSubtractorMOG2#apply">apply</a>
  * <a href="./video/BackgroundSubtractorKNN"><b>BackgroundSubtractorKNN</b></a>
    * <a href="./video/BackgroundSubtractorKNN#apply">apply</a>
* <a href="./calib3d"><b>calib3d</b></a>
  * <a href="./calib3d#findHomography">findHomography</a>
  * <a href="./calib3d#composeRT">composeRT</a>
  * <a href="./calib3d#composeRTAsync">composeRTAsync</a>
  * <a href="./calib3d#solvePnP">solvePnP</a>
  * <a href="./calib3d#solvePnPAsync">solvePnPAsync</a>
  * <a href="./calib3d#solvePnPRansac">solvePnPRansac</a>
  * <a href="./calib3d#solvePnPRansacAsync">solvePnPRansacAsync</a>
  * <a href="./calib3d#projectPoints">projectPoints</a>
  * <a href="./calib3d#projectPointsAsync">projectPointsAsync</a>
  * <a href="./calib3d#initCameraMatrix2D">initCameraMatrix2D</a>
  * <a href="./calib3d#initCameraMatrix2DAsync">initCameraMatrix2DAsync</a>
  * <a href="./calib3d#calibrateCamera">calibrateCamera</a>
  * <a href="./calib3d#calibrateCameraAsync">calibrateCameraAsync</a>
  * <a href="./calib3d#stereoCalibrate">stereoCalibrate</a>
  * <a href="./calib3d#stereoCalibrateAsync">stereoCalibrateAsync</a>
  * <a href="./calib3d#stereoRectifyUncalibrated">stereoRectifyUncalibrated</a>
  * <a href="./calib3d#stereoRectifyUncalibratedAsync">stereoRectifyUncalibratedAsync</a>
  * <a href="./calib3d#findFundamentalMat">findFundamentalMat</a>
  * <a href="./calib3d#findFundamentalMatAsync">findFundamentalMatAsync</a>
  * <a href="./calib3d#findEssentialMat">findEssentialMat</a>
  * <a href="./calib3d#findEssentialMatAsync">findEssentialMatAsync</a>
  * <a href="./calib3d#recoverPose">recoverPose</a>
  * <a href="./calib3d#recoverPoseAsync">recoverPoseAsync</a>
  * <a href="./calib3d#computeCorrespondEpilines">computeCorrespondEpilines</a>
  * <a href="./calib3d#computeCorrespondEpilinesAsync">computeCorrespondEpilinesAsync</a>
  * <a href="./calib3d#getValidDisparityROI">getValidDisparityROI</a>
  * <a href="./calib3d#getValidDisparityROIAsync">getValidDisparityROIAsync</a>
  * <a href="./calib3d#estimateAffine3D">estimateAffine3D</a>
  * <a href="./calib3d#estimateAffine3DAsync">estimateAffine3DAsync</a>
  * <a href="./calib3d#sampsonDistance">sampsonDistance</a>
  * <a href="./calib3d#sampsonDistanceAsync">sampsonDistanceAsync</a>
  * <a href="./calib3d#calibrateCameraExtended">calibrateCameraExtended</a>
  * <a href="./calib3d#calibrateCameraExtendedAsync">calibrateCameraExtendedAsync</a>
  * <a href="./calib3d#estimateAffine2D">estimateAffine2D</a>
  * <a href="./calib3d#estimateAffine2DAsync">estimateAffine2DAsync</a>
  * <a href="./calib3d#estimateAffinePartial2D">estimateAffinePartial2D</a>
  * <a href="./calib3d#estimateAffinePartial2DAsync">estimateAffinePartial2DAsync</a>
  * <a href="./calib3d#solveP3P">solveP3P</a>
  * <a href="./calib3d#solveP3PAsync">solveP3PAsync</a>
* <a href="./photo"><b>photo</b></a>
  * <a href="./photo#fastNlMeansDenoisingColored">fastNlMeansDenoisingColored</a>
* <a href="./features2d/features2d"><b>features2d</b></a>
  * <a href="./features2d/features2d#matchFlannBased">matchFlannBased</a>
  * <a href="./features2d/features2d#matchFlannBasedAsync">matchFlannBasedAsync</a>
  * <a href="./features2d/features2d#matchBruteForce">matchBruteForce</a>
  * <a href="./features2d/features2d#matchBruteForceAsync">matchBruteForceAsync</a>
  * <a href="./features2d/features2d#matchBruteForceL1">matchBruteForceL1</a>
  * <a href="./features2d/features2d#matchBruteForceL1Async">matchBruteForceL1Async</a>
  * <a href="./features2d/features2d#matchBruteForceHamming">matchBruteForceHamming</a>
  * <a href="./features2d/features2d#matchBruteForceHammingAsync">matchBruteForceHammingAsync</a>
  * <a href="./features2d/features2d#matchBruteForceHammingLut">matchBruteForceHammingLut</a>
  * <a href="./features2d/features2d#matchBruteForceHammingLutAsync">matchBruteForceHammingLutAsync</a>
  * <a href="./features2d/features2d#matchBruteForceSL2">matchBruteForceSL2</a>
  * <a href="./features2d/features2d#matchBruteForceSL2Async">matchBruteForceSL2Async</a>
  * <a href="./features2d/features2d#drawKeyPoints">drawKeyPoints</a>
  * <a href="./features2d/features2d#drawMatches">drawMatches</a>
  * <a href="./features2d/KeyPoint"><b>KeyPoint</b></a>
  * <a href="./features2d/DescriptorMatch"><b>DescriptorMatch</b></a>
  * <a href="./features2d/AGASTDetector"><b>AGASTDetector</b></a>
    * <a href="./features2d/AGASTDetector#detect">detect</a>
    * <a href="./features2d/AGASTDetector#detectAsync">detectAsync</a>
  * <a href="./features2d/AKAZEDetector"><b>AKAZEDetector</b></a>
    * <a href="./features2d/AKAZEDetector#detect">detect</a>
    * <a href="./features2d/AKAZEDetector#detectAsync">detectAsync</a>
    * <a href="./features2d/AKAZEDetector#compute">compute</a>
    * <a href="./features2d/AKAZEDetector#computeAsync">computeAsync</a>
  * <a href="./features2d/BRISKDetector"><b>BRISKDetector</b></a>
    * <a href="./features2d/BRISKDetector#detect">detect</a>
    * <a href="./features2d/BRISKDetector#detectAsync">detectAsync</a>
    * <a href="./features2d/BRISKDetector#compute">compute</a>
    * <a href="./features2d/BRISKDetector#computeAsync">computeAsync</a>
  * <a href="./features2d/FASTDetector"><b>FASTDetector</b></a>
    * <a href="./features2d/FASTDetector#detect">detect</a>
    * <a href="./features2d/FASTDetector#detectAsync">detectAsync</a>
  * <a href="./features2d/KAZEDetector"><b>KAZEDetector</b></a>
    * <a href="./features2d/KAZEDetector#detect">detect</a>
    * <a href="./features2d/KAZEDetector#detectAsync">detectAsync</a>
    * <a href="./features2d/KAZEDetector#compute">compute</a>
    * <a href="./features2d/KAZEDetector#computeAsync">computeAsync</a>
  * <a href="./features2d/GFTTDetector"><b>GFTTDetector</b></a>
    * <a href="./features2d/GFTTDetector#detect">detect</a>
    * <a href="./features2d/GFTTDetector#detectAsync">detectAsync</a>
  * <a href="./features2d/MSERDetector"><b>MSERDetector</b></a>
    * <a href="./features2d/MSERDetector#detect">detect</a>
    * <a href="./features2d/MSERDetector#detectAsync">detectAsync</a>
  * <a href="./features2d/ORBDetector"><b>ORBDetector</b></a>
    * <a href="./features2d/ORBDetector#detect">detect</a>
    * <a href="./features2d/ORBDetector#detectAsync">detectAsync</a>
    * <a href="./features2d/ORBDetector#compute">compute</a>
    * <a href="./features2d/ORBDetector#computeAsync">computeAsync</a>
  * <a href="./features2d/SimpleBlobDetectorParams"><b>SimpleBlobDetectorParams</b></a>
  * <a href="./features2d/SimpleBlobDetector"><b>SimpleBlobDetector</b></a>
    * <a href="./features2d/SimpleBlobDetector#detect">detect</a>
    * <a href="./features2d/SimpleBlobDetector#detectAsync">detectAsync</a>
    * <a href="./features2d/SimpleBlobDetector#compute">compute</a>
    * <a href="./features2d/SimpleBlobDetector#computeAsync">computeAsync</a>
* <a href="./xfeatures2d/xfeatures2d"><b>xfeatures2d</b></a>
  * <a href="./xfeatures2d/SIFTDetector"><b>SIFTDetector</b></a>
    * <a href="./xfeatures2d/SIFTDetector#detect">detect</a>
    * <a href="./xfeatures2d/SIFTDetector#detectAsync">detectAsync</a>
    * <a href="./xfeatures2d/SIFTDetector#compute">compute</a>
    * <a href="./xfeatures2d/SIFTDetector#computeAsync">computeAsync</a>
  * <a href="./xfeatures2d/SURFDetector"><b>SURFDetector</b></a>
    * <a href="./xfeatures2d/SURFDetector#detect">detect</a>
    * <a href="./xfeatures2d/SURFDetector#detectAsync">detectAsync</a>
    * <a href="./xfeatures2d/SURFDetector#compute">compute</a>
    * <a href="./xfeatures2d/SURFDetector#computeAsync">computeAsync</a>
* <a href="./tracking/tracking"><b>tracking</b></a>
  * <a href="./tracking/TrackerBoosting"><b>TrackerBoosting</b></a>
    * <a href="./tracking/TrackerBoosting#clear">clear</a>
    * <a href="./tracking/TrackerBoosting#init">init</a>
    * <a href="./tracking/TrackerBoosting#update">update</a>
  * <a href="./tracking/TrackerBoostingParams"><b>TrackerBoostingParams</b></a>
  * <a href="./tracking/TrackerGOTURN"><b>TrackerGOTURN</b></a>
    * <a href="./tracking/TrackerGOTURN#clear">clear</a>
    * <a href="./tracking/TrackerGOTURN#init">init</a>
    * <a href="./tracking/TrackerGOTURN#update">update</a>
  * <a href="./tracking/TrackerKCF"><b>TrackerKCF</b></a>
    * <a href="./tracking/TrackerKCF#clear">clear</a>
    * <a href="./tracking/TrackerKCF#init">init</a>
    * <a href="./tracking/TrackerKCF#update">update</a>
  * <a href="./tracking/TrackerKCFParams"><b>TrackerKCFParams</b></a>
  * <a href="./tracking/TrackerMedianFlow"><b>TrackerMedianFlow</b></a>
    * <a href="./tracking/TrackerMedianFlow#clear">clear</a>
    * <a href="./tracking/TrackerMedianFlow#init">init</a>
    * <a href="./tracking/TrackerMedianFlow#update">update</a>
  * <a href="./tracking/TrackerMIL"><b>TrackerMIL</b></a>
    * <a href="./tracking/TrackerMIL#clear">clear</a>
    * <a href="./tracking/TrackerMIL#init">init</a>
    * <a href="./tracking/TrackerMIL#update">update</a>
  * <a href="./tracking/TrackerMILParams"><b>TrackerMILParams</b></a>
  * <a href="./tracking/TrackerTLD"><b>TrackerTLD</b></a>
    * <a href="./tracking/TrackerTLD#clear">clear</a>
    * <a href="./tracking/TrackerTLD#init">init</a>
    * <a href="./tracking/TrackerTLD#update">update</a>
  * <a href="./tracking/MultiTracker"><b>MultiTracker</b></a>
    * <a href="./tracking/MultiTracker#addMIL">addMIL</a>
    * <a href="./tracking/MultiTracker#addBOOSTING">addBOOSTING</a>
    * <a href="./tracking/MultiTracker#addMEDIANFLOW">addMEDIANFLOW</a>
    * <a href="./tracking/MultiTracker#addTLD">addTLD</a>
    * <a href="./tracking/MultiTracker#addKCF">addKCF</a>
    * <a href="./tracking/MultiTracker#update">update</a>
* <a href="./text/text"><b>text</b></a>
  * <a href="./text/text#loadOCRHMMClassifierCNN">loadOCRHMMClassifierCNN</a>
  * <a href="./text/text#loadOCRHMMClassifierCNNAsync">loadOCRHMMClassifierCNNAsync</a>
  * <a href="./text/text#loadOCRHMMClassifierNMA">loadOCRHMMClassifierNM</a>
  * <a href="./text/text#loadOCRHMMClassifierNMAsync">loadOCRHMMClassifierNMAsync</a>
  * <a href="./text/text#createOCRHMMTransitionsTable">createOCRHMMTransitionsTable</a>
  * <a href="./text/text#createOCRHMMTransitionsTableAsync">createOCRHMMTransitionsTableAsync</a>
  * <a href="./text/OCRHMMClassifier"><b>OCRHMMClassifier</b></a>
    * <a href="./text/OCRHMMClassifier#eval">eval</a>
    * <a href="./text/OCRHMMClassifier#evalAsync">evalAsync</a>
  * <a href="./text/OCRHMMDetector"><b>OCRHMMDetector</b></a>
    * <a href="./text/OCRHMMDetector#run">run</a>
    * <a href="./text/OCRHMMDetector#runAsync">runAsync</a>
    * <a href="./text/OCRHMMDetector#runWithInfo">runWithInfo</a>
    * <a href="./text/OCRHMMDetector#runWithInfoAsync">runWithInfoAsync</a>
* <a href="./face/face"><b>face</b></a>
  * <a href="./face/EigenFaceRecognizer"><b>EigenFaceRecognizer</b></a>
    * <a href="./face/EigenFaceRecognizer#train">train</a>
    * <a href="./face/EigenFaceRecognizer#trainAsync">trainAsync</a>
    * <a href="./face/EigenFaceRecognizer#predict">predict</a>
    * <a href="./face/EigenFaceRecognizer#predictAsync">predictAsync</a>
    * <a href="./face/EigenFaceRecognizer#save">save</a>
    * <a href="./face/EigenFaceRecognizer#load">load</a>
  * <a href="./face/FisherFaceRecognizer"><b>FisherFaceRecognizer</b></a>
    * <a href="./face/FisherFaceRecognizer#train">train</a>
    * <a href="./face/FisherFaceRecognizer#trainAsync">trainAsync</a>
    * <a href="./face/FisherFaceRecognizer#predict">predict</a>
    * <a href="./face/FisherFaceRecognizer#predictAsync">predictAsync</a>
    * <a href="./face/FisherFaceRecognizer#save">save</a>
    * <a href="./face/FisherFaceRecognizer#load">load</a>
  * <a href="./face/LBPHFaceRecognizer"><b>LBPHFaceRecognizer</b></a>
    * <a href="./face/LBPHFaceRecognizer#train">train</a>
    * <a href="./face/LBPHFaceRecognizer#trainAsync">trainAsync</a>
    * <a href="./face/LBPHFaceRecognizer#predict">predict</a>
    * <a href="./face/LBPHFaceRecognizer#predictAsync">predictAsync</a>
    * <a href="./face/LBPHFaceRecognizer#save">save</a>
    * <a href="./face/LBPHFaceRecognizer#load">load</a>
