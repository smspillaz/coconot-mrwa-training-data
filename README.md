Training data for Coconot Australian Sign Detection
===================================================

Copy these files into the darknet repository directly,
you can use something like:

    ./darknet detector train cfg/obj.data cfg/yolo-obj.cfg darknet19_448conv.23

Make sure you build darknet with GPU=1 and CUDADNN otherwise
it will be *really* slow.

y u no give me trained model?
-----------------------------

Pretrained models at http://coconot-models.ap-southeast-2.s3.amazonaws.com/coconot-models.tar.bz2

They might be overfitted. ¯\_(ツ)_/¯
