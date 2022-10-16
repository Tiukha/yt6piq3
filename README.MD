# 粵語拼音Tiukha快速方案

配方：℞ **Tiukha/yt6piq3**

基於 [Rime](https://rime.im/) 的粵語拼音Tiukha快速方案。

## 雙字母簡化

- ng->q 
- aa->r
- oe/eo->v
- yu->y 

以上均爲不用的字母（y不單獨使用），故用來表示雙字母以達到簡化目的。其中eo與oe除幾個口語字外，實際上可以互補。
  
## 拼寫簡化
- ji->i 零聲母不與i拼
- joe/oe->v 零聲母不與oe/eo拼
- jyu->y 零聲母不與yu拼
- je->e 零聲母與e拼只有少數語氣字
- ai->a 無a韻母
- ui->y yu與ui可以視爲互補
- eoi->v eoi與eo只有幾個音節重複，並且重複的音節只有少數字
- ou->u ou與u只有與g相拼時有重複，不介意gou與gu重複者可以加上此條
- ei->i ei與i只有與m/n/l/s相拼時有重複，其中與m/n/l相拼時只有少數語氣字，不介意sei與si重複者可以加上此條

## 總結
 
通過以上簡化方案避免了雙字母聲母及韻尾（ng）雙字母韻母（aa/eo/oe/yu）打字的繁雜。除了gw/kw與aai/aan/aang/aat/aak/an/ang/at/ing/ik/ong/ok這幾個音節需要四個字母拼寫外，其他情況最多只需要三個字母就能拼出一個音節（聲母+韻母+韻尾）。同時因爲聲韻母拼寫的簡化，使得大量音節能以一個字母或兩個字母來拼寫，大大提高了打字效率。

值得注意的是，此方案不需要重新製作碼表，僅在schema文件的speller下的algebra下增加幾行代碼即可。

建議使用[Rime 粵語拼音方案](https://github.com/rime/rime-cantonese) ℞ **rime/rime-cantonese**

```dotnetcli
- derive/ng/q/ # 容錯 ng -> q
- derive/aa/r/ # 容錯 r -> aa
- derive/yu/y/ # 容錯 yu -> y
- derive/eo/v/ # 容錯 eo -> v
- derive/oe/v/ # 容錯 oe -> v

- derive/ji/i/ # 容錯 ji -> i
- derive/je/e/ # 容錯 je -> e
- derive/joe/v/ # 容錯 joe -> v
- derive/jeo/v/ # 容錯 jeo -> v
- derive/jyu/y/ # 容錯 jyu -> y

- derive/ai/a/ # 容錯 ai->a
- derive/ei/i/ # 容錯 ei -> i
- derive/ou/u/ # 容錯 ou -> u
- derive/ui/y/ # 容錯 ui -> y
- derive/eoi/v/ # 容錯 eoi -> v
```

粵拼音打字最大優點是音節數多重碼字少（相對普通話等），通過本文的優化進一步提高了打字效率，希望看到這的您能和我一樣享受到快速粵語拼音打字的樂趣。

## 參考資料

[1] [Rime 粵語拼音方案](https://github.com/rime/rime-cantonese) ℞ **rime/rime-cantonese**

[2] [粵語審音配詞字庫 粵語音節表](https://humanum.arts.cuhk.edu.hk/Lexis/lexi-can/)


## 安裝方法

- [Windows](https://ngli.github.io/安装方法/Windows.html)
- [macOS](https://ngli.github.io/安装方法/macOS.html)
- [Linux](https://ngli.github.io/安装方法/Linux.html)
- [Android](https://ngli.github.io/安装方法/Android.html)
- [iOS](https://ngli.github.io/安装方法/iOS.html)

## 使用

- [模糊音](https://ngli.github.io/使用/模糊音.html)
- [輸入提示](https://ngli.github.io/使用/输入提示.html)
- [反查](https://ngli.github.io/使用/反查.html)
- [自定義短語](https://ngli.github.io/使用/自定义短语.html)

## 鳴謝

- [Rime](https://rime.im/)
- [Trime](https://github.com/osfans/trime)
- [iRime](https://github.com/jimmy54/iRime)

## 聯繫

QQ：ssTiukha

mail：tiukha@foxmail.com
