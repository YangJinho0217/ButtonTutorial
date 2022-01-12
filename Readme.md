버튼을 활용한 Label 변경하기

![스크린샷 2022-01-12 오후 2 07 11](https://user-images.githubusercontent.com/73631818/149068094-3cae24c1-c5a3-45f7-9509-3e00ba835336.png)

두개의 버튼과 Label을 올려두었습니다.
<pre>
<code>

    @IBAction func ActionBtn(_ sender: Any) {
        print("왼쪽버튼눌림")
        Text.text = "왼쪽"
    }
    @IBAction func ActionSBtn(_ sender: Any) {
        print("오른쪽버튼눌림")
        Text.text = "오른쪽"
    }
    
</code>
</pre>

