Forked from [像素字体主题 / aseprite-theme-pixel](https://github.com/J-11/Aseprite-Simplified-Chinese)

# Aseprite 中文像素字型 / Pixel-Chinese-Font

A Pixel-Art Style Font Theme for Chinese Aseprite User  
  
## 說明
本主題只是將Aseprite預設主題的字型替換成適合中文顯示的類型，可自由更換至其他主題上，或使用其他字型。

### 在其他主題使用此字型的方法
將字型檔`Zfull-GB.ttf`移至該主題的目錄下，並按下方代碼所示，於該主題的`theme.xml`中添加/更改`<fonts> ... </fonts>`片段：
```
<theme>

...

    <fonts>
        <font id="default" name="Zfull-GB" type="truetype" antialias="false" file="./Zfull-GB.ttf" size="10" />
        <font id="mini" font="Zfull-GB" size="10" />
    </fonts>
    
...

</theme>
```

### 使用其他字型的方法
- 將`<fonts>`標籤屬性的`file`指向屬意的字型檔的路徑。
- 亦可利用`font`屬性，將其設定為已定義的字型`name`。
  
根據原作者[建議](https://steamcommunity.com/sharedfiles/filedetails/?id=1333477949)，中文字體大小（利用`<fonts>`標籤屬性的`size`修改）最好設定在8~10。

### 安裝
下載`.aseprite-extension`，雙擊後讓Aseprite自動安裝。

或

下載`.zip`壓縮檔，手動於Aseprite中新增、啟用主題。

### 下載
- [.aseprite-extension](pixel-chinese-font-theme.aseprite-extension)
- [.zip](https://github.com/CryMasK/Pixel-Chinese-Font/releases)
