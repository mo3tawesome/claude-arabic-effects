<div dir="rtl">

# 42 إفكت للفيديو جوه Claude، بالعربي

ارمي الفيديو بتاعك في Claude، واكتب `/effects` واسم الإفكت. ده كل الـedit.

النسخة دي بتكتب عربي صح: الحروف متوصلة، والكلام من اليمين للشمال، بخط Cairo، وتقدر تخلط عربي وإنجليزي في نفس السطر عادي.

عملها [@moatassem.ai](https://instagram.com/moatassem.ai)

مبني على claude-video-effects بتاع Vibha Ramprakash (MIT)

## التسطيب (سطر واحد)

افتح الـTerminal (أو الـterminal اللي جوه Claude Code) والصق ده:

</div>

```bash
git clone https://github.com/mo3tawesome/claude-arabic-effects ~/.claude/skills/effects
```

<div dir="rtl">

على Windows (PowerShell) اكتب `$HOME\.claude\skills\effects` بدل `~/.claude/skills/effects`.

بعدها اقفل Claude Code وافتحه تاني. خلاص كده.

> مش عارف تعملها؟ افتح Claude Code والصق: **"سطّب الـskill من github.com/mo3tawesome/claude-arabic-effects في ~/.claude/skills/effects"** وهو هيعملها لوحده.

## إزاي تستخدمها

1. افتح Claude Code (الـapp أو الـterminal).
2. اسحب الفيديو بتاعك جوه الشات.
3. اكتب الإفكت اللي عايزه:

</div>

```
/effects orbit من ثانية 3 لـ 6
/effects spotlight لما أقول "طفي النور"، والكلمة "Claude" ورايا
/effects red-collage والكلمة "مونتاج"
/effects checklist في الآخر، والخطوات بالعربي
/effects glass-widgets أول 3 ثواني
```

<div dir="rtl">

أول مرة بس، Claude بيظبط نفسه (حوالي دقيقتين). محتاج `ffmpeg` و Python، ولو مش موجودين بيسطبهم لك.

Claude بيشيك على كام frame الأول، يصلح أي حاجة بتغطي وشك، وبعدين يطلع `yourvideo_effects.mp4` جنب الفيديو الأصلي. الصوت بتاعك زي ما هو.

تقدر تحط كذا إفكت مرة واحدة: *"حط locked-on من 6 لـ 10، وبعدها orbit من 10 لـ 13، وبعدين reject-stamp على كلمة لأ."*

## الكلام العربي

- أي نص في أي إفكت ينفع يبقى عربي أو إنجليزي أو الاتنين مع بعض.
- الكلام اللي بيظهر في كل إفكت متترجم أصلا لعامية مصرية قصيرة، وتقدر تغيره بالكلام اللي انت عايزه.
- الـchecklist والـtodo ومفاتيح الآيفون بيتقلبوا يمين وشمال لما الكلام يبقى عربي، والعناوين بتتظبط على اليمين، ولافتة الـLED بتكتب نفسها من اليمين.

## الـ42 إفكت

| # | اكتب ده | اللي بيحصل |
|---|---|---|
| 1 | `noise` | ريلز بتتكوم ورا راسك |
| 2 | `lineup` | مربعات عليها أرقام بتتفرد فوق راسك |
| 3 | `locked-on` | أقواس بتمسك في وشك والكاميرا بتمشي معاك |
| 4 | `orbit` | الريلز بتاعتك بتلف حوالين راسك، ورا منك من فوق |
| 5 | `lean-in` | زووم سريع على كلمة واحدة |
| 6 | `backdrop-word` | كلمة كبيرة بتنزل ورا منك |
| 7 | `spotlight` | النور بيطفي وانت بس اللي منور |
| 8 | `the-bill` | التعليمات بتطلع زي فاتورة |
| 9 | `moody` | ألوان mood سينمائية |
| 10 | `swipe` | سلايدر قبل وبعد |
| 11 | `todo` | checklist جنب راسك بتتعلم وانت بتتكلم |
| 12 | `comment-box` | كومنت إنستجرام بيكتب نفسه وبيتنشر |
| 13 | `tap` | زرار Follow بيتقلب لـ "بتتابعه" |
| 14 | `pause-point` | الصورة بتقف وسهم مرسوم بإيد بيشاور عليك |
| 15 | `uninstall` | شريط uninstall بيكسر الكادر بـ glitch |
| 16 | `reel-frame` | الفيديو بيصغر جوه كارت ريل |
| 17 | `shortcut-rain` | زراير كيبورد بتمطر ورا منك |
| 18 | `reject-stamp` | ختم أحمر كبير بيتخبط على الشاشة |
| 19 | `countdown-flip` | عد تنازلي 3، 2، 1 فوق راسك |
| 20 | `rabbit-hole` | الأوضة بتتسحب لجوه وراك |
| 21 | `cover-star` | بتبقى غلاف مجلة |
| 22 | `scribble` | شخبطة ماركر بترسم نفسها حواليك |
| 23 | `glass-widgets` | widgets إزاز و artifacts صغيرة بتطير حوالين راسك |
| 24 | `red-collage` | انت أبيض وأسود، كلمة حمرا كبيرة وراك، وتلات سطور بتخبط |
| 25 | `split-headline` | كارت عنوان بينزل ويزقك لتحت |
| 26 | `pastel-word` | أوضة لافندر، كلمة كبيرة وراك، وكارت بروفايل بياخد Follow |
| 27 | `check-pills` | ورق مربعات، الريلز متعلقة وراك، وزراير زرقا بتتداس |
| 28 | `timeline` | لوك فيلم أحمر غامق مع timeline ومؤشر منور |
| 29 | `headline-box` | زووم مع عنوان من سطرين نضيف |
| 30 | `profile-wall` | جريد الريلز بتاعك بيملا الحيطة والعداد بيطلع |
| 31 | `tier-list` | tier list بتنزل و Claude بيطير على S |
| 32 | `broll-split` | b-roll فوق عليه تاج سعر، وانت تحت |
| 33 | `phone-fan` | الريلز بتتفرد زي موبايلات في الإيد |
| 34 | `dot-reveal` | الكادر بيتبني من نقط منورة وبعدين يبان كامل |
| 35 | `headline-wall` | العناوين بتاعتك بتتكوم ورا راسك وبعدين المجموع يطلع قدامك |
| 36 | `checklist` | task list من Claude تحت دقنك، كل خطوة بتلف وبعدين تخضر |
| 37 | `liquid-glass-graph` | كارت liquid glass فيه graph بيطلع ورقم بيعد |
| 38 | `carousel-spin` | الريلز بتلف حواليك في carousel تلاتي الأبعاد |
| 39 | `match-cut` | صفحات أخبار بتقطع على كلمة واحدة ثابتة ورا راسك |
| 40 | `apple-toggles` | مفاتيح آيفون بتفتح واحد ورا التاني |
| 41 | `led-sign` | النور بيطفي ولافتة LED بتكتب نفسها ورا منك |
| 42 | `slow-push` | زووم سينمائي بطيء والأوضة بتسيح ورا منك |

لوكات زيادة: `/effects glitter-spotlight` (أشعة دهبي ولمعة)، `cover-star look=editorial` (غلاف مجلة كلاسيك)، و `liquid-glass-graph look=bento` (داشبورد إزاز حواليك).

كل إفكت بيمشي مع وشك، وأي حاجة ممكن تغطي وشك بتروح ورا راسك.

**نصايح**
- الفيديوهات الطولي اللي انت باين فيها بتطلع أحسن حاجة.
- قول التوقيت بكلامك العادي ("لما أقول 'بص'")، و Claude بيلاقي الثانية بالظبط.
- عايز الريلز بتاعتك في `orbit` أو `noise` أو `phone-fan` أو `profile-wall`؟ ادي Claude فولدر فيه screenshots.
- الأرقام والعدادات والعناوين لازم تبقى أرقامك الحقيقية، قول لـ Claude هي كام.
- السطور العربي خليها قصيرة، من كلمتين لأربعة.
- الـrender بيطلع 1080p، ولو عايز 4K اطلبه (أبطأ شوية).

## كلام بصراحة
- دي **نسخ أولية**. مش هتطلع زي الـedit اللي في الريل بالظبط، لأن فيه sound design وتوقيت متظبط بالإيد.
- هو بيعمل draft، وانت اللي بتوافق. اتفرج على النتيجة قبل ما تنشر.
- مفيش أصوات ولا captions بتتضاف. ضيفهم في CapCut.

## لو حاجة باظت
قول لـ Claude اللي شايفه ("الكلمة مغطية وشي"، "سريع أوي"). هيصلح الخطة ويعمل render تاني.

## الكريدت
مبني على claude-video-effects بتاع Vibha Ramprakash (MIT): https://github.com/Vibha-Ramprakash/claude-video-effects

تتبع الوش: [OpenCV YuNet](https://github.com/opencv/opencv_zoo) (MIT). فصل الشخص: [MediaPipe Selfie Segmenter](https://ai.google.dev/edge/mediapipe/solutions/vision/image_segmenter) (Apache 2.0). الخطوط: Cairo و Archivo Black و Instrument Serif و Space Mono و Inter و Anton و Montserrat و Playfair Display (SIL OFL) و Permanent Marker (Apache 2.0)، والرخص في `fonts/`. الباقي MIT، شوف `LICENSE`.

</div>
