# How to use rsub with RLogin
### rsubをRLoginで使う方法

--- 

## Setting of RLogin's port forwarding

- Listened
    - Remote
    - Hostname : 127.0.0.1
    - Port : 52698
- Connect
    - Hostname : 127.0.0.1
    - Port : 52698

※ You should set it `127.0.0.1` not `localhost`.


※ `localhost` は動作しません。必ず `127.0.0.1` にします。

---

![](https://raw.githubusercontent.com/kujiy/how-to-use-rsub-with-rlogin/master/0408-02.png)

## Note
- The tab you opened first is important. You can use rsub with multiple tabs whenever you keep opening the first tab. Once you close it, suddenly all tabs will not be able to use rsub then. In that case, you need to close all tabs and reconnect them again.
- 最初に開くtabが重要です。複数シェルで同時にrsubは使えますが、最初のtabを閉じると突然全tabでrsubが使えなくなります。その場合は全tabを閉じて、すべて開き直す必要があります。
