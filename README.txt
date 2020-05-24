１　ソースのURL(git)
    https://github.com/madhawav/YOLO3-4-Py

２　ファイル
　　・オリジナルpythonファイル：video_demo.py.org
    ・今回、batのみ書きだすpythonファイル：video_demo.py
    ・出力されるbatが写っているMP4動画：outImgVideo.mp4

３　batの写っているフレーム番号
    ・

４　実行方法i
    ・動作環境:Python 3.6.9
    
    > git clone https://github.com/madhawav/YOLO3-4-Py.git
    > cd YOLO3-4-Py/
    > python3 setup.py build_ext --inplace
    > sh download_models.sh 
    *必要に応じたDL
    > get -O weights/yolov3.weights https://pjreddie.com/media/files/yolov3-tiny.weights
　　> python3 video_demo.py [input MP4 File]
