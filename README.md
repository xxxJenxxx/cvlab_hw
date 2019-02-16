# cvlab_hw - Localize & Correct License Plate
##試過 - 
1. BCE
2. SmoothL1
3. LR decay
4. lower LR

##最終修改參數 - 
1. 嘗試自己建model(五層, conv跟maxpool中間有使用relu, 最後有三層FC, 每層中間依序用了relu->tanh->sigmoid)
2. epoch = 20
