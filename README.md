# RetailGoods-identification-based-on-MindSpore-AI
为了方便薅羊毛而开发的商品识别系统~
## 可通过.py脚本中的cfg进行参数修改训练行为。cfg中的参数如下：
**data_path**         训练数据集路径，如果是zip文件需要解压  

**test_path**         测试数据集路径，如果是zip文件需要解压  

**data_size**         数据量大小   
**HEIGHT**            图片高度
**WIDTH**             图片宽度
**__R_MEAN**          R通道平均数
**__G_MEAN**          G通道平均数
**__B_MEAN**          B通道平均数
**__R_STD**           默认1
**__G_STD**           默认1
**__B_STD**           默认1
**__RESIZE_SIDE_MIN** resize边的最小值
**__RESIZE_SIDE_MAX** resize边的最大值
**batch_size**        默认32
**num_class**         分类类别数量
**epoch_size**        训练次数，默认30
**loss_scale_num**    损失规模数，默认1024
**prefix**            前缀，默认'resnet-ai'
**directory**         存储模型路径，默认'./model_resnet'
**save_checkpoint_steps**  默认10
