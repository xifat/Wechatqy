# Wechatqy
微信企业号开发SDK for thinkphp 5.0<br>
暂不支持其他框架 因为使用了tp5的缓存机制<br>
后期再进行修改

## 安装
使用命令<br>
composer require ppeerit/wechatqy

## 使用
####加载命名空间
use Ppeerit\Wechatqy;<br>
####实例化对象
$wechatqy = new Wechatqy($CorpID, $Secret, $Identity = '');<br>
####参数介绍
$CorpID：企业号唯一ID<br>
$Secret：企业号管理组凭证密钥<br>
$Identity：公众号标识，自定义，用户区分多个公众号调用缓存时的标识，不可重复，否则会导致多个公众号数据错乱，只有一个公众号时可不传入，默认缓存access_token，所以多个公众号时切勿使用access_token作为标识
####接口介绍:
待完善<br>
