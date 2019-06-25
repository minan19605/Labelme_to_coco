# Labelme_to_coco
Convert the Labelme format json files to  COCO format json file

I am using Facebook Detectron to train my data set. I got the labeled data with the 'lableme' format. I use those code to convert those labelme format json files into the one json file which follow the COCO data set.

The usage is like below:
## load the train data set and then convert and write the coco json file
labelme_json=glob.glob(r'D:\train_data\json\*.json')
labelme2coco(labelme_json,'./coco_train.json')
