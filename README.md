<h1 align="center">yolov5.js zoo</h1>

<p align="center"> 
    <img width="200" src="https://yolov5js-images.s3.eu-central-1.amazonaws.com/yolov5js-logo.png" alt="Logo">
</p>

## <div align="center">Convert</div>

```bash
# clone YOLOv5 repository
git clone https://github.com/ultralytics/yolov5.git
cd yolov5

# create python virtual environment [recommended]
virtualenv venv
source venv/bin/activate

# install dependencies
pip install -r requirements.txt
pip install tensorflowjs

# convert model to tensorflow.js format
python export.py --weights yolov5s.pt --include tfjs
```

## <div align="center">Deploy</div>

Use YOLOv5.js [npm package](https://www.npmjs.com/package/yolov5js) to run models on your website.

## <div align="center">Contribute</div>

Convert your YOLOv5 model to tensorflow.js, create [pull request](https://github.com/SkalskiP/yolov5js-zoo/pulls) and allow others to run your AI in the browser.

## <div align="center">Kudos</div>

Kudos to [ultralytics](https://ultralytics.com/) team as well as all other open-source contributors for building [YOLOv5](https://github.com/ultralytics/yolov5) project, and making it all possible.

## <div align="center">License</div>

Project is freely distributable under the terms of the [MIT license](LICENSE).
