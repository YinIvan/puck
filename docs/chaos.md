## 字符打乱
`puck`可以支持生成添加干扰符号，字符码等的变形字体，以实现个性的效果。　

## 用法

### 基本用法
```php
use puck\helpers\Chaos;
$s='你好';
$chaos = new Chaos(); 
        $prefix=[
            '[微笑]',
            '[大笑]',
            '[色]',
            '[失望]',
            '[皱眉]',
            '[哭]',
            '[惊恐]',
            '[亲亲]',
            '[大眼]',
            '[抓狂]',
            '[脸红]',
            '[书呆子]',
            '[可爱]',
            '[吐舌]',
            '[眨眼]',
            '[好吃]',
            '[天使]',
            '[得意]',
            '[讽刺]',
            '[花痴]',
            '[惊讶]'
        ];
$chaos->addPrefix($prefix);
echo $chaos->get($s);
//[惊讶]ni好
```
