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
