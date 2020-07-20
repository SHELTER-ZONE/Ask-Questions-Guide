# N.提問時你該做的事
在你提問之前，請確保你已經自我審視過 (其他章節中所提的觀念與例子)，並且你真的無法解決該問題。

## CD-N01 按邏輯與錯誤發生順序描述
遇到問題時不要慌張，先冷靜下來整理一下要釐清的問題  
可以使對方更容易理解你的狀況並加快解決速度  
#### 類通靈式提問：
```
ex. 為甚麼回傳沒東西??
ex. 為啥我sum變這麼多位數，答案明明才123...
```
#### 可以試著按邏輯描述一遍事發過程：
```
ex. 我撰寫了一個函式，但主程式呼叫的時候卻沒有顯示回傳值，請問有解嗎?
ex. 我宣告一個變數sum，為甚麼進迴圈的時候不會從0開始加總?
```

## CD-N02 請使用CodeBlock標註程式碼
請善於使用CodeBlock，將你的程式碼/錯誤碼額外框起來  
這樣一來版面更整潔，也更方便他人複製你的Code下來除錯  
#### 範例：
> **可以請教為甚麼這無法運作嗎?**  
> ```
> #include <iostream>
> int main()
> {
>     std::cout << "Hello World"
>     return 0;
> }
> ```
>> **請問這個錯誤是甚麼意思?**  
>> ```HelloWorld.cpp:4:31: error: expected ';' before 'return' std::cout << "Hello World"```  

##### 非不得已，請別使用手機翻拍畫面，螢幕截圖更加易於閱讀。 

## CD-N03 良好的詢問方式
雖然是個技術交流的地方，但還請保有基本的禮儀  
解決問題的過程往往比直接從他人口中得到結果重要  
#### 不良範例：
```
ex. 可以告訴我哪裡出問題嗎 (直接上圖,且無指出疑問點)
    我不知道
    我不會
    你幫我弄

ex. 直接進來幫我看啦 https://discordapp.com/invite/XXXXXXX
```
可以勇於提出疑問，通常都會得到解決辦法，但不是當伸手牌。  
