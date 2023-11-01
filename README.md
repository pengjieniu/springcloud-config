# Config服务端配置与测试
  用你自己的账号在GitHub上新建一个名为springcloud-config的新Repository
  由上一步获得刚新建的git地址
  本地硬盘目录上新建git仓库并clone
  此时在本地D盘符下D:\44\SpringCloud2020\springcloud-config
  新建Module模块cloud-config-center-3344 它即为Cloud的配置中心模块cloudConfig Center
  POM
  YML
  主启动类
    ConfigCenterMain3344
      @EnableConfigServer
  windows下修改hosts文件，增加映射
  测试通过Config微服务是否可以从GitHub上获取配置内容
  配置读取规则
  成功实现了用SpringCloud Config通过GitHub获取配置信息

