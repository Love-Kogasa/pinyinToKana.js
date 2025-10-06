# PinyinToKana
将中文拼音转换为日语假名  
[pinyin_to_kanji](https://bgithub.xyz/uiur/pinyin_to_kana/) 的完全JavaScript实现.  

# Usage
```js
// 将 mapping.tsv 放到 ./map.tsv
var p2k = await PinyinToKana.load( "./map.tsv" )
p2k.pinyinToKana( "ni hao，shi jie." ) // ニーハオ、シージエ
// p2k.pinyin_to_kana( "ni hao，shi jie" ) ニーshi，jieジエ
```