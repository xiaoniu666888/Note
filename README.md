# Note
Knowledge points in the development process
# 2023.1.8
1. 修改element-plus中的css样式要使用穿透 
例:  
      :deep(.el-tree-node__content .el-checkbox .is-disabled)
            display: none 

      :deep(.el-checkbox__inner)
            border-radius: 10px
