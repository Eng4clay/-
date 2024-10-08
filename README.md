<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>استبيان تصميم داخلي</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            text-align: right;
            margin: 20px;
        }
        .container {
            max-width: 600px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #f9f9f9;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"], select {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>استبيان تصميم داخلي</h2>
        <form id="surveyForm">
            <div class="form-group">
                <label for="colors">ما هي الألوان المفضلة لديك والتي ترغب في استخدامها في التصميم الداخلي؟</label>
                <select id="colors" name="colors">
                    <option value="neutral">ألوان محايدة (أبيض، رمادي، بيج)</option>
                    <option value="warm">ألوان دافئة (أحمر، برتقالي، أصفر)</option>
                    <option value="cool">ألوان باردة (أزرق، أخضر، بنفسجي)</option>
                    <option value="bold">ألوان جريئة (أسود، ذهبي، فضي)</option>
                </select>
            </div>
            <div class="form-group">
                <label for="style">هل لديك أي نمط تصميم معين تفضله؟</label>
                <select id="style" name="style">
                    <option value="modern">الحديث (المودرن)</option>
                    <option value="classic">الكلاسيكي</option>
                    <option value="industrial">الصناعي</option>
                    <option value="rustic">الريفي</option>
                    <option value="scandinavian">الاسكندنافي</option>
                    <option value="artdeco">الآرت ديكو</option>
                    <option value="bohemian">البوهيمي</option>
                    <option value="traditional">التقليدي</option>
                </select>
            </div>
            <div class="form-group">
                <label for="furniture">هل هناك أي قطع أثاث أو ديكور ترغب في الاحتفاظ بها أو دمجها في التصميم الجديد؟</label>
                <select id="furniture" name="furniture">
                    <option value="yes">نعم، أرغب في الاحتفاظ ببعض القطع</option>
                    <option value="no">لا، أرغب في تجديد كل شيء</option>
                </select>
            </div>
            <div class="form-group">
                <label for="activities">ما هي الأنشطة الرئيسية التي ستتم في كل غرفة؟</label>
                <select id="activities" name="activities">
                    <option value="reading">القراءة</option>
                    <option value="working">العمل</option>
                    <option value="entertainment">الترفيه</option>
                    <option value="sleeping">النوم</option>
                    <option value="cooking">الطهي</option>
                    <option value="dining">تناول الطعام</option>
                </select>
            </div>
            <div class="form-group">
                <label for="lighting">هل لديك أي متطلبات خاصة للإضاءة في أي من الغرف؟</label>
                <select id="lighting" name="lighting">
                    <option value="strong">إضاءة قوية</option>
                    <option value="dim">إضاءة خافتة</option>
                    <option value="adjustable">إضاءة قابلة للتعديل</option>
                    <option value="natural">إضاءة طبيعية</option>
                </select>
            </div>
            <div class="form-group">
                <label for="materials">هل هناك أي مواد أو تشطيبات تفضل استخدامها أو ترغب في تجنبها؟</label>
                <select id="materials" name="materials">
                    <option value="wood">الخشب</option>
                    <option value="stone">الحجر</option>
                    <option value="glass">الزجاج</option>
                    <option value="metal">المعدن</option>
                    <option value="plastic">البلاستيك</option>
                </select>
            </div>
            <div class="form-group">
                <label for="storage">هل لديك أي احتياجات خاصة تتعلق بالتخزين أو المساحات المخصصة للأغراض الشخصية؟</label>
                <select id="storage" name="storage">
                    <option value="yes">نعم، أحتاج إلى مساحات تخزين إضافية</option>
                    <option value="no">لا، المساحات الحالية كافية</option>
                </select>
            </div>
            <div class="form-group">
                <label for="budget">هل هناك أي قيود أو متطلبات تتعلق بالميزانية التي يجب مراعاتها؟</label>
                <select id="budget" name="budget">
                    <option value="yes">نعم، لدي ميزانية محددة</option>
                    <option value="no">لا، الميزانية مفتوحة</option>
                </select>
            </div>
            <div class="form-group">
                <label for="ideas">هل لديك أي أفكار أو تصورات مبدئية ترغب في مناقشتها أو رؤيتها في لوحة الأفكار؟</label>
                <select id="ideas" name="ideas">
                    <option value="yes">نعم، لدي بعض الأفكار</option>
                    <option value="no">لا، أترك الأمر للمصمم</option>
                </select>
            </div>
            <div class="form-group">
                <label for="focus">هل هناك أي عناصر تصميمية أو تفاصيل ترغب في التركيز عليها بشكل خاص؟</label>
                <select id="focus" name="focus">
                    <option value="furniture">الأثاث</option>
                    <option value="colors">الألوان</option>
                    <option value="lighting">الإضاءة</option>
                    <option value="finishes">التشطيبات</option>
                    <option value="decor">الديكور</option>
                </select>
            </div>
            <button type="submit">إرسال</button>
        </form>
    </div>
    <script>
        document.getElementById('surveyForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('تم إرسال الاستبيان بنجاح!');
        });
    </script>
</body>
</html>
