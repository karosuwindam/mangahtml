# mangahtml

# 説明
マンガビューアのような使い他が出来るように\
画像ファイルを並べました。

# 使い方

Javascript内のfilename,filetype,pagemaxを操作してください

下記のようなルールでimgタグの参照ファイルが出力されます。
> for(i=0;i<pagemax;i++){
>   imageout = filename + i + filetype
> }

