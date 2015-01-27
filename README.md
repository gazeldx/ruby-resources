以下资源都是本人用过的，且认为是最好的，第二名不会出现。
因此，它们是武断的。如果你发现了更好的替代方案，请issue我。谢谢。

## Ruby Web framework
+ [Rails](http://rubyonrails.org/): Ruby on Rails, Ruby Web开发使用度最高，约定较多，不适合初学者
+ [Sinatra](http://www.sinatrarb.com/): Sinatra，比Rails更轻量级，DSL设计典范，两行代码搞定一个网站，适合初学者

## Ruby Gems
+ [Pundit](https://github.com/elabs/pundit): 用于权限认证，如某用户是否可以进行某操作。因为用了policy的设计模式，将相关逻辑抽象到了独立文件中，一下子清晰了
+ [CarrierWave](httpshttps://github.com/carrierwaveuploader/carrierwave): 用于文件上传，支持传到云端。可以生成缩略图，对文件大小等做validation
+ [Slim](https://github.com/slim-template/slim): 类似haml的一个html简化的template，我本人更喜欢用slim，因为haml的东西它都有，但它语法上和html更接近
+ [Sequel](https://github.com/jeremyevans/sequel): 操作数据库。支持各种DB，和active_record类似，但用法更灵活。
