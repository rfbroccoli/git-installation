
## Git installation for windows
 1. Install မလုပ်ခင်

![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/00.png?raw=true)

 2. [git](https://git-scm.com/downloads) ကို ဒီကနေ download လုပ်ပါ

![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/01.png?raw=true)

 3. download လို့ရတဲ့ file ကို ဖွင့်

![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/02.png?raw=true)
4. next လုပ်သွား
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/03.png?raw=true)
5. အောက်က အဆင့်နည်းနည်းကလွဲပြီး၊ အကုန်နီးပါး သူပေးထားတဲ့အတိုင်း next နှိပ်
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/04.png?raw=true)
6. **ဒီအဆင့်မှာ main ပြောင်း**
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/05.png?raw=true)
7. **ဒီမှာ credential manager ကို select လုပ်ထားရမယ်**
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/06.png?raw=true)
8. cmd or powershell မှာ ဒီလိုပေါ်ရင် သွင်းတာအောင်မြင်ပြီ
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/07.png?raw=true)
9. git install ပြီးရင် search ကနေဖြစ်ဖြစ် **git bash** လို့ရှာလိုက်ရင် cmd or powershell လို terminal တစ်ခုတွေ့လိမ့်မယ်၊ နောက် code ရင် cmd or powershell အစား အဲ့ကောင်သုံးလည်းရတယ် 
10. လောလောဆယ် setup နောက်ဆုံးအဆင့်အနေနဲ့ name and email ထည့်ရမယ်။ ဘာထည့်ထည့်ရပေမယ့်၊ **email မှာ github အကောင့်လုပ်တုန်းက email၊ name နေရာ github username ထည့်ရင် github user ပြန်ရှာရတာပိုလွယ်တယ်**။ cmd or powershell or git bash တစ်ခုခုမှာ အောက်ကပုံစံ ရိုက်ထည့်လိုက်ရင် setup လုပ်တာပြီးပြီ။

    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"

![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/08.png?raw=true)
 11. github ကို git သုံးပြီး အစမ်းတင်ချင်ရင် github မှာ new repo လုပ်လိုက်။ စက်ထဲက ကိုယ်တင်ချင်တဲ့ code နေရာမှာ git terminal or git bash ဖွင့်။ အောက်က command တွေ run
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/Screenshot%20from%202022-03-29%2014-38-40.png?raw=true)

	git init 
    git add .
    git commit -m "first commit"
    git remote add origin https://github.com/rfbroccoli/git-installation.git
    git push -u origin main

 - **init** git repo လုပ်တာ။ 
 - **add .** က ရောက်နေတဲ့ folder ထဲကရှိသမျှ git repo ထဲ ယာယီထည့်တာ။ 
 - **commit** က repo ထဲထည့်ထားတာတွေကို commit လုပ်သိမ်းတာ။ **-m** က ဘာ commit လိုက်လဲ message ထည့်တာ
 - (install လုပ်တုန်းက default branch ကို main လို့ထားမယ် လုပ်ထားလို့ **git branch -M main** လို့ထည့်စရာမလိုဘူး။)
 - **remote add [name] [link]** က link နေရာက git သိမ်းလို့ရတဲ့နေရာနဲ့ချိတ်တာ။ 
 - **push** က အဲ့ remote repo ဆီတင်တာ။ **-u** က ဘယ်သူအနေနဲ့ တင်တာလဲ မပြောတော့ဘဲ အစမှာ setup ထားတဲ့ user အနေနဲ့တင်မယ်လို့ပြောတာ
 
12. ပထမဆုံး **git push** လုပ်ရင် github signin လုပ်ပေးရတယ်။ sign in with your browser ရွေးပြီး sign in လည်းရတယ်။ token နဲ့ sign in နည်းက replit ကနေ git push ပြတော့မှ ပြောမယ်။
![00.png](https://github.com/rfbroccoli/public/blob/main/git-installation/09.png?raw=true)
