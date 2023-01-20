## အသုံးပြုပုံ(CONFIG_FILE_URLထုတ်ပုံ)

- config.env မှ စာများကူးပြီး [gist](https://gist.github.com/) ဖွင့် paste လုပ်ပါ။ (anas repo, wzml repo, rclone mltb repo ဆိုင်ရာစာကိုသာကူးပါ)
- file name နေရာတွင် **config.env** ဟုပေးပါ။
- paste ချထားသော vars များမှ **#မဖြစ်မနေဖြည့်ရမည်များ** တွင်ဖြည့်ပါ။ 
- ကျန် vars များလဲ ဖြည့်လိုလျှင်ဖြည့်ပါ
- upstream repo နေရာတွင် [Anas17 repo](https://github.com/anasty17/mirror-leech-telegram-bot), [Wzml repo](https://github.com/weebzone/wzml), [RcloneMltb repo](https://github.com/Sam-Max/rclone-mirror-leech-telegram-bot) စသဖြင့် လိုသော repolink ဖြည့်ပါ
- ဘာမှမဖြည့်လျှင် anasty17 repo default သုံးပါမည်။
- ဖြည့်စရာပြီးလျှင် **create secret gist** အစိမ်းရောင်ကိုနှိပ်ပါ
- ပြီးလျှင် ဘယ်ဖက်အပေါ်မှ raw ကို နှိပ်ပါ
- address bar မှ link ကို ကူးပါ

## Render တွင် deploy ပုံ

- ⭐ ပထမဆုံး ဒီ repo ကို fork ပါ။ ဘာdata မှ မပါလို့ **public** ပဲထားပါ။
- [Render](https://render.com/) ဖွင့်ပြီး free signup လုပ်ပါ။
- dashboard.render.com ဖွင့်ပြီး new + ကို နှိပ် web service ကို ရွေးပါ
- Public Git repository နေရာတွင် မိမိ fork ထားသော ယခု repo link ထည့်ပါ
- 1.name နေရာ ကြိုက်ရာထားပါ
- 2.အောက်နားက **advanced** နှိပ်ပြီး **Add Environment Variable** ထပ်နှိပ်ပါ
- 3.key နေရာတွင် **CONFIG_FILE_URL** ဖြည့်ပါ(စာလုံးပေါင်းမှန်ရမည်)
- 4.value နေရာတွင် အပေါ်မှ ထုတ်ယူခဲ့သော **https://gist.githubusercontent.………config.env** link ထည့်ပါ
- ပြီးလျှင် အောက်ဆုံးနားက **create web service** အပြာရောင် ကို နှိပ်ပြီး ခဏေစာင့်ပါ
- terminal box တက်လာပြီး install ပါမည်။ Bot Start စာပေါ်လာလျှင် စသုံးလို့ရပါပြီ။
- render သုံးလျှင် မိမိ render app link ကို base url တွင် ထည့် port 8080 ထည့်ရမည်။ အသေးစိတ်ကို Drivetalk gp ထဲတွင်မေးပါ။

## Github Action ဖြင့်သုံးပုံ

- ဒီ repo template ကို use template ကနေ မိမိ own repo လုပ်ပါ။ fork လို့လဲရပါတယ်
- repo ရဲ့ action နေရာကိုနှိပ်
- 🎨 Allin1Mirror ကိုထပ်နှိပ်
- အပြာစာတန်းဘေးက Run Workflow ⬇ကိုနှိပ်
- CONFIG_FILE_URL နေရာတွင် gist.githubusercontent~~~~~confif.env နှင့်ဆုံးသော link ဖြည့်
- Run Workflow အစိမ်းရောင်စာကိုနှိပ်
- ၂ မိနစ်လောက်စောင့်ပြီးရင် Bot သုံးလို့ရပါပြီ
- Bot ရပ်လို လျှင် cancel workflow နှိပ်

## Koyeb တွင် သုံးလိုလျှင်

- create service တွင် docker image ရွေးပါ
- anasaty17/allinonemltb  ကိုဖြည့်ပါ
- Env variables ကို ဖွင့်ပြီး name နေရာတွင် CONFIG_FILE_URL ဖြည့် အလယ်က Plain Text ကို ဒီတိုင်းထား Value နေရာတွင် gist.githubusercontent~~~~~config.env ကိုဖြည့်
- ⭐Port ကို 80 ဖြည့်ပါ
- ![image](https://user-images.githubusercontent.com/119148169/213683316-5c92805d-a22e-4a8b-8646-23036058e840.jpeg)

- ✅base url Koyeb app link ဖြည့်ရပါမယ်။ group ထဲမှာမေးပါ။
- create ပါ

## Anasty, Wzml တို့တွင် /bsetting ချိန်နည်း

- anasty နှင့် wzml repo များတွင် importance Vars 4 ခုသာဖြည့်ပြီး ကျန် token file, sudo user, account.zip စသဖြင့်ကို bot ထဲမှတင်လို့ရပါတယ် တင်နည်းကို [ဒီမှာကြည့်ပါ။](https://github.com/dr007bot/Allin1mltb/blob/main/bsetting.md)
