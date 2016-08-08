php-emoji  ios9
=========
现在支持ios9 新表情  自己测了下没问题，如果发现问题 请多指教
Simple PHP libiary to convert Emoji(iOS 6,7,8,9,OS X) to unicode

Now support ios9 new emoji 

匹配思路：通过emoji的code编码 正则匹配 
emoji  full:http://unicode.org/emoji/charts/full-emoji-list.html
 
>usage

``` php
<?php
    require_once('path/to/Emoji.php');
    //encode
    $text = '😄,hi';
    echo Emoji::Encode($text);
    //decode
    $text='\ud83d\ude04,hi';
    echo Emoji::Decode($text);
?>
```
