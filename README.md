[index.html.txt](https://github.com/user-attachments/files/28433722/index.html.txt)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>تحليل مسرحية The Devil and Daniel Webster</title>
  <style>
    :root{
      --navy:#1f3864;
      --blue:#2e5fa3;
      --light:#eaf0fa;
      --gold:#c9a227;
      --text:#1d2433;
      --muted:#556070;
      --card:#ffffff;
      --line:#d7deea;
      --shadow:0 10px 30px rgba(31,56,100,.12);
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      font-family: "Tahoma", "Arial", sans-serif;
      background:linear-gradient(180deg, #f7f9fd 0%, #eef3fb 100%);
      color:var(--text);
      line-height:1.9;
    }
    a{color:var(--blue); text-decoration:none}
    .container{max-width:1200px; margin:auto; padding:24px}
    .hero{
      background:linear-gradient(135deg, var(--navy), var(--blue));
      color:#fff;
      border-bottom:5px solid var(--gold);
      padding:42px 24px;
      border-radius:0 0 28px 28px;
      box-shadow:var(--shadow);
    }
    .hero h1{margin:0 0 10px; font-size:clamp(28px, 4vw, 46px)}
    .hero p{margin:0; max-width:900px; color:#eef4ff}
    .topbar{
      display:flex; gap:12px; flex-wrap:wrap; margin-top:18px
    }
    .chip{
      background:rgba(255,255,255,.12);
      border:1px solid rgba(255,255,255,.2);
      padding:8px 14px; border-radius:999px
    }
    .grid{
      display:grid;
      grid-template-columns:repeat(12,1fr);
      gap:18px;
      margin-top:24px
    }
    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:18px;
      box-shadow:var(--shadow);
      padding:20px;
    }
    .span-12{grid-column:span 12}
    .span-8{grid-column:span 8}
    .span-6{grid-column:span 6}
    .span-4{grid-column:span 4}
    .span-3{grid-column:span 3}
    h2,h3,h4{color:var(--navy); margin-top:0}
    .section-title{
      background:var(--navy);
      color:#fff;
      padding:12px 16px;
      border-radius:14px;
      margin-bottom:14px;
    }
    .sub{
      color:var(--muted);
      font-size:.98rem;
      margin-top:-6px
    }
    .table{
      width:100%;
      border-collapse:collapse;
      overflow:hidden;
      border-radius:14px;
      margin-top:10px
    }
    .table th,.table td{
      border:1px solid var(--line);
      padding:12px 10px;
      vertical-align:top
    }
    .table th{background:var(--light); color:var(--navy)}
    .table tr:nth-child(even) td{background:#fafcff}
    .accent{color:var(--gold); font-weight:700}
    .btns{display:flex; flex-wrap:wrap; gap:10px; margin:12px 0}
    button,.btn{
      border:none;
      background:var(--blue);
      color:#fff;
      padding:11px 15px;
      border-radius:12px;
      cursor:pointer;
      font-size:1rem;
    }
    button:hover,.btn:hover{opacity:.92}
    .outline{background:#fff; color:var(--navy); border:1px solid var(--line)}
    details{
      background:#fff;
      border:1px solid var(--line);
      border-radius:14px;
      padding:14px 16px;
      margin:12px 0;
      box-shadow:var(--shadow)
    }
    summary{cursor:pointer; font-weight:700; color:var(--navy)}
    .flex{display:flex; gap:16px; flex-wrap:wrap}
    .mini{
      background:var(--light);
      border:1px solid #dbe5f5;
      border-radius:14px;
      padding:14px;
      flex:1 1 250px;
    }
    .timeline{
      display:grid;
      gap:14px;
    }
    .step{
      display:grid;
      grid-template-columns:110px 1fr;
      gap:14px;
      align-items:start;
      background:#fff;
      border:1px solid var(--line);
      border-radius:16px;
      padding:14px;
    }
    .step .tag{
      background:var(--gold);
      color:#fff;
      border-radius:12px;
      padding:10px;
      text-align:center;
      font-weight:700;
    }
    .quote{
      border-right:5px solid var(--gold);
      background:#fffaf0;
      padding:14px 16px;
      border-radius:14px;
      margin:12px 0;
    }
    .quiz input{
      width:100%;
      padding:12px;
      border-radius:10px;
      border:1px solid var(--line);
      margin:8px 0 12px;
    }
    .answer{
      display:none;
      background:#eef7ea;
      border:1px solid #cfe4c8;
      padding:12px;
      border-radius:12px;
      margin-top:10px;
    }
    .show{display:block}
    .footer{
      text-align:center;
      color:var(--muted);
      padding:28px 0 44px
    }
    @media (max-width: 900px){
      .span-8,.span-6,.span-4,.span-3{grid-column:span 12}
      .step{grid-template-columns:1fr}
    }
  </style>
</head>
<body>

<header class="hero">
  <div class="container">
    <h1>تحليل مسرحية <span class="accent">The Devil and Daniel Webster</span></h1>
    <p>
      موقع تعليمي تفاعلي شامل يشرح المسرحية العربية الفصحى المبسطة، مع تقسيم الأحداث، تحليل الشخصيات، الرموز، الصراعات، الاقتباسات المهمة، والاختبارات التفاعلية.
    </p>
    <div class="topbar">
      <div class="chip">تقسيم إلى مشاهد</div>
      <div class="chip">تحليل شخصيات</div>
      <div class="chip">خريطة أحداث</div>
      <div class="chip">أسئلة تفاعلية</div>
      <div class="chip">مراجعة شاملة</div>
    </div>
  </div>
</header>

<main class="container">

  <section class="grid">
    <article class="card span-12">
      <div class="section-title">1. مقدمة العمل</div>
      <p>
        هذه المسرحية من نوع <strong>Melodrama</strong>، أي الميلودراما، وفيها صراع واضح بين الخير والشر، ونهاية تنتصر فيها العدالة والحرية.
        وتدور حول الفلاح <strong>Jabez Stone</strong> الذي يبيع روحه للشيطان <strong>Mr. Scratch</strong> في لحظة يأس، ثم يستعين بالمحامي والخطيب الشهير <strong>Daniel Webster</strong> لإنقاذه.
      </p>
      <p>
        أهم ما يميز النص أنه لا يكتفي بحكاية صفقة مع الشيطان، بل يحولها إلى محاكمة رمزية لأفكار مثل الحرية، والضمير، والعدالة، والهوية الأمريكية، وقيمة الكلمة والخطابة في الدفاع عن الإنسان.
      </p>
      <div class="btns">
        <a class="btn" href="#timeline">اذهب إلى الخريطة الزمنية</a>
        <a class="btn outline" href="#characters">اذهب إلى الشخصيات</a>
      </div>
    </article>

    <article class="card span-8" id="timeline">
      <div class="section-title">2. الخريطة الزمنية للأحداث</div>
      <div class="timeline">
        <div class="step">
          <div class="tag">المشهد 1</div>
          <div>
            <strong>العرس في بيت Jabez Stone:</strong> فرح ظاهري يختلط بالقلق والشك، ويظهر المجتمع الريفي كله حول العروسين.
          </div>
        </div>
        <div class="step">
          <div class="tag">المشهد 2</div>
          <div>
            <strong>ظهور Mr. Scratch:</strong> يتضح أن الزائر الغريب هو الدائن الشيطاني الذي جاء لاسترداد روح Jabez.
          </div>
        </div>
        <div class="step">
          <div class="tag">المشهد 3</div>
          <div>
            <strong>فضح السر أمام الجماعة:</strong> بسبب المخلوق الذي خرج من الصندوق والذعر الجماعي، ينكشف أن Jabez باع روحه.
          </div>
        </div>
        <div class="step">
          <div class="tag">المشهد 4</div>
          <div>
            <strong>وصول Daniel Webster:</strong> يقدم نفسه محاميًا وصديقًا، وتبدأ مفاوضة قانونية ثم تتحول إلى معركة مصيرية.
          </div>
        </div>
        <div class="step">
          <div class="tag">المشهد 5</div>
          <div>
            <strong>محكمة الأموات:</strong> يستدعي Scratch هيئة محلفين من المذنبين والمارقين من التاريخ الأمريكي، ويظن أنه حسم القضية.
          </div>
        </div>
        <div class="step">
          <div class="tag">المشهد 6</div>
          <div>
            <strong>خطبة Webster الكبرى:</strong> يخاطب المحلفين بوصفهم بشرًا قبل أن يكونوا أرواحًا معذبة، ويدافع عن الحرية والإنسان.
          </div>
        </div>
        <div class="step">
          <div class="tag">المشهد 7</div>
          <div>
            <strong>انتصار الدفاع وطرد Scratch:</strong> تُحكم البراءة على Jabez، ثم يطرد Webster الشيطان من نيوهامبشر.
          </div>
        </div>
      </div>
    </article>

    <article class="card span-4">
      <div class="section-title">3. فكرة العمل المركزية</div>
      <p>
        الفكرة الأساسية هي أن الإنسان قد يضعف في لحظة يأس، لكن <strong>الحرية</strong> والضمير والعدالة يمكن أن ينقذوه.
      </p>
      <p>
        كما تُظهر المسرحية أن الشر ليس قوة خارقة فقط، بل قد يتغذى على الطمع والخوف والخضوع الاجتماعي.
      </p>
    </article>
  </section>

  <section class="grid" id="characters">
    <article class="card span-12">
      <div class="section-title">4. تحليل الشخصيات</div>
      <table class="table">
        <thead>
          <tr>
            <th>الشخصية</th>
            <th>دورها</th>
            <th>تطورها</th>
            <th>دلالتها</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Jabez Stone</strong></td>
            <td>بطل مأزوم باع روحه للشيطان</td>
            <td>ينتقل من الطموح واليأس إلى الندم والخوف ثم العجز الكامل</td>
            <td>يمثل الإنسان الذي يخطئ ثم يواجه نتيجة اختياره</td>
          </tr>
          <tr>
            <td><strong>Mary Stone</strong></td>
            <td>الزوجة الوفية</td>
            <td>من الفرح إلى الصدمة ثم إلى الثبات الروحي والدعاء</td>
            <td>تمثل الحب النقي والإيمان والقوة الهادئة</td>
          </tr>
          <tr>
            <td><strong>Daniel Webster</strong></td>
            <td>المدافع والخطيب والمحامي</td>
            <td>من السياسي الواثق إلى المدافع الأخلاقي ثم المنقذ النهائي</td>
            <td>يمثل قوة الكلمة والشرعية والهوية الوطنية</td>
          </tr>
          <tr>
            <td><strong>Mr. Scratch</strong></td>
            <td>الشيطان/المستولي على الروح</td>
            <td>يبدو مهذبًا ثم يكشف عن قسوته ثم يُهزم</td>
            <td>يمثل الإغواء، واستغلال الضعف، والشر المقنّع</td>
          </tr>
          <tr>
            <td><strong>The Crowd</strong></td>
            <td>صوت المجتمع</td>
            <td>من الاحتفال إلى الشك ثم الهلع ثم التحول إلى أداة طرد</td>
            <td>تمثل الرأي العام المتقلب</td>
          </tr>
        </tbody>
      </table>
    </article>
  </section>

  <section class="grid">
    <article class="card span-12">
      <div class="section-title">5. تحليل المشاهد بالتفصيل</div>

      <details open>
        <summary>المشهد الأول: العرس وبداية التوتر</summary>
        <p>
          يبدأ المشهد في بيت ريفي مريح بعد انتهاء عرس Jabez وMary، ويظهر الاحتفال الجماعي والرقص والطعام والثرثرة.
          هذا الجو السعيد ليس مجرد زينة، بل يهيئ التناقض القادم بين الفرح الخارجي والسر الداخلي الذي يثقله Jabez.
        </p>
        <p>
          من الناحية الثانوية، يلفت النص إلى المجتمع الريفي كله: الطبيب، والمحامي، والفلاح، والعجوز، والخادمة، لأن المسرحية تريد أن تجعل الحدث فرديًا وجماعيًا في الوقت نفسه.
          أما توتر Jabez الصامت مع Webester قبل كشف السر، فيشير إلى أنه يخفي خطيئة لا يستطيع قولها بسهولة.
        </p>
        <div class="quote">
          <strong>دلالة مهمة:</strong> الفرح هنا هشّ، لأن بناءه قائم على السر لا على الطمأنينة الحقيقية.
        </div>
      </details>

      <details>
        <summary>المشهد الثاني: دخول Mr. Scratch</summary>
        <p>
          دخول Scratch يتم بهدوء ودهاء، وهذا مهم جدًا؛ فهو لا يدخل كوحش مرعب من البداية، بل كـ"محامٍ" غريب مهذب.
          بذلك يرمز النص إلى أن الشر قد يأتي في صورة مألوفة ومقنعة، لا في صورة مخيفة مباشرة.
        </p>
        <p>
          اشتباكه مع Fiddler يفتح باب التوتر، ثم عزفه على الكمان وهو مرتدٍ القفازات يكشف أن هناك شيئًا غير طبيعي.
          هنا تتحول الموسيقى نفسها من عنصر احتفال إلى عنصر تهديد، وكأن الفن انقلب إلى أداة رعب.
        </p>
      </details>

      <details>
        <summary>المشهد الثالث: انكشاف الصفقة</summary>
        <p>
          عندما يخرج "العث" أو الكائن الطائر من الصندوق، ينهار الاستقرار الظاهري، ويبدأ المجتمع في إدراك أن هناك روحًا مباعة.
          ثم يتحول الخوف الفردي إلى هستيريا جماعية، فيتخلى الناس عن Jabez بسرعة، وهذا يكشف ضعف التضامن الاجتماعي حين تظهر الفضيحة.
        </p>
        <p>
          المشهد مهم لأنه يضع Jabez أمام الحقيقة: الثروة والسلطة لم تمنحاه الحصانة، بل جعلت سقوطه أكثر فظاعة.
          ويظهر أيضًا أن المجتمع الذي كان يصفق له هو نفسه الذي سينقلب عليه.
        </p>
      </details>

      <details>
        <summary>المشهد الرابع: وصول Daniel Webster</summary>
        <p>
          وصول Webster يغير طبيعة المسرحية من فضح أخلاقي إلى معركة قانونية ورمزية.
          فهو لا يأتي فقط لإنقاذ شخص، بل للدفاع عن معنى العدالة الأمريكية نفسها، ولهذا يصر على المحاكمة والجنة والهيئة.
        </p>
        <p>
          أهم ما في هذا الجزء هو احترامه الظاهري للقانون، رغم أن القضية تبدو فوق القانون البشري.
          وهذا التناقض مقصود: فالمسرحية تقول إن القانون الحقيقي ليس مجرد أوراق، بل قيم الحرية والحق.
        </p>
      </details>

      <details>
        <summary>المشهد الخامس: محكمة الأموات</summary>
        <p>
          هنا يصل النص إلى ذروته المسرحية؛ إذ يستدعي Scratch هيئة محلفين من التاريخ الأمريكي المظلم: خونة، قتلة، مستعمرين، وقراصنة.
          هذه ليست مجرد هيئة محلفين، بل تجسيد للتاريخ الملطخ بالعنف والعبودية والخيانة.
        </p>
        <p>
          اختيار Justice Hathorne يشدد على القسوة القضائية المتطرفة، ويحوّل المحكمة إلى مكان بلا رحمة.
          وهذا يعني أن المشكلة ليست في القانون وحده، بل فيمن يملك تفسيره وتطبيقه.
        </p>
      </details>

      <details>
        <summary>المشهد السادس: خطبة Webster</summary>
        <p>
          خطبة Webster من أهم خطب المسرحية كلها، لأنها تحوّل المحكمة من مكان إدانة إلى مكان تذكير بإنسانية المتهمين أنفسهم.
          هو لا يصرخ فقط، بل يستعيد فكرة الحرية والنهضة والأمل والجهد الإنساني المشترك.
        </p>
        <p>
          في هذه الخطبة، يخاطب أعضاء هيئة المحلفين بوصفهم بشرًا عاشوا قبل أن يصبحوا أرواحًا معذبة.
          وهنا يكمن سر الانتصار: لقد أيقظ فيهم الذكرى الإنسانية التي لم يستطع الشيطان محوها.
        </p>
      </details>

      <details>
        <summary>المشهد السابع: النهاية</summary>
        <p>
          بعد الحكم لصالح Jabez، تنتهي السلطة الشيطانية فجأة مع طلوع الصباح.
          الصباح هنا ليس زمنًا عاديًا، بل رمز لانتصار الحقيقة بعد ليل طويل من الخداع والذعر.
        </p>
        <p>
          ثم يجبر Webster Scratch على إطلاق سراحه، ويعده ألا يعود إلى نيوهامبشر.
          النهاية تؤكد أن الشر قد يُهزم عندما يواجهه الإنسان بالعقل والشجاعة والكلمة.
        </p>
      </details>
    </article>
  </section>

  <section class="grid">
    <article class="card span-6">
      <div class="section-title">6. العلاقات بين الشخصيات</div>
      <p>
        العلاقة بين <strong>Jabez</strong> و<strong>Mary</strong> تقوم على الحب والوفاء والصدق العاطفي، لكن السر الذي يخفيه Jabez يهدد هذا البناء.
      </p>
      <p>
        العلاقة بين <strong>Jabez</strong> و<strong>Scratch</strong> هي علاقة دين/استحواذ، وفيها توازن قسري قائم على عقد غير أخلاقي.
      </p>
      <p>
        العلاقة بين <strong>Webster</strong> و<strong>Scratch</strong> هي صراع بين الخطابة الشرعية والخداع القانوني.
      </p>
    </article>

    <article class="card span-6">
      <div class="section-title">7. رموز وأفكار</div>
      <p>
        <strong>البيت</strong> يرمز إلى الأمان الظاهر، لكنه يصبح ساحة مواجهة.
      </p>
      <p>
        <strong>الكمان</strong> يرمز إلى الفن حين يتحول إلى أداة تأثير نفسي.
      </p>
      <p>
        <strong>الصندوق الأسود</strong> يرمز إلى الأسرار والتهديد الخفي.
      </p>
      <p>
        <strong>الفجر</strong> يرمز إلى الخلاص والانكشاف والانتصار الأخلاقي.
      </p>
    </article>
  </section>

  <section class="grid">
    <article class="card span-12">
      <div class="section-title">8. اقتباسات مهمة وتحليلها</div>

      <div class="quote">
        <strong>“I will. ... if two New Hampshire men aren't a match for the devil, we might as well give the country back to the Indians.”</strong>
        <p>
          هذه العبارة تكشف الثقة الوطنية الساخرة لدى Webster، وتعني أن الرجل لا يتصور العجز أمام الشر.
          كما أنها تربط الدفاع عن Jabez بالدفاع عن كرامة نيوهامبشر وأمريكا كلها.
        </p>
      </div>

      <div class="quote">
        <strong>“Freedom is the bread and the morning and the risen sun.”</strong>
        <p>
          هذه الجملة تلخص فلسفة Webster: الحرية ليست فكرة مجردة، بل حاجة يومية مثل الخبز والضوء.
          لذلك تصبح الخطبة دفاعًا وجوديًا عن الإنسان لا مجرد مرافعة قانونية.
        </p>
      </div>

      <div class="quote">
        <strong>“Set me as a seal upon thy heart...”</strong>
        <p>
          صلاة Mary تمثل الحب المخلص الذي لا يساوم، وهي تستدعي اللغة الكتابية لتمنح المشهد بعدًا روحيًا عميقًا.
          هذا الدعاء هو آخر حاجز أخلاقي أمام سقوط Jabez الكامل.
        </p>
      </div>
    </article>
  </section>

  <section class="grid">
    <article class="card span-12">
      <div class="section-title">9. أسئلة تفاعلية وتمارين</div>

      <details class="quiz">
        <summary>اختبار 1: فهم الحدث</summary>
        <p>لماذا ازداد خوف Jabez عندما اقتربت نهاية العقد؟</p>
        <input type="text" placeholder="اكتب إجابتك هنا">
        <button onclick="showAnswer('a1')">إظهار الإجابة</button>
        <div class="answer" id="a1">لأنه أدرك أن صفقة بيع الروح ستنتهي فعلاً، وأن Scratch سيأتي لاسترداد روحه.</div>
      </details>

      <details class="quiz">
        <summary>اختبار 2: تحليل الشخصية</summary>
        <p>ما الفرق بين موقف Mary وموقف Jabez من الأزمة؟</p>
        <input type="text" placeholder="اكتب إجابتك هنا">
        <button onclick="showAnswer('a2')">إظهار الإجابة</button>
        <div class="answer" id="a2">Mary تواجه الأزمة بالإيمان والوفاء والدعاء، بينما Jabez ينهار بالخوف والندم والعجز.</div>
      </details>

      <details class="quiz">
        <summary>اختبار 3: الرموز</summary>
        <p>ماذا يرمز الفجر في النهاية؟</p>
        <input type="text" placeholder="اكتب إجابتك هنا">
        <button onclick="showAnswer('a3')">إظهار الإجابة</button>
        <div class="answer" id="a3">يرمز إلى الخلاص، وانتصار الحق، وانتهاء سلطة الشر.</div>
      </details>

      <details class="quiz">
        <summary>اختبار 4: اختيار من متعدد</summary>
        <p>من الذي قاد الدفاع في المحكمة؟</p>
        <input type="text" placeholder="أجب باسم الشخصية">
        <button onclick="showAnswer('a4')">إظهار الإجابة</button>
        <div class="answer" id="a4">Daniel Webster.</div>
      </details>

      <details class="quiz">
        <summary>اختبار 5: تحليل أدبي</summary>
        <p>لماذا تعتبر المسرحية ميلودراما؟</p>
        <input type="text" placeholder="اكتب إجابتك هنا">
        <button onclick="showAnswer('a5')">إظهار الإجابة</button>
        <div class="answer" id="a5">لأنها تعتمد على صراع واضح بين الخير والشر، وعواطف قوية، ومبالغة مسرحية، ونهاية ينتصر فيها الخير.</div>
      </details>
    </article>
  </section>

  <section class="grid">
    <article class="card span-6">
      <div class="section-title">10. مراجعة شاملة لكل فصل</div>
      <p>
        الفصل/المشهد الأول يقدم الفرح والطمأنينة ظاهريًا، لكنه يزرع القلق داخلهما.  
        الفصل الثاني يدخل الشر بلباس مهذب.  
        الفصل الثالث يكشف الخطيئة ويقلب المجتمع ضد Jabez.  
        الفصل الرابع يستدعي Webster بوصفه صوت العقل والقانون.
      </p>
      <p>
        الفصل الخامس يجعل التاريخ نفسه هيئة اتهام.  
        الفصل السادس يرفع الإنسان فوق خوفه عبر الخطابة.  
        الفصل السابع ينهي الصراع بإعادة التوازن وإعادة الاعتبار للحرية والبيت والحق.
      </p>
    </article>

    <article class="card span-6">
      <div class="section-title">11. الخلاصة الفكرية</div>
      <p>
        المسرحية لا تقول إن الإنسان معصوم، بل تقول إن الخطأ يمكن أن يكون بداية سقوط كبير إذا لم يواجهه المرء بالصدق.
      </p>
      <p>
        كما تؤكد أن العدالة لا تنتصر بالقوة وحدها، بل بالكلمة المؤثرة، وباستدعاء الإنسان إلى ضميره، وبالإيمان بأن الحرية قيمة أعلى من الخوف.
      </p>
    </article>
  </section>

  <section class="card span-12" style="margin-top:18px">
    <div class="section-title">12. خريطة العلاقات بين الشخصيات</div>
    <div class="flex">
      <div class="mini"><strong>Jabez Stone</strong><br>يرتبط بـ Mary بعلاقة حب ووفاء.</div>
      <div class="mini"><strong>Jabez Stone</strong><br>يرتبط بـ Scratch بعقد شيطاني واستحواذ.</div>
      <div class="mini"><strong>Webster</strong><br>يدافع عن Jabez بوصفه محاميًا وصوتًا وطنيًا.</div>
      <div class="mini"><strong>Scratch</strong><br>يستغل خوف Jabez ويصطدم بوعي Webster.</div>
      <div class="mini"><strong>The Crowd</strong><br>يتحول من جمهور احتفال إلى حكم اجتماعي ثم إلى قوة طرد.</div>
    </div>
  </section>

</main>

<footer class="footer">
  <div class="container">
    تم إعداد هذا الموقع ليكون أداة دراسة شاملة ومبسطة للمسرحية.
  </div>
</footer>

<script>
  function showAnswer(id){
    document.getElementById(id).classList.toggle('show');
  }
</script>

</body>
</html>
