# Tensorflow版本后门攻击
将各个文件夹下的core.py文件替代tensorflow原有core.py 

找到每个文件夹下test.py文件（vision-transformer文件夹下为vittest.py），直接运行即可得到后门模型准确率和攻击成功率（arcface部分运行时需要加上参数，类似于--cfg_path="./configs/arc_res50.yaml"） 

注意修改文件中用到的路径
