This repo contains standalone pages for profiling ONNX.js and TensorFlow.js.

We profile two models: MobileNet v2, and ResNet 50 v2.

# MobileNet

For ONNX.js, we used the model assets found here: https://github.com/onnx/models/tree/master/models/image_classification/mobilenet

For TensorFlow.js, we used https://storage.googleapis.com/tfjs-models/savedmodel/mobilenet_v2_1.0_224/tensorflowjs_model.pb

# ResNet

For ONNX.js, we used the model assets found here: https://github.com/onnx/models/tree/master/resnet50

For TensorFlow.js, we used https://storage.googleapis.com/tfjs-models/savedmodel/resnet_50_v2/tensorflowjs_model.pb

We converted this model from TF Hub: https://tfhub.dev/google/imagenet/resnet_v2_50/classification/1
